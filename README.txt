[align=center][i]I present to you the[/i]
[b]What.CD Debt Calculator[/b].
Displays remaining upload credit required if required ratio is not met.
https://github.com/Wingman4l7/debtcalc

[img]https://whatimg.com/i/thng4s.png[/img]

[img]https://whatimg.com/i/ua1e9f.png[/img][/align]

This script has two parts.  
The first part inserts your upload "debt" [i](if you have any)[/i] next to your current ratio.  [i](the first screenshot)[/i]
The second part does the same thing -- but on the sidebar of [u]any user page[/u].  [i](the second screenshot)[/i]

I was inspired to do this after reading the [url=https://what.cd/forums.php?action=viewthread&threadid=167614]"Required ratio calculator"[/url] thread in the Suggestions / Ideas subforum.  Hopefully this script will be useful for:
[*] those in ratio watch to easily find out how much upload they need to get out of it
[*] admins who would like to easily tell those in ratio watch how much upload they need to get out of it
This script uses the "required ratio" value, which already does the hard work of factoring in the % of seeding / snatched torrents.  It is assumed that the user already knows that the higher their %, the lower their required ratio.  Needless to say, the second part of this script will only work if the user's paranoia is set low enough so that all of their stats [i](UL, DL, ratio, & required ratio)[/i] are displayed.  It uses colors from style.css to indicate the "severity" of the debt [i](the color ranges were manually adjusted, so if you think they're a bit off, speak up.)[/i]

For similar scripts, search The Laboratory forum for "buffer calculator".  Thanks to the authors of the [url=https://what.cd/forums.php?action=viewthread&threadid=93458]What.CD Buffer Calculator+[/url] for the [code]toBytes()[/code], [code]fromBytes()[/code], & [code]spanColor()[/code] functions and supporting code.

This script has been tested on Chrome, with the Layer Cake stylesheet; let me know if it doesn't work with your browser / stylesheet and I'll try to fix it.

Let me know what you think!