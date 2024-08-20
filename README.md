# Twitch BRB Clips by 715209 & b3ck

---

This is a HTML/JS project that will show the top 10 overall and top 10 most recent clips of a twitch channel.

*PLEASE NOTE: if using the `clips_alt.html` it will grab 100 of your clips, shuffle them and play them, once all of the clips have been played it will fetch new clips, reshuffle, play again and continue to do this in a loop.*

## Prerequisities
- Go to the [Twitch Dev Console](https://dev.twitch.tv/console/apps), click the purple `Register Your Application` button.
- Give your application a unique name, write `http://localhost` in the `OAuth Redirect URLs` field, select a category, You could just use `Application Integration`.
- Click `Create`, afterwards it will bring you back to your application list, click on the `Manage` button.
- Once you are in the `Manage Application` section you will see a couple new things, `Client ID` and a `New Secret` button, click it
  and you will get a `Client Secret`.

## Setup
- Right click and download the `clips.html` from [HERE](https://github.com/715209/BRB-twitch-clips/raw/master/clips.html).
     - if you are having issues with the `clips.html` try the `clips_alt.html` [HERE](https://github.com/NOALBS/BRB-twitch-clips/blob/master/clips_alt.html).
-   Open HTML file in your favorite code editor program, scroll down until you see a section that where you can edit the following and enter your details accordingly;
     - if using the `clips_alt.html` you can set `debug = true` to see a debug console if you are having issues.
     - `username`
     - `clientid`
     - `clientsecret`
- Save the file.

## Usage
-   Open OBS, Add a new Browser source, check Local file, click browse, browse to your edited and saved HTML file and double click it.
    - Optional: Change the width and height to best suit your needs, I prefer the 16:9 ratio, 1280x720, 1920x1080 etc..
-   Once added it should start playing your clips, now all that is left to do is make it work with your scene.



---
If you have any questions feel free to open an issue.

