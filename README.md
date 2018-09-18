# Mp3tag Actions Pack

## About
[Mp3Tag](https://www.mp3tag.de/en/) is a [Tag Editor](https://en.wikipedia.org/wiki/Tag_editor) software.

[An action](https://help.mp3tag.de/options_format.html) is the feature of Mp3Tag allows to edit tags in automatic (pre-programmed) way. For example, user can write an action that will Uppecase Every First Letter In Every Word, or will create a folder with the "*[year] %artist% - %albumname%*" name and put audiofiles here. Basically it saves a lot of time.

Actions is a powerful feature, but require to know both Regular Expressions(https://en.wikipedia.org/wiki/Regular_expression) and learn in-build functions(https://help.mp3tag.de/main_scripting.html). For most users it is complicated. To make things 'worse' - Mp3Tag has two different syntaxes with different escaping rules and logic.

That repository provides a **pack of prebuild actions**. You *don't need to learn programming*, just copypaste those actions into your program and user them on click.

## Important
* That pack *is not a magic wand* that will satisfy any need and can handle any situation. Do not expect this pack will solve all problem.

* Before using those actions - create a backup folder for your music files and play around with actions before using them on 'real' files.

* If you have a special case and that pack cannot help you, then you mush either [learn the syntax](https://community.mp3tag.de/t/actions-and-batch-operations/967/12) or ask for the help on the [forum](https://community.mp3tag.de/).

## Installation
1. Required Mp3Tag Version - **Mp3Tag 2.87 and higher**.
2. **Download** that repository;
3. **Unpack** archive into the following folder:

```
C:\Users\ %username% \AppData\Roaming\Mp3tag\Data\Actions
```

- If you have **Windows XP**:

```
C:\Documents and Settings\ %username% \Application Data\Mp3tag\Data\Actions
```

- If you installed Mp3Tag in **[portable](https://www.mp3tag.de/en/portable.html)** mode:

```
%mp3tag location%\Data\Actions 
```

4. Now you should [see](/help/help001.png) new actions in the menu.

## FAQ

### Q. What do numbers (10_, 12_, 14_) in action names mean?
**A**. They exist for sorting purposes. Without them actions would have been sorted according to the first letter (which is not comfortable to read and follow). Those numbers allow to sort actions according to their function and what tag they affect.

### Q. I am tired to select dozen actions over and over, how can I simplify selection?
**A1**. Manually copypaste actions into one single action (via any text editor), see 00_MAIN.mta as an example
**A2**. Create _an action group_. See the [screenshot](/help/help002.png)

### Q. What is 00_MAIN action?
**A**. This is my personal action I am using to clean music in my collection. You can use it as a guideline how you can combine various actions in one file.
