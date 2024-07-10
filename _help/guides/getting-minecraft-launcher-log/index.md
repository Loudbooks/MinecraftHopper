---
layout: article
title: "Getting Minecraft Launcher Logs"
name: "getting-minecraft-launcher-log"
desc: "How to get launcher logs in Minecraft"
---

# Getting Minecraft Launcher Logs <small>(Java Only)</small>

The Minecraft launcher keeps logs of game events as they happen which can be useful for debugging errors or other issues that may occur within the game. There are five types of logs that can be obtained:

* [Game Output](/help/guides/getting-minecraft-game-output-log/)
* Launcher Log (this guide)
* [Latest Log](/help/guides/getting-minecraft-latest-log/)
* [Crash Report](/help/guides/getting-minecraft-crash-report/)
* [JVM Crash Report](/help/guides/getting-minecraft-jvm-crash-report/)

The launcher log contains history from when the launder is started up until the game is closed. It is by far the most comprehensive log that Minecraft produces. Most often this log will be requested during most troubleshooting processes.

## Instructions

#### Step 1

Start the launcher and use it to the point where the error occurs. Then close Minecraft and keep it closed.
![Minecraft premature exit example](/static/images/help/guides/getting-minecraft-launcher-log/mojang-loading.png)

#### Step 2

[Open the .minecraft folder.](/help/finding-minecraft-data-folder/)
![Minecraft data folder](/static/images/help/guides/getting-minecraft-launcher-log/minecraft-folder-launcher_log.png)

#### Step 3

Look for a file called *launcher_log* or *launcher_log.txt* and double-click it to open it in Notepad.
![Launcher Log open in Notepad](/static/images/help/guides/getting-minecraft-launcher-log/launcher_log.png)

#### Step 4

Select the entire contents (**Ctrl-A** or **Cmd-A**) of the file and copy it (**Ctrl-C** or **Cmd-C**).
![Launcher Log in Notepad with all text selected](/static/images/help/guides/getting-minecraft-launcher-log/launcher_log-selectall.png)

#### Step 5

Open {{ site.paste_site }} and paste (**Ctrl-V** or **Cmd-V**) the contents into the largest field. Put your Discord username into the **'Title'** field.

#### Step 6

Click **Submit**. On the next page, copy the URL from the address bar and give it to whoever requested the log. Wait for further instructions.

## Troubleshooting

#### Log file Only Shows Four Lines

Try again. Be sure to keep the launcher open as you're getting the log after you close the game or the game crashes. If it continues to give you only four lines, inform whoever requested the log from you for further troubleshooting.

#### Bad Gateway (500) Error on {{ site.paste_site }}

Split the contents being copied/pasted into two parts, then try again. Give both links to the requestor in order.
