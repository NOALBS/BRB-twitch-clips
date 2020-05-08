# BRB Clips by 715209

---

This is a HTML/JS project that will show the top 10 overall and top 10 most recent clips of a twitch channel.

## Prerequisities
- There are two ways you can do this;
> 1) Use your main Twitch account to get an oauth [HERE](https://twitchapps.com/tmi)
     click the connect button, login and authorize to get your 'oauth:xxxxxxxxxxxxxxxxxxxxxx'
     
> 2) Register an ALT Twitch account [HERE](https://www.twitch.tv/signup), then get an oauth [HERE](https://twitchapps.com/tmi)
     click the connect button, login and authorize to get your 'oauth:xxxxxxxxxxxxxxxxxxxxxx'

Once you have your oauth follow these steps:
- Go to the [Twitch Dev Console](https://dev.twitch.tv/console/apps), click the purple `Register Your Application` button.
- Give your application a unique name, paste your recently acquired oauth in the `OAuth Redirect URLs` field, select a category,
  I usually just use my BOTs oauth so it's 'chat bot', but you could use `Application Integration`.
- Click `Create`, afterwards it will bring you back to your application list, click on the `Manage` button.
- Once you are in the `Manage Application` section you will see a couple new things, `Client ID` and a `New Secret` button, click it
  and you will get a `Client Secret`.
- Copy & paste these in notepad or something as you will need them for the next steps.

## Setup
- Right click and download the `clips.html` from [HERE](https://github.com/715209/BRB-twitch-clips/raw/master/clips.html).
-   Open 'clips.html' in your favorite code editor program, scroll down to the bottom and edit your `channel`, `clientid`, and `clientsecret`, then save the file.

## Usage
-   Open OBS, Add a new Browser source, check Local file, click browse, browse to your file and double click it.
    - Optional: Change the width and height to best suit your needs, I prefer the 16:9 ratio, 1280x720, 1920x1080 etc..
-   Once added it should start playing your clips, now all that is left to do is make it work with your scene.



---
If you have any questions feel free to open an issue.

