# Saleor App Examples

![Saleor App Template](https://user-images.githubusercontent.com/249912/71523206-4e45f800-28c8-11ea-84ba-345a9bfc998a.png)

# Examples

Minimal implementations for one concept at a time. Feel free to clone the repository, or take a look at implementation and copy what you need.

## Dashboard extensions
Extensions can be used to integrate your app with the Saleor Dashboard

Code on GitHub:
- [Code branch](https://github.com/saleor/saleor-app-template/tree/examples-app-extensions)
- [Diff view](https://github.com/saleor/saleor-app-template/compare/main...examples-app-extensions)

Related documentation:
- [Extending dashboard](https://docs.saleor.io/docs/3.x/developer/extending/apps/extending-dashboard-with-apps)

## Metadata Manager
How to keep application preferences in the metadata and use helpers provided by the SDK.

Code on GitHub:
- [Code branch](https://github.com/saleor/saleor-app-template/tree/examples-metadata-manager)
- [Diff view](https://github.com/saleor/saleor-app-template/compare/main...examples-metadata-manager)

Related documentation:
- [SDK docs for SettingManager](https://github.com/saleor/saleor-app-sdk/blob/main/docs/settings-manager.md)
- [Metadata documentation](https://docs.saleor.io/docs/3.x/developer/metadata)

## External webhook
Example of communication with the Saleor API triggered by 3rd party external service.

Code on GitHub:
- [Code branch](https://github.com/saleor/saleor-app-template/tree/examples-external-webhook)
- [Diff view](https://github.com/saleor/saleor-app-template/compare/main...examples-external-webhook)

Related documentation:
- [ngrok knowledge base about webhooks](https://webhooks.fyi/)

## Async webhook handler
Simple implementation of app subscribing for asynchronous Saleor Webhook.

Code on GitHub:
- [Code branch](https://github.com/saleor/saleor-app-template/tree/example-async-webhook-handler)
- [Diff view](https://github.com/saleor/saleor-app-template/compare/main...example-async-webhook-handler)

Related documentation:
- [Saleor asynchronous webhooks documentation](https://docs.saleor.io/docs/3.x/developer/extending/apps/asynchronous-webhooks)
- [App SDK documentation for Async Webhooks Handlers](https://github.com/saleor/saleor-app-sdk/blob/main/docs/saleor-async-webhook.md)


## Protected route
How to expose API route and restrict it's access only for requests originated from the Saleor Dashboard.

Code on GitHub:
- [Code branch](https://github.com/saleor/saleor-app-template/tree/examples-protected-route)
- [Diff view](https://github.com/saleor/saleor-app-template/compare/main...examples-protected-route)

Related documentation:
- [App SDK app bridge documentation](https://github.com/saleor/saleor-app-sdk/blob/main/docs/app-bridge.md)
- [App SDK protected handlers for NextJS documentation](https://github.com/saleor/saleor-app-sdk/blob/main/docs/protected-handlers.md)

## tRPC
tRPC is a library providing end-to-end type safety for TypeScript applications. This example provides an example how to integrate it with the App Bridge.

Code on GitHub:
- [Code branch](https://github.com/saleor/saleor-app-template/tree/examples-trpc)
- [Diff view](https://github.com/saleor/saleor-app-template/compare/main...examples-trpc)

Related documentation:
- [tRPC website](https://trpc.io/)

# Resources

- [Saleor App Template](https://github.com/saleor/saleor-app-template)
- [Saleor App SDK](https://github.com/saleor/saleor-app-sdk)
- [Apps Docs](https://docs.saleor.io/docs/3.x/developer/extending/apps/key-concepts)
