Turn On USB Debugging and WiFi Debugging on your device.

Step 1: Install Homebrew through terminal.

/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

Step 2: There will be section after installation is done labelled as "Next Step" 
Copy, Paste & Run the command 

Step 3: Run "brew install scrcpy"

Step 4: Run "brew install --cask android-platform-tools

Step 5: Open CMF Mirror.workflow.zip in Automator 

Connect Phone with Mac vai USB.

Step 6: On terminal "adb tcpip 5555"

After this Step you can Run automator and this will only work when phone is connected.

For Wireless Mirroring After Step 6 disconnect the phone then,

Step 7: On Terminal "adb connect "Router ID""
You can get Router ID by holding Option key & clicking on wifi icon. Parentheses not included.

After this Step you can Run automator. 
