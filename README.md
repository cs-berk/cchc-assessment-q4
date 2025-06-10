## Programmer Assessment Q4



## ✅ Instructions to Set Up and Run the App

### 1. Install Python (if not already installed)

```bash
sudo apt update
sudo apt install python3 python3-venv python3-pip -y
2. Clone the repository
git clone https://github.com/cs-berk/cchc-assessment-q4.git
cd cchc-assessment-q4
3. Create and activate a virtual environment
python3 -m venv venv
source venv/bin/activate
4. Install required dependencies
pip install dash pandas
5. Run the app on port 10030
python main.py
This repository contains a broken web app built with Dash. Please follow the tasks below.

Tasks:
1. Clone this repo to your machine.
2. Fix missing dependencies and fill authors section in `pyproject.toml`.
3. Fix bugs prevent the app `main.py` from running.
4. Change port the app ruuning on to `10030`.
5. Commit you changes.
6. Update `README.md` with a instruction
   1. Assuming the user has a fresh minimum Linux installation with no python.
   2. Setup python and virtual environment for this app, use the fixed `pyproject.toml`.
   3. How to run this app and how to access it without portforwarding.
7. Push all the changes to your own repository on Github, and provide a link to your own repo in your submission in the last.f