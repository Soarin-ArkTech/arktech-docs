+++
title = "Mounting Addons"
date =  2021-03-24T22:10:47-04:00
weight = 103
+++

## workshop.lua
*AKA WorkshopDL*

This is the file containing the Workshop addons that you want all of your players to download during connection. We highly recommend that you keep the total forced download size under 1.0gb, as not everyone has the greatest network quality. Your players will thank you.

Generate a workshop.lua file with this [useful site](https://csite.io/tools/gmod-universal-workshop). The file itself wil be located in `garrysmod/lua/autorun/server`.

## resource.lua
Similar to workshop.lua, this will force your connecting players to download content. However, resource.lua is meant to force download files (such as .mdl, .vmt, .wav) to the client. 

[View more](https://wiki.facepunch.com/gmod/resource.AddFile) information on the Garry's Mod wiki. The resource.lua file is also located in `garrysmod/lua/autorun/server`.

## Steam Workshop Collections
Server-side and Client-side Workshop collections are mentioned in greater detail [here](/gmod-guides/serverowners/server-configuration/).

### Extracting Workshop Addons
Steam Workshop addons may be extracted. Ranging from intent to fix unsupported/buggy mods, to simply installing them the old fashioned way, there are many reasons why you may want the source files of an addon.

In order to extract addons, use this [handy dandy tool](https://steamworkshopdownloader.io/). Simply grab the link of your desired addon, paste it into the box, and download it!

{{% notice warning %}}
We do not condone publicly reuploading addons. Some addons are protected by copyright law, and may land you in trouble if reuploaded publicly without permission. Personal use only!
{{% /notice %}}

---
#
This page written by [wizerd](/contributors/wizerd/).
![Banner](/images/fishy.gif)