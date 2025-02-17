# Heatchain

This repository show you some information about the game "Heatchain"

learn more about the game on : 
* Steam : https://store.steampowered.com/app/2521350/Heatchain/
* Itch.io : https://hyultis.itch.io/heatchain
* Android : https://play.google.com/store/apps/details?id=hyultis.heatchain.MainActivity
* Discord : https://discord.gg/m3pnhTVCSr

## Translates

I try to have as many translations as possible for the game.
If I messed a translation, or a language is missing, you can create an issue/merge on the translate.json file

## Used resource

All resource not created by Hyultis, are inside CREDITS.md

## rust used library

All rust library used are inside Cargo.toml

## Tips and configuration

Some shortcut are available if needed :

    F1 = Debug information
    F2 = swap between fullscreen/window


you can modify the configuration inside <gamedir>/config/config.json

    "lang" : allow to change the lang between these value : en,fr,it,es,de,pt,ru,hi,ja,ko,zh,ar (more can be added latter)
    "sound" : allow to modify volume (value are not bounded, so be carefull)
    "window/type" : 0 = bordeless, 1 = windowed
    "system/swapchain/fpslimiter" : fps maximum (0 for no limit)
    "system/swapchain/presentmode" : "Fifo" by default (vsync), "Immediate" or "Mailbox" to disable vsync (beware this is dependant of your system, the game will fallback to "Fifo" is the value is not supported by your GPU)
