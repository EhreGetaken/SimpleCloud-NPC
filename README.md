# SimpleCloud-NPC

This is the documentation about SimpleCloud-NPC.

## Getting Started

Download the plugin [HERE](https://imposdev.eu/repo/org/spigotmc/simplecloudnpc/1.0.0/simplecloudnpc-1.0.0.jar) and put it on your server.
Also (if any error shows up in the consol related to simplecloudnpc and protocollib) download ProtocolLib for protocol management.

### Prerequisites

You need SimpleCloud 2.0.0 or above.
Spigot 1.8.x (version support will be done in the next update)

## List of commands

/cloudnpc reload - Reload all npcs.

/cloudnpc create (playernameOfSkinOwner) (displayName) (shouldLookAtYou) (shouldImitateYou) null(currently unavailable) (serverGroup) (useRealUUIDofPlayerSkin)

## Built With

* [PaperSpigot](https://papermc.io/downloads)
* [Maven](https://maven.apache.org/) - Dependency Management
* [NPC-Lib](https://github.com/juliarn/NPC-Lib) - Handle NPC

## Maven repository

```maven
<repository>
    <id>spigotRepo</id>
    <url>https://imposdev.eu/repo</url>
</repository>
```

```maven
<dependency>
    <groupId>org.spigotmc</groupId>
    <artifactId>simplecloudnpc</artifactId>
    <version>1.0.0</version>
</dependency>
```

## Authors

* **Espen** - *SimpleCloud-NPC* - [Espen](https://github.com/EhreGetaken)
* **Juliarn** - *NPC-Lib* - [Juliarn](https://github.com/juliarn)
