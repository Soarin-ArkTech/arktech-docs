+++
title = "Server Configuration"
date =  2021-03-24T22:10:47-04:00
weight = 101
+++

## server.cfg
garrysmod/cfg

screenshot of arktech's auto-generated server.cfg file

Basic server.cfg generator https://csite.io/tools/gmod-universal-cfg

if -1 is specified on a sbox_max line, the limit is infinite

some more useful cfg options put them in a table or something
- sv_location us
- sv_alltalk 3

## Steam Workshop Collections
Workshop collections are by far the easiest way to use addons with a server. You can slim down loading times and content amounts with a bit of cleverness and time, therefore raising your concurrent playercount.

### Server-Side Addons
Not all of your server addons need to be downloaded by the player. Things such as administrative mods, scoreboards, tools, there is no need to force download them to those joining. 

However in this collection, you must include all the addons the server must load, no matter if it's needed by clients or not.

Here are some examples of popular addons that do *not* need to be downloaded by clients;
- Admin Mods (ULX, XAdmin, SAM, etc.)
- Tools (Wiremod, Advanced Duplicator, Precision, Stacker, etc.)
- Miscellanous (Stream Radio, PAC3, etc.)

### Client-Side Addons
Addons such as materials, models, and vehicles, users must download them in order to not see errors and missing textures.

This is where the clientside collection differs from the serverside collection. In this, you will include all of the addons that clients will need, such as the addon types listed above. Once your collection is assembled, you will need to place them into the workshop.lua file. Generate one using the handy tool found [here](https://csite.io/tools/gmod-universal-workshop). A more thorough explanation on the workshop.lua file can be found [here](/gmod-guides/serverowners/mounting-addons/).

Here are some examples of popular addons that *do* need to be downloaded by clients;
- Materials (More Materials, GDisasters Material Pack, etc.)
- Car Addons (Simfphys, TDM Cars, LW Cars, etc.)
- Models (SProps, Steventechnos, etc.)

{{% notice note %}}
For servers with large amounts of content (>1.0gb) on a clientside collection, we strongly advise you not to put them all in your workshop.lua file, as those with bad internet will suffer.
{{% /notice %}}

## Commandline Manager
mention startup parameters in pterodactyl 

explain the different fields

link gslt to the dedicated page

#
![Banner](/images/fishy.gif)