---
updatedVersion: 'commerce/5.x/upgrade'
---

# Editions

<Block label="Commerce Edition Changes">

With the release of Commerce 4.5, Lite and Pro editions have been merged. This page discusses differences in earlier versions of the plugin.

</Block>

Craft Commerce comes in two editions: Lite and Pro. Each can be trialled for free in a local development environment for as long as you’d like.

## Pro

Commerce Pro is for professional ecommerce sites that typically include a cart customers can update and a multi-page checkout flow.

## Lite

Commerce Lite is for sites that need only the basics, where one-off product sales, complex tax and shipping rules, promotion management, and shopping carts would be overkill.

The Lite edition only allows for a single line item in the cart. Whenever a customer adds something to the cart, it replaces whatever item was in the cart. If multiple items are added to the cart in a single request, only the last item that was submitted is added to the cart.

Although technically a cart always exists, a customer’s experience with Lite would probably not include a front-end cart UI. The checkout flow should not include a cart icon, but rely instead of a single “buy now” button leading straight into collecting email, shipping, and payment information on a single screen.

## Feature Comparison

::: warning
As of Commerce 4.5, this feature table is no longer relevant! See the notice at the top of this page.
:::

<EditionComparison />
