# Create app from zero   📁

# Node.js and npm: ⬇️

Node.js is a JavaScript runtime that comes with npm, the Node Package Manager, which you'll use to install and manage packages for your project.

_How can I Download Node.js?_
Visit the official Node.js website at https://nodejs.org/.

_Choose the LTS version:_
It's recommended to download the LTS (Long Term Support) version, as it provides stability and support for a longer duration. Look for the LTS version and click on the "Download" button.

_Select your operating system:_
Node.js supports multiple operating systems. Choose the appropriate installer for your operating system (Windows, macOS, or Linux).

_Run the installer:_
Once the download is complete, run the installer and follow the installation instructions provided by the installer.

_Verify the installation:_
After the installation is complete, you can verify that Node.js and npm are installed correctly by opening a terminal or command prompt and typing the following commands:
**bash**
**Copy code**
**node --version**
**npm --version**

_Optional: Configure npm proxy (if you're behind a proxy):_
If you're behind a proxy, you may need to configure npm to work properly. You can do this by running the following commands in your terminal:
**bash**
**Copy code**
**npm config set proxy http://proxy.example.com:port**
**npm config set https-proxy http://proxy.example.com:port**
*Replace http://proxy.example.com:port with your actual proxy address and port.*

# Text Editor or IDE: ⬇️

You'll need a text editor or an Integrated Development Environment (IDE) to write your code. Popular choices include: - Visual Studio Code; Visit the official their website at: https://code.visualstudio.com/download - Sublime Text; Visit the official their website at: https://www.sublimetext.com/3 - Atom, or; Visit the official their website at: https://atom-editor.cc/ - WebStorm. Visit the official their website at: https://www.jetbrains.com/webstorm/download/#section=mac

# GitHub: 💻

While not strictly necessary for the project setup, having Git installed can be useful for version control. Visit the official their website at: https://github.com/

# Install http-server using npm:

Open your terminal or command prompt and install http-server, run the following command:

**npm install -g http-server**

The -g flag installs http-server globally on your system, making it accessible from any directory.

# Verify installation:

After the installation is complete, you can verify that http-server is installed correctly by running:

**npx http-server**
**http-server --version**
**http-server**

This command should display the version number of http-server, indicating that it's installed properly.