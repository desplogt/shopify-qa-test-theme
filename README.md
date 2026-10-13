# shopify-qa-test-theme

Dawn 15.0.2 used to validate [Theme QA](https://github.com/desplogt/shopify-QA) on the test store `checkout-extension-luis`.

`main` is connected to the store through the Shopify GitHub integration and published, so merging to `main` publishes the theme. Every pull request runs Theme QA (`.github/workflows/theme-qa.yml`) and must pass before merging.
