# Craftify Change Log

## 1.11.0
- Renamed hide hud to reflect the actual purpose
- Made player hide if debug info is opened.
- Added new only show when the player tab is opened.
- Fixed problem with local songs on Spotify

- Updated to 1.20

## 1.10.0
- Fixed Spotify not updating after an ad played.
- Fixed changelog screen not being scrollable.

## 1.9.0
- Fixed issue where if artist had an ampersand in their name and a valid color code following it would color the text.
- Fixed an issue where if an artist put too many artists on their song it would cover the menus in artist text, it is now limited to 3 artists.
- Added support for foobar artwork.
- Added new RenderType, Escape and Inventory menu
- Changed missing and loading icons for images to be blank as the loading would flash and the missing would be obnoxious.
- Fixed issues where YoutubeService would not ping socket that it still exists so it would close the connection.
- Fixed that ADs were not properly categorized when using YoutubeService and therefore would not show an icon or a title.

## 1.8.0
- Updated to 1.19.4
- Added support for Foobar & DeaDBeeF using Beefweb plugin
- Added new local theme option to hide image.

## 1.7.0
- Fixed SSL Issues for 1.12.2 and 1.8.9
- Added warning when in a private session for Spotify.
- Improved service loading and unloading to make sure multiple services arnt connected at once.

## 1.6.0
- Removed Essential Dependency (for 1.18+).
- Fixed a bug where logs would be spammed when the song changed if another thread rendered the contents of the player.
- Added text to the login button instructing that you need to choose a service before being able to login.
- Changed how services start after reload to possibly fix a bug where services wouldn't start off a reload.
- Changed auth services to a custom solution to have better control over the time to login, also is now on a custom website to also have a custom theme sharing service in the future.
- Fixed a bug where Spotify would not send me the track and would break the service.
- Changed YouTube to use a websocket so it should update instantly instead of having to poll for an update.
- Added a message so that if a reauth fails it will let the user know they have to manually log back in

## 1.5.0
- Switched to using a custom library with a proper standard so the different services should work in a more coherent manor. You can find the library here: https://github.com/ThatGravyBoat/Jukebox
- Fixed a lot of bugs including the bug on new game versions where it would open the documents folder instead of the link.
- Added a page for logging into Spotify instead of it just opening it because it just makes the switching alot better.
- Changed how Display Mode works to make it not break as much on Spotify.
- Added support for a new music service, Apple Music through cider.sh
- Fixed a bug where you could have a volume slider bigger than 100%

## 1.4.1
- Fixed issue where config would fail to load because of login button.
- Fixed issue on Fabric where it would break essential installer.

## 1.4.0

- Fixed bug where controls where off by 5 pixels from the center.
- Fixed login button allowing clicks when no mode is selected.
- Fixed typos in config options.
- Fixed ads showing up weirdly, replaced them with a custom ad format. (Won't affect premium of the listening platform used.)
- Added change log screen.
- Added position editor button in controls.
- Added volume control button in controls.
- Note: Themes have been updated so to get the new icons for your theme you will need to reinstall your theme with `/craftify library`
