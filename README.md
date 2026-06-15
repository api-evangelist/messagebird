# messagebird (messagebird)

Build powerful apps using the fastest and most reliable cloud communications APIs.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/messagebird/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/messagebird/refs/heads/main/apis.yml)

## Timestamps

- **Modified:** 2026-05-19

## APIs

### MessageBird SMS Messaging API

The MessageBird SMS Messaging API allows developers to send and receive SMS messages to and from any country in the world through a REST interface. It supports features such as message scheduling, delivery reports, Unicode messages, and concatenated messages for longer content. The API provides both HTTP and SMPP connectivity options for high-volume messaging use cases.

- **Human URL:** [https://developers.messagebird.com/api/sms-messaging/](https://developers.messagebird.com/api/sms-messaging/)
- **Base URL:** `https://rest.messagebird.com`

#### Tags

- Communications
- Messaging
- SMS
- Text Messages

#### Properties

- [Documentation](https://developers.messagebird.com/api/sms-messaging/)
- [OpenAPI](openapi/messagebird-sms-messaging-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/messagebird-sms-messaging.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/messagebird-sms-messaging.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### MessageBird Voice Calling API

The MessageBird Voice Calling API enables developers to make, receive, and control phone calls programmatically. It supports call flows for building interactive voice response systems, call recording, call transfers, and real-time webhooks for call events. The API provides global coverage and can be used to build contact center solutions, automated calling systems, and voice-enabled applications.

- **Human URL:** [https://developers.messagebird.com/api/voice-calling/](https://developers.messagebird.com/api/voice-calling/)
- **Base URL:** `https://voice.messagebird.com`

#### Tags

- Calling
- Communications
- Telephony
- Voice

#### Properties

- [Documentation](https://developers.messagebird.com/api/voice-calling/)
- [OpenAPI](openapi/messagebird-voice-calling-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/messagebird-voice-calling.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/messagebird-voice-calling.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### MessageBird Voice Messaging API

The MessageBird Voice Messaging API enables developers to transform text messages into voice messages delivered to any country. It supports 26 languages with configurable attributes such as male or female voice, speaking rate, repeat options, and scheduling. The API is useful for sending voice notifications, alerts, and one-time passwords to users who may not have access to SMS.

- **Human URL:** [https://developers.messagebird.com/api/voice-messaging/](https://developers.messagebird.com/api/voice-messaging/)
- **Base URL:** `https://rest.messagebird.com`

#### Tags

- Communications
- Messaging
- Text-To-Speech
- Voice

#### Properties

- [Documentation](https://developers.messagebird.com/api/voice-messaging/)
- [OpenAPI](openapi/messagebird-voice-messaging-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/messagebird-voice-messaging.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/messagebird-voice-messaging.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### MessageBird Conversations API

The MessageBird Conversations API provides a unified interface for managing omnichannel messaging across platforms such as SMS, WhatsApp, Facebook Messenger, Telegram, and more. It consolidates messages from multiple channels into a single conversation thread per contact, enabling consistent customer communication. The API supports sending and receiving messages, managing conversation state, and handling webhooks for real-time event processing.

- **Human URL:** [https://developers.messagebird.com/api/conversations/](https://developers.messagebird.com/api/conversations/)
- **Base URL:** `https://conversations.messagebird.com`

#### Tags

- Chat
- Communications
- Messaging
- Omnichannel
- WhatsApp

#### Properties

- [Documentation](https://developers.messagebird.com/api/conversations/)
- [OpenAPI](openapi/messagebird-conversations-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/messagebird-conversations.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/messagebird-conversations.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [AsyncAPI](asyncapi/messagebird-conversations-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)

### MessageBird WhatsApp API

The MessageBird WhatsApp API allows developers to send and receive WhatsApp messages for alerts, notifications, customer support, and two-factor authentication. It provides access to all WhatsApp Business features through a single API, including template messages, media messages, and interactive message types. The API supports rich media content and provides delivery and read receipts for message tracking.

- **Human URL:** [https://developers.messagebird.com/api/whatsapp](https://developers.messagebird.com/api/whatsapp)
- **Base URL:** `https://conversations.messagebird.com`

#### Tags

- Communications
- Messaging
- Notifications
- WhatsApp

#### Properties

- [Documentation](https://developers.messagebird.com/api/whatsapp)
- [OpenAPI](openapi/messagebird-whatsapp-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/messagebird-whatsapp.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/messagebird-whatsapp.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### MessageBird Verify API

The MessageBird Verify API provides a simple way to implement two-factor authentication and phone number verification. It generates and validates one-time passwords delivered via SMS or voice call, handling token generation, delivery, and verification in a single workflow. The API supports configurable token length, expiration time, and delivery channel selection for flexible integration into sign-up and login flows.

- **Human URL:** [https://developers.messagebird.com/api/verify/](https://developers.messagebird.com/api/verify/)
- **Base URL:** `https://rest.messagebird.com`

#### Tags

- OTP
- Security
- Two-Factor Authentication
- Verification

#### Properties

- [Documentation](https://developers.messagebird.com/api/verify/)
- [OpenAPI](openapi/messagebird-verify-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/messagebird-verify.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/messagebird-verify.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### MessageBird Lookup API

The MessageBird Lookup API enables developers to validate and look up mobile phone numbers. It performs HLR lookups on the mobile network to identify number format, country, operator, and availability in real-time. The API is useful for cleaning contact lists, validating user-provided phone numbers, and determining the correct format before sending messages.

- **Human URL:** [https://developers.messagebird.com/api/lookup/](https://developers.messagebird.com/api/lookup/)
- **Base URL:** `https://rest.messagebird.com`

#### Tags

- HLR
- Number Intelligence
- Phone Numbers
- Validation

#### Properties

- [Documentation](https://developers.messagebird.com/api/lookup/)
- [OpenAPI](openapi/messagebird-lookup-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/messagebird-lookup.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/messagebird-lookup.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### MessageBird HLR API

The MessageBird HLR API provides a way to send Home Location Register network queries to any mobile number globally. It allows developers to determine which operator a mobile number belongs to in real-time and check whether the number is currently active on the network. This API is commonly used for number portability checks, fraud prevention, and optimizing message routing.

- **Human URL:** [https://developers.messagebird.com/api/hlr/](https://developers.messagebird.com/api/hlr/)
- **Base URL:** `https://rest.messagebird.com`

#### Tags

- HLR
- Mobile Network
- Network Query
- Phone Numbers

#### Properties

- [Documentation](https://developers.messagebird.com/api/hlr/)
- [OpenAPI](openapi/messagebird-hlr-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/messagebird-hlr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/messagebird-hlr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### MessageBird Contacts API

The MessageBird Contacts API allows developers to manage contact information for end-users and customers across messaging platforms. It supports creating, reading, updating, and deleting contacts, as well as organizing them into groups for targeted messaging campaigns. A single contact can be associated with multiple communication channels such as SMS, WhatsApp, and Telegram.

- **Human URL:** [https://developers.messagebird.com/api/contacts/](https://developers.messagebird.com/api/contacts/)
- **Base URL:** `https://rest.messagebird.com`

#### Tags

- Address Book
- Contacts
- Customer Data
- Groups

#### Properties

- [Documentation](https://developers.messagebird.com/api/contacts/)
- [OpenAPI](openapi/messagebird-contacts-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/messagebird-contacts.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/messagebird-contacts.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### MessageBird Numbers API

The MessageBird Numbers API enables developers to search for, purchase, and manage phone numbers programmatically. It supports local, toll-free, and mobile number types across multiple countries, with the ability to filter by pattern, type, and region. Purchased numbers can be configured for SMS and voice capabilities and assigned to specific messaging or calling workflows.

- **Human URL:** [https://developers.messagebird.com/api/numbers/](https://developers.messagebird.com/api/numbers/)
- **Base URL:** `https://numbers.messagebird.com`

#### Tags

- Number Management
- Phone Numbers
- Provisioning
- Telecommunications

#### Properties

- [Documentation](https://developers.messagebird.com/api/numbers/)
- [OpenAPI](openapi/messagebird-numbers-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/messagebird-numbers.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/messagebird-numbers.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### MessageBird Balance API

The MessageBird Balance API provides developers with access to their account balance information. It returns the current payment type, available amount, and currency for the account associated with the API key. This API is useful for monitoring credit usage, building billing dashboards, and setting up automated alerts when account balances fall below a threshold.

- **Human URL:** [https://developers.messagebird.com/api/balance/](https://developers.messagebird.com/api/balance/)
- **Base URL:** `https://rest.messagebird.com`

#### Tags

- Account
- Balance
- Billing
- Credits

#### Properties

- [Documentation](https://developers.messagebird.com/api/balance/)
- [OpenAPI](openapi/messagebird-balance-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/messagebird-balance.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/messagebird-balance.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### MessageBird Integrations API

The MessageBird Integrations API allows developers to create, fetch, and delete message templates for supported platforms. It currently supports template management for the WhatsApp platform, enabling developers to programmatically manage the templates required for sending WhatsApp Business notifications and messages. The API handles template submission, approval status tracking, and lifecycle management.

- **Human URL:** [https://developers.messagebird.com/api/integrations/](https://developers.messagebird.com/api/integrations/)
- **Base URL:** `https://integrations.messagebird.com`

#### Tags

- Integrations
- Message Templates
- Templates
- WhatsApp

#### Properties

- [Documentation](https://developers.messagebird.com/api/integrations/)
- [OpenAPI](openapi/messagebird-integrations-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/messagebird-integrations.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/messagebird-integrations.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/messagebird)
- [LinkedIn](https://www.linkedin.com/company/birdhq)
- [JSON-LD](json-ld/messagebird-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/messagebird-message-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/messagebird-conversation-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/messagebird-contact-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Features](undefined)
- [L L Ms Txt](https://bird.com/llms.txt)
