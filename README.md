# Integrating Microsoft Quick Authentication

Microsoft Quick Authentication offers you the ability to let your users sign up and sign in to your website using a Microsoft Account (MSA). You are likely familiar with similar offerings from other providers (e.g., “Sign in with ________”) and this offering provides that same capability to connect with people who use Microsoft products and cloud services, such as Outlook, OneDrive, Xbox LIVE, and Microsoft 365.

## Getting Started

### Prerequisites

In order to use Quick Authentication, you will need to register your website with Azure. To do that

1. [Sign up for an Azure account](https://signup.azure.com/) (if you don’t have one already)
1. Navigate to your [Registered Apps](https://ms.portal.azure.com/#blade/Microsoft_AAD_IAM/ActiveDirectoryMenuBlade/RegisteredApps)
1. Select "New registration"
1. Enter a name for your application (e.g., "Contoso - Sign in With Microsoft")
1. Select "Personal Microsoft Accounts Only" under "Supported Account Types"
1. Enter a Redirect URI; we recommend setting up your website to serve a blank page at a specific URL and entering that URL here (for example, `http://*your domain*/blank.html`)
1. Choose "Single-page application (SPA)" when registering the Redirect URI
1. Click the "Register" button to complete the process

If you’d like to see the enhanced sign-in experience in Microsoft Edge:

1. Download Canary build of Edge from [Microsoft Edge Insider](https://www.microsoftedgeinsider.com/en-us/download/)
1. Open Edge Canary and navigate to [edge://flags/#edge-enable-easy-auth-private](edge://flags/#edge-enable-easy-auth-private)
1. Toggle it to "Enabled" and click the "Restart" button.


### Installation

- ...

### Quickstart

1. git clone [repository clone url]
2. cd [repository name]
3. ...


## Demo

This project includes demonstrations of the three different ways you can integrate Quick Authentication:

* [HTML-based Configuration](./demos/quick_auth_markup.html)
* [JavaScript-based Configuration](./demos/quick_auth_js.html)
* [Custom Integration](./demos/quick_auth_custom.html)

## Resources

- ...
