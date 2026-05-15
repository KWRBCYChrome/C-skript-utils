# skript essentials
> a library of lightweight skripts for Paper servers that need it, this is for the most part commands. i will add stuff as i go and also by request
### commands:
| Command               | Arguments                                 | Description                                                                                       | Permission |
|-----------------------|-------------------------------------------|---------------------------------------------------------------------------------------------------|------------|
| **setspawn**          | none                                      | Set the location for the **/spawn** command                                                        | none |
| **spawn**             | none                                      | Teleport to the location set with **/setspawn**                                                   | none |
| **to**                | `<player>`                                | Teleport to *player*                                                                              | none |
| **bring**             | `<player>`                                | Bring *player* to you                                                                              | none |
| **tor**               | none                                      | Teleport to a random player                                                                       | none |
| **bringa**            | none                                      | Bring every player to you                                                                         | none |
| **fly**               | `[player]` (optional)                     | Toggle flight for you or another player                                                           | none |
| **clearchat**         | none                                      | Clear the chat for everyone                                                                        | none |
| **sc** / **staffchat**| `<text>`                                  | Send a message only to staff (those with permission)                                            | skript.mod |
| **v** / **vanish**    | none                                      | Hide you from the tab‑list and from other players                                                  | skript.mod |
| **broadcast**         | `<text>`                                  | Send a server‑wide announcement                                                                    | skript.mod |
| **telefrag**          | `<player>`                                | Teleport to *player* and kill them                                                                 | skript.mod |
| **report**            | `<player>` `<reason>`                     | File a report about *player* with a reason                                                         | none |
| **suggest**           | `<text>`                                  | Submit a suggestion                                                                                | none |
| **reportlist**        | none                                      | View all reports (who reported who, reason, timestamp)                                            | skript.mod |
| **suggestlist**       | none                                      | View all suggestions (who suggested what and when)                                                | skript.mod |
| **clearlist**         | `[report/sugg]` (optional)               | Clear both lists (no arg) or only the specified list                                             | skript.mod |
| **home**              | none                                      | Teleport to your personal home                                                                      | none |
| **sethome**           | none                                      | Set your current location as home                                                                  | none |
| **warp**              | `<warp‑name>`                             | Teleport to a predefined warp point                                                                | none |
| **setwarp**           | `<warp‑name>`                             | Create a new warp at your location                                                                 | skript.mod |
| **delwarp**           | `<warp‑name>`                             | Delete an existing warp                                                                           | skript.mod |
| **tpa**               | `<player>`                                | Send a teleport‑request to *player*                                                               | none |
| **tpaccept**          | none                                      | Accept the most recent teleport request                                                            | none |
| **tpdeny**            | none                                      | Deny the most recent teleport request                                                              | none |
| **msg** / **pm**      | `<player>` `<text>`                      | Private message another player                                                                     | none |
| **reply**             | `<text>`                                  | Reply to the last private message you received                                                     | none |
| **afk**               | `[reason]` (optional)                     | Toggle AFK status (shows in chat & tab list)                                                     | none |
| **nickname**          | `[nick]` (optional)                       | Set/clear your own nickname (or another’s with permission)                                      | skript.mod |
| **kick**              | `<player>` `[reason]`                     | Kick a player from the server                                                                     | skript.mod |
| **ban**               | `<player>` `[reason]`                     | Ban a player permanently                                                                          | skript.mod |
| **tempban**           | `<player>` `<duration>` `[reason]`       | Temporarily ban a player                                                                          | skript.mod |
| **unban**             | `<player>`                                | Remove a ban                                                                                      | skript.mod |
| **mute**              | `<player>` `[duration]`                  | Mute a player (prevent chat)                                                                      | skript.mod |
| **unmute**            | `<player>`                                | Unmute a player                                                                                   | skript.mod |
| **warn**              | `<player>` `<reason>`                     | Add a warning to a player’s record                                                                | skript.mod |
| **warnings**          | `<player>`                                | List a player’s warnings                                                                          | skript.mod |
| **clearwarnings**     | `<player>`                                | Remove all warnings for a player                                                                  | skript.mod |
| **freeze**            | none                                      | Freeze all player movement (maintenance mode)                                                    | skript.admin |
| **unfreeze**          | none                                      | Unfreeze the server                                                                              | skript.admin |
| **gmc** / **gms** / **gma** / **gmsp** | none                      | Quick‑switch your own gamemode (creative, survival, adventure, spectator)                        | none |
| **speed**             | `<value>` `[player]`                      | Change walk/fly speed for you or another player                                                   | skript.mod |
| **invsee**            | `<player>`                                | Open a GUI to view another player’s inventory                                                     | skript.mod |
| **enderchest / echest**        | `[player]` (optional)                     | Open your own (or another’s) ender chest                                                          | skript.mod |
| **god**               | `[player]` (optional)                     | Toggle invulnerability                                                                           | skript.mod |
| **day** / **night**   | none                                      | Set world time to day or night                                                                   | skript.mod |
| **weather**           | `<clear/rain/storm>`                      | Change the server weather                                                                         | skript.mod |
| **reportinfo**        | `<id>`                                    | View details of a specific report                                                                | skript.mod |
| **suggestinfo**       | `<id>`                                    | View details of a specific suggestion                                                             | skript.mod |
| **reporttoggle**      | none                                      | Enable/disable the whole report system                                                            | skript.admin |
| **suggesttoggle**     | none                                      | Enable/disable the whole suggestion system                                                         | skript.admin |
| **ping**              | none                                      | Show your current ping                                                                            | none |
| **uptime**            | none                                      | Show how long the server has been running                                                         | none |
| **whois**             | `<player>`                                | Show basic info: UUID, first join, last join, playtime                                           | none |
| **seen**              | `<player>`                                | Show when the player was last online and how long ago                                            | none |
| **stats**             | `[player]` (optional)                    | Show a quick summary of kills, deaths, blocks placed/broken, etc.                               | none |
| **repair**            | `[player]` (optional)                    | Repair the item in your hand (or another’s)                                                      | skript.mod |
| **realname**          | `<nickname>`                              | Resolve a nickname to the real player name                                                        | none |
| **togglerank**        | `<player>` `<rank>`                       | Switch a player’s rank between groups                                                 | skript.admin |
| **list**              | none                                      | Show a compact list of online players with ping & health                                         | none |
| **locate**            | `<player>`                                | Show coordinates of a player without teleporting                                                | none |
| **roll**              | `[max]` (optional, default 100)          | Roll a random number between 1 and *max*                                                          | none |
| **coinflip**          | none                                      | Flip a coin (heads/tails)                                                                        | none |
| **whoami**            | none                                      | Display your rank, gamemode, world, etc.                                                          | none |
| **randomtp**          | none                                      | Teleport to a random safe location                                                                | none |
| **action**               | `[hug/kiss/five]`                                | Broadcast a friendly message directed towards a player                                                         | none |




## Requirements

| Requirement | Minimum version | Download / Source |
|------------|----------------|-------------------|
| Paper      | 1.21.5+        | https://fill-data.papermc.io/v1/objects/2ae6ae22adf417699746e0f89fc2ef6cb6ee050a5f6608cee58f0535d60b509e/paper-1.21.5-114.jar |
| Skript     | 2.15.0+        | https://github.com/SkriptLang/Skript/releases/download/2.15.0/Skript-2.15.0.jar |

---

## Folder tree
```text
.
├── master
    └── config.sk
├── main
│   ├── teleport.sk
│   ├── staff.sk
│   ├── telefrag.sk
│   └── lists.sk
├── utilities
│   ├── warps.sk
│   ├── msg.sk
│   ├── reply.sk
│   ├── afk.sk
│   ├── nickname.sk
│   ├── ping.sk
│   ├── uptime.sk
│   ├── whois.sk
│   ├── seen.sk
│   ├── stats.sk
│   └── repair.sk
└── README.md
