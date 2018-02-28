# Tweaked Version of PhoneGap Push Plugin

This is a private fork of the PhoneGap Push Plugin.   It contains an additional API method that allows us to get the token for the device after the initial registration.

In general it is overkill for our purposes, both on Android and on iOS and it also may contribute to performance issues on iOS especially.

My preference would be to replace it with a smaller, lighter, simpler in-house plugin but currently doing so would probably take up an entire two-week sprint, so there's no point in that when we have at least a functioning system with minimal effort.