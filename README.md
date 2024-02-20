# Password Manager

## Purpose

This app is made so you can generate secure passwords, in addition to saving them all in a document.

It was based on the same course as other projects that are on my GitHub.

## Overview

It works very simply. You have three options to fill in, as well as 3 buttons.

Website: you enter the website where you are storing the password

E-mail/Username: you enter your e-mail or website username

Password: you enter the respective password for your account

Generate button: generates a secure random password for your account

You can see them in the next image:

<p align="center">
  <img width="450" height="373" src="https://github.com/Fjfj02/password-manager/assets/84993558/b83893d4-0123-4015-b21b-d2651cf11191">
</p> 

After using these, there are two buttons left to explain.

Add button: you add the account to the database (you receive a confirmation)

<p align="center">
  <img width="450" height="373" src="https://github.com/Fjfj02/password-manager/assets/84993558/a11158f7-c7e9-4d85-bce5-c5a80c6f1a3a">
</p> 

And finally, the search button: after writing the name of the website and clicking to search, it shows you the account information.

<p align="center">
  <img width="450" height="373" src="https://github.com/Fjfj02/password-manager/assets/84993558/8d82e565-dc30-4340-a5f0-dbf2c06482fb">
</p> 

The interface may be crooked if it is not running on Windows.

## Run code

First you have to install the following library:

```shell
pip install pyperclip
```

To run the code, use:

```shell
python3 main.py
```

## Change of data

If you want to change the default e-mail, go to line 122 of main.py and change the "email_entry.insert" entry.

And if you want to delete the test accounts, delete the data.json file.
