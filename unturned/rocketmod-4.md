# RocketMod 4

So, You would like to make your server more unique to have such as plugins, user permissions, auto-saving rocket mod allows you to do just that!

{% hint style="info" %}
Each time you make a change or changes to any of the files you can either reboot your server or do `/rocket reload` in-game or do it in the console without the `/`
{% endhint %}

### How do install this? <a id="how-do-install-this"></a>

To do this you will want to login to [lyhmepanel.com](https://lyhmepanel.com)

1. Click on [Game Services](http://lyhmepanel.com/Interface/GameHosting/GameServers.aspx) under Game & Voice Management then if you have more then one server select the one you want to change
2. Save and then stop your service then click on `Mod Manager` then click on `[ Install ]` to the right of Rocketmod at the top.

Now you have rocketmod installed good work!

```markup
<?xml version="1.0" encoding="utf-8"?>
<RocketPermissions xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:xsd="http://www.w3.org/2001/XMLSchema">
  <DefaultGroup>default</DefaultGroup>
  <Groups>
    <Group>
      <Id>default</Id>
      <DisplayName>Guest</DisplayName>
      <Prefix />
      <Suffix />
      <Color>white</Color>
      <Members />
      <Priority>100</Priority>
      <Permissions>
        <Permission Cooldown="0">p</Permission>
        <Permission Cooldown="0">compass</Permission>
        <Permission Cooldown="0">rocket</Permission>
      </Permissions>
    </Group>
    <Group>
      <Id>vip</Id>
      <DisplayName>VIP</DisplayName>
      <Prefix />
      <Suffix />
      <Color>FF9900</Color>
      <Members>
        <Member>76561198016438091</Member>
      </Members>
      <ParentGroup>default</ParentGroup>
      <Priority>100</Priority>
      <Permissions>
        <Permission Cooldown="0">effect</Permission>
        <Permission Cooldown="120">heal</Permission>
        <Permission Cooldown="30">v</Permission>
      </Permissions>
    </Group>
  </Groups>
</RocketPermissions>
```

```markup
<?xml version="1.0" encoding="utf-8"?>
<RocketSettings xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:xsd="http://www.w3.org/2001/XMLSchema">
  <RCON Enabled="false" Port="27115" Password="changeme" EnableMaxGlobalConnections="true" MaxGlobalConnections="10" EnableMaxLocalConnections="true" MaxLocalConnections="3" />
  <AutomaticShutdown Enabled="false" Interval="86400" />
  <WebConfigurations Enabled="false" Url="" />
  <WebPermissions Enabled="false" Url="" Interval="180" />
  <LanguageCode>en</LanguageCode>
  <MaxFrames>60</MaxFrames>
</RocketSettings>
```



```markup
<?xml version="1.0" encoding="utf-8"?>
<UnturnedSettings xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:xsd="http://www.w3.org/2001/XMLSchema">
  <RocketModObservatory CommunityBans="true" KickLimitedAccounts="true" KickTooYoungAccounts="true" MinimumAge="604800" />
  <AutomaticSave Enabled="true" Interval="1800" />
  <CharacterNameValidation>true</CharacterNameValidation>
  <CharacterNameValidationRule>([\x00-\xAA]|[\w_\ \.\+\-])+</CharacterNameValidationRule>
  <LogSuspiciousPlayerMovement>true</LogSuspiciousPlayerMovement>
  <EnableItemBlacklist>false</EnableItemBlacklist>
  <EnableItemSpawnLimit>false</EnableItemSpawnLimit>
  <MaxSpawnAmount>10</MaxSpawnAmount>
  <EnableVehicleBlacklist>false</EnableVehicleBlacklist>
</UnturnedSettings>
```

