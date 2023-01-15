# Exit-Save Backup Tool for Stoneshard

*The original files and idea came from **[zMenta](https://github.com/zMenta)**. I simply updated the code to be more user-friendly.*

## Requirements

- 28KB of storage

- [Python](https://www.python.org/downloads/) version 3.X or higher.

- Check all the boxes during the Python installation, especially when installing Python to your path.

- Open a command prompt and upgrade pip.

$`python -m pip install --upgrade pip`

## Installation

- Download or clone this [repo](https://github.com/ZeroOneZero/Stoneshard-Exit-Save-Backup-Tool.git)

- Unzip the repo.

- From inside the repo directory, open a command prompt and verify the Python version.

$`python --version`

>**Python 3.10.4**

- Next we can install the requirements.txt

$`pip install -r requirements.txt`

- To run the script, double-click on the `run.py` file. You may also execute it from the command window with:

$`python run.py` **or** `python3 run.py`

*The latter is a command in Linux.*

- When you run the script, it creates backup directories in the **%LOCALAPPDATA%/Stoneshard** directory for you.

- By default, the first character you create is named **character 1**.

> **If you are using any additional characters, make sure you go into `settings.py` and update the directory name from `character_1` to `character_#`.

*Backup your save folder before running this tool.*

*As long as you need the script to backup and restore, you will have to run it and keep it running during the play.*

## Usage

- Run the script.

- Load up a save

- To save your progress, press **ESC** and then select **Save and Exit.**

*This action will take you back to the Main Menu.*

# DO NOT EXIT THE GAME

*The game, by default, erases the exit save upon exiting the game.*

- To backup the **Exit Save**, press `F5`

*Pressing **F5** causes the script to backup the **exitsave_1** directory to **.exitsave_1** within the same parent directory.*

- Return to the **Exit Save** by selecting **Load** from the Main Menu.

- When you die, exit back to the main menu.

- To load the Exit Save, press “F8.”

*Pressing **F8** causes the script to copy the **Exit Save** from the **.exitsave_1** directory to the **exitsave_1** directory.*

- This allows you to save anywhere and anytime you want.

# CHEERS
