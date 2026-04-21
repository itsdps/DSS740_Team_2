Hello team! This is Group 2 Project for DSS 740.

I just put some information I thought might be useful below.
=============================================================

**Download Necessary Packages**

To download packages, type in terminal (make sure you in .venv):
    pip install -r requirements.txt     # If this fails, look below

    Set up Virtual Enviroment with correct version then:
        py -3.12 -m venv .venv            # Create Virtual Enviroment
        .venv\Scripts\activate            # Activate Virtual Enviroment
        pip install -r requirements.txt       # Download all necessary packages


    If fails requirements fails, check that you have Python Version. 
    I found 3.11 or 3.12 work best, while 3.14 did not work with some packages (might still be fine though). Go to this link to download 3.12 (for Windoes I did Windows Installer (64-bit)): https://www.python.org/downloads/release/python-3128/

    Check your Python Versions downloaded using:
        py --list


  **Push and Pull to GitHub**

    **Push to GitHub:**

        git add .
        git commit -m "message about what you change"
        git push -u origin HEAD      

        # Now tell David to Accept Pull Request :D
        # OR you might be able to too!
        
    **Pull from Github**:
        # Create a ".temp" folder in this project and put anything you don't want to be deleted in there

        Now Type:
            git pull       # All Done!