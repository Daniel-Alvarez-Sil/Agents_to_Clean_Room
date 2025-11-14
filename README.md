# Description.

This project contains the files that implement the cleaning of an N x M room using agents, with varying parameters. This are the following files: 
- Requirements: Python libraries used to run this project
- clean_room.ipynb: Jupyter notebook with the logic to execute the simulation (either with Basic Visualization or only the simulation).
- clean_room.html: Export of the Jupyter notebook on HTML. 

Next, we will show how to clone this project. 

> Note: This project was ran upon Ubuntu. 

# Windows (PowerShell)

1. **Install prerequisites (once)**

* Git: install from git-scm.com and reopen PowerShell.
* Python 3.10+ : install from python.org and check “Add Python to PATH”.

2. **Clone the repo**
Clone the repository using GitHub Desktop. 

3. **Create & activate a virtual environment**

```powershell
# Create venv in a hidden folder .venv
py -3 -m venv .venv

# If activation is blocked, temporarily allow scripts for this session:
# Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass

# Activate
.\.venv\Scripts\Activate
```

You should see `(.venv)` at the start of your prompt.

4. **Install dependencies**

```powershell
python -m pip install --upgrade pip
pip install -r requirements.txt
```

5. **(If Jupyter isn’t included) install it**

```powershell
pip install jupyter
```

---

# Ubuntu / Debian-based Linux

1. **Install prerequisites (once)**

```bash
sudo apt update
sudo apt install -y git python3 python3-venv python3-pip
```

2. **Clone the repo**

```bash
cd ~
git clone https://github.com/Daniel-Alvarez-Sil/Agents_to_Clean_Room.git
cd Agents_to_Clean_Room
```

3. **Create & activate a virtual environment**

```bash
python3 -m venv .venv
source .venv/bin/activate
```

You should see `(.venv)` in your prompt.

4. **Install dependencies**

```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```

5. **(If Jupyter isn’t included) install it**

```bash
pip install jupyter
```

