# GSV Changelog
### A list of all changes made to GSV over time.

## v3 {id=changelog-v3}
- Entirely rewrote the code of Global Stats Viewer
- Homepage background displays the current daily level
- Added featured achievements to the homepage, highlighting recent community accomplishments
- Added changelog to the main website on the homepage
- Added search filters by username, GSV ID, Discord ID, GD Account ID, AREDL, Pointercrate, and Pemonlist account
- Added ability to search for any registered or unregistered user on the GSV database
- Added statistic related filters for only searching users that exceed or fail to exceed a set GSV or GD stat
- You can filter users by levels they have beat as well, with the option to require all stated levels or just one
- You may now search multiple location related filters at once such as leaderboards from two countries at once
- The Classic and Platformer GSV point formulas have been redone
- Added overall leaderboards that combine stats from both Classic and Platformer
- Level difficulties can be combined in leaderboards, allowing you to create for example a harder and insanes leaderbaord
- Added true stars and true demons leaderboard, allowing players to see how many of each stat they would have if dailies, weeklies, and gauntlet levels did not count twice over
- Added leaderboards for each level rating such as featured, epic, or mythic
- Added most created daily, weekly, and event level leaderboard
- GD icons are now uses in place of profile pictures if there is no associated Discord profile picture
- Added a new dashboard for users to manage their completions
- Added a graph and list in the dashboard to show when completions were recently added to Global Stats Viewer
- Refresh completions has been moved to the dashboard under the gear icon in a menu known as Manage Completions
- Added a difficulty breakdown for completions for both classic and platformer in Manage Completions
- Edit data contains an entire menu for managing completions further
- Added append info, which lets you enter your attempt count, worst fail, and enjoyment rating, along with notes you would like to share about said completion
- Added a custom demonlist, letting users order their completions by how hard they think the levels are
- Added difficulty opinions menu to allow the user to further specify difficulty by NLW/LW and GDDL tier, along with in-between tiers in case a user is unsure of which two tiers a level should belong in
- Created a spreadsheet generator that creates a spreadsheet based on your completions that can be sorted by name, difficulty, attempts, date, position, enjoyment, and rating
- Added the ability to import a save file from Geometry Dash to the website, requires a /profile command on the Updated Leaderboard before you can import
- Created an initial batch of achievements, more to come soon
- Ranks have been created, allowing you to progressively increase your tier by completing demons and extreme demons, along with gaining stars and moons
- There is also an overall rank that can be obtained by have 3 of the 4 stat based ranks fufilled
- A brand new level browser has been added to Global Stats Viewer
- Added search filters by gamemode, rating, difficulty, and collection (daily, weekly, event)
- Additionally, conditional filters have been added based on if a level has greater or less than a desired stat such as downloads or likes
- Level page disaplys downloads, likes, reward value, level ID, object count, song, and coin count
- Difficulty face fire is animated courtesy of the [Animated Fires](https://geode-sdk.org/mods/uproxide.animated_fire) Geode mod, this can be disabled in website personalization settings
- Additionally, there is a leaderboard of who on-site has beaten the level, the order may not be accurate to when it was beaten though
- Added Spanish translations
- Revamped the profile page to allow data to feel a lot less cluttered, adding an overall, classic, platformer, and creator section
- Profile pictures may now use the Discord profile effects if they have one on Discord
- Bios can now be written in markdown
- Each icon in the displayed icon set can be clicked on to send you to the [GDBrowser](https://gdbrowser.com/) icon kit
- The overview tab contains hardest levels, GSV point values, and completion difficulty breakdowns
- The completion tab shows a summary of all rated levels completed, providing you with a percentage of all rated levels in the game complete as well
- Clicking on a difficulty will show which levels the user has completed in the difficulty along with completion stats from completion manager, given the user has done a save file import
- Added an opinions viewer for each profile page, allowing the viewing of the player's difficulty opinions for both Classic and Platformer levels
- Added a created levels tab, showing what rated levels an account has, by rating and difficulty, along with a search field
- Created a comparison page on the profile page, allowing one account to be compared to another with stats, hardest completions, completions per difficulty, and GSV points for both Classic and Platformer
- Added option to display playing device as PC or Mobile
- Added the ability to unlink an account if needed
- Added new website themes, currently hosting classic, slate, fire, emerald, gold, and dark
## v2.3 {id=changelog-v2-3}
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
## v2.2.2 {id=changelog-v2-2-2}
- Show "Levels" instead of "Points" for level count leaderboards
- Fixed rankings sometimes appearing as `null`
- Fixed syncing completions not working
## v2.2.1 {id=changelog-v2-2-1}
- Favorite level selector now lets you choose both classic & platformer levels
- Notifications system
- Auto UL import with notifications when your GD stats got refreshed
- Leaderboards for Dailies, Weeklies and Gauntlets
- Fixed a bug where new users would have their rank set to `-1` for a bit.
## v2.2 {id=changelog-v2-2}
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
## v2.1 {id=changelog-v2-1}
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
## v2 {id=changelog-v2}
- Initial release of new website
- Brand new design
- Over 10 new leaderboard types 
- Country & subdivisions specific leaderboards
- Instant AREDL & GD Link
- 28000+ Fetched users for a more accurate position (~"in community" position instead of gsv-exclusive)
- Possibility to add more detailed info to your completions & export them as a spreadsheet
## v1.1 {id=changelog-v1-1}
- Added Weekly Extremes
- Fixed Players Tab being a copy of leaderboards. It now returns every user on the website.
- Made Infinite Demon face animated
## v1.0.2 {id=changelog-v1-0-2}
- Fixed Deadlocked, Clubstep, Toe II not displaying difficulty faces
- Fixed an exploit where list % and denied records on pointercrate (again) would count as completions in a user's extremes list
- Fixed a bug where difficulty faces wouldn't load in the leaderboard when the url finished with `"/"`
- Fixed broken unavailable pfps by displaying a blank pfp instead
## v1.0.1 {id=changelog-v1-0-1}
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
## v1.0 {id=changelog-v1}
- Initial release
