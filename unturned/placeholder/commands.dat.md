# Commands.dat

 You would like to maybe change your server name, maybe even the map and other things lets do just that!

{% hint style="info" %}
Each time you make a change or changes to this file you have to reboot your server. Along with capitals and lowercases don't matter. 💪🏼
{% endhint %}

### File Location <a id="where-is-it-located"></a>

Great question! To do this you will want to login to [lyhmepanel.com](https://lyhmepanel.com)

1. Click on [Game Services](http://lyhmepanel.com/Interface/GameHosting/GameServers.aspx) under Game & Voice Management then if you have more then one server select the one you want to change
2. Save and then stop your service then click on `Configuration Files` then to the left of `Commands.dat` Click on `[ Text Editor ]`

Now you are there! Nice work.

```text
name Unturned 3 - Server
bind 1.1.1.1
port 27015
maxplayers 24
PvP
map PEI
mode normal
perspective both
owner 
chatrate 0
```

 Here is an example of what yours should look like, please keep in mind that the `bind` will be different along with the `maxplayers` and `port` could be the same or different in this example.

{% hint style="danger" %}
📢 Please do not change or remove the bind or port numbers.
{% endhint %}

### Server Name <a id="change-server-name"></a>

This feature assigns the name of the server on the server list.

```text
name Unturned 3 - Server 
bind 1.1.1.1
port 27015
maxplayers 24
PvP
map PEI
mode normal
perspective both
owner 
chatrate 0
```

What we will be changing is what is highlighted above.

1. You will want to delete the `Unturned 3 - Server` text and replace it with your own.

There is a **50 character** limit including spaces. If you find yourself setting your server name and does not seem to change but it changes to `Unturned` this is the because you are over the 50 character limit.

You can use the following site to count the characters for you, [Lettercount](https://www.lettercount.com/) You do not need to include the `name` and first space of your server name when counting.

Example:

```text
name superCoolServer|PvE|Kits|TPA|Home 
```

 That is a total of 33 characters, you can now save the file and then reboot your server and the name will be changed.

### Set to PvE <a id="change-to-pve"></a>

This feature disables player versus player combat in favor of player versus environment.[3](https://lyhmewiki.com/user-guide/unturned/commandsdat/#fn:3)

```text
name superCoolServer|PvE|Kits|TPA|Home
bind 1.1.1.1
port 27015
maxplayers 24
PvP
map PEI
mode normal
perspective both
owner 
chatrate 0
```

What we will be changing is what is highlighted above.

1. You can delete the last `P` in `PvP` and change it to an `E` making it `PvE` see the example below

Example:

```text
PvE 
```

You can now save the file and then reboot your server and it will be changed to PvE.

### Set to PvP <a id="change-to-pvp"></a>

This feature disables player versus environment in favor of player versus player combat[3](https://lyhmewiki.com/user-guide/unturned/commandsdat/#fn:3)

```text
name superCoolServer|PvE|Kits|TPA|Home
bind 1.1.1.1
port 27015
maxplayers 24
PvE
map PEI
mode normal
perspective both
owner 
chatrate 0
```

What we will be changing is what is highlighted above.

1. You can delete the `E` in `PvE` and change it to an `P` making it `PvP` see the example below

Example:

```text
PvP 
```

You can now save the file and then reboot your server and it will be changed to PvP.

### Change Map <a id="change-the-map"></a>

This feature sets the map that the server loads on startup.[3](https://lyhmewiki.com/user-guide/unturned/commandsdat/#fn:3)

```text
name superCoolServer|PvE|Kits|TPA|Home
bind 1.1.1.1
port 27015
maxplayers 24
PvE
map PEI
mode normal
perspective both
owner 
chatrate 0
```

What we will be changing is what is highlighted above.

1. If you do want your server PEI, You will want to delete the `PEI` text and replace it with one of the following but not limited to

| List of Vanilla Maps |  |  |
| :--- | :--- | :--- |
| **`Alpha Valley`** / Arena Map | **`Cyprus Arena`** / Arena Map | **`Monolith`** / Arena Map |
| **`Paintball_Arena_0`** / Arena Map | **`PEI Arena`** / Arena Map | **`Washington Arena`** / Arena Map |
| **`Cyprus Survival`** / Survival Map | **`Germany`** / Survival Map | **`Greece`** / Survival Map |
| **`Hawaii`** / Survival Map | **`PEI`** / Survival Map | **`Russia`** / Survival Map |
| **`Washington`** / Survival Map | **`Yukon`** / Survival Map |  |
| **`Destruction`** / Other Map | **`Tutorial`** / Other Map |  |

1. Now let's say you want to use `Paintball_Arena_0` see the example below

Example:

```text
map Paintball_Arena_0 
```

You can now save the file and then reboot your server and the map will be changed.

### Change Difficulty <a id="change-the-difficulty"></a>

This feature assigns the difficulty of your server

```text
name superCoolServer|PvE|Kits|TPA|Home
bind 1.1.1.1
port 27015
maxplayers 24
PvE
map Paintball_Arena_0
mode normal
perspective both
owner 
chatrate 0
```

What we will be changing is what is highlighted above.

With the default option being set to `normal` this has but not limited to bullet drop, and bleeding enabled. If you do not want them to have this option and want to change it...

1. You will want to delete `normal` text and replace it with one of the following:

| List of Modes |
| :--- |
| **`easy`** / Such as but not limited to: Bullet Drop, Bleeding are disabled. |
| **`normal`** / Such as but not limited to: Bullet Drop, Bleeding are enabled. |
| **`hard`** / Such as but not limited to: Zombies are harder. |

1. Now let's say you want to use `easy` see the example below

Example:

```text
mode easy
```

You can now save the file and then reboot your server and the mode will be changed.

### Change Perspective <a id="change-the-perspective"></a>

```text
name superCoolServer|PvE|Kits|TPA|Home
bind 1.1.1.1
port 27015
maxplayers 24
PvE
map Paintball_Arena_0
mode easy
perspective both
owner 
chatrate 0
```

What we will be changing is what is highlighted above.

With the default option being set to `Both` this grants all your players access to first, third and third person in the vehicles. If you do not want them to have this option and want to change it...

1. You will want to delete `both` text and replace it with one of the following:

| List of Perspectives |  |
| :--- | :--- |
| **`first`** / First Person Only | **`third`** / Third Person Only |
| **`vehicle`** / Third person available in vehicles | **`both`** / First and Third Person available |

1. Now let's say you want to use `easy` see the example below

Example:

```text
perspective first 
```

You can now save the file and then reboot your server and the perspective will be changed.

### Set myself Owner <a id="set-myself-owner"></a>

This feature gives admin rights to the steamid64

```text
name superCoolServer|PvE|Kits|TPA|Home
bind 1.1.1.1
port 27015
maxplayers 24
PvE
map Paintball_Arena_0
mode easy
perspective first
owner 
chatrate 0
```

What we will be changing is what is highlighted above.

You will want to do the following:

1. You will want to go here: [https://steamid.io/](https://steamid.io/)
2. Once there sign in via Steam
3. Once signed in click on your username to the left of `privacy`
4. Click on `profile`
5. Next, you will want to copy the number that starts with... `76561198`

Now that you have your steamID64 copied add a space after the word owner and paste it.

Example:

```text
owner 76561198267201306 
```

 You can now save the file and then reboot your server and you will be admin.

_It should be similar to the example but the number above will not the exact one as each profile has a unique one. Unless you are the owner of the account above, which is Nelsons._

### Change Chat Rate <a id="change-the-chat-rate"></a>

This feature assigns a minimum time between chat messages to prevent spamming.[3](https://lyhmewiki.com/user-guide/unturned/commandsdat/#fn:3)

```text
name superCoolServer|PvE|Kits|TPA|Home
bind 1.1.1.1
port 27015
maxplayers 24
PvE
map Paintball_Arena_0
mode easy
perspective first
owner 76561198267201306 
chatrate 0
```

What we will be changing is what is highlighted above.

1. You will want to delete the `0` number and replace it a number you desire.

Example:

```text
chatrate 3 
```

 You can now save the file and then reboot your server and the chat rate will be different.

### Enable or Disable Cheats <a id="enable-or-disable-cheats"></a>

This feature allows your server to access certain commands such as Give.[3](https://lyhmewiki.com/user-guide/unturned/commandsdat/#fn:3)

```text
name superCoolServer|PvE|Kits|TPA|Home
bind 1.1.1.1
port 27015
maxplayers 24
PvE
map Paintball_Arena_0
mode easy
perspective first
owner 76561198267201306 
chatrate 3
cheats
```

What we will be changing is what is highlighted above.

{% hint style="danger" %}
Not Done!
{% endhint %}

### Enable Gold Only <a id="enable-gold-only"></a>

This feature restricts the server to only allow Gold players.[3](https://lyhmewiki.com/user-guide/unturned/commandsdat/#fn:3)

{% hint style="danger" %}
Not Done!
{% endhint %}

### Hide Admins <a id="hide-admins"></a>

This feature allows admins to appear as if they are normal players. Also allows the recording of cinematic footage without the admin labels visible to players.[3](https://lyhmewiki.com/user-guide/unturned/commandsdat/#fn:3)

{% hint style="danger" %}
Not Done!
{% endhint %}

### Enable a Loadout <a id="enable-a-loadout"></a>

This feature gives players each item when spawning.[3](https://lyhmewiki.com/user-guide/unturned/commandsdat/#fn:3)

{% hint style="danger" %}
Not Done!
{% endhint %}

### Enable a Password <a id="enable-a-password"></a>

This feature assigns the codeword required for entry to the server

{% hint style="danger" %}
Not Done!
{% endhint %}

For any other changes, you would like done you can check out this site [here!](http://unturned.wikia.com/wiki/Server_Commands)

