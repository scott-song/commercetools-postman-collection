# commercetools Postman collections

Postman provides a REST client that helps you executing API requests without any development effort.
API requests can be organized into **collections** that you can import into Postman.

Theoretically, you can run the whole commerce journey from creating Customers and Products to creating Orders where these Customers purchase the Products.

Key benefits of using Postman collections of commercetools APIs:

- Works with minimum technical knowledge with no coding required
- Can be used as soon as you have created a commercetools project
- The API endpoints can be explored to achieve a holistic view of how the commercetools Platform and other services operate

This repository contains Postman collections including requests and responses for most commercetools endpoints.
For each request, the smallest possible payload is given. Optional fields can be found in the related [official documentation](http://docs.commercetools.com/).

Additionally, the collections provide example requests and responses for specific tasks and more complex data models.

## Disclaimer

This is not the official commercetools documentation.
To learn more about commercetools APIs and to find the complete and approved documentation, visit [docs.commercetools.com](http://docs.commercetools.com/).

## Available Postman collections

The following Postman collections are available:

- [Platform API](api/)
- [Import](import/)
- [Machine Learning](ml/)

> **:warning: Note:**
>
> - Be aware that Postman automatically synchronizes environment variables (including your API client credentials) to your workspace if logged in.
> - Use these collections only for development purposes and non-production projects.

Feel free to clone the collections and adjust them to your needs.

## Getting started

For information on how to use the commercetools Postman collections and set up an environment, refer to [Getting started](GettingStarted.md).
