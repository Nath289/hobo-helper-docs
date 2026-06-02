# Hobo Helper - User Changelog
All notable functional changes that impact the user experience will be documented in this file in simple language.

## [10.10] - 2026-06-02
### Fixed
- **Gang Vault:** Fixed an issue where the new searchable select dropdown wouldn't correctly update to match when clicking "Insert" on a saved gang loan or bulk payment.

## [10.09] - 2026-06-02
### Changed
- **Northern Fence:** Fixed the Super-Cart racing sort order so it accurately maintains chronological sign-up order to group you into your correct race batch of 10, while sorting you by skill against your direct opponents. Added clickable table headers to sort by pure sign up order.
- **Explore:** Made the Explore Logs for both the City and Bernard's Basement fully collapsible by clicking their headers to save screen space when you don't need to look at them.

## [10.08] - 2026-06-02
### Changed
- The Trading Post in the Mines has received a compact UI overhaul. The trading tiles are now smaller, and the trades are organized into a neat side-by-side layout (stat ores on the left, non-stat items on the right) to prevent unnecessary scrolling.

## [10.07] - 2026-06-01
### Added
- **Gang Vault:** Overhauled the "Give a Loan" form to include a fully searchable, filtering dropdown box! No more endlessly scrolling through a list of hundreds of members to find the right person.
- **Gang Vault:** Added bidirectional syncing for the Hobo ID box! If you paste or type a Hobo ID manually into the box, the dropdown will instantly jump to select the correct matching member to visually confirm you've got the right person!

## [10.06] - 2026-05-31
### Changed
- **Settings:** The "Check for Updates" button will now instruct you to manually check for updates via the Tampermonkey extension if it fails to connect.

## [10.05] - 2026-05-31
### Changed
- **Northern Fence:** Sorted the Super-Cart Racing sign-up list so that players are automatically ordered from highest to lowest known racing skill.
### Fixed
- **Settings:** Fixed an issue where the "Check for Updates" button was failing due to a cross-origin connection block.

## [10.04] - 2026-05-31
### Changed
- **Mines:** Styled the "Request a rescue tube" link when you're trapped to look like a proper button, and moved it up next to the other actions below your character's picture.

## [10.03] - 2026-05-31
### Fixed
- **Food Bank:** Fixed a bug where the side-by-side Food Bank layout would occasionally fail to construct and display properly on modern browsers.

## [10.02] - 2026-05-31
### Changed
- **Preferences:** Upgraded the "Check for Updates" button to route through the new, faster distribution network!

## [10.01] - 2026-05-31
### Added
- **Living Area:** Added an "Effective Total" calculation beneath your Combat Stats that automatically sums up and adds all of your positive/negative stat boosts into a final, easy-to-read total number!
- **Mines:** Restyled the "Continue Mining" and "Exit the Mines" links when trapped into large, easy-to-click buttons positioned properly underneath the adventure image!
### Improved
- **Mines:** The Mining Log is now wrapped inside a scrolling panel to stop it from making your page extremely long!

## [10.00] - 2026-05-30
### Fixed
- Corrected phrasing in the Recycling Bin Helper guide to accurately reflect the Quick-Add buttons.

## [9.99] - 2026-05-30
### Fixed
- Corrected a typo in the Bank Helper documentation.

## [9.98] - 2026-05-30
### Added
- Added 5 new official How-To Guides covering: Market Helper, Wellness Clinic Helper, Backpack Helper, Active List Helper, and the Drinks & Mixing System! Access them via the Living Area links.

## [9.97] - 2026-05-30
### Fixed
- Fixed an issue where the Mixer's "Possible Drinks" and "Shopping List" were failing to recognize ingredients like "Rev's Rum" due to missing apostrophes in the game's interface.

## [9.96] - 2026-05-30
### Added
- Added an official **How-To Guides** section! You can access it directly from the Living Area beneath the "View Documentation" link. These guides provide visual walkthroughs for configuring and using the script's features.
### Improved
- Cleaned up the buttons at the Tattoo Parlor to look more seamless with the game's UI.
- Improved the visuals of the "+ Bank" buttons across the entire script.

## [9.95] - 2026-05-30
### Added
- **City Statistics**: A new collapsible graph section has been added to the top of the City Statistics page! It automatically records your city stats every time you visit the page, building a historical line graph of all 18 tracked values (such as Cash in bank, Government Income, Demographics, etc.). This history also securely backs up via Cloud Sync.

## [9.94] - 2026-05-30
- 🏢 **Gangs:** The Gang Member Summary table now also calculates the **Minimum** and **Maximum** values for every stat!
- 🏢 **Gangs:** Added a brand new **Stat Ratio** calculated column to the gang member list! It automatically reveals the exact percentage makeup between Speed, Power, and Strength for any given member. 
- 🏢 **Gangs:** The Gang Member List now features an incredibly handy "Freeze Panes" function! When scrolling down through hundreds of members, the table header now firmly locks to the top of your screen so you'll never lose track of what column is what.

## [9.93] - 2026-05-30
- 🏢 **Gangs:** Added an expandable Gang Member Summary table at the top of the gang member list! It dynamically totals and averages every stat currently visible on your screen (Level, Cash, Tokens, etc) giving you a neat breakdown of your gang's strength at a glance.

## [9.92] - 2026-05-30
- 🛒 **Market:** Added an expandable Market Summary table to SGHM that aggregates total listings, lowest prices, and average prices for the item type you are currently viewing!

## [9.91] - 2026-05-30
- 🏁 **Explore:** Added flag tracking to your Explore Log! It will securely log the coordinates when you find a flag, and the exact moment you pick it up, without spamming your log with movement text while holding it.

## [9.90] - 2026-05-30
- 🍬 **Candy Store Helper:** Added new quick-buy buttons next to candy items allowing you to quickly purchase multiple items at once. You can configure your own preset amounts by clicking the gear icon!

## [9.89] - 2026-05-30
- **Cloud Sync:** Completely modernized the background data sync engine. Your devices will automatically and safely migrate your existing data to the new database structures!

## [9.88] - 2026-05-30
- **Northern Fence:** Moved the global "Cancel Bank Goal" button for Pikies NPC races to cleanly sit below the racing table.

## [9.87] - 2026-05-29
- **Added:** Added a "View Documentation" link under the changelog on the living area page to easily access the new script documentation.

## [9.86] - 2026-05-27
- **Mines:** Widened the Mining Stats sidebox to cleanly display large Ore values without the text awkwardly wrapping across multiple lines.

## [9.85] - 2026-05-27
- **Bug Fix:** Fixed an aggressive caching bug in the Cloud Sync engine that could occasionally overwrite the database with stale data when syncing across devices.

## [9.84] - 2026-05-26
- **Added:** Added Up and Down arrow buttons to the Skill Repository page! You can now easily reorder your equipped skills on mobile devices without needing to drag and drop.

## [9.83] - 2026-05-26
- **Added:** Added a new custom player title for HoboID 2924238.

## [9.82] - 2026-05-25
- **Bug Fix:** Fixed an issue where the Mining Stats display in the Living Area would fail to sync across your devices.
- **Bug Fix:** Improved the Mining Log timezone accuracy to ensure logging perfectly matches HoboWars server time even across midnight thresholds.

## [9.81] - 2026-05-25
- **Performance:** Improved overall script performance and loading times reducing layout stuttering.

## [9.80] - 2026-05-24
- **Performance:** Optimized the trolley page DOM observer to prevent lag.

## [9.79] - 2026-05-24
- **Performance:** Completely rewrote the behind-the-scenes storage engine wrappers to eliminate game lag and browser stuttering when saving settings or tracking features.

## [9.78] - 2026-05-24
- **Preferences:** Added a new "Prevent Layout Flash" toggle in the main Hobo Helper preferences. You can disable this if you prefer a brief unstyled page load over a brief blank page load.
- **Global:** Softened the brief transition screen between page loads to allow native themes to shine through naturally without flashing a dark grey background.

## [9.77] - 2026-05-24
- **Northern Fence:** Fixed a syncing bug where Super-Cart tracking data could be unexpectedly lost if the Hall of Fame page was loaded before the background sync finished updating.

## [9.76] - 2026-05-24
- **Preferences:** Added a handy eye icon next to the Sync Password field to easily toggle password visibility.

## [9.75] - 2026-05-21
- **Northern Fence:** Added a handy "Refresh List" button to the internal Super-Cart signup page so you can watch other racers pile in without risking your place in line!

## [9.74] - 2026-05-20
- **Northern Fence:** Updated the Super-Cart Racing Skill Tracker so the "Active" racers count in the Racers Summary is now based on weekly gains instead of total gains.
- **Northern Fence:** Added a new configuration setting in your Preferences to customize the minimum weekly skill gain required for a racer to be considered "Active".

## [9.73] - 2026-05-19
- **Bank Goals:** Separated temporary bank goals from the Pikies (Permanent) bank goals to resolve an issue where session-specific goals were constantly overwriting and wiping cloud-synced device instances.
- **Message Board:** Fixed a bug in the new Signature Character Tracker where backslashes (`\`) and quotation marks (`'` or `"`) were under-calculated against the strict 1,500 limit.

## [9.72] - 2026-05-19
- **Added:** Added a real-time character counter to the Message Board Signature editor! Easily see exactly how many characters you have left, including accurate predictions of how special characters and formatting symbols eat into your cap limit.
- **Message Board:** Added a real-time character limit tracker underneath the Message Board Signature editor that perfectly mimics the game's exact underlying character restrictions, including emojis and line-break encoding bloat.

## [9.71] - 2026-05-19
- **Removed:** Removed the "max payout per hobo" feature from the GangStaff helper for the Sunday Funday tier settings.

## [9.70] - 2026-05-19
- Removed the custom title configuration for SeventhHeaven.

## [9.69] - 2026-05-19
- **Fixed:** Resolved display issues in "The Future" layout on mobile devices where the "Tokens" and "Cans" would indefinitely stretch off the screen instead of wrapping.
- **Fixed:** Fixed a bug on the Rats page where certain items (like the Pack of Candy Cigarettes) would break the consolidated visual feeding interface.

## [9.67] - 2026-05-18
- The internal 'Trade Stat Gain' metric provided at the Trading Post is now recorded directly into the Mining Log JSON structure and correctly overlays onto the daily visual log layout alignment.

## [9.66] - 2026-05-18
- Fixed an issue where the mining log would unnecessarily auto-clear/create entries for today before any stats were earned.
- Added a much easier tracking setup for saving up to race specific Pikies at the Northern Fence! Just click "Set Bank Goal" next to a Pikie.

## [9.65] - 2026-05-17
- Minor bug fix preventing unnecessary syncing and data thrashing for Rat's status graphs.

## [9.64] - 2026-05-17
- Fixed an issue where the Mines daily log was intermittently clearing its captured stats across page navigation.

## [9.63] - 2026-05-16
- Updated Northern Fence Helper to add a side-by-side list format to view signed up racers on the signup page natively by clicking a "Load Registered Racers" button, preventing game rule violation.

## [9.61] - 2026-05-16
- Added settings to the Preferences page allowing you to configure the Assumed EXP and Assumed Life per meal for your Rats. This gives you more accurate life span estimates based on your feeding habits!

## [9.60] - 2026-05-16
- **Fixed:** Resolved a large vertical gap appearing under the Swim Team image on computer screens by properly grouping the meals and refill lists together.

## [9.59] - 2026-05-15
- Fixed a critical layout bug affecting mobile phones where the Living Area layout restructure inadvertently squished your basic profile links (List Hobos Referred, Settings, Purchases Log, Chat) to the point of vanishing completely!

## [9.58] - 2026-05-15
- Added a new option to the preferences page to completely hide the "Invite Friends" text box from your Living Area.
- Fixed a long-standing janky visual bug where your Swim Team image could overlap the News section, and squish your referral links entirely out of existence on mobile devices.

## [9.57] - 2026-05-14
- Internal engine layout updates and AI framework tweaks for consistency.

## [9.56] - 2026-05-14
- Fixed formatting issues where mining multiple ores or hitting ores while at the mining exp cap wouldn't properly update the Mining Log.
- Fixed a bug where purchasing Dynamite Pouches or other equipment at the Mine Store would mistakenly appear in your Mining Log, and automatically cleaned up any incorrectly logged items.

## [9.55] - 2026-05-14
- Under-the-hood engine optimizations and security improvements.

## [9.54] - 2026-05-14
- Fixed an issue where the Rats 'Days to Live' graph would skew vastly out of mathematical proportion because it incorrectly interpreted raw rat life-points instead of 'days to live'. Your graph scale will automatically self-repair upon visiting the page!

## [9.53] - 2026-05-14
- Relocated the injected Hobo Helper version and sync metadata component inside the Living Area UI to properly align beneath tattoos and respect the new layout structure.

## [9.52] - 2026-05-13
- Fixed an issue where today's Mining Log header would temporarily disappear if you had not completed any stat-altering actions yet. It now properly stays visible, and only empty older days are secretly swept away at midnight.

## [9.51] - 2026-05-13
- Simplified the look of the Mining Stats panel inside the Living Area, making it cleaner and more consistent with standard text.

## [9.50] - 2026-05-13
- Added a `[latest]` link directly on the Message Board topic list for multi-page threads, letting you jump straight to the end of massive topics with a single click.

## [9.49] - 2026-05-13
- Fixed a bug where Mining Stats in your Living Area did not correctly respect the "Show More" visibility tracking toggle.

## [9.48] - 2026-05-13
- The extrapolated Rat Life progress bar in your Rats page is now clickable! Clicking it dynamically reveals a beautifully animated drop-down charting your rat's combat stats (`Speed`, `Attack`, `Defense`), `Level`, and complete `Life` decay cleanly tracked over time.

## [9.47] - 2026-05-12
- Expanded the new Mining Stats readout in your Living Area to explicitly show the exact absolute number of ores you have found and total mining experience you have gained today, independent of 'T used'.

## [9.46] - 2026-05-12
- Added a visual Swim Team Image block to the Living Area that floats beside your basic user links, helping keep your active information compact. Includes a fresh user preference toggle for you to enable or disable it freely!

## [9.45] - 2026-05-12
- Expanded the internal system architecture to gather your mining trade data continuously in the background, preserving accurate stat updates natively within your Living Area regardless of any interface format preferences.

## [9.44] - 2026-05-12
- Expanded the 'Mine Stats' readout on your Living Area page to natively pull and display your "Net Stat Gain" and "Stat Trades Today" data natively from caching layers within the Mining Interface. Data will automatically begin tracking once you interact with the Mine Trades window.

## [9.43] - 2026-05-12
- Dynamically rescaled the Living Area left stat column when both "Widen Page" and "Always Show More Info" are active to more evenly distribute white space.

## [9.42] - 2026-05-12
- Reorganized `MinesHelper` trading interface grids. Complementary stat ores are grouped together in a 3-column layout (Green/White/Yellow, Orange/Red/Purple) to reduce vertical space usage.

## [9.41] - 2026-05-12
- **Living Area Helper**: Your active tattoo now displays the number of days left directly below its icon! No more hover required.

## [9.40] - 2026-05-12
- Added a **Fight Display Helper**. Multi-hobo log reading just got way easier; click [highlight] to auto-bold and tab over every row that you hit (or got hit) on!
- **Duplicate Safety Prevention**: The script will now loudly complain natively on the webpage via a blaring red UI banner if you accidentally leave multiple versions enabled at the same time in your extension! Keep your TamperMonkey clean, folks!

## [9.41] - 2026-05-12
- **Living Area Helper**: Your active tattoo now displays the number of days left directly below its icon! No more hover required.

## [9.39] - 2026-05-11
### Fixed
- Fixed an issue in the Mines where the Mining Log would erroneously double-count ores and experience if you navigated using your browser's "Back" or "Forward" buttons.

## [9.41] - 2026-05-12
- **Living Area Helper**: Your active tattoo now displays the number of days left directly below its icon! No more hover required.

## [9.40] - 2026-05-12
- Added a **Fight Display Helper**. Multi-hobo log reading just got way easier; click [highlight] to auto-bold and tab over every row that you hit (or got hit) on!
- **Duplicate Safety Prevention**: The script will now loudly complain natively on the webpage via a blaring red UI banner if you accidentally leave multiple versions enabled at the same time in your extension! Keep your TamperMonkey clean, folks!

## [9.41] - 2026-05-12
- **Living Area Helper**: Your active tattoo now displays the number of days left directly below its icon! No more hover required.

## [9.38] - 2026-05-11
### Added
- Added an Explore Log feature to Bernard's Basement that tracks the valuable rare soups you discover (Garlic Salmon Bisque, Cream of Okra Soup, Texas Fajita Soup, Beef Mushroom Stew) and logs their XY coordinates so you can track findings across sessions!

## [9.41] - 2026-05-12
- **Living Area Helper**: Your active tattoo now displays the number of days left directly below its icon! No more hover required.

## [9.40] - 2026-05-12
- Added a **Fight Display Helper**. Multi-hobo log reading just got way easier; click [highlight] to auto-bold and tab over every row that you hit (or got hit) on!
- **Duplicate Safety Prevention**: The script will now loudly complain natively on the webpage via a blaring red UI banner if you accidentally leave multiple versions enabled at the same time in your extension! Keep your TamperMonkey clean, folks!

## [9.41] - 2026-05-12
- **Living Area Helper**: Your active tattoo now displays the number of days left directly below its icon! No more hover required.

## [9.37] - 2026-05-11
### Added
- Added a Developer Credits link to the Living Area panel above the Changelog.

## [9.41] - 2026-05-12
- **Living Area Helper**: Your active tattoo now displays the number of days left directly below its icon! No more hover required.

## [9.40] - 2026-05-12
- Added a **Fight Display Helper**. Multi-hobo log reading just got way easier; click [highlight] to auto-bold and tab over every row that you hit (or got hit) on!
- **Duplicate Safety Prevention**: The script will now loudly complain natively on the webpage via a blaring red UI banner if you accidentally leave multiple versions enabled at the same time in your extension! Keep your TamperMonkey clean, folks!

## [9.41] - 2026-05-12
- **Living Area Helper**: Your active tattoo now displays the number of days left directly below its icon! No more hover required.

## [9.36] - 2026-05-10
### Changed
- Under-the-hood engine optimizations and security improvements.

## [9.41] - 2026-05-12
- **Living Area Helper**: Your active tattoo now displays the number of days left directly below its icon! No more hover required.

## [9.40] - 2026-05-12
- Added a **Fight Display Helper**. Multi-hobo log reading just got way easier; click [highlight] to auto-bold and tab over every row that you hit (or got hit) on!
- **Duplicate Safety Prevention**: The script will now loudly complain natively on the webpage via a blaring red UI banner if you accidentally leave multiple versions enabled at the same time in your extension! Keep your TamperMonkey clean, folks!

## [9.41] - 2026-05-12
- **Living Area Helper**: Your active tattoo now displays the number of days left directly below its icon! No more hover required.

## [9.35] - 2026-05-10
### Added
- Added a toggle configuration option `NorthernFenceHelper_RestoreBanner` to conditionally restore or disable the classic custom Suicide Hill UI header graphic cleanly based on user preference.
### Fixed
- Fixed an issue causing duplicate page highlighting on specific subpages.

## [9.41] - 2026-05-12
- **Living Area Helper**: Your active tattoo now displays the number of days left directly below its icon! No more hover required.

## [9.40] - 2026-05-12
- Added a **Fight Display Helper**. Multi-hobo log reading just got way easier; click [highlight] to auto-bold and tab over every row that you hit (or got hit) on!
- **Duplicate Safety Prevention**: The script will now loudly complain natively on the webpage via a blaring red UI banner if you accidentally leave multiple versions enabled at the same time in your extension! Keep your TamperMonkey clean, folks!

## [9.41] - 2026-05-12
- **Living Area Helper**: Your active tattoo now displays the number of days left directly below its icon! No more hover required.

## [9.33] - 2026-05-10
### Fixed
- Fixed an issue where the Update Checker inside the Settings page would only point to the standard release script, downgrading installed Staff builds.
- Included explicit Build Type indicators alongside the version string on the settings page for easier debug reference.

## [9.41] - 2026-05-12
- **Living Area Helper**: Your active tattoo now displays the number of days left directly below its icon! No more hover required.

## [9.40] - 2026-05-12
- Added a **Fight Display Helper**. Multi-hobo log reading just got way easier; click [highlight] to auto-bold and tab over every row that you hit (or got hit) on!
- **Duplicate Safety Prevention**: The script will now loudly complain natively on the webpage via a blaring red UI banner if you accidentally leave multiple versions enabled at the same time in your extension! Keep your TamperMonkey clean, folks!

## [9.41] - 2026-05-12
- **Living Area Helper**: Your active tattoo now displays the number of days left directly below its icon! No more hover required.

## [9.32] - 2026-05-10
### Added
- Added an optional link to the Gang Hitlist at the end of the top bar menu (can be toggled in Preferences).

## [9.41] - 2026-05-12
- **Living Area Helper**: Your active tattoo now displays the number of days left directly below its icon! No more hover required.

## [9.40] - 2026-05-12
- Added a **Fight Display Helper**. Multi-hobo log reading just got way easier; click [highlight] to auto-bold and tab over every row that you hit (or got hit) on!
- **Duplicate Safety Prevention**: The script will now loudly complain natively on the webpage via a blaring red UI banner if you accidentally leave multiple versions enabled at the same time in your extension! Keep your TamperMonkey clean, folks!

## [9.41] - 2026-05-12
- **Living Area Helper**: Your active tattoo now displays the number of days left directly below its icon! No more hover required.

## [9.31] - 2026-05-10
### Changed
- Food Bank lists (Frozen and In Trolly) now display side-by-side if the page is widened (over 950px layout).

## [9.41] - 2026-05-12
- **Living Area Helper**: Your active tattoo now displays the number of days left directly below its icon! No more hover required.

## [9.40] - 2026-05-12
- Added a **Fight Display Helper**. Multi-hobo log reading just got way easier; click [highlight] to auto-bold and tab over every row that you hit (or got hit) on!
- **Duplicate Safety Prevention**: The script will now loudly complain natively on the webpage via a blaring red UI banner if you accidentally leave multiple versions enabled at the same time in your extension! Keep your TamperMonkey clean, folks!

## [9.41] - 2026-05-12
- **Living Area Helper**: Your active tattoo now displays the number of days left directly below its icon! No more hover required.

## [9.30] - 2026-05-10
### Added
- Added a "Race Again" button to the results page when racing an NPC Pikie in the Northern Fence.

## [9.41] - 2026-05-12
- **Living Area Helper**: Your active tattoo now displays the number of days left directly below its icon! No more hover required.

## [9.40] - 2026-05-12
- Added a **Fight Display Helper**. Multi-hobo log reading just got way easier; click [highlight] to auto-bold and tab over every row that you hit (or got hit) on!
- **Duplicate Safety Prevention**: The script will now loudly complain natively on the webpage via a blaring red UI banner if you accidentally leave multiple versions enabled at the same time in your extension! Keep your TamperMonkey clean, folks!

## [9.41] - 2026-05-12
- **Living Area Helper**: Your active tattoo now displays the number of days left directly below its icon! No more hover required.

## [9.29] - 2026-05-09
### Fixed
- Fixed an issue where breaking a 'Spelunking Satchel' or other equipment in the mines would mistakenly parse and log it as an acquired ore type.

## [9.41] - 2026-05-12
- **Living Area Helper**: Your active tattoo now displays the number of days left directly below its icon! No more hover required.

## [9.40] - 2026-05-12
- Added a **Fight Display Helper**. Multi-hobo log reading just got way easier; click [highlight] to auto-bold and tab over every row that you hit (or got hit) on!
- **Duplicate Safety Prevention**: The script will now loudly complain natively on the webpage via a blaring red UI banner if you accidentally leave multiple versions enabled at the same time in your extension! Keep your TamperMonkey clean, folks!

## [9.41] - 2026-05-12
- **Living Area Helper**: Your active tattoo now displays the number of days left directly below its icon! No more hover required.

## [9.28] - 2026-05-08
### Changed
- Swapped the Active Miners list map outline animation from a flashing color to a continuous expanding blue pulse overlay for 5 seconds.

## [9.41] - 2026-05-12
- **Living Area Helper**: Your active tattoo now displays the number of days left directly below its icon! No more hover required.

## [9.40] - 2026-05-12
- Added a **Fight Display Helper**. Multi-hobo log reading just got way easier; click [highlight] to auto-bold and tab over every row that you hit (or got hit) on!
- **Duplicate Safety Prevention**: The script will now loudly complain natively on the webpage via a blaring red UI banner if you accidentally leave multiple versions enabled at the same time in your extension! Keep your TamperMonkey clean, folks!

## [9.41] - 2026-05-12
- **Living Area Helper**: Your active tattoo now displays the number of days left directly below its icon! No more hover required.

## [9.27] - 2026-05-08
### Added
- Added an Active Miners list to the left column while exploring the Mines. It lists all players visible on the map and their coordinates. Clicking on a player initiates a 5-second flashing highlight on their map location for easy tracking.

## [9.41] - 2026-05-12
- **Living Area Helper**: Your active tattoo now displays the number of days left directly below its icon! No more hover required.

## [9.40] - 2026-05-12
- Added a **Fight Display Helper**. Multi-hobo log reading just got way easier; click [highlight] to auto-bold and tab over every row that you hit (or got hit) on!
- **Duplicate Safety Prevention**: The script will now loudly complain natively on the webpage via a blaring red UI banner if you accidentally leave multiple versions enabled at the same time in your extension! Keep your TamperMonkey clean, folks!

## [9.41] - 2026-05-12
- **Living Area Helper**: Your active tattoo now displays the number of days left directly below its icon! No more hover required.

## [9.26] - 2026-05-08
### Added
- Added a new setting to the Mines helper to highlight players on the mini-map. Other players are outlined in red, and the player character ("You!") is outlined in green.
