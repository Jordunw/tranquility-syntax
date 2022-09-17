# Tranquility Syntax

A basic syntax highlighting (and eventually autocompletion) vscode extension for the Tranquility language written by Dr. Stuart of Drexel for his CS164 class.

### [Tranquility Manual](https://www.cs.drexel.edu/~bls96/tranquility.pdf)

---

## Installing the Extension

### Option A - Installing the Provided VSIX
1. Download the VSIX
2. Move the file to your Visual Studio Code extensions folder. This is located in:
    * **Windows:**  %USERPROFILE%\\.vscode\\extensions
    * **MacOS:**    ~/.vscode/extensions
    * **Linux:**    ~/.vscode/extensions
3. Restart Visual Studio Code


### Option B - Packaging and Installing the VSIX Yourself
1. Clone the repository
2. [Install Node.js](https://nodejs.org/en/download)
3. Run `npm install -g vsce`
4. Set directory to extension directory and run `vsce package`
5. Move the file to your Visual Studio Code extensions folder. See above for location.
6. Restart Visual Studio Code

---

## Release Notes

### 1.0.0
- Very basic syntax highlighting implemented. Highlights all std function names, keywords, strings, comments, etc. Variable/function names and numbers are not yet highlighted. No autocompletion.