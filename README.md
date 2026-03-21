# MessageBird (messagebird)
MessageBird is a cloud communications platform that enables businesses to communicate with customers across SMS, voice, and chat channels through a unified API. Their developer platform provides RESTful APIs for messaging, voice calling, phone number management, verification, and omnichannel conversations including WhatsApp integration.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/messagebird/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - SMS, Voice, Messaging, Communications, WhatsApp, Omnichannel

## Timestamps

- **Created:** 2026-03-20
- **Modified:** 2026-03-20

## APIs

### MessageBird SMS Messaging API
The MessageBird SMS Messaging API allows developers to send and receive SMS messages to and from any country in the world through a REST interface. It supports features such as message scheduling, delivery reports, Unicode messages, and concatenated messages for longer content. The API provides both HTTP and SMPP connectivity options for high-volume messaging use cases.

**Human URL:** [https://developers.messagebird.com/api/sms-messaging/](https://developers.messagebird.com/api/sms-messaging/)


#### Tags:

 - SMS, Messaging, Text Messages, Communications

#### Properties

- [Documentation](https://developers.messagebird.com/api/sms-messaging/)
- [OpenAPI](openapi/messagebird-sms-messaging-openapi.yml)

### MessageBird Voice Calling API
The MessageBird Voice Calling API enables developers to make, receive, and control phone calls programmatically. It supports call flows for building interactive voice response systems, call recording, call transfers, and real-time webhooks for call events. The API provides global coverage and can be used to build contact center solutions, automated calling systems, and voice-enabled applications.

**Human URL:** [https://developers.messagebird.com/api/voice-calling/](https://developers.messagebird.com/api/voice-calling/)


#### Tags:

 - Voice, Calling, Telephony, Communications

#### Properties

- [Documentation](https://developers.messagebird.com/api/voice-calling/)
- [OpenAPI](openapi/messagebird-voice-calling-openapi.yml)

### MessageBird Voice Messaging API
The MessageBird Voice Messaging API enables developers to transform text messages into voice messages delivered to any country. It supports 26 languages with configurable attributes such as male or female voice, speaking rate, repeat options, and scheduling. The API is useful for sending voice notifications, alerts, and one-time passwords to users who may not have access to SMS.

**Human URL:** [https://developers.messagebird.com/api/voice-messaging/](https://developers.messagebird.com/api/voice-messaging/)


#### Tags:

 - Voice, Text-to-Speech, Messaging, Communications

#### Properties

- [Documentation](https://developers.messagebird.com/api/voice-messaging/)
- [OpenAPI](openapi/messagebird-voice-messaging-openapi.yml)

### MessageBird Conversations API
The MessageBird Conversations API provides a unified interface for managing omnichannel messaging across platforms such as SMS, WhatsApp, Facebook Messenger, Telegram, and more. It consolidates messages from multiple channels into a single conversation thread per contact, enabling consistent customer communication. The API supports sending and receiving messages, managing conversation state, and handling webhooks for real-time event processing.

**Human URL:** [https://developers.messagebird.com/api/conversations/](https://developers.messagebird.com/api/conversations/)


#### Tags:

 - Omnichannel, Messaging, WhatsApp, Chat, Communications

#### Properties

- [Documentation](https://developers.messagebird.com/api/conversations/)
- [OpenAPI](openapi/messagebird-conversations-openapi.yml)
- [AsyncAPI](asyncapi/messagebird-conversations-asyncapi.yml)

### MessageBird WhatsApp API
The MessageBird WhatsApp API allows developers to send and receive WhatsApp messages for alerts, notifications, customer support, and two-factor authentication. It provides access to all WhatsApp Business features through a single API, including template messages, media messages, and interactive message types. The API supports rich media content and provides delivery and read receipts for message tracking.

**Human URL:** [https://developers.messagebird.com/api/whatsapp](https://developers.messagebird.com/api/whatsapp)


#### Tags:

 - WhatsApp, Messaging, Notifications, Communications

#### Properties

- [Documentation](https://developers.messagebird.com/api/whatsapp)
- [OpenAPI](openapi/messagebird-whatsapp-openapi.yml)

### MessageBird Verify API
The MessageBird Verify API provides a simple way to implement two-factor authentication and phone number verification. It generates and validates one-time passwords delivered via SMS or voice call, handling token generation, delivery, and verification in a single workflow. The API supports configurable token length, expiration time, and delivery channel selection for flexible integration into sign-up and login flows.

**Human URL:** [https://developers.messagebird.com/api/verify/](https://developers.messagebird.com/api/verify/)


#### Tags:

 - Verification, Two-Factor Authentication, Security, OTP

#### Properties

- [Documentation](https://developers.messagebird.com/api/verify/)
- [OpenAPI](openapi/messagebird-verify-openapi.yml)

### MessageBird Lookup API
The MessageBird Lookup API enables developers to validate and look up mobile phone numbers. It performs HLR lookups on the mobile network to identify number format, country, operator, and availability in real-time. The API is useful for cleaning contact lists, validating user-provided phone numbers, and determining the correct format before sending messages.

**Human URL:** [https://developers.messagebird.com/api/lookup/](https://developers.messagebird.com/api/lookup/)


#### Tags:

 - Phone Numbers, Validation, HLR, Number Intelligence

#### Properties

- [Documentation](https://developers.messagebird.com/api/lookup/)
- [OpenAPI](openapi/messagebird-lookup-openapi.yml)

### MessageBird HLR API
The MessageBird HLR API provides a way to send Home Location Register network queries to any mobile number globally. It allows developers to determine which operator a mobile number belongs to in real-time and check whether the number is currently active on the network. This API is commonly used for number portability checks, fraud prevention, and optimizing message routing.

**Human URL:** [https://developers.messagebird.com/api/hlr/](https://developers.messagebird.com/api/hlr/)


#### Tags:

 - HLR, Network Query, Phone Numbers, Mobile Network

#### Properties

- [Documentation](https://developers.messagebird.com/api/hlr/)
- [OpenAPI](openapi/messagebird-hlr-openapi.yml)

### MessageBird Contacts API
The MessageBird Contacts API allows developers to manage contact information for end-users and customers across messaging platforms. It supports creating, reading, updating, and deleting contacts, as well as organizing them into groups for targeted messaging campaigns. A single contact can be associated with multiple communication channels such as SMS, WhatsApp, and Telegram.

**Human URL:** [https://developers.messagebird.com/api/contacts/](https://developers.messagebird.com/api/contacts/)


#### Tags:

 - Contacts, Address Book, Customer Data, Groups

#### Properties

- [Documentation](https://developers.messagebird.com/api/contacts/)
- [OpenAPI](openapi/messagebird-contacts-openapi.yml)

### MessageBird Numbers API
The MessageBird Numbers API enables developers to search for, purchase, and manage phone numbers programmatically. It supports local, toll-free, and mobile number types across multiple countries, with the ability to filter by pattern, type, and region. Purchased numbers can be configured for SMS and voice capabilities and assigned to specific messaging or calling workflows.

**Human URL:** [https://developers.messagebird.com/api/numbers/](https://developers.messagebird.com/api/numbers/)


#### Tags:

 - Phone Numbers, Number Management, Provisioning, Telecommunications

#### Properties

- [Documentation](https://developers.messagebird.com/api/numbers/)
- [OpenAPI](openapi/messagebird-numbers-openapi.yml)

### MessageBird Balance API
The MessageBird Balance API provides developers with access to their account balance information. It returns the current payment type, available amount, and currency for the account associated with the API key. This API is useful for monitoring credit usage, building billing dashboards, and setting up automated alerts when account balances fall below a threshold.

**Human URL:** [https://developers.messagebird.com/api/balance/](https://developers.messagebird.com/api/balance/)


#### Tags:

 - Balance, Account, Billing, Credits

#### Properties

- [Documentation](https://developers.messagebird.com/api/balance/)
- [OpenAPI](openapi/messagebird-balance-openapi.yml)

### MessageBird Integrations API
The MessageBird Integrations API allows developers to create, fetch, and delete message templates for supported platforms. It currently supports template management for the WhatsApp platform, enabling developers to programmatically manage the templates required for sending WhatsApp Business notifications and messages. The API handles template submission, approval status tracking, and lifecycle management.

**Human URL:** [https://developers.messagebird.com/api/integrations/](https://developers.messagebird.com/api/integrations/)


#### Tags:

 - Integrations, Templates, WhatsApp, Message Templates

#### Properties

- [Documentation](https://developers.messagebird.com/api/integrations/)
- [OpenAPI](openapi/messagebird-integrations-openapi.yml)

## Common Properties

- [Developer Portal](https://developers.messagebird.com/)
- [Documentation](https://developers.messagebird.com/api/)
- [Website](https://messagebird.com/)
- [TermsOfService](https://messagebird.com/en/legal/terms-of-service)
- [PrivacyPolicy](https://messagebird.com/en/legal/privacy)
- [Support](https://support.messagebird.com/)
- [Blog](https://messagebird.com/blog)
- [Login](https://dashboard.messagebird.com/login)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
