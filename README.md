# MK's Periodic Note Templates
A set of periodic note templates for Obsidian.md.

![image](https://user-images.githubusercontent.com/50339059/156691046-e7b383a0-65ee-43b4-b1d2-266389bb326f.png)
___

## Before You Start...
Please note that these templates generally suit _my workflow._ I supply them here (_and try to keep them up to date_) so that other members of the community can use them. **By all means**, you should change the templates when you download them--you might want to change the date formats, the trackers, the layout... All in all, this can be used as a base, or out of the box. 

These templates also assume you know how to use the plugins required. If you don't, please refer to the instructions on their repos--I unfortunately don't have the time to write a full-blown tutorial on how to use these files.

With all that out of the way, have fun!

## Required Plugins
- [Dynamic Table of Contents](https://github.com/Aidurber/obsidian-plugin-dynamic-toc)
- [Dataview](https://github.com/blacksmithgu/obsidian-dataview) (_ensure JS queries are enabled_)
- [Obsidian Banners](https://github.com/noatpad/obsidian-banners)
- [Obsidian Charts](https://github.com/phibr0/obsidian-charts)
- [Periodic Notes](https://github.com/liamcain/obsidian-periodic-notes)
- [Tasks](https://github.com/schemar/obsidian-tasks)
- [Templater](https://github.com/SilentVoid13/Templater)

___
### Setup
After installing the plugins required for these notes and configuring them, there are a couple other things that you may want to change too.

#### Banner Images
You may notice that in the examples in this repo, there are banners that compliment the notes. By default, they are set as `![[<% tp.date.now("YYYY MMMM") %> Weekly Banner.jpg]]` in the template's frontmatter. When generating a new daily note, it will be translated to `![[2022 March Weekly Banner.jpg]]`. I personally like to have different banners for each month of the year, so I have a small backlog of chronologically named banners.
___
### Daily Notes
Daily notes are used to take quick memos, and fill out various inline dataview trackers. They also manage tasks, and allow you to keep a simple view of what's to come, what's to be done, and such. They're quite nice to look at, and having a couple open at a time isn't an eyesore.

![image](https://user-images.githubusercontent.com/50339059/156691741-5f827d03-3f41-4216-95a6-3b9316c80304.png)

### Weekly Notes
Weekly notes are used as a bigger picture of a period of your life. They link automatically to all days of the week, and has a fully automated _Overview_ section where you can see a graph and dataview table of the trackers you choose. The memos in your daily notes get pulled into the _Daily Memos_ section so that you can see everything at a glance.

![image](https://user-images.githubusercontent.com/50339059/156692722-07407996-9c68-41a8-a801-e84402461ff9.png)

Concerning the weekly note's graph, the JS code rendering it has the path to daily notes as `dv.current().file.folder`. This assumes that your weekly notes are in the same folder as your daily notes. If you're like me, and sort your daily notes into folders chronologically, you could change the path to `"02 Personal/02.01 Periodic Notes/2022/Daily/03 March"` or similar.

### Monthly/Quarterly/Yearly Notes
As I don't really have a use case for these types of periodic notes, I doubt that I will make templates for them. If the request is high enough however, I will consider, and perhaps adopt it in my own workflow.
___
### Attribution
Huge thanks to the following people for...
- [Olivier Carizzoni](https://github.com/oliviercarizzoni): Improved graph code

### Support me!
Check out my other stuff:
- [Absolve](https://github.com/mulfok/obsidian-absolve)
- [mulfok's garden](https://publish.obsidian.md/mulfok-vault)

### Contact
- Discord: @mulfok#6931
- Twitter: @mulfok
