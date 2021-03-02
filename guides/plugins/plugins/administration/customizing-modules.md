# Customize modules

## Overview

In the `Administration` core code, each module is defined in a directory called `module`.
A `module` is an encapsulated unit which implement a whole feature. For example there are modules for customers, orders, settings, etc.

## Prerequisites

All you need for this guide is a running Shopware 6 instance. Of course, you'll have to understand JavaScript and have a basic familiarity with TwigJS, the templating engine, used in the Administration. However, that's a prerequisite for Shopware as a whole and will not be taught as part of this documentation.

## Customizing a module

Module settings like `color`, `icon`, `navigation` are fixed by design and cannot be changed.

A guide for customizing components which are already defined in existing modules can be found here - [Customizing components](./customizing-components.md).

At some point you need add or change the routes of a module. For example when you want to add a tab to the page

This is done by creating a new component an implementing a `routeMiddleware`.
You can add those changes to your `main.js` file, which could then look like this:

{% code title="<plugin root>/src/Resources/app/administration/src/main.js" %}
```js
Shopware.Module.register('my-new-custom-route', {
    routeMiddleware(next, currentRoute) {
        if (currentRoute.name === 'sw.product.detail') {
            currentRoute.children.push({
                name: 'sw.product.detail.custom',
                path: '/sw/product/detail/:id/custom',
                component: 'sw-product-detail-custom',
                meta: {
                    parentPath: "sw.product.index"
                }
            });
        }
        next(currentRoute);
    }
});
```
{% endcode %}

In this example we register a new module which uses the `routeMiddleWare` to scan the routes while the `Vue router` is being set up.
If we find the route `sw.product.detail` we just add another child route by pushing it to the `currentRoute.children`.

You can find a detailed example in the [Add tab to existing module](./add-new-tab.md) guide.

## Next steps

As you might have noticed, we are just adding a custom tab to the module. However, there's a lot more possible when it comes to extending the Adminsitration. You may want to try the following things:

* If you want to learn about other possibilities to extend the Administration, we got you covered with other guides:
    * [Writing templates](./writing-templates.md)
    * [Add custom module](./add-custom-module.md)
    * [Add menu entry](./add-menu-entry.md)
    * [Add custom routes](./add-custom-route.md)