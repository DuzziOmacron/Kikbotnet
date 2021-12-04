# 5.3 Updates
- Added automated startup
- Patched JID spam issues
- Patched "gif [query]" command
- Added 5 second delay in group spam
- Moved update check from Pastebin to Replit

# Notes from Stetho

There were a few features that I was going to add but ended up abandoning before releasing this update. 
- First feature was image spam, it was decided that this feature could be too easily abused to spam illegal content such as CP, so the feature was ultimatley abandoned. Even if I set preset images, considering the code is open source, it could be easily tampered with to change the preset image links. 
- Second feature was a Flask server toggle, which was abandoned in favor of not confusing users by explaining how to use UptimeRobot. I did however add a quoted out keepalive.py file to GitHub for those of you who know what you're doing, in case you want to fork the respository and unquote it.
- Third feature was adding an option for the user to customize a preset list of usernames/passwords, which was abandoned in favor of keeping automatic setup as simple as possible. There were too many extra options in the startup menus when I added this feature, and I wanted to do everything in my power to keep it simple. _(I may release a seperate version for this, as I heard that Kik has been mass-banning accounts that have ascending numbers in the usernames.)_




