# MarsinSight Setup Guide

This document explains how to run MarsinSight locally on a laptop.

## Requirements

- Python installed
- Git installed

Download Git here if needed:
https://git-scm.com/downloads

------------------------------------------------------------

STEP 1 — Open System Terminal

Windows:
Press Windows Key → Type "cmd" → Press Enter

Mac:
Press Command + Space → Type "Terminal" → Press Enter

------------------------------------------------------------

STEP 2 — Clone the Repository

Type the following:

cd Desktop
git clone https://github.com/BoyofMars/marsinsight.git
cd marsinsight

------------------------------------------------------------

STEP 3 — Create Virtual Environment

Type:

python -m venv venv

Activate it:

On Windows:
venv\Scripts\activate

On Mac/Linux:
source venv/bin/activate

If successful, you will see (venv) at the beginning of your terminal line.

------------------------------------------------------------

STEP 4 — Install Required Packages

Type:

pip install -r requirements.txt

------------------------------------------------------------

STEP 5 — Run the Application

Type:

uvicorn main:app --reload

If successful, you will see:

Uvicorn running on http://127.0.0.1:8000

------------------------------------------------------------

STEP 6 — Open in Browser

Open Chrome (or any browser) and go to:

http://127.0.0.1:8000

MarsinSight should now be running.

------------------------------------------------------------

NOTES

- Git downloads your project.
- Python runs your project.
- The terminal is where you type commands.
- GitHub is where your code is stored online.
