# Random Clip Player
A simple random Twitch clip player with zero limitations.

# Setup
You are required to create a Twitch developer application in order for this to function.
If you have already created one and have the Client ID and Client Secret, skip to Step 8.

1. Visit https://dev.twitch.tv/ and Login.
2. Press "Your Console" in the top right.
3. Under "Applications" press "Register Your Application"
4. Give it any name, it doesn't matter. Select the most appropriate category, or just "Other."
5. As an "OAuth redirect URL" is required, enter a link to any website - preferably one you own, or just enter a link to google (https://google.com/). **The app doesn't use this so it's not important.**
6. Press "Create"
7. Once created, press "Manage" and scroll to the bottom of the page. **Take note of the "Client ID" and "Client Secret"** (press new secret if there isn't one there)
8. Now, download the `viewer.html` file from [here](https://github.com/ShaderWave/RandomClipPlayer/releases/tag/v1.0). Save this file somewhere accessible.
9. Open the `viewer.html` file in a text editor of your choice.
10. In `CLIENT_ID` and `CLIENT_SECRET` enter the Client ID and Client Secret respectively, **between the quotes.**
11. In `BROADCASTER_NAME` enter your Twitch username, **between the quotes.**
12. Adjust any of the other settings as you wish.
13. Once this is complete, save and close the file.
14. In OBS/other streaming software, simply add this file as a Browser Source. You may need to tick "local file" in order for this to be possible.
