# JsMacros Ruby

> [!WARNING]  
> **This is an unofficial patch/fork to get the Ruby extension working with current JSMacros versions.**
> 
> - **Original Repository**: https://github.com/wagyourtail/JsMacros-Ruby
> - **JSMacros Core JAR**: Taken from [therealevvv/jsmacrostorage releases](https://github.com/therealevvv/jsmacrostorage/releases/tag/1.21.8) to provide necessary build dependencies
> - **Status**: This is a temporary fix while we wait for the original maintainer to return and provide proper updates
> - **Hope**: We hope [@wagyourtail](https://github.com/wagyourtail) will come back and fix this extension properly in the official repository

This extension adds `ruby 2.5.x` support to JsMacros `1.2.9+` and Minecraft `1.21.8`

## Installation

1. Download `jsmacros-ruby-1.0.9.jar` from the releases
2. Place it in your `~/.minecraft/config/jsMacros/Extensions/` directory
3. Restart Minecraft
4. Create `.rb` files in your JSMacros scripts folder

# Issues/Notes

##
for wrapping methods and stuff use `consumer.autoWrap(method(:methodName))` or whatever to pass the method to autoWrap, you probably know more about ruby than me.
