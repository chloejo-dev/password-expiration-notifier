# Password Expiration Notifier

A Windows automation tool built with PowerShell that notifies users of upcoming password expiration through a pop-up message.

## 🎯 Problem

In many enterprise environments, users often forget to update their passwords, leading to:

- Account lockouts
- Increased IT support tickets
- Productivity disruption

## 💡 Solution

This tool automatically checks user password expiration status and sends notifications before expiration.

## 🛠 Tech Stack

- PowerShell
- Windows
- Active Directory

## ⚙️ How it works

- Retrieves a user's password expiration date from Active Directory
- Triggers a notification when the threshold is reached (e.g., 14 days remaining)
- Displays a pop-up message to the user

## ✨ Key Features

- Automated password expiration detection
- Pop-up notification

## 📈 Impact

- Helps reduce password-related account lockouts
- Helps improve user awareness of password expiration
- Aims to reduce password-related IT support requests

## 📷 Screenshots

<img width="575" height="243" alt="image" src="https://github.com/user-attachments/assets/953cdacf-dbc7-48bb-941a-a077a5ab2528" />

<img width="575" height="239" alt="image" src="https://github.com/user-attachments/assets/c5ad2b2f-f00a-4228-9467-4c0994429749" />
