# Get More Ram
A simple [StosSign](https://github.com/stossy11/StosSign) wrapper app that allows you to enable "Increased Memory Limit" for your sideloaded apps without using Xcode.

This fork pins a [patched StosSign](https://github.com/m7830380-cyber/StosSign) that fixes Apple sign-in error **-80045** ("This action cannot be completed at this time") by reporting the `akd` daemon instead of the now-blocked Xcode identifier in the client-info and User-Agent sent to Apple's GSA endpoints (Mac device identifiers are unchanged), the same fix shipped in [nab138/iloader v2.3.7](https://github.com/nab138/iloader/releases/tag/v2.3.7).

# How to use
1. Sideload this app
2. Go to settings, sign in your account that you used to sign the app you want to enable "Increased Memory Limit"
3. Go to "App IDs" page
4. Tap Refresh
5. Tap the app you want to enable "Increased Memory Limit"
6. Tap "Add Increased Memory Limit"
7. Reinstall the app from SideStore/AltStore
8. Check if you have "Increased Memory Limit"

# Credits
Stossy11 - For StosSign.
SideStore - Anisette Data fetching codes are stolen from SideStore
