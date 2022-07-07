# RevitAPISnippets

Revit API snippets for Visual Studio and JetBrains Rider.

[![Visual Studio 2019](https://img.shields.io/badge/Visual%20Studio%202019-16.11.7+-blue)](#)
[![JetBrains Rider 2022](https://img.shields.io/badge/JetBrains%20Rider%20-2022-blue)](#)
[![Release](https://img.shields.io/github/v/release/mayconrfreitas/RevitAPISnippets)](https://github.com/mayconrfreitas/RevitAPISnippets/releases)
[![Stars](https://img.shields.io/github/stars/mayconrfreitas/RevitAPISnippets)](https://github.com/mayconrfreitas/RevitAPISnippets/stargazers)
[![Forks](https://img.shields.io/github/forks/mayconrfreitas/RevitAPISnippets)](https://github.com/mayconrfreitas/RevitAPISnippets/network/members)
[![Issues](https://img.shields.io/github/issues-raw/mayconrfreitas/RevitAPISnippets)](https://github.com/mayconrfreitas/RevitAPISnippets/issues)
[![Issues](https://img.shields.io/github/issues-closed-raw/mayconrfreitas/RevitAPISnippets)](https://github.com/mayconrfreitas/RevitAPISnippets/issues?q=is%3Aissue+is%3Aclosed)
[![Contributors](https://img.shields.io/github/contributors/mayconrfreitas/RevitAPISnippets)](https://github.com/mayconrfreitas/RevitAPISnippets/graphs/contributors)
[![License MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)


## Installation For Visual Studio

1. [Download](https://github.com/mayconrfreitas/RevitAPISnippets/archive/refs/heads/main.zip) or [clone](git-client://clone?repo=https%3A%2F%2Fgithub.com%2Fmayconrfreitas%2FRevitAPISnippets) this repo;
2. On Visual Studio, go to `Tools > Code Snippets Manager...` or press <kbd>Ctrl</kbd> + <kbd>K</kbd> and <kbd>Ctrl</kbd> + <kbd>B</kbd>;
3. Click on `Add` button.
4. Navigate to the folder where you saved this repo;
5. Open the repo [`Folder > Snippets`](./Snippets/) and Select the RevitAPI folder according to your Revit version (E.g.: [`RevitAPI2020`](./Snippets/RevitAPI2020/));
6. Click on `OK`.

## Installation For JetBrains Rider
Download the Settings File (.zip) for Rider and Import to your project. You can leave this file zipped as when we import these settings, we will need a zip file.

After download, open Rider. Click on File > Manage IDE Settings > Import Settings... 

![](.\Source\images\rider_importSettings.png)

Navigate to the zip file downloaded and click "Select Folder".

![](.\Source\images\rider_importSettingsDialog.png)

You should see a new dialog display that asks if you desire to import the Live Templates

![](.\Source\images\rider_importSettingsSelection.png)

Finally, Restart Rider.

![](.\Source\images\rider_importSettingsFinal.png)

## How to use

1. After installation, type the command (as in the [Snippets List](#snippets)) `command` and press <kbd>tab</kbd> 2x;
<p>
	<img width="800" src="./Source/gifs/howtouse_01.gif" alt="Revit API Snippets - Example of snippet">
</p>

2. Use <kbd>tab</kbd> to navigate through fields and edit them as you wish;
<p>
	<img width="800" src="./Source/gifs/howtouse_02.gif" alt="Revit API Snippets - Example of snippet">
</p>

3. Press <kbd>enter</kbd> to complete the command.

<br />

### [![Youtube logo](./Source/images/youtube-logo.png)](https://youtu.be/moD7CYUkJHw) Watch this [video](https://youtu.be/moD7CYUkJHw) to see a more detailed use of Revit API snippets.

<br />

---

## Snippets

Below is a hyperlink to each individual .snippet for Visual Studio. JetBrains Rider code is the exact same, but the settings cannot be visualized the same way on GitHub.

List of snippets ready to use:

| Command (Visual Studio)                                                                        | Description                                                                          |
|------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------|
| [rvtiexcom](./Snippets/RevitAPI2020/CreateIExternalCommand.snippet)                            | Creates a sample of a IExternal Command implemented with the main codes.             |
| [rvtallinstcat](./Snippets/RevitAPI2020/Collector/CollectAllInstancesByCategory.snippett)      | Collects all instances in the project by the builtin category.                       |
| [rvtalltypescat](./Snippets/RevitAPI2020/Collector/CollectAllTypesByCategory.snippet)          | Collects all element types in the project by the builtin category.                   |
| [rvtgetparamdoub](./Snippets/RevitAPI2020/Parameters/GetParameterValueAsDouble.snippet)        | Gets a parameter value as a double.                                                  |
| [rvtgetparamelmid](./Snippets/RevitAPI2020/Parameters/GetParameterValueAsElementId.snippet)    | Gets a parameter value as an ElementId.                                              |
| [rvtgetparamint](./Snippets/RevitAPI2020/Parameters/GetParameterValueAsInteger.snippet)        | Gets a parameter value as an integer.                                                |
| [rvtgetparamstr](./Snippets/RevitAPI2020/Parameters/GetParameterValueAsString.snippet)         | Get Parameter Value As String.                                                       |
| [rvtgetparamvalstr](./Snippets/RevitAPI2020/Parameters/GetParameterValueAsValueString.snippet) | Get Parameter Value As Value String.                                                 |
| [rvtsetparam](./Snippets/RevitAPI2020/Parameters/SetParameterValue.snippet)                    | Set Parameter Value.                                                                 |
| [rvtsetparamstr](./Snippets/RevitAPI2020/Parameters/SetParameterValueString.snippet)           | Set Parameter Value String.                                                          |
| [rvtselfilt](./Snippets/RevitAPI2020/Selection/CreateSelectionFilter.snippet)                  | Creates a sample of a Selection Filter code implementing ISelectionFilter interface. |
| [rvtgetsel](./Snippets/RevitAPI2020/Selection/GetSelectedElements.snippet)                     | Gets the elements in the model.                                                      |
| [rvtpickelms](./Snippets/RevitAPI2020/Selection/SelectElements.snippet)                        | Creates a selection of elements in the model.                                        |
| [rvttrans](./Snippets/RevitAPI2020/Transactions/CreateTransaction.snippet)                     | Creates a sample of a Transaction code.                                              |
---

## Contributors

If you have any snippets that you think might be interesting to share, follow the steps below to contribute to this project:

### Instructions
1. [Fork](https://github.com/mayconrfreitas/RevitAPISnippets/fork) this repo;
2. Use the `template` inside [`Snippets > Templates > Csharp.snippet`](./Snippets/Templates/Csharp.snippet);
3. Use the **prefix** `rvt` to name your **shortcut** (E.g.: `rvt` + `getsel` (abbreviation to Get Selection) = [`rvtgetsel`](./Snippets/RevitAPI2020/Selection/GetSelectedElements.snippet));
4. **Be sure** that your shortcut doesn't exist in the [Snippets List](#snippets);
5. Write your snippets in **individual files** grouped inside folders of their **respective subject** (E.g.: [rvtselfilt](./Snippets/RevitAPI2020/Selection/CreateSelectionFilter.snippet) is inside [Selection](./Snippets/RevitAPI2020/Selection/) folder);
6. `Commit` and `Push` your changes to your forked repo;
7. Send a `Pull Request` to [Develop branch](https://github.com/mayconrfreitas/RevitAPISnippets/tree/develop).

### More Information

For more information, feel free to contact me via email `mayconrfreitas@gmail.com` or [LinkedIn](https://www.linkedin.com/in/maycon-freitas/).

---

## License

This project is [licensed](LICENSE) under the [MIT Licence](https://en.wikipedia.org/wiki/MIT_License).

---

Do you like this solution? Please [star this project on GitHub](../../stargazers)!