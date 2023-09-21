# [Jupyter_bard](https://https://github.com/Oscar-Amarilla/Jupyter_bard)

by Oscar Amarilla, 2023

[Jupyter_bard](https://github.com/Oscar-Amarilla/Jupyter_bard) is a project that is meant to be a guide to anyone who wants to use the [Google Bard](https://bard.google.com/chat) chatbot inside a Jupyter notebook.

You are free to copy, modify, and distribute this project, without asking for permission. The developer suggests to the users to read about the policies of the [Google Bard](https://bard.google.com/chat) in order to avoid legal actions from [Google](https://en.wikipedia.org/wiki/Google). See *[Public domain dedication](#public-domain-dedication)* for details of this project.

## How does [Jupyter_bard](https://github.com/Oscar-Amarilla/Jupyter_bard) works?

The structure of the project is the following:

```
|--input/ (Input data)
|
|--.env (Necessary credential to use the chatbot)
|
|--Jupyter_bard.ipynb (Notebook with the codes)
|
|--requirements.txt (List of necessary libraries to run the project.)
|
|__ README.md 
```

The user may take a look at the notebook, where the project has been explained in further details an could be a little more easy to follow.

## How to run [Jupyter_bard](https://github.com/Oscar-Amarilla/Jupyter_bard)?

First thing to do is to generate a python virtual enviornment in a bash terminal.
```bash
python -m venv here_goes_the_name_of_the_venv # The name of the venv is up to the user.
```
Activate the virtual enviorment
```bash
source name_of_the_venv/bin/activate
```
Then install the requirements listed in the requirements.txt using pip.
```bash
pip install -r requirements.txt
```
Then the project can be run in the notebook. In the terminal, go to the notebook directory and run the notebook and open it.
```bash
jupyter lab
```

The next step is to go to the [Google Bard](https://bard.google.com/chat) and follow the following instructions:

- Create a file called .env with the following estructure:
```
SECURE_1PSID_KEY = 
SECURE_1PSIDTS_KEY = 
```
Then, while you are logged into the Bard website. You can do this using the following steps:
- Open the Bard website in your browser.
- Press F12 to open the developer tools console.
- Click on the Application tab.
- Under Storage, click on Cookies.
- Find the cookies named __Secure-1PSID and the __Secure-1PSIDTS.
- Copy each cookie values and paste them in the .env file on their respective variables.

**Warning** The cookies values will expire from time to time, even without closing the project. This can be noted when the error
```SNlM0e value not found. Double-check __Secure-1PSID value or pass it as token='xxxxx'.``` arise. 
## Contributing to [Jupyter_bard](https://github.com/Oscar-Amarilla/Jupyter_bard)

Every comment and/or suggestion for improving [Jupyter_bard](https://github.com/Oscar-Amarilla/Jupyter_bard) will be very welcome, so every user is cordially invited to [open an issue or pull request on GitHub](https://github.com/Oscar-Amarilla/Jupyter_bard/issues).

## Public domain dedication

This work is dedicated to the [public domain (CC0 1.0)](https://creativecommons.org/publicdomain/zero/1.0/). To the extent possible under law, Oscar Amarilla has waived all copyright and related or neighboring rights to the README checklist. See the LICENSE file for all the legalese.
