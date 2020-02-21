# ![app icon](./Screenshot/EB.png) [DBM] JSON Embed Builder
[![release](https://img.shields.io/static/v1?label=release&message=1.0.8&color=red)](https://github.com/Gr3nDy/DBM-Embed-Builder/)

Create **Embed** inside **Discord**
![gif](./Screenshot/GIF.gif)

 
# Installation
Copy [Embed (Raw Data)](https://raw.githubusercontent.com/Gr3nDy/DBM-Embed-Builder/master/RawData/embed.json) and import to
DBM.
* 1.Create New Command
* 2.Right click the command
* 3.Select Edit Raw Data
* 4.Paste [Embed (Raw Data)](https://raw.githubusercontent.com/Gr3nDy/DBM-Embed-Builder/master/RawData/embed.json)
* 5.Click on save


# Usages
<details><summary>Commands</summary>

* `embed <embed>` | Create embed from json
* `embed help <1/2/3/4/5>` | Embed Builder guide
* `embed variables` | List of variables
* `embed colors` | List of color variables
* `embed examples` | List of example format
</details>

# Features
* A Few built in variables & colors that you could use 
* Colors are in both decimal & hexadecimal
* Plaintext (content message)
* Simplified JSON for `image` and `thumbnail`


# Changelogs

<details><summary>1.0.0</summary>

* Added `embed help`
* Bugs fixed
</details>

<details><summary>1.0.2</summary>

* Added `embed variables`
* Added `embed colors`
* Added `embed examples`
* Bugs fixed
</details>

<details><summary>1.0.4</summary>

* More relaxed JSON
* Thumbnail & Image both works with or without `{url:}`
* Added more colors & variables
* Added `plainText`
* Bugs fixed
</details>

<details><summary>1.0.6</summary>

* Added Random Color `{RANDOM_COLOR}`
* Fixed Invalid `\` When creating new line
* Fixed Invalid `\` When inserting double quotes
+ [1.0.6 (OLDER VERSION)](https://raw.githubusercontent.com/Gr3nDy/DBM-Embed-Builder/master/RawData/embed-1-0-6(old%20version).json)
</details>

<details><summary>1.0.8</summary>

* Added `ALIASES` (Now it's easier to post an embed)
* Ability to change `ALIASES` Prefix
* Bugs fixed
+ [1.0.8 (LATEST VERSION)](https://raw.githubusercontent.com/Gr3nDy/DBM-Embed-Builder/master/RawData/embed.json)
</details>

# Note
Make sure you've installed <em>betamods</em> on your DBM
<br>
<br>
If you like to use an online generator for json embed builder you can use; [Nadeko Embed Builder](https://eb.nadeko.bot)
<br>
Heres a few guides that might come in handy; [Embeds|Discord.js](http://discordjs.guide/popular-topics/embeds.html)
<br>
<br>
If you are experiencing problem try to post it without `curly brackets`/`{ }` on the first and the last letter of the message
<details><summary>Gif</summary>

![curly](./Screenshot/curlybrackets.gif)
</details>
