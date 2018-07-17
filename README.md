Mystcraft-Issues
================
This repository exists primarily in order to have a GitHub issue tracker for Mystcraft.
It doubles as a location to maintain and improve the lang files for Mystcraft.

Join us on Discord: https://discord.gg/pRGH45W

See https://minecraft.curseforge.com/projects/mystcraft for downloads

Thanks! :)

### Getting the API
#### Maven Repo
```
repositories {
	maven {
		name "xcompwiz"
		url "http://maven.xcompwiz.com"
	}
}
dependencies {
    compile "com.xcompwiz.mystcraft:mystcraft:0.13.5.01:dev"
}
```

#### Manual Download
You can manually obtain an API jar from the Mystcraft CurseForge page: https://minecraft.curseforge.com/projects/mystcraft

Once equipped with your API version of choice (the most recent one, right?), you can put it in the "jars" folder at the same level as your gradle scripts.  You may need to create this folder.
You can then either import the jar manually into your workspace or rerun the gradle command to build your workspace of choice:
ex: gradlew.bat eclipse

### Getting Started
Mystcraft uses a very robust but rather complex method of maintaining its API versions.  This allows it to support older versions of the API alongside new versions, but there is a small cost of complexity.
It is recommended you look at the APIInstanceProvider class.  It should be well documented in its usage. Using the static instance of this class you are ready to get into Mystcraft's API properly.

### Available API Interfaces
>It is also possible to get a list of interfaces and their available versions supported from the APIInstanceprovider

TODO:
