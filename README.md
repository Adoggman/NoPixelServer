# NoPixel

A few fixes to NoPixelServer. No guarantee that I'll work on this any more.

original credit:
- Swxy#0001 
- Sydres#9887
- Rubidium#7756(hawkeye)

# Installation
1. Create a FiveM server ([guide](https://i.imgur.com/PltX24m.png))
2. Stop the server
3. Open the new folder that was created under the `txData` folder
4. Delete everything in that folder
5. Clone this repository to that folder
6. Run `nopixel.sql` in your database
7. Run `set-passwords.bat` (requires wlr - I used [Ubuntu](https://ubuntu.com/wsl))
    - If you screw this up, the database information goes in `resources/ghmattimysql/config.json` and the rest of the information is in server.cfg
9. Start the server
