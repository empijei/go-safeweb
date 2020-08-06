_Authors: grenfeldt@google.com_

# Plugins

The framework will support plugins. Plugins can run before and after the request handlers. They provide a flexible way to address security issues by setting non-overridable security headers or interrupting and responding to incoming requests before they reach the handler.

## Provided plugins

- [HSTS](https://github.com/google/go-safeweb/blob/master/docs/plugins/hsts.md): Automatically redirects HTTP traffic to HTTPS and sets the `Strict-Transport-Security` header.