Are you tired of small empires establishing the galactic market within their borders?
 - Then this is for you!

[b]Empires with higher trade income are now even more likely to host the galactic market![/b]

As of Federations, the base game included a small deliberation of this fact already. But, even with Orion, Paradox has still not touched some of the issues present in the event chain (which are fixed by this mod). 

This mod tweaks the event that chooses the country to lead the galactic market. It also fixes the relocation of the market through the galactic community, which still uses the completely outdated formula in the vanilla game (it was forgotten by the Paradox developer who updated the event chain).

Country wide trade income will be increasing the likelihood of being chosen as the host (the income is multiplying the chances of getting chosen) if you use this mod.
The base game only uses the trade flowing through the solar system of the planet as well as the candidate rating displayed in the planet modifier.
The vanilla rating system has been kept, this mod just applies an additional multiplier.

It effects all countries (including the AI) the same way.

This makes the luck-of-the-draw more predictable and accurate for empires with a different trade_income.

[b]All in all this ensures that countries with more trade have way higher chances of being selected[/b], while pushing your rating is still very much worthwhile, if most countries are on the same level. You should also carefully choose the planet to nominate, as its location will strongly influence your rating. Your capital system will be a great candidate, because all your trade routes connect there.

Single system galactic market hosts are therefore way more unlikely and you, the player, are able to strategically decide, if going for more trade value to acquire the 10% Market Discount that the station provides is worth it or not with a strong guarantee that it'll work out how you planned.

The system of the hosting country where the station will be installed, is the one home to the nominated planet.
This is a change from vanilla, where any planet of the empire still had a very slight chance to be chosen (however it was pretty much already impossible with weights of 1:9999).

[i]Should be save game compatible, for as long as the founding event hasn't fired.
Ironman compatibility status is questionable due to changes for a vanilla event chain (please leave a comment if you notice otherwise).[/i]

[h1]Details[/h1]
The Galactic Market event chain starts when the resolution in the Galactic Community to found it has been passed. 

Calculation of drawing weights:
[code]weight = ( 5 * rating_multiplier ^ 2 ) * trade_income * system_trade_value )[/code]

Calculation of the rating multiplier:
[list]
[*]Weak = [b]5[/b][code]= ( 1 )^2 * 5[/code]
[*]Adequate = [b]20[/b][code]= ( 2 )^2 * 5[/code]
[*]Strong = [b]45[/b][code]= ( 3 )^2 * 5[/code]
[*]Exceptional = [b]90[/b][code]= ( 4 )^2 * 5[/code]
[*]Perfect = [b]125[/b][code]= ( 5 )^2 * 5[/code]
[/list]

[h2]Compatibility[/h2]

This mod edits [i]on_action_events.txt[/i] and [i]galactic_community_events.txt[/i]. Currently the two events that are overwritten will be FIOS (first in - only loaded) due to ASCII order and the vanilla file will not be overwritten. Thus this mod should be compatible with any other mods that don't also edit the country events
[code]action.98[/code]
[code]galcom.67[/code]
This is may break between updates - but it didn't for Federations and Orion, so it should be safe to assume it will continue to work even if I (god forbid) abandon the mod one day. Still, if you notice any bugs (like a way too small empire hosting the galactic market), please report it in the comments so I can fix the issue.

[h1]Future Development & Notes[/h1]
As requested, another mod that will exclude isolationist nations, less likely to engage in strong intergalactic trade, like xenophobe empires, will probably be developed in the near future. It will be posted on its own though, since it'd probably not be for everyone. Especially when playing a xenophobe empire yourself, you'd probably not want that mod enabled. I'll leave a link here when I get to it.

If requested I can look into developing another mod that guarantees the country with the highest trade income will host the galactic market. In my opinion though, having a chance for each country, corresponding to their economic trading power is more realistic. This is especially true if multiple countries are on the same scale.

I tried to query a planets trade value directly, by the way. However, there was no way to read the value so prominently displayed ingame on the colony window. It was only possible to get access to a system's trade route value. And that is sadly inflated by other routes running through the system and/or doesn't differentiate between multiple colonies in the same system.

[i]The whole trade value interface under the hood is still "slightly" lacking.[/i]

If you have any information that would help me out concerning these problems, please do leave a comment!

Sadly, even the Federations and Orion updates didn't change this fact.

[h1]Obligatory Footnote[/h1]
[url=https://github.com/n1ghthavvk/stellaris-galketion][img]https://i.imgur.com/0nVeF3I.png[/img][/url]
Looking for my other creations?
[url=https://steamcommunity.com/sharedfiles/filedetails/?id=1998204784][img]https://i.imgur.com/wJgHgx8.jpg[/img][/url]
[url=https://steamcommunity.com/sharedfiles/filedetails/?id=2080968400][img]https://i.imgur.com/IBj3WfX.jpg[/img][/url]
[url=https://steamcommunity.com/sharedfiles/filedetails/?id=2036087802][img]https://i.imgur.com/JCGnvng.jpg[/img][/url]

Thanks for reading the description, downloading & playing with my mods!

[strike][i]Don't forget to leave a comment, smash that like button, subscribe and hit the bell icon!!![/i][/strike]
