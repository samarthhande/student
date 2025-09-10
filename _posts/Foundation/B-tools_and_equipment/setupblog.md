---
author: samarthhande
title: Enviornment Setup for CSSE
description: A guide on how to set up your Kali/Ubuntu envionrment
permalink: /setuphelp
---
 
# 🖥️ Enviornment Setup for CSSE
*A guide on how to set up our enviornment-- for either Kali Linux or Ubuntu*
 
Hello! This is a guide on how to set up your Kali/Ubuntu envionrment. In the near future, this guide will expand to give us instruction for how to setup KASM, MacOS, and Windows to be ready for Ubuntu/Kali setup.
 
Know that throughout this guide...
 
- You should treat all instances of `<YOUR-USERNAME>` as text that should be filled in with your github username.
- You should treat all instances of `<YOUR-REPO>` as the repository you want to change.
 
---
 
## Getting your repo on the system
 
1. 💻 **Open Terminal** \
    For Kasm, you can find terminal in the top navigation bar. For Ubuntu, select "Applications," and you should find it there.
2. 📁 **Verify Home Directory** \
    Once your terminal opens, ensure you are in the home directory. Run `cd ~`, as this command will take you directly there.
3. 📁 **Make Github Directory** \
    Now, run `mkdir <YOUR-USERNAME>`. This will create a directory where we can store your repo's on the system!
4. 📁 **Enter Github Directory** \
    Run `cd <YOUR-USERNAME>` to travel to the said directory.
5. 🛠️ **Clone Your Repo** \
    Run `git clone https://github.com/<YOUR-USERNAME>/<YOUR-REPO>.git`
 
Overall commands:
 
```bash
cd ~
mkdir <YOUR-USERNAME>
cd <YOUR-USERNAME>
git clone https://github.com/<YOUR-USERNAME>/<YOUR-REPO>.git
```
 
---
 
## Enviornment setup for your repo
 
1. 🛠️ **Create your venv** \
    Run the command `./scripts/venv.sh`. Ensure that you are in the same directory as where you left off in the previous step!
2. 🛠️ **Run the activate script** \
    Run the command `./scripts/activate.sh`. This will ensure that your enviornment works.
3. 💻 **Activate the venv** \
    Run `source venv/bin/activate`. This should create a `(venv)` in your terminal prompt. IF THIS STEP DOSEN'T WORK, PLEASE PLEASE **PLEASE** look at the troubleshooting guide given my Mr. Mortenson.
4. 💻 **Open vscode** \
    Run `code .` in the same directory as above. You should now have everything setup and ready to go for the first time on this machine!
 
---
 
## Necissary Commands (Linux: Ubuntu / Kali)
| Command | Description |
|---------|-------------|
| `mkdir <folder>` | Create a new folder |
| `cd <folder>` | Change directory |
| `git clone https://github.com/<username>/<repo>` | Clone a repository from Github |
 
---
 
**Links:**  
- [Git Documentation](https://git-scm.com/doc)  
- [GitHub Guides](https://guides.github.com/)
