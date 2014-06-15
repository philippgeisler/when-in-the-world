When In The World
=================
[When In The World](https://github.com/philippgeisler/when-in-the-world) is a collection of calendar files for use with the [When](https://github.com/bcrowell/when) calendar program by Benjamin Crowell.

Eventually this collection shall contain holidays for more or less all countries in the world.

Usage
-----
Install When. You can find instructions and info for your operating system at the program’s homepage at http://www.lightandmatter.com/when/when.html. You will also need the m4 macro processor to make use of imports for several calendar files.

Clone this repository in your home directory into the .when directory:

    git clone https://github.com/philippgeisler/when-in-the-world .when

(Should you have already run When at least once, the .when directory will already exist. It will be easiest to (re)move the entire directory before cloning so things stay simple. Also make sure you have a backup of your When settings and calendar files if you already made adjustments.)

Open .when/preferences and adjust it to your needs.

Adjust the m4 include lines to your needs: Chose the holiday file for your country/area from the ones provided in ./holidays. The usual country codes apply. Two includes for a birthdays and a personal calendar file are pointing to non-existent files (they are .gitignore’d to keep things simple on my end); either create these files for your own use or delete the include lines to prevent parsing errors.

Current state / plans for the future
------------------------------------
This repository starts with only the common German holidays. I plan to add calendars for most of the European countries and the United States soon.

A nice addition would be historic calendars, which list dates in the past for one theme e.g. to get “What happened 200 years ago on this date” kind of info. “Themes” could be World War I, Renaissance artists, birthdays of famous persons and some such.

Of course this also depends on what you…

Contribute!
-----------
[Wikipedia](https://en.wikipedia.org/wiki/List_of_sovereign_states) tells me there are 206 individual states give or take a couple disputed ones – and that’s not even counting regional variants. So I guess I could use some help here. Please feel free to send pull requests if you have a calendar file for your country.
