# mcmod-workflow
This is a (relatively) simple shared GitHub Actions workflow for my mods.

It is used in conjunction with [necauqua-mod](https://github.com/necauqua/necauqua-mod) to automatically
build and publish my mods on CurseForge, GitHub releases, as well as to push the Maven artifacts to
[my repo](https://maven.necauqua.dev) and to the GitHub Packages.

Also, it generates an update.json file for Forge and a human-readable changelog from a basic format I use
in the commit bodies and stores them in the hidden wiki repository of the mod.
