# Table of contents

* [Home](README.md)

## Concepts

* [Commerce](concepts/commerce/README.md)
  * [Catalog](concepts/commerce/catalog/README.md)
    * [Categories](concepts/commerce/catalog/categories.md)
    * [Products](concepts/commerce/catalog/products.md)
    * [Sales Channels](concepts/commerce/catalog/sales-channels.md)
  * [Checkout](concepts/commerce/checkout-concept/README.md)
    * [Cart](concepts/commerce/checkout-concept/cart.md)
    * [Orders](concepts/commerce/checkout-concept/orders.md)
  * [Content](concepts/commerce/core/README.md)
    * [Shopping Experiences \(CMS\)](concepts/commerce/core/shopping-experiences-cms.md)
* [Framework](concepts/framework/README.md)
  * [Architecture](concepts/framework/architecture/README.md)
    * [Storefront](concepts/framework/architecture/storefront-concept.md)
    * [Administration](concepts/framework/architecture/administration-concept.md)
  * [Data Abstraction Layer](concepts/framework/data-abstraction-layer/README.md)
  * [Messaging](concepts/framework/messaging.md)
  * [Migrations](concepts/framework/migrations.md)
  * [Rules](concepts/framework/rules.md)
* [Extensions](concepts/extensions/README.md)
  * [Apps](concepts/extensions/apps-concept.md)
  * [Plugins](concepts/extensions/plugins-concept.md)
* [API](concepts/api/README.md)
  * [Store API](concepts/api/store-api.md)

## Products

* [Editions](products/editions/README.md)
  * [Community Edition](products/editions/community-edition.md)
  * [Professional Edition](products/editions/professional-edition.md)
  * [Enterprise Edition](products/editions/enterprise-edition/README.md)
    * [B2B Suite](products/editions/enterprise-edition/b2b-suite.md)
    * [Search](products/editions/enterprise-edition/search/README.md)
      * [Installation](products/editions/enterprise-edition/search/installation.md)
      * [Field Configuration](products/editions/enterprise-edition/search/field-config.md)
      * [Extensibility](products/editions/enterprise-edition/search/extensibility.md)
    * [Publisher](products/editions/enterprise-edition/publisher.md)
    * [Contribution Guidelines](products/editions/enterprise-edition/contribution-guidelines.md)
* [Plugins](products/plugins/README.md)
  * [Custom Products](products/plugins/custom-products.md)
  * [PayPal](products/plugins/paypal.md)
  * [Migration Assistant](products/plugins/migration-assistant/README.md)
    * [Concept](products/plugins/migration-assistant/concept/README.md)
      * [Profile and Connection](products/plugins/migration-assistant/concept/profile-and-connection.md)
      * [DataSelection and DataSet](products/plugins/migration-assistant/concept/dataselection-and-dataset.md)
      * [Migration Context](products/plugins/migration-assistant/concept/migration-context.md)
      * [Premapping](products/plugins/migration-assistant/concept/premapping.md)
      * [Gateway and Reader](products/plugins/migration-assistant/concept/gateway-and-reader.md)
      * [Convert and Mapping](products/plugins/migration-assistant/concept/convert-and-mapping.md)
      * [Logging](products/plugins/migration-assistant/concept/logging.md)
      * [Writer](products/plugins/migration-assistant/concept/writer.md)
      * [Media Processing](products/plugins/migration-assistant/concept/media-processing.md)
    * [Guides](products/plugins/migration-assistant/guides/README.md)
      * [Extending a Shopware migration profile](products/plugins/migration-assistant/guides/extending-a-shopware-migration-profile.md)
      * [Extending the Migration Connector](products/plugins/migration-assistant/guides/extending-the-migration-connector.md)
      * [Decorating a Shopware Migration Assistant converter](products/plugins/migration-assistant/guides/decorating-a-shopware-migration-assistant-converter.md)
      * [Creating a new migration profile](products/plugins/migration-assistant/guides/creating-a-new-migration-profile.md)
    * [Reference](products/plugins/migration-assistant/reference.md)
* [Cloud](products/cloud-1.md)
* [PWA](products/pwa-1/README.md)
  * [Quick Setup](products/pwa-1/quick-setup.md)

## Guides

* [Installation](guides/installation/README.md)
  * [Installation overview](guides/installation/overview.md)
  * [Dockware](guides/installation/dockware.md)
  * [Docker](guides/installation/docker.md)
  * [from scratch](guides/installation/from-scratch.md)
  * [Valet+](guides/installation/valet.md)
  * [Vagrant](guides/installation/vagrant.md)
  * [MAMP](guides/installation/mamp.md)
* [Extensions](guides/plugins/README.md)
  * [Overview](guides/plugins/overview.md)
  * [Plugins](guides/plugins/plugins/README.md)
    * [Plugin Base Guide](guides/plugins/plugins/plugin-base-guide.md)
    * [Plugins for Symfony developers](guides/plugins/plugins/plugins-for-symfony-developers.md)
    * [Plugin fundamentals](guides/plugins/plugins/plugin-fundamentals/README.md)
      * [Listening to events](guides/plugins/plugins/plugin-fundamentals/listening-to-events.md)
      * [Dependency injection](guides/plugins/plugins/plugin-fundamentals/dependency-injection.md)
      * [Add plugin configuration](guides/plugins/plugins/plugin-fundamentals/add-plugin-configuration.md)
      * [Use plugin configuration](guides/plugins/plugins/plugin-fundamentals/use-plugin-configuration.md)
      * [Add plugin dependencies](guides/plugins/plugins/plugin-fundamentals/add-plugin-dependencies.md)
      * [Add custom service](guides/plugins/plugins/plugin-fundamentals/add-custom-service.md)
      * [Adjusting a service](guides/plugins/plugins/plugin-fundamentals/adjusting-service.md)
      * [Add custom CLI commands](guides/plugins/plugins/plugin-fundamentals/add-custom-commands.md)
      * [Database migrations](guides/plugins/plugins/plugin-fundamentals/database-migrations.md)
      * [Add scheduled task](guides/plugins/plugins/plugin-fundamentals/add-scheduled-task.md)
      * [Using custom fields of type media](guides/plugins/plugins/plugin-fundamentals/custom-fields-of-type-media.md)
    * [Checkout](guides/plugins/plugins/checkout/README.md)
      * [Cart](guides/plugins/plugins/checkout/cart/README.md)
        * [Add cart items](guides/plugins/plugins/checkout/cart/add-cart-items.md)
      * [Customer](guides/plugins/plugins/checkout/customer.md)
      * [Document](guides/plugins/plugins/checkout/document.md)
      * [Order](guides/plugins/plugins/checkout/order.md)
      * [Payment](guides/plugins/plugins/checkout/payment/README.md)
        * [Add payment plugin](guides/plugins/plugins/checkout/payment/add-payment-plugin.md)
      * [Shipping](guides/plugins/plugins/checkout/shipping.md)
    * [Content](guides/plugins/plugins/content/README.md)
      * [CMS](guides/plugins/plugins/content/cms/README.md)
        * [Add CMS block](guides/plugins/plugins/content/cms/add-cms-block.md)
        * [Add CMS element](guides/plugins/plugins/content/cms/add-cms-element.md)
      * [Import / export](guides/plugins/plugins/content/import-export.md)
      * [Mail](guides/plugins/plugins/content/mail.md)
      * [Media](guides/plugins/plugins/content/media.md)
      * [Product Stream](guides/plugins/plugins/content/product-stream.md)
      * [SEO](guides/plugins/plugins/content/seo.md)
      * [Sitemap](guides/plugins/plugins/content/sitemap.md)
    * [Framework](guides/plugins/plugins/framework/README.md)
      * [Data Handling / DataAbstractionLayer](guides/plugins/plugins/framework/data-handling/README.md)
        * [Adding custom complex data](guides/plugins/plugins/framework/data-handling/add-custom-complex-data.md)
        * [Reading data](guides/plugins/plugins/framework/data-handling/reading-data.md)
        * [Writing data](guides/plugins/plugins/framework/data-handling/writing-data.md)
        * [Replacing associated data](guides/plugins/plugins/framework/data-handling/replacing-associated-data.md)
        * [Removing associated data](guides/plugins/plugins/framework/data-handling/deleting-associated-data.md)
        * [Adding data translations](guides/plugins/plugins/framework/data-handling/add-data-translations.md)
        * [Using flags](guides/plugins/plugins/framework/data-handling/using-flags.md)
        * [Adding complex data to existing entities](guides/plugins/plugins/framework/data-handling/add-complex-data-to-existing-entities.md)
        * [Adding data associations](guides/plugins/plugins/framework/data-handling/add-data-associations.md)
      * [Custom Fields](guides/plugins/plugins/framework/custom-field/README.md)
        * [Add custom field](guides/plugins/plugins/framework/custom-field/add-custom-field.md)
        * [Using database events](guides/plugins/plugins/framework/custom-field/using-database-events.md)
      * [Event](guides/plugins/plugins/framework/event.md)
      * [Message Queue](guides/plugins/plugins/framework/message-queue.md)
      * [Rule](guides/plugins/plugins/framework/rule.md)
      * [Store API](guides/plugins/plugins/framework/store-api.md)
    * [Administration](guides/plugins/plugins/administration/README.md)
      * [Adding permissions](guides/plugins/plugins/administration/add-acl-rules.md)
      * [Add custom route](guides/plugins/plugins/administration/add-custom-route.md)
      * [Writing templates](guides/plugins/plugins/administration/writing-templates.md)
      * [Add menu module](guides/plugins/plugins/administration/add-custom-module.md)
      * [Add menu entry](guides/plugins/plugins/administration/add-menu-entry.md)
      * [Add tab to existing module](guides/plugins/plugins/administration/add-new-tab.md)
      * [Customizing components](guides/plugins/plugins/administration/customizing-components.md)
      * [Add own component](guides/plugins/plugins/administration/add-custom-component.md)
      * [Adding snippets](guides/plugins/plugins/administration/adding-snippets.md)
      * [Add custom styles](guides/plugins/plugins/administration/add-custom-styles.md)
    * [Storefront](guides/plugins/plugins/storefront/README.md)
      * [Add custom controller](guides/plugins/plugins/storefront/add-custom-controller.md)
      * [Override existing routes](guides/plugins/plugins/storefront/override-existing-routes.md)
      * [Customize templates](guides/plugins/plugins/storefront/customize-templates.md)
      * [Add custom Javascript](guides/plugins/plugins/storefront/add-custom-javascript.md)
      * [Override existing Javascript](guides/plugins/plugins/storefront/override-existing-javascript.md)
      * [Add custom assets](guides/plugins/plugins/storefront/add-custom-assets.md)
      * [Add custom styling](guides/plugins/plugins/storefront/add-custom-styling.md)
      * [Add data to storefront page](guides/plugins/plugins/storefront/add-data-to-storefront-page.md)
      * [Add cookie to manager](guides/plugins/plugins/storefront/add-cookie-to-manager.md)
      * [Reacting to cookie consent changes](guides/plugins/plugins/storefront/reacting-to-cookie-consent-changes.md)
      * [Add custom page](guides/plugins/plugins/storefront/add-custom-page.md)
      * [Reacting to javascript events](guides/plugins/plugins/storefront/reacting-to-javascript-events.md)
      * [Add translations](guides/plugins/plugins/storefront/add-translations.md)
      * [Use CSRF protection](guides/plugins/plugins/storefront/use-csrf-protection.md)
    * [Testing](guides/plugins/plugins/testing/README.md)
      * [End-to-end testing](guides/plugins/plugins/testing/end-to-end-testing.md)
      * [Jest unit tests in Shopware's administration](guides/plugins/plugins/testing/jest-admin.md)
      * [PHP unit testing](guides/plugins/plugins/testing/php-unit.md)
  * [Themes](guides/plugins/themes/README.md)
    * [Theme base guide](guides/plugins/themes/theme-base-guide.md)
    * [Create a first theme](guides/plugins/themes/create-a-theme.md)
    * [Differences Plugins and Apps vs Themes](guides/plugins/themes/differences-plugins-and-apps-vs-themes.md)
    * [Theme configuration](guides/plugins/themes/theme-configuration.md)
    * [Add SCSS Styling and JavaScript to a Theme](guides/plugins/themes/add-css-js-to-theme.md)
    * [Override Bootstrap variables in a Theme](guides/plugins/themes/override-bootstrap-variables-in-a-theme.md)
    * [Add assets to a Theme](guides/plugins/themes/add-assets-to-theme.md)
    * [Theme inheritance](guides/plugins/themes/add-theme-inheritance.md)
    * [Theme with Bootstrap styling](guides/plugins/themes/add-theme-inheritance-without-resources.md)
  * [Apps](guides/plugins/apps/README.md)
    * [App Base Guide](guides/plugins/apps/app-base-guide.md)
    * [Storefront](guides/plugins/apps/storefront.md)
    * [Administration](guides/plugins/apps/administration/README.md)
      * [Add custom action button](guides/plugins/apps/administration/add-custom-action-button.md)
      * [Add custom module](guides/plugins/apps/administration/add-custom-module.md)
    * [Custom Data](guides/plugins/apps/custom-data.md)
    * [Configuration](guides/plugins/apps/configuration.md)
* [Hosting](guides/hosting/README.md)
  * [Installation & Updates](guides/hosting/installation-updates/README.md)
    * [Deployments](guides/hosting/installation-updates/deployments/README.md)
        * [Deployment with Deployer](guides/hosting/installation-updates/deployments/deployment-with-deployer.md)
    * [Versioning & Dependencies](guides/hosting/installation-updates/composer.md)
  * [Performance](guides/hosting/performance/README.md)
    * [HTTP Cache](guides/hosting/performance/caches.md)
  * [Infrastructure](guides/hosting/infrastructure/README.md)
    * [Filesystem](guides/hosting/infrastructure/filesystem.md)
    * [Message Queue](guides/hosting/infrastructure/message-queue.md)
* [Integrations / API](guides/integrations-api/README.md)
  * [General Concepts](guides/integrations-api/general-concepts/README.md)
    * [Search Criteria](guides/integrations-api/general-concepts/search-criteria.md)
    * [Request Headers](guides/integrations-api/general-concepts/request-headers.md)
    * [Generated Reference](guides/integrations-api/general-concepts/generated-reference.md)
  * [Admin API Guide](guides/integrations-api/admin-api/README.md)
    * [Authentication](guides/integrations-api/admin-api/authentication.md)
    * [Reading entities](guides/integrations-api/admin-api/reading-entities.md)
    * [Writing entities](guides/integrations-api/admin-api/writing-entities/README.md)
      * [Bulk Payloads](guides/integrations-api/admin-api/writing-entities/bulk-payloads.md)
    * [Action Routes](guides/integrations-api/admin-api/action-routes.md)
  * [Store API Guide](guides/integrations-api/store-api-guide/README.md)
    * [Register a customer](guides/integrations-api/store-api-guide/register-a-customer.md)
    * [Search for products](guides/integrations-api/store-api-guide/search-for-products.md)
    * [Work with the cart](guides/integrations-api/store-api-guide/work-with-the-cart.md)
    * [Handling the payment](guides/integrations-api/store-api-guide/handling-the-payment.md)
    * [FAQ](guides/integrations-api/store-api-guide/faq.md)

## Resources

* [References](resources/references/README.md)
  * [API Reference](resources/references/api-reference/README.md)
    * [Store API Reference](resources/references/api-reference/store-api-reference/README.md)
        * [Product](resources/references/api-reference/store-api-reference/product.md)
        * [Category](resources/references/api-reference/store-api-reference/category.md)
        * [Customer](resources/references/api-reference/store-api-reference/customer.md)
    * [Admin API Reference](resources/references/api-reference/admin-api-reference.md)
  * [Core Reference](resources/references/core-reference/README.md)
    * [DAL Reference](resources/references/core-reference/dal-reference/README.md)
      * [Fields Reference](resources/references/core-reference/dal-reference/fields-reference.md)
      * [Flags Reference](resources/references/core-reference/dal-reference/flags-reference.md)
      * [Filters Reference](resources/references/core-reference/dal-reference/filters-reference.md)
      * [Aggregations Reference](resources/references/core-reference/dal-reference/aggregations-reference.md)
    * [Commands Reference](resources/references/core-reference/commands-reference.md)
  * [App Reference](resources/references/app-reference/README.md)
    * [Manifest Reference](resources/references/app-reference/manifest-reference.md)
  * [Testing Reference](resources/references/testing-reference)
    + [Custom E2E Commands](resources/references/testing-reference/e2e-custom-commands.md)
    + [PSH E2E Commands](resources/references/testing-reference/e2e-psh-commands.md)
* [Guidelines](resources/guidelines/README.md)
  * [Code](resources/guidelines/code.md)
    * [Cart Process](resources/guidelines/code/cart-process.md) 
    * [Context Rules &amp; Rule Systems](resources/guidelines/code/context-rules-rule-systems.md) 
    * [Dependency Injection &amp; Dependency Handling](resources/guidelines/code/dependency-injection-dependency-handling.md) 
    * [Document Code](resources/guidelines/code/document-code.md)
    * [Events](resources/guidelines/code/events.md) 
    * [Page Loader](resources/guidelines/code/pageloader.md) 
    * [Platform Domains](resources/guidelines/code/platform-domains.md)
    * [Public APIs](resources/guidelines/code/public-apis.md) 
    * [Routing](resources/guidelines/code/routing.md) 
    * [Session and State](resources/guidelines/code/session-and-state.md) 
    * [Store API](resources/guidelines/code/store-api.md) 
    * [Storefront Controller](resources/guidelines/code/storefront-controller.md) 
  * [Documentation](resources/guidelines/documentation/README.md)
    * [Structure](resources/guidelines/documentation/structure.md)
    * [Writing](resources/guidelines/documentation/writing.md)
  * [Testing](resources/guidelines/testing/)
    * [E2E](resources/guidelines/testing/e2e-best-practises.md)
