**Make sure you have python version <=3.12.11.**
## Make sure you have git-lfs
  Arch:
    `sudo pacman -S git-lfs`
  or
  Ubuntu:
   `sudo apt install git-lfs`
  or
  Fedora:
    `sudo dnf install git-lfs`
## Setup
1. Clone this repository: `git clone https://github.com/MasonAndrewHarrison/Point-Cloud-Voxelizer.git`
2. Change Directory: `cd Point-Cloud-Voxelizer`
3. Clone the lfs file: `git lfs pull`
4. Create virtual environment: `python -m venv venv`
5. Activate it: `source venv/bin/activate`
6. Install dependencies: `pip install -r requirements.txt`
7. Run: `python main.py`
