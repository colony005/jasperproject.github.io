---
title: Using Jasper
layout: default
currentpage: usage
---

Using Jasper
===


<h2 class="linked" id='selecting-network'><a href="#selecting-network" title="Permalink to this headline">Selecting a wireless network</a></h2>

When you turn on Jasper for the first time, it will ask you to configure a new wireless network connection. From your laptop, connect to the temporary "Jasper" network that will appear after a few minutes.

After connecting to Jasper's temporary network, browse to [192.168.1.1:8000/cgi-bin/index.cgi](http://192.168.1.1:8000/cgi-bin/index.cgi) and follow the on-screen instructions. When complete, your Jasper will restart and connect to your selected wireless network automatically.

To change the wireless network in the future, just turn on your Jasper without the wifi adapter, wait a few minutes, then restart Jasper with the wifi adapter plugged in. Jasper will again ask you to select a wireless network and you can just follow the steps outlined above.

<h2 class="linked" id='interacting'><a href="#interacting" title="Permalink to this headline">Interacting with Jasper</a></h2>

The most common way to speak with Jasper is with the following sequence:

- _You_: "Jasper"
- _Jasper_: *high beep*
- _You_: *speak your command*
- _Jasper_: *low beep*
- _Jasper_: *speaks the response*

After saying Jasper, you must wait for the high beep to speak your command. If you don't speak a command within a few seconds, Jasper will stop listening or ask you to repeat your command.

<h2 class="linked" id='modules'><a href="#modules" title="Permalink to this headline">Modules to try</a></h2>

By default, we've included the following modules to demonstrate Jasper's capabilities:

- Time: "What's the time?"
- Weather: "How's the weather?... What's the weather like tomorrow?"
- News: "What's in the news?"
- Gmail: "Do I have any email?"
- Hacker News: "What's on Hacker News?"
- Facebook Notifications: "Facebook notifications?"
- Birthday: "Who has a birthday today?"
- Jokes: "Tell me a knock-knock joke."
- Life: "What is the meaning of life?"


To learn how to write your own module, check out the [Developer API documentation](/documentation/api).

<h2 class="linked" id='spotify-mode'><a href="#spotify-mode" title="Permalink to this headline">Spotify Mode</a></h2>

If you've [configured Spotify](/documentation/software/#spotify-integration), Jasper will enter Spotify mode with the "Music" or "Spotify" command. Here's a list of example commands you can issue while in Spotify mode:

- "Play Hipster Playlist": plays playlist titled "Hipster" from your Spotify library
- "Play": plays currently playing song
- "Pause": pauses currently playing song
- "Stop": stops currently playing song
- "Louder": raises volume
- "Softer": lowers volume
- "Next": plays next song in playlist
- "Previous": plays previous song in playlist
- "Close": exits Spotify mode and resumes normal command interpretation

Jasper may have difficulty detecting your cues when the music is loud. In these instances, it helps to distance the microphone from the speakers, lowering the volume, and/or speaking closer to the microphone.
