<div align="center">
  <img src="assets/logo.png" width="150"/>
  <h1>Shopify CLI Example App</h1>
</div>

This repository contains an example Shopify App that uses [shopify/shopify-cli-action](https://github.com/Shopify/shopify-cli-action) to build, test, and deploy an app to the Shopify platform using Shopify CLI 2.0.

## CLI Deprecation & Sunset

Note that Shopify CLI 2.0 is deprecated and will be sunset on May 31, 2023. We encourage using [Shopify CLI 3.0](https://github.com/Shopify/cli) to develop apps, custom storefronts, and themes.

Documentation about Shopify CLI 3.0 and CI/CD:
- https://shopify.dev/apps/tools/cli/ci-cd
- https://shopify.dev/themes/tools/cli/ci-cd

## Blocks

| Block | Description | CI | CD |
| --- | ---- | --- | --- |
| [home](/home) | An block that's loaded in the admin | [![Home](https://github.com/Shopify/shopify-cli-example-app/actions/workflows/home.yml/badge.svg)](https://github.com/Shopify/shopify-cli-example-app/actions/workflows/home.yml) | |
| [scripts/payment_method](/scripts/payment_method) | A payment method script | [![Payment method](https://github.com/Shopify/shopify-cli-example-app/actions/workflows/payment-method.yml/badge.svg)](https://github.com/Shopify/shopify-cli-example-app/actions/workflows/payment-method.yml) | [![Checkout post purchase deploy](https://github.com/Shopify/shopify-cli-example-app/actions/workflows/payment-method-deploy.yml/badge.svg)](https://github.com/Shopify/shopify-cli-example-app/actions/workflows/payment-method-deploy.yml) |
| [ui-extensions/checkout_post_purchase](ui-extensions/checkout_post_purchase) | A checkout post-purchase UI extension | [![Checkout post purchase](https://github.com/Shopify/shopify-cli-example-app/actions/workflows/checkout-post-purchase.yml/badge.svg)](https://github.com/Shopify/shopify-cli-example-app/actions/workflows/checkout-post-purchase.yml) | [![Checkout post purchase deploy](https://github.com/Shopify/shopify-cli-example-app/actions/workflows/checkout-post-purchase-deploy.yml/badge.svg)](https://github.com/Shopify/shopify-cli-example-app/actions/workflows/checkout-post-purchase-deploy.yml) |
