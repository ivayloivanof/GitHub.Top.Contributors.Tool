# GitHub Top Contributors Tool
==================================================================================
###A tool that allows one to get a list of the top 10 contributors to a GitHub repo and how many commits each contributor has.

####First navigate to the "requests" directory and run `python setup.py install` to install the python requests library.

You may need to prefix this with `sudo`

To use the tool run `python get_top_ten_contributors.py`

It will request the repo name and repo owner. If the name and owner are valid, it will return a list of the top ten contributors for that repo, and how many commits each contributor has. If the name or owner is invalid, it will raise an error.

Assumptions:
- the user has python installed on their machine
- repo is public
