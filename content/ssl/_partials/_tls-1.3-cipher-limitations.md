---
_build:
  publishResources: false
  render: never
  list: never
---

You cannot set specific TLS 1.3 ciphers. Instead, you can enable [TLS 1.3](/ssl/edge-certificates/additional-options/tls-13/#enable-tls-13) for your entire zone and Cloudflare will use [all applicable TLS 1.3 cipher suites](/ssl/edge-certificates/additional-options/cipher-suites/supported-cipher-suites/).

In combination with this, you can still [disable weak cipher suites](/ssl/edge-certificates/additional-options/cipher-suites/customize-cipher-suites/) for TLS 1.0-1.2.