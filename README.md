# devcenter-quickstarts

Source code for the **Request Signature** and **Embedded Signing** Quickstart examples in the [DocuSign Developer Center](https://www.docusign.com/developer-center).  

**Pre-requisites**

It's free to start using the DocuSign API, you just need:

- DocuSign Developer Sandbox 
- Integrator Key (aka API key).

You can sign-up directly from the Dev Center or [here](https://secure.docusign.com/signup/developer).  Once you activate your developer sandbox you can create your Integrator Key through your account preferences screen.

**Request Signature**

This quickstart shows you how to request a signature on a document. The recipient receives an email that lets them initiate the signing process through the DocuSign Website. Advantages are that recipients do not need to install any software and they can sign using any web browser on any device.

* [Java](1-SignatureRequest/SignatureRequest.java)
* [C#](1-SignatureRequest/SignatureRequest.cs)
* [Node.js](1-SignatureRequest/signatureRequest.js)
* [PHP](1-SignatureRequest/SignatureRequest.php)

**Embedded Signing**

This quickstart shows you how to embed document signing directly into your website or app. This is done by opening a custom signing URL in an iFrame for web or Webview for mobile. Advantages with Embedded Signing are that your users do not need to context-switch out of your UI and wait for an email to arrive to sign documents.

* [Java](2-EmbeddedSigning/EmbeddedSigning.java)
* [C#](2-EmbeddedSigning/EmbeddedSigning.cs)
* [Node.js](2-EmbeddedSigning/embeddedSigning.js)
* [PHP](2-EmbeddedSigning/EmbeddedSigning.php)
