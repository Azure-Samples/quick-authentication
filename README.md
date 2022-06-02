---
page_type: sample
languages:
- html
- javascript
products:
- microsoft-authentication-library
---

# Integrating Microsoft Quick Authentication

Microsoft Quick Authentication offers you the ability to let your users sign up and sign in to your website using a Microsoft Account (MSA). You are likely familiar with similar offerings from other providers (e.g., “Sign in with ________”) and this offering provides that same capability to connect with people who use Microsoft products and cloud services, such as Outlook, OneDrive, Xbox LIVE, and Microsoft 365.

## Getting Started

### Prerequisites

1. An active [Azure account](https://signup.azure.com/) (free)
1. An application registered in Azure
    1. Go to [Register an application](https://ms.portal.azure.com/#blade/Microsoft_AAD_IAM/ActiveDirectoryMenuBlade/RegisteredApps)
    1. Select **New registration**
    1. Enter a name for your application (e.g., "Contoso - Sign in With Microsoft")
    1. Under **Supported Account Types**, select "Personal Microsoft Accounts Only"
    1. Provide a Redirect URI with the “Single-page application (SPA)” option; at this time, we recommend that you use `*your domain*/blank.html` and that you serve a blank page at that endpoint
    1. Complete the process by clicking "Register"

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
