---
description: SciShare documentation
---

# SciShare

## How to connect

You can access your SciShare projects either through the [web portal](scishare.md#using-filezilla) or via terminal using the following command: `ssh`` `<mark style="color:purple;">`<username>`</mark>`@ki.se@scishare.ki.se`

## Data transfer

You can upload or download data to/from SciShare from/to your computer using the terminal, the [web portal](scishare.md#using-filezilla), or an SFTP client like FileZilla.

### Using the terminal

1. **Connect** to the server with _sftp_:

&#x20;`sftp`` `_`username`_`@ki.se@scishare.ki.se` and enter your password when prompted.

2. To **download data** from SciShare to your computer, you can use the terminal, the web portal, or an SFTP client like FileZilla

Using the terminal: `get -r`` `<mark style="color:green;">`<remote_directory>`</mark> <mark style="color:orange;">`<local_directory>`</mark>

3.  To **upload data** to SciShare from your computer, you can use the following command:

    `put -r`` `<mark style="color:orange;">`<local_directory>`</mark>` `<mark style="color:green;">`<remote_directory>`</mark>

### Using Filezilla

1. **Download** and **install** the [FileZilla client](https://filezilla-project.org) for your OS.
2. Connect to the server with the following settings: \
   **Hostname**: `ki.se@scishare.ki.se`, **port**: `22`, your **username** and **password**. \
   Once connected, you can upload or download files between SciShare and your local machine.
