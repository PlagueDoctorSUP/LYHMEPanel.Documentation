# Commands.dat

{% hint style="danger" %}
Each time you make a change or changes to this file you have to reboot your server. Along with capitals and lowercases don't matter. 💪🏼

**📢 Please do not change or remove the bind or port numbers.**
{% endhint %}

### File Location <a id="where-is-it-located"></a>

Wanting to edit the name of your server along with maybe even change the map? Great question! To do this you will want to login to [lyhmepanel.com](https://lyhmepanel.com) 

1. Click on [Game Services](http://lyhmepanel.com/Interface/GameHosting/GameServers.aspx) under Game & Voice Management then if you have more then one server select the one you want to change
2. Save and then stop your service then click on `Configuration Files` then to the left of `Commands.dat` Click on `[ Text Editor ]`

Now you are there! Nice work.

### Commands List <a id="where-is-it-located"></a>

Note: Each command you want to add goes on its own line.

<table>
  <thead>
    <tr>
      <th style="text-align:left">Command</th>
      <th style="text-align:left">Syntax</th>
      <th style="text-align:left">Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">Chatrate</td>
      <td style="text-align:left">Chatrate [Number]</td>
      <td style="text-align:left">Assigns a minimum time between chat messages to prevent spamming.</td>
    </tr>
    <tr>
      <td style="text-align:left">Cheats</td>
      <td style="text-align:left">Cheats [Enable | Disable]</td>
      <td style="text-align:left">Allows your server to access certain commands, such as Give, and can only
        be used in the server's commands.dat file.</td>
    </tr>
    <tr>
      <td style="text-align:left">Cycle</td>
      <td style="text-align:left">Cycle [Number]</td>
      <td style="text-align:left">Assigns the length of the day/night cycle in seconds.</td>
    </tr>
    <tr>
      <td style="text-align:left">Filter</td>
      <td style="text-align:left">Filter</td>
      <td style="text-align:left">Filters out players with non-English-alphanumeric names.</td>
    </tr>
    <tr>
      <td style="text-align:left">Gold</td>
      <td style="text-align:left">Gold</td>
      <td style="text-align:left">Restricts the server to only allow Gold players.</td>
    </tr>
    <tr>
      <td style="text-align:left">Hide_Admins</td>
      <td style="text-align:left">Hide_Admins</td>
      <td style="text-align:left">
        <p>Admins will appear as if they are normal players.</p>
        <p>Also allows the recording of cinematic footage without the admin labels
          visible to players.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">Loadout</td>
      <td style="text-align:left">Loadout [SkillsetID]/[ItemID]/[ItemID]/...</td>
      <td style="text-align:left">
        <p>Gives players each item when spawning. Using a skillset ID of 255 gives
          the item to everyone.</p>
        <p>Can only be used in a server console or the server's Commands.dat file.
          <a
          href="https://unturned.fandom.com/wiki/Character_Skillsets">SkillsetIDs</a>are from 0-10 in the same order as displayed when editing
            a survivor. 255 = All Skillsets.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">Log</td>
      <td style="text-align:left">Log [Chat]/[Join/Leave]/[Death]/[Anticheat]</td>
      <td style="text-align:left">Enables logging Chat/Join/Leave/Death messages. Each parameter can only
        be Y or N. (eg. log y/y/y will log all chat, connections and death messages.)</td>
    </tr>
    <tr>
      <td style="text-align:left">Map</td>
      <td style="text-align:left">Map [Level]</td>
      <td style="text-align:left">Sets the map that the server loads on startup.</td>
    </tr>
    <tr>
      <td style="text-align:left">MaxPlayers</td>
      <td style="text-align:left">MaxPlayers [Number]</td>
      <td style="text-align:left">Sets the maximum number of connections the server is willing to accept.</td>
    </tr>
    <tr>
      <td style="text-align:left">Mode</td>
      <td style="text-align:left">Mode [Easy | Normal | Hard]</td>
      <td style="text-align:left"><b>easy</b> / Such as but not limited to: Bullet Drop, Bleeding are disabled.
        <br
        /><b>normal</b> / Such as but not limited to: Bullet Drop, Bleeding are enabled.
        <br
        /><b>hard</b> / Such as but not limited to: Zombies are much harder.</td>
    </tr>
    <tr>
      <td style="text-align:left">Name [Text]</td>
      <td style="text-align:left">Assigns the name of the server on the server list.</td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">Owner</td>
      <td style="text-align:left">Owner [SteamID]</td>
      <td style="text-align:left">Gives admin rights to the steamid. Must be placed in the server's Commands.dat</td>
    </tr>
    <tr>
      <td style="text-align:left">Password</td>
      <td style="text-align:left">Password [Text]</td>
      <td style="text-align:left">Assigns the codeword required for entry to the server.</td>
    </tr>
    <tr>
      <td style="text-align:left">Perspective</td>
      <td style="text-align:left">Perspective [First | Third | Both | Vehicle]</td>
      <td style="text-align:left">Assigns the perspective of the server.</td>
    </tr>
    <tr>
      <td style="text-align:left">PvE</td>
      <td style="text-align:left">PvE</td>
      <td style="text-align:left">Disables player versus player combat in favor of player versus environment.</td>
    </tr>
    <tr>
      <td style="text-align:left">Queue_Size</td>
      <td style="text-align:left">Queue_Size [Number]</td>
      <td style="text-align:left">Sets the maximum number of queued connections the server is willing to
        hold on to.</td>
    </tr>
    <tr>
      <td style="text-align:left">Time</td>
      <td style="text-align:left">Time [Number]</td>
      <td style="text-align:left">Assigns the current time in seconds of the day/night cycle.</td>
    </tr>
    <tr>
      <td style="text-align:left">Timeout</td>
      <td style="text-align:left">Timeout [Number]</td>
      <td style="text-align:left">Assigns a maximum ping threshold to the server before a client is kicked.</td>
    </tr>
    <tr>
      <td style="text-align:left">Votify</td>
      <td style="text-align:left">Votify [Vote Allowed Y|N]/[Pass Cooldown]/[Fail Cooldown]/[Vote Duration]/[Vote
        Percentage]/[Required Players]</td>
      <td style="text-align:left">Sets up voting. Pass/fail cooldown specifies the amount of time that players
        must wait after a successful/failed vote before initiating another vote.
        Vote duration specifies the amount of time for each vote to remain active.
        Vote percentage indicates the percentage of "yes" votes required for a
        successful vote and must be expressed in decimals (e.g., 0.6 for 60%).
        Required players specifies the minimum number of connected players in order
        to initiate a vote.</td>
    </tr>
    <tr>
      <td style="text-align:left">Welcome</td>
      <td style="text-align:left">Welcome [Text]/[R]/[G]/[B]</td>
      <td style="text-align:left">Sets a chat box welcome message shown to clients when connected to the
        server.
        <br />
      </td>
    </tr>
  </tbody>
</table>> The commands list credit to [http://unturned.wikia.com/wiki/Server\_Commands](http://unturned.wikia.com/wiki/Server_Commands)  
> Modified/Edited/Added by Uncle LYHME, Not all commands are present.  
> If you would like additional commands please go to the link above.

