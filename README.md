<p align="center">
  <img src="images/box-dev-logo.png" alt= “box-dev-logo” width="30%" height="50%">
</p>

# Official Box Tools

The following tools are actively developed and supported by Box. These tools
receive regular product updates, as well as security updates.

# SDKs & Tools

The following SDKs and tools are developed and supported by Box.

## SDKs

The table lists Box SDKs that you can use
when building your applications.

|                                      | Tool                                                                                          | Maintained?                         | Parity?   |
| ------------------------------------ | --------------------------------------------------------------------------------------------- | ----------------------------------- | --------- |
| [![Java][javaimg]][javasdk]          | [Java SDK][javasdk] - Use the Box content APIs from your Java application                     | ☑️ Full                             | ☑️ Full   |
| [![.NET][dotnetimg]][dotnetsdk]      | [.NET SDK][dotnetsdk] - Use the Box content APIs from your .NET application                   | ☑️ Full                             | ☑️ Full   |
| [![Python][pythonimg]][pythonsdk]    | [Python SDK][pythonsdk] - Use the Box content APIs from your Python application               | ☑️ Full                             | ☑️ Full   |
| [![Node][nodeimg]][nodesdk]          | [Node SDK][nodesdk] - Use the Box content APIs from your JavaScript or TypeScript application | ☑️ Full                             | ☑️ Full   |
| [![iOS][iosimg]][iossdk]             | [iOS Content SDK][iossdk] - Use the Box content APIs from your Swift application              | ☑️ Full                             | ☑️ Full   |
| [![Android][androidimg]][androidsdk] | [Android Content SDK][androidsdk] - Use the Box content APIs from your Android app            | End of support as of May 31st, 2023 | 🔸Partial |

> **Maintained:** Fully maintained projects are actively developed by Box. They receive the latest security updates and new features. For support with these projects please visit GitHub or [our Platform support forum](https://community.box.com/box-platform-5).
>
> **API Parity**:  Projects with full API parity are actively updated with all platform functionality as this becomes available on the Box Platform. Projects with partial API parity lack some functionality while we work on bringing these projects to full parity.

## Next generation SDKs

### 🚨 Notice

As of September 17, 2025 Box Next Generation SDKs are no longer supported as separate artifacts. Don't worry, your existing code will continue to work without changes. You can still use your applications based on Box Next Generation SDKs with no impact, but you won't receive new features, updates, or bug fixes. We will be still providing patches for security vulnerabilities until version that combines both artifacts is released. In keeping with industry best practices, we are consolidating the Box Next Generation SDKs and Box core SDKs into a single package for each programming language. This makes migration efforts much easier and allows to seamlessly add new capabilities to existing applications still powered by the manually maintained Box core SDKs. Box Next Generation SDKs are available as the latest major version release (v10) of Box core SDKs. Currently, it’s available as a separate branch called `sdk-gen`.

For more details, see our [SDK versioning strategy document][versioning].

| Platform                            | Maintained?           | API Parity |
| ----------------------------------- | --------------------- | ---------- |
| [Python Gen SDK][pythongensdk]      | 🔸 Only critical bugs | 🔸Partial  |
| [Typescript Gen SDK][tsgensdk]      | 🔸 Only critical bugs | 🔸Partial  |
| [.NET Gen SDK][dotnetgensdk]        | 🔸 Only critical bugs | 🔸Partial  |
| [Java Gen SDK][javagensdk] (Beta)   | 🔸 Only critical bugs | 🔸Partial  |
| [Swift Gen SDK][swiftgensdk] (Beta) | 🔸 Only critical bugs | 🔸Partial  |

## Box CLI

Box CLI is a user-friendly command line tool which
allows both technical and non-technical users to
leverage Box API to perform routine or bulk actions.

| Platform   | Maintained? | API Parity |
| ---------- | ----------- | ---------- |
| [CLI][cli] | Yes         | 🔸Partial  |

## Postman Collection

[Postman][postman] is a tool that lets you build and test HTTP requests in an
easy-to-use interface without configuring a full development environment. The
**Box Postman Collection** is a set of preconfigured requests that make it
possible to get started with the Box API without having to manually configure
the requests.

## UI Libraries

Extend your application with pre-built UI components to browse, share, and
preview files on Box.

|                                                                             |                                                                                      |                                                                                                  |
| --------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ |
| ![Browse][browseimg]                                                        | ![Share][shareimg]                                                                   | ![Preview][previewimg]                                                                           |
| **Browse** Navigate and manipulate your files on Box using our pre-built UI | **Share** Share files with our pre-built UI elements for file & folder collaboration | **Preview** Preview over 120 files types, from PDFs to HD videos, with a rich preview experience |

### Box UI Elements

Box UI Elements are pre-built UI components that allow developers to add elements of the main Box web application into their own applications. They can be used to navigate through, upload, preview, and select content stored on Box and are available both as React components and framework-agnostic JavaScript libraries.

|              | Platform                                              | Maintained? |
| ------------ | ----------------------------------------------------- | ----------- |
| ![JS][jsimg] | **Javascript** [Box UI Elements](doc:box-ui-elements) | ☑️ Full     |

### Mobile

|                        | Platform                                                                                                                                                                                          | Maintained?                         |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------- |
| ![Android][androidimg] | **Android** [Browse SDK](https://github.com/box/box-android-browse-sdk), [Share SDK](https://github.com/box/box-android-share-sdk), [Preview SDK](https://github.com/box/box-android-preview-sdk) | End of support as of May 31st, 2023 |
| ![iOS][iosimg]         | **iOS** [Browse SDK](https://github.com/box/box-ios-browse-sdk), [Share SDK](https://github.com/box/box-ios-share-sdk), [Preview SDK](https://github.com/box/box-ios-preview-sdk)                 | 🔸 Only critical bugs               |

> **Maintained:** Fully maintained projects are actively developed by Box. They receive the latest security updates and new features. For support with these projects please visit GitHub or [our Platform support forum](https://community.box.com/t5/Platform-and-Development-Forum/bd-p/DeveloperForum).

# Unofficial & Community Tools

The following tools are developed by Box and maintained by Box and its community
members. These tools do not receive regular product updates or security updates.

|                              | Tool                                                                                                   | Maintained?                              | Parity?    |
| ---------------------------- | ------------------------------------------------------------------------------------------------------ | ---------------------------------------- | ---------- |
| ![Saleforce][sfimg]          | **[Salesforce SDK][sfsdk]** Use the Box content APIs from your Salesforce application.                 | 🔸 Limited, by Box and community members | 🔸 Partial |
| ![Ruby][rubyimg]             | **[Ruby SDK][rubysdk]** Use the Box content APIs from your server-side Ruby application.               | 🔸 Limited, by Box and community members | 🔸 Partial |
| ![Javascript][jsimg]         | **[Client-Side JS SDK][jssdk]** Use the Box content APIs from your client-side Javascript application. | 🔸 Limited, by Box and community members | 🔸 Partial |
| ![Chrome App SDK][chromeimg] | **[Chrome App SDK][chromesdk]** Use the Box content APIs from your Chrome App.                         | 🔸 Limited, by Box and community members | 🔸 Partial |
| ![R SDK][rimg]               | **[R SDK][rsdk]** Integrate Box APIs into your R workflow.                                             | 🔸 Limited, by Box and community members | 🔸 Partial |

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
[versioning]: https://developer.box.com/guides/tooling/sdks/sdk-versioning/

# Collection of sample code

You can find sample code catalog on [developer website](https://developer.box.com/sample-code/). The abovementioned section aggregates existing demo application built with Box SDKs or CLI and showcases the functionality. Projects that are built by and for the Box developer community.

You can reference it and use it as inspiration. Support for these projects is provided by the individual maintainers and might vary from one project to the next.
