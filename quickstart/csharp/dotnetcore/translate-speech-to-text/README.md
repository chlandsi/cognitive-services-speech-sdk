# Quickstart: Translate speech in C# for .NET Core on Windows or Linux

This sample demonstrates how to translate speech with C# under .NET 6.0 (Windows or Linux) using the Speech SDK.
See the [accompanying article](https://docs.microsoft.com/azure/cognitive-services/speech-service/get-started-speech-translation?tabs=script%2Cwindowsinstall&pivots=programming-language-csharp) on the SDK documentation page which describes how to build this sample from scratch in Visual Studio 2017.

> **Note:**
> We currently only support [specific Linux distributions and target architectures](https://docs.microsoft.com/azure/cognitive-services/speech-service/speech-sdk?tabs=linux).

## Prerequisites

* A subscription key for the Speech service. See [Try the speech service for free](https://docs.microsoft.com/azure/cognitive-services/speech-service/get-started).
* A PC (Windows x64 or a supported Linux distribution) with a working microphone.
* Either one of the following:
  * On Windows:
    * [Microsoft Visual Studio 2017](https://www.visualstudio.com/), Community Edition or higher.
    * The **.NET Core cross-platform development** workload in Visual Studio.
      You can enable it in **Tools** \> **Get Tools and Features**.
  * On Windows or Linux:
    * [.NET 6.0](https://dotnet.microsoft.com/download/dotnet/6.0)
    * On Windows you also need the [Microsoft Visual C++ Redistributable for Visual Studio 2015, 2017 and 2019](https://support.microsoft.com/help/2977003/the-latest-supported-visual-c-downloads) for your platform.
* On Linux, see the [Linux platform requirements](https://learn.microsoft.com/azure/ai-services/speech-service/quickstarts/setup-platform?tabs=linux&pivots=programming-language-csharp#platform-requirements) for installing the required dependencies.

## Build the sample

* **By building this sample you will download the Microsoft Cognitive Services Speech SDK. By downloading you acknowledge its license, see [Speech SDK license agreement](https://aka.ms/csspeech/license).**
* [Download the sample code to your development PC.](/README.md#get-the-samples)

* If you are using Microsoft Visual Studio 2017 on Windows:
  * Start Microsoft Visual Studio 2017 and select **File** \> **Open** \> **Project/Solution**.
  * Navigate to the folder containing this sample, and select the solution file contained within it.
* Edit the `Program.cs` source:
  * Replace the string `YourSubscriptionKey` with your own subscription key.
  * Replace the string `YourServiceRegion` with the service region of your subscription.
    For example, replace with `westus` if you are using the 30-day free trial subscription.
* If you are using Microsoft Visual Studio 2017 on Windows, press Ctrl+Shift+B, or select **Build** \> **Build Solution**.
* If you are using the .NET Core CLI, run the following command from the directory that contains this sample:

  ```bash
  dotnet build helloworld/helloworld.csproj
  ```

## Run the sample

### Using Visual Studio 2017

To debug the app and then run it, press F5 or use **Debug** \> **Start Debugging**. To run the app without debugging, press Ctrl+F5 or use **Debug** \> **Start Without Debugging**.

### Using the .NET Core CLI

Run the following command from the directory that contains this sample:

```bash
dotnet helloworld/bin/Debug/net6.0/helloworld.dll
```

## References

* [Quickstart article on the SDK documentation site (Windows)](https://docs.microsoft.com/azure/cognitive-services/speech-service/quickstart-translate-speech-dotnetcore-windows)
* [Speech SDK API reference for C#](https://aka.ms/csspeech/csharpref)
