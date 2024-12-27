# Compact Calendar

## Where it comes from
In 2010 I came across a compact calendar. It's a spreadsheet where you just change the year and it creates a compact view of that year so you can print it and write notes on certain periods. It gives an overview and let you think about the coming year.

The original version is the .xls file. The PDF version is for those who won't open a spreadsheet blindly ;). Change the year in G1 to get that year's compact calendar. This spreadsheet was modified in 2011 to include french holidays. Then I made a larger version for a specific need and I'm putting it here because I'm probably the only person looking at it anyway. I've only used LibreOffice and OpenOffice for about 20 years. You can be sure these spreadsheet files are compatible with open source office suites.

![](Compact%20Calendar%20screenshot.png)

### The original files
- [The original 2011 verions](CompactCalendar2011-France.xls)
- [A version with 4 more months](CompactCalendar2011-France-with4monthsIn2012.xls)
- [Larger version](CompactCalendar2021-large-France.xls)
- [The PDF version for 2025](CompactCalendar2025-France.pdf), see page 2

## Port to Obsidian
I don't use paper anymore and I felt like using this calendar in Obsidian.
Here's [my template](Compact%20Calendar%20Template.md). It asks for a year then generates a huge table with an extra column on the right to note stuff.

This version doesn't highlight holidays (yet) but it highlights the first day of each month. Feel free to adapt it as you like and please send your version in [an issue](https://github.com/Djyp/obsidian-djyp-things/issues/new), I'd love to see what you've done with it.

## How to use it

### Technically
You need [Templater](https://github.com/SilentVoid13/Templater) to use it. You can insert the template in any file with the command called `Templater: Insert template` then type `Alt + R` to execute the template. It will prompt to ask what year you are asking then you will see the calendar.

### As a tool
Just a list of ideas
- Give yourself an overview of your personal year and jot ideas on your milestones in the coming year
- Reflect on a project and help yourself to have an idea of how long this project can take. You can delete the table anytime
- Use it to assign a content publication to each weeks of the coming year
- Use it with [Dataview](https://github.com/blacksmithgu/obsidian-dataview) or [Tasks](https://github.com/obsidian-tasks-group/obsidian-tasks) to dynamically list tasks or notes related to each weeks. You would have to do it yourself though, it's not in the template.
- Use it to show a client the main milestones of their project
