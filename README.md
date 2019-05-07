# ![LOGO](logo.png) Jumpseller API **flow**ground Connector

## Description

A generated **flow**ground connector for the Jumpseller API API (version 1).

Generated from: https://api.apis.guru/v2/specs/jumpseller.com/1/swagger.json<br/>
Generated at: 2019-05-07T17:42:37+03:00

## API Description

Explore all our endpoints with your own set of of access tokens. All changes affect your production Jumpseller store.

## Authorization

This API does not require authorization.

## Actions

### Retrieve all Jumpseller Apps.

*Tags:* `Apps`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.

### Retrieve all Categories.

*Tags:* `Categories`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.

### Create a new Category.

> Category's permalink is automatically generated from the given category's name.

*Tags:* `Categories`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.

### Delete an existing Category.

*Tags:* `Categories`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - Id of the Category

### Retrieve a single Category.

*Tags:* `Categories`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - Id of the Category

### Modify an existing Category.

*Tags:* `Categories`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - Id of the Category

### Retrieve all Checkout Custom Fields.

*Tags:* `Checkout Custom Fields`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `limit` - _optional_ - List restriction
* `page` - _optional_ - List page

### Create a new CheckoutCustomField.

*Tags:* `Checkout Custom Fields`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.

### Delete an existing CheckoutCustomField.

*Tags:* `Checkout Custom Fields`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - Id of the CheckoutCustomField

### Retrieve a single CheckoutCustomField.

*Tags:* `Checkout Custom Fields`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - Id of the CheckoutCustomField

### Update a CheckoutCustomField.

*Tags:* `Checkout Custom Fields`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - Id of the CheckoutCustomField

### Retrieve all Countries.

*Tags:* `Countries`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.

### Retrieve a single Country information.

*Tags:* `Countries`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `country_code` - _required_ - ISO3166 Country Code

### Retrieve all Regions from a single Country.

*Tags:* `Countries` `Regions`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `country_code` - _required_ - ISO3166 Country Code

### Retrieve a single Region information object.

*Tags:* `Countries` `Regions`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `country_code` - _required_ - ISO3166 Country Code
* `region_code` - _required_ - Region Code

### Retrieve all Customer Categories.

*Tags:* `Customer Categories`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `limit` - _optional_ - List restriction
* `page` - _optional_ - List page

### Create a new CustomerCategory.

*Tags:* `Customer Categories`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.

### Delete an existing CustomerCategory.

*Tags:* `Customer Categories`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - Id of the CustomerCategory

### Retrieve a single CustomerCategory.

*Tags:* `Customer Categories`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - Id of the CustomerCategory

### Update a CustomerCategory.

*Tags:* `Customer Categories`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - Id of the CustomerCategory

### Delete Customers from an existing CustomerCategory.

*Tags:* `Customer Categories`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - Id of the CustomerCategory

### Retrieves the customers in a CustomerCategory.

*Tags:* `Customer Categories`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - Id of the CustomerCategory

### Adds Customers to a CustomerCategory.

*Tags:* `Customer Categories`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - Id of the CustomerCategory

### Retrieve all Customers.

*Tags:* `Customers`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `limit` - _optional_ - List restriction
* `page` - _optional_ - List page

### Create a new Customer.

*Tags:* `Customers`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.

### Retrieve a single Customer.

*Tags:* `Customers`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `email` - _required_ - Email of the Customer

### Delete an existing Category.

*Tags:* `Customers`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - Id of the Customer

### Retrieve a single Customer.

*Tags:* `Customers`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - Id of the Customer

### Update a new Customer.

*Tags:* `Customers`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - Id of the Customer

### Retrieves the Customer Additional Field of a Customer.

*Tags:* `Customer Additional Fields`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - Id of the Customer

### Adds Customer Additional Fields to a Customer.

*Tags:* `Customer Additional Fields`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - Id of the Customer

### Delete a Customer Additional Field.

*Tags:* `Customer Additional Fields`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - Id of the Product
* `field_id` - _required_ - Id of the Customer Additional Field

### Create a new Customer Additional Field.

*Tags:* `Customer Additional Fields`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - Id of the Customer
* `field_id` - _required_ - Id of the Customer Additional Field

### Retrieve all Store's Custom Fields.

*Tags:* `Custom Fields`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.

### Create a new Custom Field.

*Tags:* `Custom Fields`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.

### Retrieve all Hooks.

*Tags:* `Hooks`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `limit` - _optional_ - List restriction
* `page` - _optional_ - List page

### Create a new Hook.

*Tags:* `Hooks`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.

### Delete an existing Hook.

*Tags:* `Hooks`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - Id of the Hook

### Retrieve a single Hook.

*Tags:* `Hooks`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - Id of the Hook

### Update a Hook.

*Tags:* `Hooks`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - Id of the Hook

### Create a Store JSApp

*Tags:* `Apps`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.

### Delete an existing JSApp.

*Tags:* `Apps`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `code` - _required_ - Code of the App

### Retrieve a JSApp

*Tags:* `Apps`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `code` - _required_ - Code of the App

### Retrieve all Orders.

*Tags:* `Orders`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `limit` - _optional_ - List restriction
* `page` - _optional_ - List page

### Create a new Order.

> Use the JSON format:<br/>'{ "order": {"status": "Paid", "shipping_method_id": 123, "products": [{ "id": 123, "qty": 1}], "customer": {"id": 123}}}'<br/>or in CURL:<br/>curl -X POST -d '{ "order": {"status": "Paid", "shipping_method_id": 123, "products": [{ "id": 123, "qty": 1}], "customer": {"id": 123}}}' "https://api.jumpseller.com/v1/orders.json?login=storecode&authtoken=XXXXX" -H "Content-Type:application/json"

*Tags:* `Orders`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.

### Retrieve orders filtered by Order Id.

> For example the GET /orders/after/5000 will return Order 5001, 5002, 5003, etc.

*Tags:* `Orders`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - Id of the Order

### Count all Orders.

*Tags:* `Orders`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.

### Retrieve orders filtered by status.

*Tags:* `Orders`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `status` - _required_ - Status of the Order used as filter
    Possible values: Abandoned, Canceled, Pending Payment, Paid.

### Retrieve a single Order.

*Tags:* `Orders`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - Id of the Order

### Modify an existing Order.

> Only 'status', 'tracking_number', 'tracking_company', 'additional_information' and 'additional_fields' are available for update.<br/>Use the JSON format:<br/>'{ "order": {"status": "Paid", "tracking_company": "other", "tracking_number": "123456789", "additional_information": "My custom message.", "additional_fields": [{"label": "Gift Name", "value": "Duarte"}, {"label": "Gift Wrapping Color", "value": "Green"}]} }}'<br/>or in CURL:<br/>curl -X PUT -d '{ "order": {"status": "Paid", "additional_information": "My custom message."}}' "https://api.jumpseller.com/v1/orders/{id}.json?login=storecode&authtoken=XXXXX" -H "Content-Type:application/json"

*Tags:* `Orders`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - Id of the Order

### Retrieve all Order History.

*Tags:* `Orders`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - Id of the Order

### Create a new Order History Entry.

*Tags:* `Orders`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - Id of the OrderHistory

### Retrieve all Store's Payment Methods.

*Tags:* `Payment Methods`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.

### Retrieve a single Payment Method.

*Tags:* `Payment Methods`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - Id of the Payment Method

### Retrieve all Products.

*Tags:* `Products`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `limit` - _optional_ - List restriction
* `page` - _optional_ - List page

### Create a new Product.

*Tags:* `Products`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.

### Retrieves Products after the given id.

*Tags:* `Products`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - Id of the Product

### Retrieve Products filtered by category.

*Tags:* `Products`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `category_id` - _required_ - Category ID of the Product used as filter

### Count Products filtered by category.

*Tags:* `Products`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `category_id` - _required_ - Category ID of the Product used as filter

### Count all Products.

*Tags:* `Products`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.

### Retrieve a Product List from a query.

*Tags:* `Products`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `query` - _required_ - Query for the Product

### Retrieve a single Product by SKU.

*Tags:* `Products`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `sku` - _required_ - SKU of the Product

### Retrieve Products filtered by status.

*Tags:* `Products`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `status` - _required_ - Status of the Product used as filter
    Possible values: available, not-available, disabled.

### Count Products filtered by status.

*Tags:* `Products`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `status` - _required_ - Status of the Product used as filter
    Possible values: available, not-available, disabled.

### Delete an existing Product.

*Tags:* `Products`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - Id of the Product

### Retrieve a single Product.

*Tags:* `Products`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - ID of the Product

### Modify an existing Product.

*Tags:* `Products`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - Id of the Product

### Retrieve all Product Custom Fields

*Tags:* `Product Custom Fields`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - Id of the Product

### Create a new Product Custom Field.

*Tags:* `Product Custom Fields`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - Id of the Product

### Count all Product Custom Fields.

*Tags:* `Product Custom Fields`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - ID of the Product

### Retrieve all Product Images.

*Tags:* `Product Images`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - ID of the Product

### Create a new Product Image.

*Tags:* `Product Images`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - Id of the Product

### Count all Product Images.

*Tags:* `Product Images`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - ID of the Product

### Delete a Product Image.

*Tags:* `Product Images`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - Id of the Product
* `image_id` - _required_ - Id of the Product Image

### Create a new Product Image.

*Tags:* `Product Images`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - Id of the Product
* `image_id` - _required_ - Id of the Product Image

### Retrieve all Product Options.

*Tags:* `Product Options`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - ID of the Product

### Create a new Product Option.

*Tags:* `Product Options`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - Id of the Product

### Count all Product Options.

*Tags:* `Product Options`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - ID of the Product

### Delete a Product Option.

*Tags:* `Product Options`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - Id of the Product
* `option_id` - _required_ - Id of the Product Option

### Create a new Product Option.

*Tags:* `Product Options`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - Id of the Product
* `option_id` - _required_ - Id of the Product Option

### Modify an existing Product Option.

*Tags:* `Product Options`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - Id of the Product
* `option_id` - _required_ - Id of the Product Option

### Retrieve all Product Option Values.

*Tags:* `Product Option Values`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - ID of the Product
* `option_id` - _required_ - ID of the Product Option

### Create a new Product Option Value.

*Tags:* `Product Option Values`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - Id of the Product
* `option_id` - _required_ - Id of the Product Option

### Count all Product Option Values.

*Tags:* `Product Option Values`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - ID of the Product
* `option_id` - _required_ - ID of the Product Option

### Delete a Product Option Value.

*Tags:* `Product Option Values`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - Id of the Product
* `option_id` - _required_ - Id of the Product Option
* `value_id` - _required_ - ID of the Product Option Value

### Create a new Product Option Value.

*Tags:* `Product Option Values`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - Id of the Product
* `option_id` - _required_ - Id of the Product Option
* `value_id` - _required_ - ID of the Product Option Value

### Modify an existing Product Option Value.

*Tags:* `Product Option Values`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - Id of the Product
* `option_id` - _required_ - Id of the Product Option
* `value_id` - _required_ - Id of the Product Option Value

### Retrieve all Product Variants.

*Tags:* `Product Variants`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - ID of the Product

### Create a new Product Variant.

*Tags:* `Product Variants`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - Id of the Product

### Count all Product Variants.

*Tags:* `Product Variants`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - ID of the Product

### Retrieve a single Product Variant.

*Tags:* `Product Variants`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - Id of the Product
* `variant_id` - _required_ - Id of the Product Variant

### Modify an existing Product Variant.

*Tags:* `Product Variants`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - Id of the Product
* `variant_id` - _required_ - Id of the Product Variant

### Retrieve all Promotions.

*Tags:* `Promotions`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `limit` - _optional_ - Promotions' list restriction (default: 50 | max: 200).
* `page` - _optional_ - Promotions' list page (default: 1).

### Create a new Promotion.

*Tags:* `Promotions`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.

### Delete an existing Promotion.

*Tags:* `Promotions`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - Id of the Promotion

### Retrieve a single Promotion.

*Tags:* `Promotions`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - Id of the Promotion

### Update a Promotion.

*Tags:* `Promotions`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - Id of the Promotion

### Retrieve Store Information

*Tags:* `Stores`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.

### Retrieve Store Languages

*Tags:* `Stores`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.

### Retrieve all Taxes.

*Tags:* `Taxes`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.

### Create a new Tax.

*Tags:* `Taxes`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.

### Retrieve a single Tax information.

*Tags:* `Taxes`

#### Input Parameters
* `login` - _required_ - API OAuth login.
* `authtoken` - _required_ - API OAuth token.
* `id` - _required_ - Id of the Tax

## License

**flow**ground :- Telekom iPaaS / jumpseller-com-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
