---
title: How to Make a Jellyfin Music Player for Cheap
description: Mostly because I miss Symfonium and iOS Jellyfin music apps sucks, IMO. 
slug: how-to-make-a-diy-musicplayer
date: 2025-04-16 00:00:00+0000
image: cover.jpg
draft: true
categories:
    - Security

tags:
    - Jellyfin music player cheap
    - Cheap Jellyfin music player
    - DIY Jellyfin music player
    - Budget Jellyfin music player
    - Make Jellyfin music player
    - Jellyfin music streaming
    - Jellyfin audio player
    - Affordable music server client
    - Old phone Jellyfin music player
    - DIY home music server client
    - Stream music from Jellyfin
    - Free Jellyfin music player
    - Turning an old phone into a Jellyfin music player
    - Cheapest way to stream music from my Jellyfin server
    - Step-by-step guide to making a low-cost Jellyfin music player
    - Jellyfin music player setup for beginners
    - Setting up a cheap Jellyfin audio streaming device
    - Alternatives to expensive music streaming devices with Jellyfin
    - Can I use an old tablet as a Jellyfin music player?

---

## Introduction
You might call me impulsive and crazy, but one of the only things I miss from Android is [Symfonium](https://www.symfonium.app/), it’s the best music player app for people who self host. It supports Jellyfin and Subsonic and local music and is one of the few music players that feels *complete.* <abbr title="iPhone Operating System">iOS</abbr> Jellyfin apps don’t compare to the experience [Symfonium](https://www.symfonium.app/) gave me.

I decided to make a <abbr title="Do It Yourself">DIY</abbr> music player and pretend it’s the early 2000’s! :) It’s pretty cheap so I hope you’ll make it! I do software tweaking to fit my needs but you don’t need to follow everything to make this work, do what serve you and makes you comfortable! :)

## What You Need?
- A miniature phone (you can buy one for cheap on Aliexpress or Amazon)
- Camera cover stickers
- A <abbr title="Personal Computer">PC</abbr> (Windows/Linux/MacOS)
- <abbr title="Universal Android Debloater">UAD</abbr> <abbr title="Graphical User Interface">GUI</abbr> installed on your <abbr title="Personal Computer">PC</abbr> - https://github.com/0x192/universal-android-debloater https://github.com/Universal-Debloater-Alliance/universal-android-debloater-next-generation/

## Step 0 - Cover the device’s cameras.
Just in case. My device runs Android 10 and I couldn’t take any risks so I covered the cameras with specialised stickers I ordered from Aliexpress. If I could, I would break the microphone, but alas.

## Step 1 - Debloating the miniature phone
Those phones come with basic apps installed and quite a bit of bloat. If you’ve ordered something similar to mine, you’ve got 16GB of storage and 2GB of <abbr title="Random-access memory">RAM</abbr>. Yeah... Not a lot...

First step is to enable developer mode, clicking on build number several times should do the trick. Next, enter developer options and enable *USB debugging.*

Second step, connect the device to your <abbr title="Personal Computer">PC</abbr> and open <abbr title="Universal Android Debloater">UAD</abbr> software, the name of the device should appear on top of the program alongside a list of apps you can uninstall/disable.

Read carefully through the list and uninstall unnecessary bloat. It takes a lot of trial and error to know which bloat might break your device, so don’t feel alarmed to uninstall and reinstall things.

After debloating your phone, put your phone on airplane mode and then connect to your wifi.

Airplane mode enhances privacy by turning off all wireless connections on your phone, including cellular networks, Wi-Fi, Bluetooth, and <abbr title="Global Positioning System">GPS</abbr>. This prevents your device from transmitting or receiving any signals, thereby reducing the amount of data that can be collected about your location and activities.

Airplane mode also saves battery life, you could solely waste it on listening to music! :)

## Step 2 - Install [Symfonium](https://www.symfonium.app/)
I installed it through the Google Play store. I paid for the program so I wanted to have access to it. I also wanted automatic updates. It was a risk I was willing to take. You can download it through Aurora Store, if you want, and using Google Play Store and Google Services is against your [threat model](https://www.privacyguides.org/en/basics/threat-modeling/).

## Step 3 - Set [Symfonium](https://www.symfonium.app/) up and Enjoy! :3
Open the app, follow the process in the screen and enjoy your new music player!! :) I also added [Symfonium](https://www.symfonium.app/) widget on the home screen to give it more of a music player vibe.

I connected a <abbr title="Micro Secure Digital">MicroSD</abbr> card to have more space for my music. I used 128GB, but I think 64GB or 32GB is enough. It’s up to how large your library is and how much music you wanna download.

I highly recommend going through the settings on [Symfonium](https://www.symfonium.app/) to tweak the interface and setup automatic downloads! :)

Enjoy!~

## Bonus Step - Download Nova Launcher
I write this 24ish hours after initial setup! I got sick of the homepage: having apps scattered around all the home screen and I needed a better grid for my widgets. 

Nova launcher is super easy to install and use. I’ve been using them for years at this point. I put cute image as a widget + [Symfonium](https://www.symfonium.app/) music player widget. 

![The aesthetic I went with was retro cybercore with lots of anime waifus, hehe.](Screenshot_20250416-002047.png)

## Summary
It’s a fun <abbr title="Do It Yourself">DIY</abbr> “iPod” project which doesn’t cost a lot. The 2GB of <abbr title="Random-access memory">RAM</abbr> is surprisingly enough, although I internally wish it had 4GB to avoid lag... ):

Please support [Symfonium](https://www.symfonium.app/) developers by donating or purchasing the app if you can! :)

My only complaint in this <abbr title="Do It Yourself">DIY</abbr> is that I can’t connect my headphones through <abbr title="Universal Serial Bus">USB</abbr> C and have to use my Bluetooth ones, I looked over and over again on my disabled apps but couldn’t find a source for it and Google wasn’t helpful either.

I’ll finish this article with: be careful when debloating and don’t go overkill like yours truly! Don’t panic though as everything is reversible! :)