# Hobo Helper – Script Introduction

## What is Hobo Helper?

**Hobo Helper** is a [Tampermonkey](https://www.tampermonkey.net/) userscript designed to enhance your experience playing [HoboWars](https://hobowars.com). It adds quality-of-life improvements directly to the game's pages in your browser — no additional software required beyond the Tampermonkey browser extension.

## Features

Hobo Helper breaks its functionality into individual modules to enhance the game. Notable features include:

- **Bank Helper:** Manage bank savings and custom financial goals.
- **Drinks & Mixing System:** Tools for drinking, stat enhancement, and Mixer recipes.
- **Stat & Training Helpers:** Quality-of-life additions for University training and Tattoo Parlor planning.
- **Location Specific Helpers:** Enhancements for the Northern Fence, Wellness Clinic, Message Board, Kurtz Camp, Bernard's Basement, Can Depo, and Recycling Bin.
- **Settings Dashboard:** Granular toggles to enable or disable features directly from the in-game preferences page.

These modules provide the following general benefits:
- **At-a-glance stats** – key character information surfaced on every page so you never have to navigate away to check your status.
- **Quick-action shortcuts** – convenient buttons and links to frequently visited pages, reducing the number of clicks needed to play.
- **Visual improvements** – cleaner layout tweaks and highlighting to make important information easier to read.
- **Notifications & reminders** – on-page alerts when timers (such as fight cooldowns or daily resets) are about to expire.

> Looking for instructions on how to use specific features? Check out our visual [How-To Guides](guides/index.html).

> For a complete list of all active modules and what they do, please see our [Features Documentation](FEATURES.md).

> To see what's changed recently, check out our [Changelog](CHANGELOG.md).

> More features will be added over time. Suggestions and contributions are welcome!

## Installation

Hobo Helper runs inside your browser via the **Tampermonkey** extension.

1. **Install Tampermonkey:** Ensure the extension is installed for your browser (Chrome, Firefox, Safari, Edge, or Opera).
2. **Install the Script:** Click here to install the latest version: [hobo-helper-latest.user.js](https://gist.github.com/Nath289/5f64aeba6c6bd0664adc651fb1f9cbc2/raw/hobo-helper-latest.user.js).
   *(If you are a Gang Staff member, install the **[Staff Version](https://gist.github.com/Nath289/dd88338eefd7b41a169d8ae13adc7123/raw/hobo-helper-all-latest.user.js)** instead).*
3. Tampermonkey will prompt you to install or update the script. Confirm to finalize installation.

For a more detailed step-by-step guide, please refer to the [Installation Guide](INSTALL.md).

## Supported Layouts

HoboWars can be viewed in various layouts that significantly change how the UI is displayed, including: Simple, Original, Stripped, Darkened, Classic (v2), Modern (v3), Stylish (v4), SFW, and The Future.

**Warning:** So far the tool has only been built for the layout called **"The Future"**. If you use a different layout, expect broken features or unexpected behavior.

## Is Hobo Helper Legal?

Andy has confirmed that the Hobo Helper is Legal to use in its current form and for its current purpose, given that it doesn't breach the Hobowars Game Rules. 

To that end, any feature requests or pull requests that transform the Tool to something outside its agreed purpose and function, will need to be denied.

The [HoboWars Game Rules](https://wiki.hobowars.com/index.php?title=Game_Rules) define and forbid three categories of programs:

> **Macros/Refreshers**
>
> A **macro** is a program that plays part or all of the game for you.  
> A **refresher** is a program (most often an add-in to your web browser) that reloads a web page at set intervals.  
> A **script** is a list of commands that are executed by a certain program or scripting engine **without user interaction**.  
>
> HoboWars rewards players for their time spent on the game. Use of these programs gives players an unfair advantage and is strictly forbidden on all levels.

Hobo Helper is designed so that it does **not** fall into any of these categories:

- It does **not** play the game for you — no actions (attacking, stealing, spending stats, etc.) are ever taken on your behalf.
- It does **not** reload pages at set intervals — it is a purely passive enhancement that runs when *you* navigate.
- It does **not** execute commands without user interaction — every in-game action is still triggered manually by you.

The script's sole purpose is to surface information more conveniently and add visual improvements to pages you are already visiting. This keeps your gameplay fair and within the rules.

> ⚠️ **Important:** Any future feature that automates game actions or reloads pages automatically would violate the rules above and will **not** be added to Hobo Helper. If you spot behaviour that looks like automation, please [open an issue](../../issues) immediately.

If you are ever unsure whether a specific feature is permitted, please review the official rules at:  
<https://wiki.hobowars.com/index.php?title=Game_Rules>

## Contributing

Pull requests and feature suggestions are welcome! Please open an issue to discuss any major changes before submitting a PR.

## Disclaimer

Hobo Helper is an independent, community-made project and is not affiliated with or endorsed by the HoboWars development team.