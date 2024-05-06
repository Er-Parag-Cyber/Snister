<p align="center">
  <img src="https://github.com/PushpenderIndia/technowlogger/blob/master/img/technowlogger-logo.png" alt="Sinister Logo" width=200 height=200/>
</p>

<h1 align="center">Sinister</h1>

<p align="center">
  <img src="https://github.com/Er-Parag-Cyber/snister/blob/main/hacker-gif.gif" width=200 height=200/>
</p>

             
                                              This small python script can do really awesome work.

Sinister is Keylogger Generator for Windows/Linux, which sends key-logs & screenshot via email with other juicy target info written in Python 3.

## Disclaimer
<p align="center">
  :computer: This project was created only for good purposes and personal use.
</p>

THIS SOFTWARE IS PROVIDED "AS IS" WITHOUT WARRANTY OF ANY KIND. YOU MAY USE THIS SOFTWARE AT YOUR OWN RISK. THE USE IS COMPLETE RESPONSIBILITY OF THE END-USER. THE DEVELOPERS ASSUME NO LIABILITY AND ARE NOT RESPONSIBLE FOR ANY MISUSE OR DAMAGE CAUSED BY THIS PROGRAM.

## Features
- [x] Works on Windows/Linux
- [x] Notify New Victim Via Email
- [x] Undetectable
- [x] Persistence
- [x] Email Credentials Validation before Payload Generation.
- [x] Can receive Keylogs in any email provider such as GMAIL, YAHOO, OUTLOOK, Custom SMTP.

* SMTP Server/ Port

| Server Name | SMTP Server | SMTP Port |
| ----------- | ----------- | --------- |
| GMAIL       | smtp.gmail.com | 587 |
| OUTLOOK     | smtp-mail.outlook.com | 587 |
| YAHOO       | smtp.mail.yahoo.com | 587 |

- [x] Sends Screenshot of Victim PC's Screen via email

- [x] Grabs & Send Useful Information of Victim's Device

| These Things are Grabbed & Sended: |
| -----------------------------------|
| Operating System |
| Computer Name    |
| User Name |
| Public IPv4 |

- [x] If your payload is unable to execute, then specify --debug to run exe on foreground with CMD

## Important
On **30 May 2022**, Google has **removed less secure apps feature**, so instead of Gmail Password:
- Enable 2FA on your attacker gmail
- Create App Specific Password
- Use that `app specific password`, while creating payload. 
- How to Create App Specific Password: [Click Here](https://support.google.com/mail/answer/185833?hl=en) 


## Tested On
[![Windows)](https://www.google.com/s2/favicons?domain=https://www.microsoft.com/en-in/windows/)](https://www.microsoft.com/en-in/windows/) **Windows 10**

[![Windows)](https://www.google.com/s2/favicons?domain=https://www.microsoft.com/en-in/windows/)](https://www.microsoft.com/en-in/windows/) **Windows 8.1 - Pro**

[![Windows)](https://www.google.com/s2/favicons?domain=https://www.microsoft.com/en-in/windows/)](https://www.microsoft.com/en-in/windows/) **Windows 7 - Ultimate**

## Prerequisite
- [x] Python 3.X
- [x] Few External Modules

## How To Use in Windows
```bash
# Install dependencies 
$ Install latest python 3.x

# Clone this repository
$ git clone https://github.com/Er-Parag-Cyber/snister.git

# Go into the repository
$ cd sinister

# Installing dependencies
$ python -m pip install -r windows_packages.txt

# Open keylogger.py in Text editor and Configure Line 16 WINDOWS_PYTHON_PYINSTALLER_PATH = "C:/Python37-32/Scripts/pyinstaller.exe"
```
## New Screenshots:

#### Getting report

#### Victim Photo Mail
![Victim Photo Mail](https://github.com/Er-Parag-Cyber/snister/assets/62016806/139e2165-0bce-4261-95a2-0751b86b4339)

#### Screenshots Mail
![SS Mail](https://github.com/Er-Parag-Cyber/snister/assets/62016806/0086c16c-887e-4c0d-a0a2-36b19393ba75)

#### Mic Recording From Victim PC
![Mic Recording](https://github.com/Er-Parag-Cyber/snister/assets/62016806/8f7ffcda-ae4c-4bb2-ad4a-0f1cc06c6b82)

#### Logs Output From Victim PC
![Log Folders](https://github.com/Er-Parag-Cyber/snister/assets/62016806/8ab772ad-5826-4222-b7db-cad8fc8145a2)
![Logs Output](https://github.com/Er-Parag-Cyber/snister/assets/62016806/3ea0fcfd-02d3-4a0b-b1c2-29ff3c460513)

#### Net Information XML From Victim PC
![Net Info Xml(1)](https://github.com/Er-Parag-Cyber/snister/assets/62016806/e185827d-3e44-4699-a954-aaa96f26b330)

#### Screenshots From Victim PC
![SS](https://github.com/Er-Parag-Cyber/snister/assets/62016806/95f57dc1-5e2a-49ff-9ced-415388723456)







