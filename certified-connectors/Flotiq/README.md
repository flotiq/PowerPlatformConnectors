<a href="https://flotiq.com/">
    <img src="https://editor.flotiq.com/fonts/fq-logo.svg" alt="Flotiq logo" title="Flotiq" align="right" height="60" />
</a>

Flotiq connector
================

[Flotiq](https://flotiq.com) is an API-first, headless Content Management System which allows users to easily publish their content through APIs that are dynamically built to support the current content model. You can use Flotiq to store content and consume it in any kind of system. We provide a variety of simple, low-code (or no-code) solutions to integrate systems with Flotiq in order to efficiently work with data. This connector allows you to easily integrate your Microsoft services with Flotiq and exchange data between systems with very little effort.

## Prerequisites

You will need the following to start using the connector:
- Flotiq subscription (you can [register a free Flotiq account here](https://editor.flotiq.com/register.html))
- At least 1 Content Type Definition defined in Flotiq
- At least 1 API key which allows access to the Content Type Definition
- A Microsoft Power Apps plan or
- Microsoft Azure subscription for building Logic Apps.

## Getting Started

1. **Create a Content Type Definition in Flotiq**  
   Follow the guide in [our documentation](https://flotiq.com/docs/panel/content-types/#creating-content-type-definitions) or start with a ready-made example like `"Event"`:

   ![Creating content type in Flotiq](https://api.flotiq.com/image/0x0/_media-bd6699ad-8940-4315-92aa-898ce0a4d091.png)

2. **Generate a scoped API key**  
   Navigate to the API Keys section in Flotiq and [create a new key](https://flotiq.com/docs/API/#user-defined-api-keys).  
   We recommend limiting its scope to only the CTD and operations (e.g., Create, Update) required by the connector.

   ![Scoped API keys in Flotiq](https://api.flotiq.com/image/0x0/_media-12fd9d37-408a-4b1c-b138-ff71296c2811.png)

## Enabling the connector in Logic Apps

   ![flotiq connector authorization](https://api.flotiq.com/image/0x0/_media-4eb8ec6b-ae57-4efb-9a0a-28ec1acbe700.png)

2. **Use the `Create Content Object` action**  
   Choose your target Content Type Definition from the dropdown.  
   Once selected, a dynamic form will appear, letting you map all the CTD’s fields.

   ![Creating event in Flotiq from outlook](https://api.flotiq.com/image/0x0/_media-cb00a2f9-e895-4378-9ec4-52e35670f1ce.png)

3. **Continue building your Logic App**  
   You can now connect Flotiq with other Microsoft services in your workflow.

---

Got questions? Visit [flotiq.com](https://flotiq.com) or reach out via our support channels.
