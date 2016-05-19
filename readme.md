# twitch-bash

```
You can add channels you would like to track. You can
use a shorthand for channels so you don't need to
type the full channel name to start watching them.
Just add a track line for every shorthand 
you want to add.
The last one you add will be displayed on the
online channel overview

-> track <shorthand> <channel>
example: track hmh handmade_hero
         track hero handmade_hero
         track allen mr4thdimention

Usage: twitch - show online channel overview
       twitch <channel/shorthand> - play with livestreamer at quality best
       twitch <channel/shorthand> <quality> - play with livestreamer at quality <quality>
       twitch --livecheck-xfce-genmon - output that can be used in xfce4-genmon
       twitch --livecheck-xfce-genmon --display-number - also display the number of online channels *very ugly* (requires optional dependency imagemagick)
             http://goodies.xfce.org/projects/panel-plugins/xfce4-genmon-plugin

Internal: twitch --livecheck-channel <channel> - Check if a channel is live, output formatted string
          twitch --livecheck-channel-boolean <channel> - Check if a channel is live, output 0/1

Dependencies: coreutils, findutils, curl, grep, livestreamer
Optional dependency: imagemagick (to display number in xfce4-genmon)
```
# License
This software is considered to be in the public domain by the author and all contributors.
If release into the public domain is not possible in your country, an equivalent usage permission is granted.
