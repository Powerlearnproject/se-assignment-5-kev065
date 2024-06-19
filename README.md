[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15290271&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code: Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed

   - Visit the official vs code [website](https://code.visualstudio.com/download).
   - Click the download button and select the version compatible with Windows 11.
   - The download should start automatically.
   - Locate the downloaded installer file i.e. VSCodeSetup.exe in the Downloads folder.
   - Double-click on it to start the installation process.
   - Accept the License Agreement by checking the box to accept the terms and conditions.
   - Click "Next" to proceed.
   - Select the folder where you want Visual Studio Code to be installed. Accept the default directory as suggested.
   - Choose the option to create a desktop icon.
   - Click "Install" to begin the installation process.
   - Check the box to launch VS Code immediately after installation, or you can launch it manually after installation from the windows start menu or from the desktop icon.

2. First-time Setup: After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.
   - Install the following extensions: Python, Dart, Flutter, Thunder Client and Github Theme.
   - Settings: Access settings by clicking the gear icon (⚙️) in the bottom left corner and selecting “Settings.” You can change the following: font size, line height, default language mode, tab size, and auto-save preference.

3. User Interface Overview: Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.
   - Activity Bar: It's located on the left and it lets us switch between different views (e.g, Explorer, Source Control, Extensions and the Remote Explorer).
   - Editor Group: This is the area where you edit your files. You can open multiple editors side by side vertically or horizontally. Also enables us to customize font size, line height, and other visual preferences here.
   - Status Bar: Located at the bottom, it provides information about the opened project, the file you’re editing, and active extensions. 

4. Command Palette: What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.
   - The Command Palette in VS Code is a tool that allows us to access various features, commands, and settings directly through keyboard shortcuts. 
   - To access it, press `Ctrl+Shift+P`. 
   - Then start typing to search for a specific command by name.
   - Common tasks you can perform using the Command Palette include: 
      - Running commands (e.g., opening files, formatting code).
      - Changing settings (e.g., adjusting font size, theme).
      - Installing extensions. 
      - Git-related actions (e.g., committing changes, switching branches).

5. Extensions in VS Code: Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.
   - Finding Extensions 
      - Open VS Code and click the Extensions icon in the Activity Bar. Alternatively, you can use the shortcut `Ctrl+Shift+X`.
      - Search for extensions by name or functionality in VS code Marketplace.
      
   - Installing Extensions
      - When you find the extension you're looking for click the `Install` button.

   - Managing Extensions
      - Click the gear icon next to an installed extension to configure settings or disable it. 
      - Keep your extensions up to date for the best experience. 

6. Integrated Terminal: Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?
   - You can open the integrated terminal in VS Code using the following methods:
      - Type `Ctrl+backtick`
      - Click `View > Terminal` from the menu.

   - Advantages of the Integrated Terminal
      - Seamless Integration: The integrated terminal is part of VS Code, so you don’t need to switch between different apps.
      - Context Awareness: It automatically opens in the workspace directory of your current file, making it contextually relevant.
      - Customization: You can choose your preferred shell (e.g., PowerShell, Command Prompt, Git Bash) and configure it within VS Code.
      - Split View: You can split the terminal horizontally or vertically alongside the regular code editor.
      - Direct Interaction: Execute commands, run scripts, and manage Git directly from the terminal.
      - Output Capture: Terminal output (e.g., build logs, test results) is captured within VS Code, making it easier to review.

7. File and Folder Management: Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?
   - Opening a Folder:
      - To open a folder, use `File > Open Folder` from the menu.
      - Alternatively, from the terminal, to launch the current folder in VS code, type `code .` 

   - Explorer View:
      - Once a folder is opened, its contents appear in the Explorer view. Here, you can:
         - Create, delete, and rename files and folders.
         - Move files and folders using drag and drop.


8. Settings and Preferences: Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

   -  You can customize VS code through the Settings editor. Here’s how:
      - Open the Settings Editor:
         - Navigate to `File > Preferences > Settings`.

      - Alternatively, use the Command Palette by clicking `Ctrl+Shift+P` and search for Preferences: Open Settings.

   - To change the theme, search for `Color Theme` in settings and select your preferred theme.
   - Adjust font size by searching for `Font Size` and modifying the value.
   - Customize keybindings by searching for `Keybindings` and editing the JSON file.

9. Debugging in VS Code: Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

   - Setting Up Debugging
      - Open the Run and Debug view: Click the Run and Debug icon in the left sidebar or use the shortcut `Ctrl+Shift+D`.
      - Create a launch.json file.
         - In the Run and Debug view, click "Create a launch.json file."
         - VS Code will automatically detect your program's type (e.g., Python, Dart etc) and create a basic configuration. This file can be customized later for more complex scenarios.

   - Starting Debugging
      - Set a breakpoint: Click in the left margin next to the line of code where you want execution to pause. A red dot appears, indicating the breakpoint.

      - Run the program in debug mode:
         - Click the green `Run and Debug` button (play icon) in the Run and Debug view.
         - Alternatively, use the shortcut F5.

   - Key Debugging Features in VS Code
      - Breakpoints: Control program execution by pausing at specific lines.
      - Stepping: Navigate code line by line:
         - Step Over (F10): Execute the current line and skip over function calls.
         - Step Into (F11): Enter a function call and debug its internal code.
         - Step Out (Shift+F11): Exit the current function and continue execution.
      - Call Stack: View the hierarchy of function calls, allowing you to see how the program reached the current point.
      - Variables: Inspect the values of variables at any point during execution.
      - Expressions: Evaluate custom expressions within the debugger to check calculations or data structures.
      - Console: Interact with your program's standard output stream for logging or debugging messages.
      - Watches: Monitor the values of specific variables in real time as the program runs.
      - Source Control Integration: Step through code changes and see how they affect program behavior.

10. Using Source Control: How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.
   - Initialize a Repository:
      - Open your project folder in VS Code.
      - Click the Source Control icon in the Activity Bar on the left.
      - Initialize a new Git repository by clicking “Initialize Repository.”

   - Make Commits:
      - Create or modify files in your project and save your changes.
      - Click the `+` icon next to a file to stage changes.
      - Add a commit message and press `Ctrl+Enter` to commit.
      - Staged changes are now committed.

   - Push to GitHub:
      - Click the three dots (…) in the Source Control view and choose “Push.”
      - Select the branch to push to.
      - Your changes are now on GitHub.


## References
1. [How to Install Visual Studio Code in Windows 11: A Step-by-Step Guide](https://www.supportyourtech.com/articles/how-to-install-visual-studio-code-in-windows-11-a-step-by-step-guide/)
2. [VS Code - User Interface](https://riptutorial.com/visual-studio-code/learn/100006/user-interface)
3. [VS Code - Get the basics right!](https://microsoft.github.io/vscode-essentials/en/02-basics.html)
4. [Top 15 Best Visual Studio Code Extensions For Web Development](https://codeforgeek.com/best-visual-studio-code-extensions-web-development/)
5. [Personalize Visual Studio Code](https://code.visualstudio.com/docs/introvideos/configure)
6. [VS Code - Debugging](https://vscode-docs.readthedocs.io/en/latest/editor/debugging/)
7. [How to Use Version Control in Visual Studio Code](https://codingcampus.net/how-to-use-version-control-in-visual-studio-code/)
8. [Organizing Folders in Visual Studio Code: A Better Way for Grouping Files](https://devcodef1.com/news/1110545/organizing-folders-in-vs-code)



