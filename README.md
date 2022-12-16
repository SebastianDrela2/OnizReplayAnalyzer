![Opennotes](https://user-images.githubusercontent.com/107455395/194939909-deac73ea-d073-4cce-9549-723683c8d962.JPG)
![Graphs](https://user-images.githubusercontent.com/107455395/195956076-38aa0485-3732-4650-a803-814a73274090.png)
![Average data](https://user-images.githubusercontent.com/107455395/197844374-05e11e27-0194-4e16-bafe-d0a1c25e2175.JPG)

# SC2_ONIZ_ANALYZER
//Usage//

Select replay from the listbox dropdown and click Analyze button
Wait for Result

# Ver 1. 0
- Program now lists all users as well as all their purchases of given replay.
- Program seperates Z player with M players.

# Ver 1.1
- Program now calculates all kills for given strains and the general warpig unit.
- Program is now able to calculate killed alphas as well as queens per each player.
- Added a function to take in calculation init units too.
- Fixed crash 237 and 240.
- Output of dragged replay is now saved in .../Replays/(replayname).txt

# Ver 1.2
- Added chat messages

# Ver 1.3
- Added a born init unit events.
- Spaced out an output in order to help readability.

# Ver 1.4
- Changed project integrity from console to inteligent WPF window

# Ver 1.5
- Added a moderate ammount of styling to textbox and listbox control as well as added a background image

# Ver 1.6
- Added curently only one working menuitem that styles results textbox

# Ver 1.7
- Fixed start up crash error initiated by invalid image path.

# Ver 1.8
- Added Notes section.
- Allowed user to change their primal directory path

# Ver 1.9
- Added Filter button and a filter menu for specified filtering player names

# Ver 2.0
- Extended length of listbox.
- User is now notified with what directory they are selecting.
- Made Listbox font bigger.
- User now can push any replay they want manually by using Analyze in file menu

# Ver 2.1
- Fixed LongRangeScope and SpecOpsAssauslt rifle atributes.
- Followed up a data progression (oniz discord)

# Ver 2.2
- Added asynchronous analyzing of all replays in given listbox providing diffrentiated data.
- Completely rework entire framework.

# Ver 2.3
- Increased speed of analysing given replays (by 10x even)
- Memory leak problems with IronPython have been worked around program now launches multiple threads instead of working on one async method.
- Added a bias window at the end of mass replay analyse to prevent bias on player purchases.

# Ver 2.4
- Added a LiveGraphs nuget responsible for drawing graphs
- Added a new tool segment for drawing graphs  (each of 8 types)
- Seperated classes into folders


# Ver 2.5
- Added ability for users to use color picker to change results font in styling section

# Ver 2.6
- Allowed user to change font dynamically presets saving will come in future update.

# Ver 2.7
- Saving font settings is now avaliable.

# Ver 2.8
- settings of Font are  now auto loaded whenever new styling window opens

# Ver 2.9
- Notes now have their own font and font size settings too

# Ver 3.0
- Added an instance of exception notes showing the problem instead of crashing a program.

# Ver 3.1
- User can now set his own background image.

# Ver 3.2
- Added a comparison tool avaliable in "Tools"
- User can compare two totals of player purchases must analyze them first and possibly restart application if needed then use "Compare tool"

# Ver 3.3
- After doing mass analyze user can now see averaged out values per player if value is over 1 then you can expect certain value to appear multiple times on average in a certain match.
- User will be prompted with a message if he did not did mass analyze.

# Ver 3.4
- Added a bank comparison mode in form of button swtic as well as some custom values.
- Replay now auto pushes out players banks to the text file.

# Ver 3.5
- By using Replay Analyze All user will also get all the Banks from all the replays -
- Fixed 7th bank of the replay not showing up.

# Ver 3.6
- Added Handles indicator to banks as well as date indicator.
- Fixed 6th bank not having bonus stats.

# Ver 3.7
- Directories are now listed by the date in the listbox for both Selectdirectory and original load

# Ver 3.8
- Fixed region and realm listing.
- Fixed graphs displaying invalid values.

# Ver 3.9
- Added Banks tool which displays Top 500 results of given bank key.
- Results are saved in the TopResults folder.
- 0 selection is HumansWinsNormal.

# Ver 4.0
- Added K/D ratio and AVG deaths per game bank keys.
- Banks folder now auto deletes it self after every mass analaze.


# Ver 4.1
- Fixed Handles issues with replays consisting of less than 7 players.
- Handles checking is now dynamic and function related.


# Ver 4.2
- Added message box to features that users cant use due to their state of application folder.

# Ver 4.3
- Optimized handles calculation code.
- Handles no longer repeats nor starts belonging to another player.
- Values no longer are distinct from each other or zeroed out.

# Ver 4.4
- Removed banks that have handles which  only cosists of zeroed id's (broken replay)
- Compare window now works with double values
- Optimized mass replay analyze
- Added player names to new average values.
- Added new "Captures per game" value to bank key selection window.
- Added new "Fuel Diverts per game" value to bank key selection window.
- Added new "Vespene Harvested per game" value to bank key selection window.
- Fixed naming of menu tab (Top 50 => Top 500).

# Ver 4.5
- Added anti bank hack measures , hacked banks will be deleted and wont show up in leaderboards. 

# Ver 4.6
- Added new keys related to win condition, program will now calculate and show the win% of a given first alpha after succesfull finish of mass analyze.
- Win condition and Lose condition is now handled by dropship leaving event.

# Ver 4.7
- Fixed t2 strains not appearing in all_data.txt , fixed it with Regex.

# Ver 4.8
- Win% related keys now are graph supported.

# Ver 4.9
- Fixed security showing up on general analyse.
- Replay analyzer now counts total greaters.
- Backend code for counting average greater per player in (analyze all) backend code for Greaters class.

# Ver 5.0
- Added new tab responsible for showing globlal analyze data (currently only Greaters).
- Mass analyze will now print total greaters placed in all_data.txt

# Ver 5.1
- Added a search box that will initiate replays search after users stops typing for one second.
- Made analyze all asynchronous.

# Ver 5.2
- Added a new tab in Tools responsible for filtering replays with certain openings.
- Added a indicator of how many openings of certain chosen list box were used.

# Ver 5.3
- Added categories section in filter values menu. (Currently only GM sort).
- Process should no longer run after application is closed.

# Ver 5.4
- Added two more sub-filters.
- categories can be reopened.
- Replay files now track game length.

# Ver 5.5
- Added a save feature for filtered replays. Select folder alike.
- Added more filter options and more default info on analyzed replays.


# Ver 5.6
- Fixed issue  with names within filtering.
- Fixed issue with average gm filter showing 0 during mass analysement.

# Ver 5.7
- Added a Save replays feature which will sort all your replays depending on their result.
- Save replays feature now renames copied files according to the sorter.

# Ver 5.8
- Fixed directory listing within user selected replay directories
- Added Career calculation graph , after mass analysement is done

# Ver 5.9
- Fixed all UI interupts coming from all sources (mass analyze , single analyze).
- Fixed One key bank selection value.
- Made screen dependant on user end resolution rather than on developer premade settings.
- gave single analysis a progress bar.
- Analyzer now has ONIZ Icon.
- Completely refactored most interuption causing functions.
- Bankkey selection will now not show 500 results if for given reason there is less.
- Single analyze now also provides a date.
- Removed Full replay name from people's iterals.
- Added Date visual to category results.
- Main textbox is now uneditable to prevent data corruption.
- Now it doesnt matter if you use coma or dot in your country for decimal numbers, regex covers it.

# Ver 6.0
- Screen now is also auto adjusted on comparison mode.
- Fixed issue with global comas or dots in floating point values.
- NaN% value inside bank was replaced with 0.
- Buttons have little tool tips explaining what they do.

# Ver 6.1
- Fixed issue with dates.
- Mass analyze all does not now crash at the end of mass analyze.

# Ver 6.2
- Added feature to view banks.
- Added Name of player at the top of the bank.
- Added an exception IF program wont find desired bank.

# Ver 6.3
- Fixed zombie setting function (now works even if original zombie leaves the game.)

# Ver 6.4
- Added a progress bar to single analyze.
- Added the GM counter for mass analyze (alldata.txt) / as well as for One player.
- And advocated a Dispatcher for progress bar.

# Ver 6.5
- Added Gm counter as well as ZM and WM counter
- Added a Text for a total of analyzed replays.
- Added a Games displayer for total of each Gm rank.
- Added a developer tool option for analyzing already analyzed replays.

# Ver 6.6
- Replays will be now skipped in mass analysis if they are gonna get tagged as duplicates.
- Added a Duplicate counter in mass analyze to prevent confusion.

# Ver 6.7
- Removed dupliate counter and duplicate function , paremeters are now eliminated after analysis (hashmap).

# Ver 6.8
- Applied fix to duplicate issue.

# Ver 6.9
- Added a live estimated time counter at mass analyze.
- Reworked mass analyze into multi threading from multiple process launches.
- Duplicates no longer share same factor as (null and key value).
- At the end of mass analyze total time will be prompted.
- Analyze efficency has been improved by x ammount (depending on the users end CPU).
- Added a display for current replay that is being analysed

# Ver 7.0
- Optimized tracker events a bit.
- Fixed gameloop. 
- Fixed Win% on alpha (graphs.)

# Ver 7.1
- Fixed dupplicate issues.
- Added a table as a values indicator.
- Used bindings on table.
- Allowed Subterrenean games.
- Unfortunately subterrenean games only count games no win/loss.


# Ver 7.2
- Added a seperate private games analysis.

# Ver 7.3
- Allowed select dir check for multiple sub directories.
- Allowed subterrenean replays in the thing.
- Added a insurance policy for the mass analyze.

# Ver 7.4
- Added Grid for banks.
- Used different method for sorting and opening banks.


# Ver 7.5
- Added UI Grid for global alpha kills, includes average with and without underseer.
- Fixed inproportional marine kill scaling.
- Speeded up process of analysing greaters.
- Used new techniqe for faster grid analysement
