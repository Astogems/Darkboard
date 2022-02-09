# Darkboard
This repository contains all the YAML Codes required to recreate https://github.com/matt8707/hass-config entirely on the UI Editor

## Disclaimer:

All of the magic done here is not solely my work. It is the work of all the awesome contributors such as:

https://github.com/matt8707/hass-config
https://github.com/lukevink/hass-config-lajv
https://github.com/DBuit/sidebar-card

The main purpose of this repository is not to showcase the entire code, but to teach users how to implement as majority of users are using the UI Editor, hence it seemed to be impossible to implement this dashboard, but it never was.

## Installation requirements:
1. You are not in Lovelace-UI Config mode.
2. You have all the prerequisite custom components installed.

## Guide:

As of 28/1/2022, I will post a video tutorial first, and then slowly update this repository as time goes.

Watch this video for the full installation guide.

https://www.youtube.com/watch?v=Rky5UP-2MlI

## FAQ:

Question: I have installed everything as shown in the video but my light popup is not working.
Answer: You probably did not install browser_mod correctly. Check if your configurations.yaml contains 

browser_mod:

Secondly, under Developer-Tools, check if you have browser_mod services. If all of these are present and it still does not work, check your custom_components again and be sure not to miss out anything!


