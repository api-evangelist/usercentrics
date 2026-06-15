# Usercentrics (usercentrics)

Usercentrics is a Munich-based consent management platform (CMP) and privacy compliance provider. Founded in 2017 and led by CEO Donna Dror, Usercentrics acquired Danish CMP Cookiebot (Cybot) in September 2021 and acquired MCP Manager in January 2026. The platform serves 2.4M+ websites and apps across 195 countries, processing 8.8B+ monthly consents. Products span Web CMP, App CMP, CTV CMP, Server-Side Tagging, Meta Signals Gateway, Preference Manager, Privacy Policy Generator, Compliance Scanners, and MCP Manager for AI governance.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/usercentrics/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/usercentrics/refs/heads/main/apis.yml)

## Tags

- Privacy
- Consent
- CMP
- Compliance
- GDPR
- CCPA
- TCF
- GPP
- Cookies
- AI Governance

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Usercentrics App CMP SDK

Mobile and TV consent management SDK with native iOS (11+), tvOS (11+), Android (API 16+), AndroidTV, Unity (2018.4+), Flutter (1.20+), and React Native (0.65+) support. Comprises UsercentricsCore (backend logic) and UsercentricsUI (prebuilt banner). Supports GDPR, CCPA, LGPD, and IAB TCF 2.0.

- **Human URL:** [https://docs.usercentrics.com/cmp_in_app_sdk/latest/](https://docs.usercentrics.com/cmp_in_app_sdk/latest/)

#### Tags

- SDK
- Mobile
- iOS
- Android
- Flutter
- React Native
- Unity
- TV
- Consent

#### Properties

- [Documentation](https://docs.usercentrics.com/cmp_in_app_sdk/latest/)
- [API Reference](https://docs.usercentrics.com/cmp_in_app_sdk/latest/api/api_documentation/)
- [SDK](https://github.com/Usercentrics/flutter-sdk)
- [SDK](https://github.com/Usercentrics/react-native-sdk)
- [SDK](https://github.com/Usercentrics/ios-sample)
- [SDK](https://github.com/Usercentrics/android-sample)
- [OpenAPI](openapi/usercentrics-app-cmp-sdk-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/usercentrics-app-cmp-sdk.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usercentrics-app-cmp-sdk.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Usercentrics Web CMP (V3)

Browser-side consent management platform for websites. Exposes the UC_UI JavaScript API, IAB __tcfapi (TCF 2.3), IAB __gpp (GPP), dataLayer events, and Google Consent Mode v2 / Microsoft UET Consent Mode signals. Configurable through the Usercentrics Admin Interface and delivered via the Usercentrics CDN.

- **Human URL:** [https://docs.usercentrics.com/cmp_v3/latest/](https://docs.usercentrics.com/cmp_v3/latest/)

#### Tags

- Web
- JavaScript
- CMP
- TCF
- GPP
- Consent Mode

#### Properties

- [Documentation](https://docs.usercentrics.com/cmp_v3/latest/)
- [OpenAPI](openapi/usercentrics-web-cmp-v3-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/usercentrics-web-cmp-v3.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usercentrics-web-cmp-v3.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cookiebot CMP

Cookiebot consent management platform (a Usercentrics company since the September 2021 Cybot acquisition). Provides a JavaScript SDK (Cookiebot global, show()/hide()/renew()/getScript()/ runScripts()/withdraw()/submitCustomConsent()), CookiebotOnConsentReady / OnAccept / OnDecline events, server-side CookieConsent cookie integration (C#, PHP, VB samples), and the patented monthly site scanner.

- **Human URL:** [https://www.cookiebot.com/en/developer/](https://www.cookiebot.com/en/developer/)

#### Tags

- Cookies
- Scanner
- JavaScript
- GDPR
- GTM

#### Properties

- [Documentation](https://www.cookiebot.com/en/developer/)
- [Documentation](https://www.cookiebot.com/en/help/)
- [Support](https://support.cookiebot.com/hc/en-us/)
- [OpenAPI](openapi/usercentrics-cookiebot-cmp-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/usercentrics-cookiebot-cmp.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usercentrics-cookiebot-cmp.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Usercentrics Server-Side Tagging (sGTM)

Hosted server-side Google Tag Manager service for first-party data collection, consent enforcement, and tag execution off the browser. Includes Meta Signals Gateway for the Meta Conversions API and consent-aware event forwarding.

- **Human URL:** [https://usercentrics.com/integrations/](https://usercentrics.com/integrations/)

#### Tags

- Server-Side
- GTM
- Tagging
- Meta
- Conversions API

#### Properties

- [Documentation](https://usercentrics.com/integrations/)
- [Postman Collection](collections/usercentrics-app-cmp-sdk.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usercentrics-app-cmp-sdk.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/usercentrics-cookiebot-cmp.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usercentrics-cookiebot-cmp.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/usercentrics-web-cmp-v3.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usercentrics-web-cmp-v3.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://usercentrics.com/)
- [Portal](https://docs.usercentrics.com/)
- [Sign Up](https://usercentrics.com/free-trial/)
- [Pricing](https://usercentrics.com/pricing/)
- [Plans](plans/usercentrics-plans-pricing.yml)
- [Rate Limits](rate-limits/usercentrics-rate-limits.yml)
- [Fin Ops](finops/usercentrics-finops.yml)
- [Blog](https://usercentrics.com/knowledge-hub/)
- [Support](https://support.usercentrics.com/)
- [Privacy Policy](https://usercentrics.com/privacy-policy/)
- [Terms of Service](https://usercentrics.com/terms-and-conditions/)
- [Documentation](https://usercentrics.com/legal-documents/)
- [GitHub Organization](https://github.com/Usercentrics)
- [LinkedIn](https://www.linkedin.com/company/usercentrics/)
- [Documentation](https://www.cookiebot.com/en/)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Solutions](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
