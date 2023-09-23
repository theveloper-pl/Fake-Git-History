# Fake Git History
A Python script to generate a fake Git repository history with random commit messages and commit dates. Script is in basic version, to show how to easily make looks your github like you commit a lot, in case of dumb recruitments requirements

# Usage
 When prompted, choose between two options:

Create a single commit on a specific date
Create multiple commits between two dates
If you choose to create a single commit, you will be prompted to enter the date in the format YYYY/MM/DD. The script will then create a random number of commits on that day, each with a random commit message.

If you choose to create multiple commits, you will be prompted to enter the start and stop dates in the format YYYY/MM/DD. The script will then create a random number of commits (between 45 and 113) on each day between the start and stop dates, with random commit messages.
## You should adjust these variables 
```
        self.min_commits = 45
        self.max_commits = 113
        self.remote_url = "https://github.com/theveloper-pl/Fake-Git-History.git"
```
## How to use
``````
git clone https://github.com/theveloper-pl/Fake-Git-History.git
cd Fake-Git-History/
python3 -m venv env
source env/bin/activate
pip install -r requirements.txt
Change variables in source code
python main.py

1.Create single commit
2.Range of commits
>> 2

Start date in format YYYY/MM/DD
>> 2022/01/01

Stop date in format YYYY/MM/DD
>> 2022/01/13

Currently commiting 2022-01-01 with 63 commits
Currently commiting 2022-01-02 with 63 commits
...
Changes have been pushed !
``````



# License
This project is licensed under the MIT License - see the LICENSE file for details.


### This readme.md was generated by ChatGPT