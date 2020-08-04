# BRB Clips by 715209

---

This is a HTML/JS project that will show the top 10 overall and top 10 most recent clips of a twitch channel.

## Prerequisities
- Go to the [Twitch Dev Console](https://dev.twitch.tv/console/apps), click the purple `Register Your Application` button.
- Give your application a unique name, write `http://localhost` in the `OAuth Redirect URLs` field, select a category, You could just use `Application Integration`.
- Click `Create`, afterwards it will bring you back to your application list, click on the `Manage` button.
- Once you are in the `Manage Application` section you will see a couple new things, `Client ID` and a `New Secret` button, click it
  and you will get a `Client Secret`.

## Setup
- Right click and download the `clips.html` from [HERE](https://github.com/715209/BRB-twitch-clips/raw/master/clips.html).
-   Open 'clips.html' in your favorite code editor program, scroll down to the bottom and edit your;
     - `username`
     - `clientid`
     - `clientsecret`
- Save the file.

## Usage
-   Open OBS, Add a new Browser source, check Local file, click browse, browse to your edited and saved `clips.html` file and double click it.
    - Optional: Change the width and height to best suit your needs, I prefer the 16:9 ratio, 1280x720, 1920x1080 etc..
-   Once added it should start playing your clips, now all that is left to do is make it work with your scene.



---
If you have any questions feel free to open an issue.

