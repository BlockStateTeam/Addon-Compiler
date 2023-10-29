# Addon-Compiler from BlockState.Team (Made by Blues)

This simple compiler requires both [NodeJS](https://nodejs.org/en) and [Chrome](https://www.google.com/chrome/) to work properly!
[CLICK ME FOR DOWNLOAD](https://blockstate.team/projects/BlockState-Add-On-Compiler.vbs)


For dev, download this repo, and run "npm i" then "node app" to launch the compiler UI

If you want to add your own UI (through CSS), go to "C:\Addon-Compiler-main\public", create a "user.css", the program should now be able to use it as an UI

# Changelog
### v1.0.0
- Add compiling feature using CLI

### v1.1.0
- Add an UI for the program
- Auto-scan and seperate projects into RP, BP and Add-On
- Add auto-update system to handle update from Github
- Add an UI switcher system
- Add "Let me decide" option as an export location when compiling Add-On
- Fix several bugs related to the UI
- Fix a bug that could happen when user cancel the Directory Promt when they're exporting Add-On
- Fix several bugs related to how NodeJS BE handle file scanning
- Add a new user.css for further customization
- Revamp UI for more animations
- Fix an important bugs that cause the program to crash if the user changes the UI rapidly
- Add "Setting" with Help section (Discord) and an Uninstall feature
- Add a new system to let user select their own Directory as a default path
- Add an Alert system and manual update mode

### v1.1.1 [CURRENT]
- Fix bugs that cause the program to freeze when rapid compiling request
- The alert system is now triggered for more events (add/remove directory, compiling request, uninstall alert, etc)
- Fix a bug that prevent user from removing custom directory
- Revamp the compiling process! Now it should run faster
- New DEV-mode for contributor! Prevent updates, manual-update, uninstall from happening / Prevent queue system to take effect (for rapid request testing) / Enable logs system (Backend logs ONLY) if DEV-mode is activated