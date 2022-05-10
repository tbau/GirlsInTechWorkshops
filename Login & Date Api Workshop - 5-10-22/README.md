## Login & Date Api Workshop  
  

### Steps to get started

1. Install chocolatey  
    1. Open PowerShell as Admin
    2. Run Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))  
    3. Press enter and then answer 'y' to all questions.

2.  Install vscode  
    1. Open PowerShell as Admin
    2. Run choco install vscode
    3. Press enter and then answer 'y' to all questions.

3.  Install nvs (node version switcher)  
    1. Open PowerShell as Admin
    2. Run choco install nvs
    3. Press enter and then answer 'y' to all questions.
    4. If you have vscode open already, restart it.

4.  Open vscode and start a new terminal  
    1. Click open folder and open the repo that you cloned
    1. Click Terminal in the bar at the top of the screen
    2. Click New Terminal 

5.  Install node through nvs
    1. In the Terminal, type nvs and press enter.
    2. Select the first option and press enter.
    3. Use your arrow keys to navigate to version 14.17.1 and press enter.  
    4. Now you have node version 14.17.1 installed.
    5. Everytime you open vscode, you will need to open a new terminal, then run nvs. Press enter to select version 14.17.1.
    6. If you are on a project that requires a different version, you can add new versions by using that option.

6. Install packages
   1. After node is installed, which also installs npm, type in npm i, then press enter.
   2. This will install all of the packages.  

7. Edit login
   1. The login for the app is stored in login.json. You can change the email and password you want to use there. I would just keep it like it is.

8. Run the application  
   1. Type in npm run start, then press enter.
   2. Open a browser (preferably Chrome), then type http://localhost:80 into the browser and press enter. 
   3. You should see the app running. 
   4. If you want to stop the app, press Ctrl+c in the terminal to stop it.
