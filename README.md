The creation of this app is motivated by nostalgia. Microsoft removed MS-Wordpad in latest Windows releases, so I created an alternate version written in Python with .docx processing (write/read/edit) capabilities.

## Installation on Windows (Method 1):
1. Click **Start**, search and open **Powershell terminal** (Powershell 5.1 is required)
2. Copy and paste this command to install Scoop ```Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser; Invoke-RestMethod -Uri https://get.scoop.sh | Invoke-Expression``` - Press **ENTER**
3. Install PyPad, copy and run this command ```scoop install https://raw.githubusercontent.com/Admin9961/pypad-scoop-bucket/main/pypad.json```

By using Method 1, PyPad will appear in your App list, in the Start Menu.

## Installation on Windows (Method 2 - Traditional):
No steps, just download and run the PyPad.exe from this repository using browser. But you're warned, the executable is **NOT SIGNED**, so you are likely running into Smartscreen security prompts and false positives. Use this method only if you know how to deal with Smartscreen and MOTW.
