# Overview of custom commands for Shopware usage

In this reference, all Shopware commands provided by 
[e2e-testsuite-platform](https://github.com/shopware/e2e-testsuite-platform) or
[shopware platform](https://github.com/shopware/platform) are listed here. 

## General commands 
| Command        | Parameter           | Description  |
| -------------- |-------------------- | ------------ |
| setLocaleToEnGb | - | Switches administration UI locale to EN_GB |
| login | `(userType)` | Logs in to the Administration manually |
| typeAndCheck | `(textToType)` | Types in an input element and checks if the content was correctly typed |
| clearTypeAndCheck | `(textToType)` | Clears field, types in an input element and checks if the content was correctly typed |
| typeMultiSelectAndCheck | `(textToType, { searchTerm: searchTerm })` | Types in a sw-select field and checks if the content was correctly typed (multi select) |
| typeSingleSelect | `(textToType, selector)` | Types in an sw-select field (single select) |
| typeSingleSelectAndCheck | `(textToType, selector)` | Types in an sw-select field and checks if the content was correctly typed (single select) |
| typeLegacySelectAndCheck | `(textToType, { searchTerm: searchTerm })` | Types in an legacy swSelect field and checks if the content was correctly typed |
| typeAndCheckSearchField | `(searchTerm)` | Types in the global search field and verify search terms in url |
| awaitAndCheckNotification | `(message)` | Wait for a notification to appear and check its message |
| clickContextMenuItem | `(actionInMenuSelector, openMenuSelector, scope = '')` | Click context menu in order to cause a desired action |
| clickMainMenuItem | `({ targetPath, mainMenuId, subMenuId })` | Navigate to module by clicking the corresponding main menu item |
| openUserActionMenu | `({ targetPath, mainMenuId, subMenuId })` | Click user menu to open it up |
| dragTo | `(target)` | Drags the previous subject element to a target, performing a drag and drop operation |
| onlyOnFeature | `(feature)` | Only run the test (skip otherwise) if the feature is activated |
| skipOnFeature | `(feature)` | Skip the test if the feature is activated |

## Storefront-related / Sales Channel API commands

| Command        | Parameter           | Description  |
| -------------- |-------------------- | ------------ |
| getSalesChannelId | - | Get the sales channel Id via Admin API |
| storefrontApiRequest | `(method, endpoint, header = {}, body = {})` |  Performs Storefront API Requests |
| getRandomProductInformationForCheckout | - | Returns random product with id, name and url to view product |

## System Commands

| Command        | Parameter           | Description  |
| -------------- |-------------------- | ------------ |
| activateShopwareTheme | - | Activates Shopware theme for Cypress test runner |
| cleanUpPreviousState | - | Cleans up any previous state by restoring database and clearing caches |
| openInitialPage | - | Opens up the administration initially and waits for the "me" call to be successful |

## API commands

| Command        | Parameter           | Description  |
| -------------- |-------------------- | ------------ |
| authenticate | - | Authenticate towards the Shopware API |
| loginViaApi | - | Logs in silently using Shopware API |
| searchViaAdminApi | `(data)` | Search for an existing entity using Shopware API at the given endpoint |
| requestAdminApi | `(method, url, requestData)` | Handling API requests |
| updateViaAdminApi | `(endpoint, id, data)` | Updates an existing entity using Shopware API at the given endpoint |

## Fixture commands 

| Command        | Parameter           | Description  |
| -------------- |-------------------- | ------------ |
| setToInitialState | - | Sets Shopware back to its initial state if using platform E2E backup routine |
| createDefaultFixture | `(endpoint, data = {}, jsonPath)` | Create entity using Shopware API via given endpoint |
| createProductFixture | `(userData = {})` | Create product fixture using Shopware API via given endpoint |
| createCategoryFixture | `(userData = {})`      | Create category fixture using Shopware API via given endpoint |
| createSalesChannelFixture | `(userData = {}`  |  Create sales channel fixture using Shopware API via given endpoint |
| setSalesChannelDomain | `(salesChannelName = 'Storefront')` | Create sales channel domain using Shopware API at the given endpoint |
| createCustomerFixture | `(userData = {})` | Create customer fixture using Shopware API via given endpoint |
| createCmsFixture | `(userData = {})` | Create cms fixture using Shopware API at the given endpoint |
| createPropertyFixture | `(options, userData)` | Create property fixture using Shopware API at the given endpoint |
| createLanguageFixture | - | Create language fixture using Shopware API at the given endpoint |
| createShippingFixture | `(userData)` | Create shipping fixture using Shopware API at the given endpoint |
| createSnippetFixture | - | Create snippet fixture using Shopware API at the given endpoint |
| createGuestOrder | `productId, userData)` | Create guest order fixture |
| setProductFixtureVisibility | `(productName, categoryName)` | Sets category and visibility for a product in order to set it visible in the Storefront |

