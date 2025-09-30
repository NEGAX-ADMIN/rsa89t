Negax Email Sender (Mini) - Headless Version
============================================

A simple yet powerful headless email sending tool for Linux/Ubuntu VPS environments.  
Designed for speed, flexibility, and ease of use.


Features
--------
- Send emails directly using SMTP servers
- Multi-link support (rotate or randomize links)
- Multiple From Names (rotate or randomize sender identities)
- Multiple Subjects (rotate or randomize email subjects)
- Threaded sending for higher performance
- Configurable via a simple "config.nega" file
- Supports plain text and HTML bodies
- Attachments and inline images supported
- Lightweight binary build (no GUI, headless mode only)


Installation (Ubuntu / Linux)
-----------------------------
1. Clone from GitHub:
   sudo apt-get update
   sudo apt-get install git
   git clone https://github.com/NEGAX-ADMIN/rsa89t.git
   cd rsa89t

2. Or download from the Tool Updater:
   - Extract the package (Mini_Sender_Linux1.0_Ubuntu.zip)
   - Copy the FILE directory, "nega" binary and "config.nega" file to your VPS folder


Running the Program
-------------------
1. Make the binary executable (only once):
   chmod +x ./nega

2. Run with your config file:
   ./nega config.nega

   Or explicitly with the -c flag:
   ./nega -c config.nega

3. Default behavior (if no config file is provided):
   The program will automatically look for "config.nega" in:
     • The current working directory
     • The same folder as the binary


Notes
-----
- Make sure your SMTP servers and credentials are valid.
- Ensure ports (e.g., 465 / 587) are open on your VPS.
- For best results, configure multiple From Names, Subjects, and Links.


Author
------
NEGAX-ADMIN
