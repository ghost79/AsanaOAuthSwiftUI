# AsanaOAuthSwiftUI
AsanaOAuthSwiftUI is an iOS app using SwiftUI and the [OAuthSwift](https://github.com/OAuthSwift/OAuthSwift) library to show how to work with the [Asana Developer API](https://developers.asana.com).

The lack of iOS specific documentation on Asana's API pages makes it challenging, an even more so if you're unfamiliar with OAuth, to get an app to work with their API. AsanaOAuthSwiftUI shows one way of making this work. One of the main challenges with the Asana API is the use of OOB (out of band), without properly explaining what to expect when this is used. Some more info can be found in this [StackOverflow post](https://stackoverflow.com/questions/13522497/what-is-oob-in-oauth).
The main thing with OOB is that there is no redirect back to your app, so you'll have to handle retrieving the token yourself, even when using a library like OAuthSwift. OAuthSwift has a way of doing this described [here](https://github.com/OAuthSwift/OAuthSwift/wiki/API-with-only-HTTP-scheme-into-callback-URL#handle-a-specific-url-into-delegate), although it's not OOB specific.

## Dependencies
AsanaOAuthSwiftUI uses the [OAuthSwift](https://github.com/OAuthSwift/OAuthSwift) library through Swift Package Manager.

## Installation
### Prerequisite
You'll need an Asana account - which you can get at [Asana's website](https://www.asana.com).
And you'll need to register an app with Asana - more info [here](https://developers.asana.com/docs/register-an-application).

### Disclaimer
AsanaOAuthSwiftUI is in no way associated with the company, website or the app [Asana](https://www.asana.com), and is only provided for educational purposes as an example on how to work with [Asana Developer API](https://developers.asana.com). There are no support provided for AsanaOAuthSwiftUI.
