# v2.3
- Added a brand new [support and FAQ page](https://globalstatsviewer.com/support)
- Accounts can now be linked with the Pointercrate Demon List without having to be manually approved by staff, the guide to do so can be found [here](https://globalstatsviewer.com/support/accounts-linking)
  - With this, manual Pointercrate request are no longer a feature
- It is no longer needed to enter account names when attempting to link with lists or Geometry Dash / Updated Leaderboard, just make sure the service you are linking to uses the same Discord account as GSV
- Notifications are no longer sent when your account is part of a UL import, old notifications have been deleted too
- Added new leaderboard backgrounds for Platformer and Creators based on Diamonds for Dashers and RIVERS OF NAZARETH respectively
- Revamped the settings page with a new style and multiple categories
- Added the ability to refresh your site PFP
- New "Notifications" and "Performance" categories added to settings allowing you to disable site notifications and remove level thumbnails and site backgrounds
- Removed "Dashboard" and replaced with "Completions"
- Moved account linking to settings
- Clicking on an profile's AREDL link while on their platformer page leads to their AREDL platformer profile appearing
- Supporter can be added to users by staff without having to update the website
- Refreshing profiles are now done in a more efficient way
- Admins are now credited as such on the website
- Switched to a new SQL database known as Postgres
- Created tons of new staff tools and a staff area to allow GSV to not be reliant on a Discord bot
- The Global Stats Viewer API is now properly documented [here](https://api.globalstatsviewer.com/docs)
# v2.2.2
- Show "Levels" instead of "Points" for level count leaderboards
- Fixed rankings sometimes appearing as `null`
- Fixed syncing completions not working
# v2.2.1
- Favorite level selector now lets you choose both classic & platformer levels
- Notifications system
- Auto UL import with notifications when your GD stats got refreshed
- Leaderboards for Dailies, Weeklies and Gauntlets
- Fixed a bug where new users would have their rank set to `-1` for a bit.
# v2.2
- Platformer leaderboard now selectable without needing to go to a filters menu
- Added leaderboard for in-game stats
  - These include stars, diamonds, secret and user coins, and creator points
- Added creator leaderboard
- Brand new filters menu
  - Leaderboard types are separated into **Points** (GSV score) and **Stats** (stars, moons, coins, etc.)
- Redesigned the page select
- Brand new player cards for leaderboard positions
- Greatly reduced load time for leaderboards
- Added level thumbnails support and the ability to set your favorite level (if completed) as your profile background
  - Level thumbnails appear on profile backgrounds, player cards on the leaderboards, and the account's hardest demons list
- Users can choose an accent color for their profile
- Improved alert system
# v2.1.0
- Added support for platformer levels
   - New "divided" profile with Classic & Platformers
   - All leaderboards now support Platformers
   - New Pemonlist link
- Fixed a bug where the country select would overflow on large screens
- Fixed a bunch of typos
- Made Staff & Supporter profiles in main page clickable.
- Fixed non-points leaderboard decimal inconsistencies (Would show 5.0 demons instead of 5)
- Fixed a bug where a user's bio would overflow on mobile devices
- Fixed a bug where the spreadsheet generator would straight up not work
- Fixed a CSS issue where long demon names would overflow on mobile in the user page, making the info option unclickable.
# v2.0.0
- Initial release of new website
- Brand new design
- Over 10 new leaderboard types 
- Country & subdivisions specific leaderboards
- Instant AREDL & GD Link
- 28000+ Fetched users for a more accurate position (~"in community" position instead of gsv-exclusive)
- Possibility to add more detailed info to your completions & export them as a spreadsheet
# v1.1
- Added Weekly Extremes
- Fixed Players Tab being a copy of leaderboards. It now returns every user on the website.
- Made Infinite Demon face animated
# v1.0.2
- Fixed Deadlocked, Clubstep, Toe II not displaying difficulty faces
- Fixed an exploit where list % and denied records on pointercrate (again) would count as completions in a user's extremes list
- Fixed a bug where difficulty faces wouldn't load in the leaderboard when the url finished with `"/"`
- Fixed broken unavailable pfps by displaying a blank pfp instead
# v1.0.1
- Fixed missing profile pictures on some accounts
- Fixed missing difficulty faces on some profiles
- Fixed GD Stats not updating
- Fixed Demons (non extremes) not fetching
- Fixed an exploit where list % and denied records on pointercrate would count as completions
- Change formula to reduce non-hardest points
- Fixed broken css on mobile for player profiles
- Fixed a bug where extremes composed of only numbers would show up at the top of your demonlist
- Added GD DMs to `Error -1` message
- Added 25 Extremes Badge
# v1.0
- Initial release
