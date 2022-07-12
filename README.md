# README
You can install this extension pack in VS Code to quickly set up the tools many of our teams use.

# Installation 
The project generates a package file (.vsix) that is installed through the VSCode
1. Download the .vsix file from the Releases section in the sidebar
2. Launch Visual Studio Code
3. Open the command palette <kbd>CTRL/CMD</kbd>+<kbd>SHIFT</kbd>+<kbd>P</kbd>
4. Type `VSIX` and select `Extensions: Install from VSIX...`
5. Select the file you downloaded
6. If you have revised the package and are testing the new file open the command palette and type `Reload` and select a reload window option to ensure successful completion.

# Development
To make changes to this extension pack:

- Clone the repo
- Make your changes.
- Install vsce (the CLI tool for managing VS Code extensions): <br> `$ npm install -g vsce`
- Build the extension file: <br>`$ vsce package`

# Publishing
_We're not currently doing this, and would make the package public if we did._

- Create a publisher: <br>`$ vsce create-publisher <publisher-name>`
- Login: <br>`$ vsce login <publisher-name>`
- Publish <br>`$ vsce publish`

