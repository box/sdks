<p align="center">
  <img src="images/box-dev-logo.png" alt= “box-dev-logo” width="30%" height="50%">
</p>

# Official Box Tools

The following tools are actively developed and supported by Box. These tools
receive regular product updates, as well as security updates. 

# SDKs & Tools

The following SDKs and tools are developed and supported by Box.

## SDKs

Here you will find a list of SDKs
you can use to build your application.
Separately, we have listed the next generation
Python, Typescript, and .NET SDKs, which are the
newest addition.
.NET is still a beta feature, but we encourage
you to give it a try and explore all the
features they bring along.


### Next generation SDKs

The latest generation of SDKs are designed to elevate the developer
experience and streamline your integration
with the Box Content Cloud.


Here's what you can expect from the new SDKs:

* **Full API Support**: New Box SDKs empower developers with complete coverage of the Box API ecosystem. You can access all the latest features and functionalities offered by Box and build feature-rich applications.
* **Rapid API Updates**: The new auto-generation development approach allows for adding Box APIs to SDKs at a much faster pace (in a matter of days). This means you can leverage the most up-to-date features in your applications without delay.
* **Embedded Documentation**:  All objects and parameters are documented directly in the source code of the SDK so all the necessary information is stored in one place.
* **Enhanced Convenience Methods**: The newly introduced convenience methods cover various aspects such as authentication, chunk uploads, exponential back-offs, automatic retries, type checkers which help to ensure that you’re using variables correctly, and much more.

| Platform                             | Maintained?  | API Parity |
|--------------------------------------| ----------- | ------- |
| [Python Gen SDK][pythongensdk]       | Yes         | Full    |
| [Typescript Gen SDK][tsgensdk]       | Yes         | Full    |
| [.NET Gen SDK][dotnetgensdk]         | Yes         | Full    |
| [Java Gen SDK][javagensdk] (Beta)    | Yes         | Full    |
| [Swift Gen SDK][swiftgensdk] (Beta)  | Yes         | Full    |



### SDKs

The table lists Box SDKs that you can use
when building your applications.

| | Tool | Maintained? | Parity? |
|-|------|-------------|---------|
| [![Java][javaimg]][javasdk] | [Java SDK][javasdk] - Use the Box content APIs from your server-side Java application | ☑️ Full | ☑️ Full |
| [![.NET][dotnetimg]][dotnetsdk] | [.NET SDK][dotnetsdk] - Use the Box content APIs from your server-side .NET application | ☑️ Full | ☑️ Full |
| [![Python][pythonimg]][pythonsdk] | [Python SDK][pythonsdk] - Use the Box content APIs from your server-side Python application | ☑️ Full | ☑️ Full |
| [![Node][nodeimg]][nodesdk] | [Node SDK][nodesdk] - Use the Box content APIs from your server-side Node application | ☑️ Full | ☑️ Full |
| [![CLI][cliimg]][cli] | [CLI][cli] - Use the Box content APIs from your command line | ☑️ Full | ☑️ Full |
| [![iOS][iosimg]][iossdk] | [iOS Content SDK][iossdk] - Use the Box content APIs from your iOS app | ☑️ Full | 🔸Partial |
| [![Android][androidimg]][androidsdk] | [Android Content SDK][androidsdk] - Use the Box content APIs from your Android app | End of support as of May 31st, 2023 | 🔸Partial |

> **Maintained:** Fully maintained projects are actively developed by Box. They receive the latest security updates and new features. For support with these projects please visit GitHub or [our Platform support forum](https://community.box.com/t5/Platform-and-Development-Forum/bd-p/DeveloperForum).
> 
> **API Parity**:  Projects with full API parity are actively updated with all platform functionality as this becomes available on the Box Platform. Projects with partial API parity lack some functionality while we work on bringing these projects to full parity.

## Box CLI

Box CLI is a user-friendly command line tool which
allows both technical and non-technical users to
leverage Box API to perform routine or bulk actions.

| Platform                          | Maintained?  | API Parity |
| --------------------------------- | ----------- | ------- |
| [CLI][cli]                        | Yes         | Full    |

## Postman Collection

[Postman][postman] is a tool that lets you build and test HTTP requests in an
easy-to-use interface without configuring a full development environment. The
**Box Postman Collection** is a set of preconfigured requests that make it
possible to get started with the Box API without having to manually configure
the requests.


## UI Libraries

Extend your application with pre-built UI components to browse, share, and
preview files on Box.

|   |   |   |
| - | - | - |
| ![Browse][browseimg] | ![Share][shareimg] | ![Preview][previewimg] |
| **Browse** Navigate and manipulate your files on Box using our pre-built UI | **Share** Share files with our pre-built UI elements for file & folder collaboration | **Preview** Preview over 120 files types, from PDFs to HD videos, with a rich preview experience |

| | Platform | Maintained? | 
|-|-|-|
| ![Android][androidimg] | **Android** [Browse SDK](https://github.com/box/box-android-browse-sdk), [Share SDK](https://github.com/box/box-android-share-sdk), [Preview SDK](https://github.com/box/box-android-preview-sdk) | ☑️ Full |
| ![iOS][iosimg] | **iOS** [Browse SDK](https://github.com/box/box-ios-browse-sdk), [Share SDK](https://github.com/box/box-ios-share-sdk), [Preview SDK](https://github.com/box/box-ios-preview-sdk) | ☑️ Full |
| ![JS][jsimg] | **Javascript** [Box UI Elements](doc:box-ui-elements) | ☑️ Full |

> **Maintained:** Fully maintained projects are actively developed by Box. They receive the latest security updates and new features. For support with these projects please visit GitHub or [our Platform support forum](https://community.box.com/t5/Platform-and-Development-Forum/bd-p/DeveloperForum).

# Unofficial & Community Tools

The following tools are developed by Box and maintained by Box and its community
members. These tools do not receive regular product updates or security updates.

| | Tool | Maintained? | Parity? |
|-|------|-------------|---------|
| ![Saleforce][sfimg] | **[Salesforce SDK][sfsdk]** Use the Box content APIs from your Salesforce application. | 🔸 Limited, by Box and community members | 🔸 Partial |
| ![Ruby][rubyimg] | **[Ruby SDK][rubysdk]** Use the Box content APIs from your server-side Ruby application. | 🔸 Limited, by Box and community members | 🔸 Partial |
| ![Javascript][jsimg] | **[Client-Side JS SDK][jssdk]** Use the Box content APIs from your client-side Javascript application. | 🔸 Limited, by Box and community members | 🔸 Partial |
| ![Chrome App SDK][chromeimg] | **[Chrome App SDK][chromesdk]** Use the Box content APIs from your Chrome App. | 🔸 Limited, by Box and community members | 🔸 Partial |
| ![R SDK][rimg] | **[R SDK][rsdk]** Integrate Box APIs into your R workflow. | 🔸 Limited, by Box and community members | 🔸 Partial |

> **Maintained:** Projects with limited maintenance are updated by Box in collaboration with the community. They receive irregular security updates. If you are a Box customer on a premium support plan, please contact customer services for any urgent feature requests for these tools. For other support queries with these projects please visit GitHub or [our Platform support forum](https://community.box.com/t5/Platform-and-Development-Forum/bd-p/DeveloperForum).
> 
> **API Parity:**  Projects with limited API parity can lack some functionality as new features are not automatically rolled out to these projects as they become available for the Box Platform. If you are a Box customer on a premium support plan, please contact customer services for any urgent feature requests for these tools.

[pythongensdk]: https://github.com/box/box-python-sdk-gen
[tsgensdk]: https://github.com/box/box-typescript-sdk-gen
[dotnetgensdk]: https://github.com/box/box-dotnet-sdk-gen
[javagensdk]: https://github.com/box/box-java-sdk-gen
[swiftgensdk]: https://github.com/box/box-swift-sdk-gen
[javaimg]: images/java.png
[javasdk]: https://github.com/box/box-java-sdk
[dotnetimg]: images/dotnet.png
[dotnetsdk]: https://github.com/box/box-windows-sdk-v2
[pythonimg]: images/python.png
[pythonsdk]: https://github.com/box/box-python-sdk
[nodeimg]: images/node.png
[nodesdk]: https://github.com/box/box-node-sdk
[cliimg]: images/cli.png 
[cli]: https://github.com/box/boxcli
[iosimg]: images/ios.png
[iossdk]: https://github.com/box/box-ios-sdk
[androidimg]: images/android.png
[androidsdk]: https://github.com/box/box-android-sdk
[browseimg]: images/browse.jpg
[shareimg]: images/share.jpg
[previewimg]: images/preview.jpg
[jsimg]: images/js.png
[jssdk]: https://github.com/allenmichael/box-javascript-sdk
[sfimg]: images/salesforce.png
[sfsdk]: https://github.com/box/box-salesforce-sdk
[rubyimg]: images/ruby.png
[rubysdk]: https://github.com/cburnette/boxr
[chromeimg]: images/chrome.png
[chromesdk]: https://github.com/box/Chrome-App-SDK
[rimg]: images/rlogo.png
[rsdk]: https://github.com/r-box/boxr
[postman]: https://developer.box.com/guides/tooling/postman/quick-start

# Collection of sample code
You can find sample code catalog on [developer website](https://developer.box.com/sample-code/). The abovementioned section aggregates existing demo application built with Box SDKs or CLI and showcases the functionality. Projects that are built by and for the Box developer community.

You can reference it and use it as inspiration. Support for these projects is provided by the individual maintainers and might vary from one project to the next.
