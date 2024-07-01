

# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

**ANSWERED ASSIGNMENT**

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.

**ANSWERS**

i. **PREREQUISITES**: Laptop or computer should at least have the specs below;
- OS Windows 11
- Processor: 1.6 Ghz or faster
- RAM of 4GB and above (for optimal response)
- Storage space of atleast 500GB (HDD)/256GB(SSD)
- Display resolution of atleast 1024 x 768
- .NET Framework 4.5.2 or better
- Latest version of Git (for Git source control features)
- 
ii. **INSTALLATION**:
Download & installation;
- Visit https://code.visualstudio.com/ (VS Code website)
- Download the installer for windows (stable build)
  
<img src="https://github.com/Powerlearnproject/se-assignment-5-Chilundika/blob/main/Screenshots/1.%20INSTALLER.png" alt="installer" width="300" height="200">
- Run the downloaded installer
- accept the Terms & Conditions
<img src="https://github.com/Powerlearnproject/se-assignment-5-Chilundika/blob/main/Screenshots/2.%20Accept%20Ts%20%26%20Cs.png"alt="Accept Ts & Cs"width="500"height="500">
- Click install button to begin the installation (it took me about a minute to install)
<img src="https://github.com/Powerlearnproject/se-assignment-5-Chilundika/blob/main/Screenshots/3.%20Install.png"alt="Begin installation"width="500"height="500">
<img src="https://github.com/Powerlearnproject/se-assignment-5-Chilundika/blob/main/Screenshots/4.%20Begin%20install.png"alt="Begin installation"width="500"height="500">
- Then click finish to launch the installed VS CODE.
<img src="https://github.com/Powerlearnproject/se-assignment-5-Chilundika/blob/main/Screenshots/5.%20Finish.png"alt="Finish installation"width="500"height="500">
<img src="https://github.com/Powerlearnproject/se-assignment-5-Chilundika/blob/main/Screenshots/6.%20Launched.png"alt="VS Code launched"width="500"height="500">

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

    **ANSWERS**

   i. **Initial Configs & Settings**
    (a).SETTINGS: Navigate to "File > Preferences > Settings"
    - Adjust the font Size, Line height, and font family for better readability
 <img src="https://github.com/Powerlearnproject/se-assignment-5-Chilundika/blob/main/Screenshots/7.%20nav%20to%20settings.png" alt="navigation to settings" width="500" height="500">

 <img src="https://github.com/Powerlearnproject/se-assignment-5-Chilundika/blob/main/Screenshots/7.1.%20font.png" alt="git bash terminal" width="500" height="500">

 - Enabling "Autosave"
 <img src="https://github.com/Powerlearnproject/se-assignment-5-Chilundika/blob/main/Screenshots/8.%20autosave.png" alt="autosave" width="500" height="500">
    - Configure preferred theme or leave it at "Default Dark (My Preference)
    - Sync Settings: used to sync your preferred VS-Code settings, installations and extensions
    
 (b). CONFIGURATIONS for setting up preferred integrated terminal.
    - Git Bash (my preferred terminal)
    
  <img src="https://github.com/Powerlearnproject/se-assignment-5-Chilundika/blob/main/Screenshots/9.%20Git%20Bash%20Terminal.png" alt="git bash terminal" width="500" height="500">
    
 (c). Extentions: The extentions I installed;
 - Prettier - Code formatter
 -  GitLens
 -  Live Server
 -  Path Intellisense
 -  Python
 -  Intellicode
 -  Code runner
 -  HTML CSS Support
 -  Docker
 -  Markdown All in One
 -  Remote - WSL


3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

    **ANSWERS**
   MAIN COMPONENTS OF VS CODE USER INTERFACE:

   (a). ACTIVITY BAR

     The Activity Bar is located on the far left side of the VS Code window. It provides access to different views and features through a series of icons.(The purpose of the Activity Bar is to provide quick navigation between these different functionalities, enhancing workflow efficiency). The default icons include

   - Explorer: Shows a tree view of your project files and folders.
   - Search: Allows you to search for files and content within your project.
   - Source Control: Integrates with version control systems like Git.
   - Run and Debug: Provides debugging controls and configurations.
   - Extensions: Lets you browse, install, and manage extensions.

   (b). SIDE BAR

     The Side Bar is adjacent to the Activity Bar and changes its content based on the selected Activity Bar icon:(This provides detailed views and controls for the selected activity, allowing for efficient management and navigation).

   - File Explorer: Lists all files and folders in your current project.
   - Search Results: Shows results from a search query.
   - Source Control Panel: Displays version control status, changes, and controls.
   - Run and Debug Panel: Offers debugging options and configurations.
   - Extensions Panel: Lists installed extensions and allows you to search for   new ones.

   (c). EDITOR GROUP

     The Editor Group is the central part of the VS Code interface where you write and view code. It supports multiple tabs and split views, allowing you to:

   - Open and edit multiple files simultaneously.
   - Split the editor into multiple panes for side-by-side file comparison.
   - View and edit files in different layouts to optimize screen space and workflow.

   (d). STATUS BAR

     The Status Bar is located at the bottom of the VS Code window. It provides useful information and controls, including:

   - Current Line and Column Number: Shows the cursor’s position in the active file.
   - Programming Language Mode: Displays the current file's language mode, which you can change by clicking on it.
   - Branch and Repository Status: Shows the current Git branch and repository status.
   - Error and Warning Counts: Indicates the number of errors and warnings in the current file.
   - Live Server: If you have the Live Server extension installed, it provides a button to start the server.
   - Notifications: Shows information about tasks, updates, and other notifications.

5. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

   **ANSWERS**
  The command Palette in VS code is a powerful tool that provides quick access to various commands and functions within the editor. This allows to perform tasks without needing to navigate through menus or remember complex keyboard shortcuts.

  (a). Accessing the command palette: In VS Code, go to the top navigation, then view, then command palette.

<img src="https://github.com/Powerlearnproject/se-assignment-5-Chilundika/blob/main/Screenshots/10.%20Command%20Palette.png" alt="command palette" width="500" height="500">

  (b). COMMON TASKS:
  
   - Opening Files and Folders
   - Command Execution (e.g. document formating, toggle terminal)
   - Source Control (e.g. git commit and git pull)
   - Extensions (e.g installing extensions)
   - View and Navigation


5. Extensions in VS Code:Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.


**ANSWERS**
Extensions in Visual Studio Code play a crucial role in enhancing the functionality and versatility of the editor by allow users to customize and extend the capabilities of VS Code to suit their development needs, providing support for additional programming languages, tools, frameworks, and utilities

(a). FINDING THE EXNTENSIONS: Access the Extensions view by clicking the Extensions icon in the Activity Bar on the side of the window. Browse the marketplace for extensions by category, popularity, or search for specific extensions using keywords.

(B). INSTALLATION OF EXTENSIONS: 
   - Search for the desired extension in the Extensions view.
   - Click the Install button next to the extension name.
   - After installation, the extension may prompt you to reload VS Code to activate it.

(C). MANAGING THE EXTENSIONS:
   - Many extensions come with configurable settings. Access these by clicking the gear icon next to the extension name and selecting Extension Settings.


6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

     **ANSWERS**
(a). DESCRIPTION:

   To open the integrated terminal in VS Code on Windows 11:
   you can navigate to View then Terminal. Additionally, another way to open the terminal is through the Command Palette by pressing "Ctrl + Shift + P" to open it, then type "Toggle Integrated Terminal" and select it.

(b). USING THE INTEGRATED TERMINAL:
   - It can be used for basic operations such as opening a new terminal, switching between terminals, and closing the terminaL
   - The terminal can be size adjusted and be split into two side-by-side panels.

(c). ADVANTAGES:
   - Contextual awareness: commands executed in the integrated terminal have direct access to the VS Code environment, ensuring consistency and reducing setup time.
   - Seamless workflow: Running commands, debugging, and viewing output within the same window enhances productivity by reducing the need to switch between applications.
   - integrated features:The terminal can utilize VS Code extensions and settings, providing features such as syntax highlighting, IntelliSense, and command history.
   - Multitasking: Multiple terminal sessions can be run simultaneously, each with its own dedicated panel.
   - Customizable appearances:The appearance of the integrated terminal can be customized to match your theme and preferences, creating a visually consistent development environment.
   - Cross-Platform consistency:The integrated terminal provides a consistent interface and behavior across different operating systems, reducing the learning curve and simplifying development on multiple platforms.  


7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

    **ANSWERS**

(a). CREATING & OPENING FILES:
   - To create a new file in VS Code, press "Ctrl + Shift + P" to open the Command Palette, type "File: New File", and select it; the new file will be created in the currently open folder or workspace. To create a new folder, press "Ctrl + Shift + P" to open the Command Palette, type "Files: Create New Folder", and select it; you will be prompted to enter the folder name and location. To open a file, double-click the file name in the Explorer to open it in a new tab, or press "Ctrl + O" to open a file dialog and navigate to the file you want to open. To open a folder, click "File, then Open Folder" then select the folder you want to open, and it will appear in the Explorer.

(b). MANAGING FILES & FOLDERS:
  - Renaming Files and Folders: Right-click on the file or folder in the Explorer and select Rename,then type the new name and press Enter.

  - Moving Files and Folders: Drag and drop files or folders within the explorer to move them to a new location.

  - Deleting Files and Folders:Right-click on the file or folder in the Explorer and select Delete, or press Delete; Confirm the deletion when prompted.

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

   **ANSWERS**
(a). FINDING & CUSTOMIZING SETTINGS:
   - Users can go to "file, then preferences, then settings on windows 11.

(b). CHANGING THE THEME & SELECTING THE THEME:
   - Access the theme settings in the settings interface by typing "color theme" in the search bar.
   - Browse through the list of available themes and choose the theme of choice and apply it.

(C). CHANGING THE FONT SIZE:
   - Access the font size setting in the settings interface by typing "font size" in the search bar.
   - Adjust the font size by going to the font size editor in the settings, enter the desired font size.

(d). CHANGING KEYBINDINGS:
   - Access the keyboard shortcuts by going to file, then preferences, then keyboard shortcuts. Change them by searching for the command to rebind in the shortcut editor, click the pencil icon next to the command to enter a new keybinding anf press the desired key combination and enter to save it.

(e). EXAMPLES:
   - Change Theme: Open the Command Palette with Ctrl + Shift + P, type Preferences,then Color Theme. Select a theme from the list.
   - Change Font Size: Open Settings with Ctrl + , then type "Font Size" in the search bar; adjust the Editor: Font Size value.
   - Change Keybinding for Copy: Open Keyboard Shortcuts with Ctrl + K, Ctrl + S, search for Copy. click the pencil icon next to Copy. press the new key combination (e.g., Ctrl + C) and hit Enter.


9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

**ANSWERS**
(a). STEPS:
   i. Open Your Project:Open the folder containing your project files in VS Code by navigating to File then Open Folder and select the project folder.

   ii. Open the Main File: Open the main file of your project that you want to debug (e.g. main.py for a Python project).

   iii. Add Breakpoints: click in the space to the left of the line numbers, next to the line of code where you want to set a breakpoint. A red dot will appear, indicating that a breakpoint is set.

   iv. Open the Run and Debug View: click on the Run icon in the activity Bar on the side of the window or press Ctrl + Shift + D to open the Run and Debug view.

   v. Create a Debug Configuration: for the first time debugging in a project, there is need to create a launch.json file to configure the debugger. Click the gear icon in the Run and Debug view and select your environment (e.g. Python). This will then prompt VS Code to generate a launch.json file with some default configurations. These config files can be customized if needed.

   vi. Start Debugging: click the green play button at the top of the Run and Debug view or press F5 to start the debugging session. The program will start, and execution will pause at the breakpoints you’ve set.

(b). KEYBINDING FEATURES:
   - Breakpoints
   - Watch expressions
   - Call Stack
   - Variable inspection
   - Step over, Step into, Step out
   - Debug Console
   - Logpoints



10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

    **ANSWERS**
(a). INTEGRATION:

  i. CHECK GIT INSTALLATION:
    - verify git installation by running the "git --version" commanf in the powershell terminal.

  ii. OPEN THE SOURCE CONTROL VIEW:
    - click on the Source Control icon in the Activity Bar on the side of the window, or press Ctrl + Shift + G to open the Source Control view.

  iii. INITIALIZING A REPOSITORY:
    - In the Source Control view, click the Initialize Repository button. This will create a new .git directory in your workspace, initializing it as a Git repository.

  iv. MAKING COMMITS: Stage Changes: 
  - In the Source Control view, you’ll see a list of changed files under the Changes section. Hover over a file and click the + icon to stage it. You can also stage all changes by clicking the + icon next to Changes. 
  - Write a Commit Message: (Once you’ve staged your changes, write a commit message in the input box at the top of the Source Control view).
  - Commit the Changes: Click the checkmark icon above the input box to commit the staged changes

   v. Pushing Changes to GitHub
    - Add a Remote Repository: Open the terminal within VS Code (Ctrl + or Ctrl + Shift + ) and add a remote repository by running:"git remote add origin https://github.com/your-username/your-repository.git"
    - Push Changes: git push -u origin main (replace the main with the correct branch name when using different branch, otherwise, leave it as is)




**REFERENCES**:

- Microsoft Visual Studio Code Documentation. Available at: https://code.visualstudio.com/docs

- Visual Studio Code - GitHub Repository. Available at: https://github.com/microsoft/vscode

- "Getting Started with Visual Studio Code" by Visual Studio Code Team. Available at: https://code.visualstudio.com/docs/getstarted/introvideos

- "Visual Studio Code: End-to-End Editing and Debugging Tools for Web Developers" by J. Johnson. ACM, 2019. DOI: 10.1145/3289600

- "Mastering Visual Studio Code" by A. Dang. Packt Publishing, 2021. ISBN: 9781803230088.

- "Visual Studio Code for JavaScript Developers" by S. Ward. Apress, 2020. ISBN: 9781484265184.

- "Using Git with Visual Studio Code" by Visual Studio Code Team. Available at: https://code.visualstudio.com/docs/editor/versioncontrol

- "Visual Studio Code: A Comprehensive Guide" by D. Tyson. O'Reilly Media, 2022. ISBN: 9781492084054.

- "Debugging in Visual Studio Code" by Visual Studio Code Team. Available at: https://code.visualstudio.com/docs/editor/debugging

- "Introduction to Visual Studio Code" by Visual Studio Code Team. Available at: https://code.visualstudio.com/docs/getstarted/intro

