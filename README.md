# **Alien Invasion**

**Alien Invasion Game written in [Python](https://www.python.org) built using [Pygame](https://www.pygame.org/news).**

The goal is to shoot the enemy space ships before they reach earth. The game continuously gets more difficult as the levels progress. You can play yourself or let a computer play for you!

----
## **Requirements**

- [Python 3.10.5](https://www.python.org/downloads/release/python-3105/)
- [Pygame 2.1.2](https://www.pygame.org/news)
----
## **Installation**

Alien Invasion can be installed via [Pip](https://pypi.org/project/pip/). To start, clone the repository to your local computer and change into the proper directory.

* **Clone Repository**
```bash
  $ git clone https://github.com/niel-conradie/Alien-Invasion.git
  $ cd Alien-Invasion
```
### **Pip Install**

* **Create Environment**
```bash
  $ python -m venv .venv
```
* **Activate Environment**
```bash
  # Bash
  $ source .venv/Scripts/activate

  # Command Prompt
  C:> .venv\Scripts\activate.bat

  # macOS
  $ .venv/bin/activate

  # PowerShell
  PS C:> Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
  PS C:> .venv\Scripts\Activate.ps1
```
* **Install Requirements**
```bash
  (.venv) $ python -m pip install -r requirements.txt
```
----
## **Usage**

To start Alien Invasion game run one of these two files.
```bash
  # Human Player
  run.py

  # Computer Player
  run_computer.py
```
----