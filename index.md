<script src="//code.tidio.co/ozbdrimnhdmec3oucu580m1ut2acp6i1.js" async></script>

![Logo](mallabee-logo.png)

## mallabee Toolchain

### What is it?

mallabee Toolchain is a collective API of resource type based tools.

We create a set of technological advanced, super simple web tools.

We strive to make the APIs for the public use - we do that by allowing others to easily interact and automate (e.g.: using [**Zapier**](https://zapier.com/developer/public-invite/110808/ab56aed0459357f3c7aaee1149fedcbd/)).

The tools sit on top of Amazon infrastructure (AWS) to allow scalability as we grow our toolset.

The tools are grouped - each resource / object type has it's functionallities / actions.

### Toolset

The current toolset contains only:

- Images
  - Image Resizing

and lots more to come.. (this is your time to shine and tell us through support what's your needs and request a feature), Check out what the future holds [`here`](#future)..

#### Image Resizing

Check our [**Zapier**](https://zapier.com/developer/public-invite/110808/ab56aed0459357f3c7aaee1149fedcbd/) integration in here to see how you can automate.

##### Integration Use Cases
- Google Drive -> Image Resize -> Google Drive
- DropBox -> Image Resize -> DropBox
- OneDrive -> Image Resize -> OneDrive
- WordPress -> Image Resize -> WordPress
- Image Resize -> GMail (Create email with attachment)
- Image Resize -> GMail (Create draft with attachment)
- Image Resize -> Evernote (Create draft with attachment)
- Image Resize -> Slack (Send to channel / person)

### API

The API is super simple.

All you need in order to start using it is having an API key.

Currently, you can just use a random generated UUID version 4 as API key because the API is free.

You can generate a UUID version 4 API key in [here](https://www.uuidgenerator.net/) (just use the random generated key on the top as your API key, e.g. `ebb6c59f-c00e-4ec3-9cce-41c5eb11d2ba`).

## Postman
<a name="using-postman"> </a>

Postman is an amazing application. It's a tool that allows developers to make HTTP requests extremely easy, save examples, work under different environments, we LOVE it!

Postman is downloadable for free use from [here](https://www.getpostman.com/) and supported with lots of developer docs [here](https://www.getpostman.com/docs/).

We are providing you the full collection of this API for your usage with Postman, this collection includes examples of different requests & responses, the endpoints, documentation to immensely ease your interaction with our API.

After downloading Postman click on the following button to download our collection:

[![Run in Postman](https://run.pstmn.io/button.svg)](https://www.getpostman.com/collections/024261330e9ef06d3789)

You can also view the documentation online in [here](https://documenter.getpostman.com/view/2329721/T1DmCdd4?version=latest)

### Generate code using Postman

Postman allows for easy code generation to use with your favorite language.

After downloading and using our Postman collection follow the GIF below to generate the code for your used language:

![Generate Code-POSTMAN](https://cdn.greeninvoice.co.il/files/ugc/8/c/7/8c7ea6c7af9046e2987ec70ab6e54dcd.gif)


### <a name="future">Toolset Future</a>

#### General Idea

The idea is to open an SDK for programmers and let anyone create a tool based on pre-defined core & core values, performance & scalability.

The API objects are supposed to be "short-lived" objects, that usually doesn't require a database, only a function of a "do" action.

Having a core & core values will potentially allow programmers that use the SDK to create a new tool within a couple of days (even a day) and not weeks.

#### What Does the Core Gives a Programmer

- Logging & Exception Handling
- Background Work Handling (such as webhooks)
- API Key Based Authentication
- AWS Resource Integrations - DynamoDB, S3
- Operations Database (to understand the request & response of operations based on API Key)
- Utilities (such as Image Utilities)
- Hassle-free Zapier Integration
- Testing Framework

#### Some Future Ideas for Tools

- Images
  - Get Image Info (File Type, Width, Height, Size, etc..)
  - Image Compression
  - Image Conversion
  - Analyze Colors
- Websites
  - Website Thumbnail Generation
  - Is Down For Me? (Popular)
  - Make Proxied Request
- URLs
  - Shorten URL (Popular)
- Files
  - File Antivirus Scanning
  - File Upload
  - Zip Files
- Documents
  - Convert Document (PDF to Doc, etc..)
  - Take Image
- Texts
  - Text Difference
- IPs
  - IP to Location
- Proxies
  - Get Proxy
- Currencies
  - Get Currency Conversion Rate (Popular)
- Countries
  - Get Cities
- Phones
  - Parse Phone Number
- UserAgent
  - Parse UserAgent
- Languages
  - Translate
  - Synonyms
  - Talk
- Maps?
  - Path Find
- SMSs?
  - Send SMS
- Emails?
  - Send Transactional Email
- Validations
  - Validate Multiple
  - Validate URL
  - Validate Phone Number

## Support or Contact

Want to request a future feature? Have problems with Zapier integrations? something else?

Use this contact to also tell us what you do - it helps us understand our market!

Contact us at [contact support](https://www.tidio.com/talk/ozbdrimnhdmec3oucu580m1ut2acp6i1) and we’ll help you sort it out.
