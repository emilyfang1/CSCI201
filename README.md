---
title: "Deployment Guide"
author: Spike Fu
date: April 11, 2021
output: pdf_document
fontsize: 12pt

---
## CSCI_201_Final_Project Deployment Guide
### Prerequisites
The following dependencies are necessary:
- [IntelliJ IDEA - click to download](https://www.jetbrains.com/idea/download/)
setup guide: [Windows](https://www.guru99.com/download-install-node-js.html) | [MacOS](https://www.webucator.com/how-to/how-install-nodejs-on-mac.cfm) | [Linux](https://www.geeksforgeeks.org/installation-of-node-js-on-linux/)
- [NodeJS - click to download](https://nodejs.org/en/) 
setup guide: [Windows](https://www.guru99.com/download-install-node-js.html) | [MacOS](https://www.webucator.com/how-to/how-install-nodejs-on-mac.cfm) | [Linux](https://www.geeksforgeeks.org/installation-of-node-js-on-linux/)
### Step by Step
1. Clone [this repository](https://github.com/Spike-Fu/CSCI_201_Final_Project)
2. Navigate to the front-end folder
3. In the command line run
    ``` bash
    $ npm install //install dependencies in the front-end/node_modules
    ```
    ``` bash
    $ npm start //start up the development server on http://localhost:3000
    ```
4. Open Intellij IDEA
5. If no project is currently opened in IntelliJ IDEA, click **Open** on the welcome screen. Otherwise, select **File | Open** from the main menu.
6. In the dialog that opens, select the back-end folder and click OK. IntelliJ IDEA opens and syncs the project in the IDE.
7. Slect **View | Tool Windows | Gradle**
8. In the Gradle tool window, on the toolbar, click ![alt text](/gradle-common.icons.gradle.jpg "Elephant logo"). Alternatively, press `Ctrl` twice to open the **Run Anything** window.
9.  Select **-run-task-name-goes-here-** and press `Enter`.
10. Go to http://localhost:3000 and enjoy.