# TransperentFox
A transparent skin for Firefox and Thunderbird. This skin is intended to be used on Linux systems, with a compositor configured to blur the background. To achieve this on KDE Plasma, I use the following: https://github.com/taj-ny/kwin-effects-forceblur

# Screenshots


# How To Install
## Firefox
1) Go to about:config and enable toolkit.legacyUserProfileCustomizations.stylesheets
2) Go to ~/.mozilla/Firefox/Profiles/[Random String]/chrome
  - You may need to create the chrome folder
  - If you installed Firefox via snap of flatpak, the .mozilla folder may be located elsewhere
3) Put this userChrome.css file in the chrome folder
4) Restart Firefox

## Firefox
1) Go to settings, scroll all the way to the bottom, and click "Config Editor"
2) Enable toolkit.legacyUserProfileCustomizations.stylesheets
3) Go to ~/.thunderbird/Profiles/[Random String]/chrome
  - You may need to create the chrome folder
  - If you installed Firefox via snap of flatpak, the .mozilla folder may be located elsewhere
4) Put this userChrome.css file in the chrome folder
5) Restart Firefox

# Configuring Kwin
If you are using kwin-effects-forceblur, enable force blur and add the following to your applications list:
```
firefox
thunderbird-bin
```
You may adjust the blur intensity to your liking.
