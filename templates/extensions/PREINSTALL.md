<!-- 
This file provides your users an overview of your extension. All content is optional, but this is the recommended format. Your users will see the contents of this file when they run the `firebase ext:info` command.

Include any important functional details as well as a brief description for any additional setup required by the user (both pre- and post-installation).

Learn more about the PREINSTALL.md file in the docs.
-->

Use this extension to send a friendly greeting.

When triggered by an HTTP request, this extension responds with your specified friendly greeting.

# Additional setup
After installing this extension, you'll need to use the Google Cloud console to make the Cloud Function deployed for this extension publicly accessible.

Detailed information for this post-installation task is provided after you install this extension.


<!-- We recommend keeping the following section to explain how billing for Firebase Extensions works -->
# Billing
This extension uses other Firebase or Google Cloud Platform services which may have associated charges:

<!-- List all products the extension interacts with -->
- Cloud Functions

When you use Firebase Extensions, you're only charged for the underlying resources that you use. A paid-tier billing plan is only required if the extension uses a service that requires a paid-tier plan, for example calling to a Google Cloud Platform API or making outbound network requests to non-Google services. All Firebase services offer a free tier of usage. [Learn more about Firebase billing.](https://firebase.google.com/pricing)