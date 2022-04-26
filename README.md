# Official Box Tools

The following tools are actively developed and supported by Box. These tools
receive regular product updates, as well as security updates. 

## SDK Client Libraries & CLIs

| | Tool | Maintained? | Parity? |
|-|------|-------------|---------|
| [![Java][javaimg]][javasdk] | [Java SDK][javasdk] - Use the Box content APIs from your server-side Java application | ☑️ Full | ☑️ Full |
| [![.NET][dotnetimg]][dotnetsdk] | [.NET SDK][dotnetsdk] - Use the Box content APIs from your server-side .NET application | ☑️ Full | ☑️ Full |
| [![Python][pythonimg]][pythonsdk] | [Python SDK][pythonsdk] - Use the Box content APIs from your server-side Python application | ☑️ Full | ☑️ Full |
| [![Node][nodeimg]][nodesdk] | [Node SDK][nodesdk] - Use the Box content APIs from your server-side Node application | ☑️ Full | ☑️ Full |
| [![CLI][cliimg]][cli] | [CLI][cli] - Use the Box content APIs from your command line | ☑️ Full | ☑️ Full |
| [![iOS][iosimg]][iossdk] | [iOS Content SDK][iossdk] - Use the Box content APIs from your iOS app | ☑️ Full | 🔸Partial |
| [![Android][androidimg]][androidsdk] | [Android Content SDK][androidsdk] - Use the Box content APIs from your Android app | ☑️ Full | 🔸Partial |

> **Maintained:** Fully maintained projects are actively developed by Box. They receive the latest security updates and new features. For support with these projects please visit GitHub or [our Platform support forum](https://community.box.com/t5/Platform-and-Development-Forum/bd-p/DeveloperForum).
> 
> **API Parity**:  Projects with full API parity are actively updated with all platform functionality as this becomes available on the Box Platform. Projects with partial API parity lack some functionality while we work on bringing these projects to full parity.

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

# Collection of sample code
The following sections aggregate existing demo application built with Box SDKs or CLI and showcases the functionality. Projects that are built by and for the Box developer community

You can reference it and use it as inspiration. Support for these projects is provided by the individual maintainers and might vary from one project to the next.

For Box's official SDKs or CLI, and any other officially supported examples make sure to head over to [developer website](https://developer.box.com/).

|  Link   | Description |
|-----|--|
|   [PowerShell Automations](https://github.com/kylefernandadams/box-powershell-automations)  | Box PowerShell Automations are example scripts to help reduce manual overhead for repetitive tasks. |
|    [Box/Jira Integration](https://github.com/goodgrid/etsi-document-control) | The interface between Box and Jira can be used to let a Box Relay workflow signal to Jira that a task can be progressed |
|  [Box Java SDK Samples](https://github.com/box/box-java-sdk-samples)   | Includes example sample that can create Box App User account and leverages webhook and AWS service. |
|    [Box Samples](https://github.com/box/samples) | Repo contains Box SDKs examples in Node, Java, Angular and .Net languages. |
| [Collection of Box Samples](https://github.com/box-community) | List of various sample and demo applications |
| [iOS Example for Browse Files in Box](https://github.com/jlawton/BrowseSDK) | A simple SDK for browsing files stored on Box using iOS. |
