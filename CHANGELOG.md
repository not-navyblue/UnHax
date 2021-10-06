# UnHax Changelog
## v1.9 (October 6, 2021 Update)
*...?*
### Major Changes
- Added 2 new Pantheons (1 with RekMOD enabled), 1 new Founder belief, and 1 new Enhancer belief
- **Religion** now allows 1 extra Pantheon when founding a religion, and 1 extra Follower & Enhancer beliefs when enhancing a religion
- **Better Wayfinding** now allows naval units to move through impassable tiles
- **Improved Radar** now provides +2 Sight to aircraft units
- **Tidal Connection** now provides +50% Strength to units fighting in water tiles
- All buildings now have starred descriptions directly from (README.md)[https://github.com/not-navyblue/UnHax/blob/main/README.md]
### Minor Changes
- **Base**'s empire-wide Gold generation no longer applies to the capital (and is increased from 4200 to 6900)
- Increased the number of **Founder** units **Base** provides from 2 to 3
- Multiplied the Production cost of **Founder** by 10
### Removed Features
- **Settler** is no longer replaced by **Founder** when **Founder's Entrance** is researched

## v1.8 (October 4, 2021 Update)
*...*
**Warning: Incompatible with saves that use UnHax v1.5 and below.**
### Major Changes
- Added the **Founder** unit
- Added 1 new tech: **Founder's Entrance**, and 1 new unit promotion exclusive to **Founder**: **Founder's Frontier**
- Added 1 new Pantheon and 1 new Follower Belief
- **Enhancement** now provides 1 Free Technology
### Minor Changes
- All of **Enhancement**'s empire-wide stat increase percentages are now 100% instead of 90%, 75%, or 50%
- Population increase provided by **Base** is now 4 from 2
### Removed Features
- Deleted **Military+** for good, ending compatibility with versions below v1.5
- All buildings except for **Base** no longer trigger a global alert when completed

## v1.7 (October 1, 2021 Update)
*constant great prophet generation started to annoy me a lot*
### Major Changes
- Added 3 new Religious Beliefs; 2 Follower Beliefs and 1 Enhancer Belief
- **Religion** now causes Great Prophets to stop generating naturally. Talk about irony.
- **Religion** now provides 2 free Great Prophets, for founding and enhancing religions
- Great Prophets can now be bought with Faith at a lower price when **Religion** is built
### Minor Changes
- 'Reduced' cost of purchasing Civilian units with Faith from -69% to -75% (again, this is a buff, trust me)
- Increased empire-wide Faith generation from 325 to 800 (this is doubled in capital city)
### Bugfixes
- Fixed **Base** not giving 2 free Settlers for free
- Updated some uniques (is this even a bugfix???)

## v1.6 (September 28, 2021 Update)
*playing with unit promotions*
### Major Changes
- **Enhanced Vision** now bypasses land units' embarked vision limitation and allows units to ignore terrain cost
- **Better Wayfinding** now allows naval Military units to spot invisible Submarine units
- **Base** now provides **Enhanced Vision** to land-based Civilian units
- **Enhancement** now provides **Quick Study** to all non-Missile Military Units (except Atomic Bomber)
- **Military** now provides **Haka War Dance** to all newly-trained non-air Military units of the city the building is built on
- All Civilian units now gain **Civilian Assistance** (taking account for RekMOD's, and in vanilla in the future, Great Admiral unit)
- **Base** now gives Gold equivalent to 10 times the capital-only Gold production upon completion (not retroactive; works only on newer saves)
- Tile yields from Natural Wonders are now doubled with **Enhancement**
### Re-added Features
- Re-added **Base**'s free **Rejuvenation** promotion for most Military units (**Panacea's Gift** still stays)
- **Enhancement** now reveals the entire map (before it was removed in v1.2, **Base** revealed the whole map)
### Minor Changes
- **Base** now provides **Military** for your first 4 cities for free (from just the capital only)
- Increased **Base**'s capital-only Gold generation from 6969420 to 7769420
- Increased **Base**'s empire-wide Gold generation from 1234 to 4200
- Increased **Military**'s city health increase from 3625 to 3650 and additional Experience increase from 175% to 200%
- Increased **Enhancement**'s empire-wide Faith generation from 60% to 75%
### Removed Features
- Eligible Military units not trained in cities with **Military** no longer gain **Panacea's Gift**

## v1.5.1 (September 24, 2021 Update)
*smallest number of changes ever; a stark contrast to v1.5*
### Minor Changes
- Doubled the specialist slots provided by **Base** (now 8 instead of 4)
### Bugfixes
- Fixed **Base** providing the deprecated **Military+** instead of **Military**. Oops.

## v1.5 (September 19, 2021 Update)
*7 days has passed, but such many changes were done in only 2 days lol*<br>
### Major Changes
- **UnHax Mode - Military+** is now renamed as simply **UnHax Mode - Military**
- **Religion** can no longer be built normally; it must be bought in capital like **Military** and **Enhancement**
- **Mastery of War** promotion now allows non-air units to ignore the Zone of Control
- Added a new promotion, **Panacea's Gift**, which is available only on **Military** (not the deprecated **Military+**)
- **Enhancement** now gives a 60% increase of Faith generation in all cities
- **Base** now adds 4 slots for all Specialists
### Minor Changes
- Healing uniques provided by **Mastery of War** and **Air Superiority** are transferred to **Panacea's Gift**
- Increased city health and city strength with **Military** from 360 & 3600 to 365 & 3625
- Increased capital city Gold generation from 6669420 to 6969420
- Increased empire-wide Gold generation from 777 to 1234
- Increased Culture generation from 420 to 690
- Increased great person points generation from 40 to 45
- Increased Faith generation from 540 & 270 to 650 and 325, respectively
- Increased percentage of additional XP gain from 100% to 150%
- Decreased percentage of reduced Faith cost for civilian units from -50% to -69% (this is a buff, decreasing values is how buffing negatives work)
- Amount of damage healed with **Panacea's Gift** promotion is reduced from 60 to 40 whenever a Military Unit kills an enemy Unit
- The amount of HP healed for any unit when adjacent to a Civilian unit with the **Civilian Assistance** promotion is reduced from 150 to 60
- Reduced the percentage of damage reduction when intercepted with **Air Superiority** promotion from 175% to 100%
- Reduced the percentage of additional Strength when defending with **Mastery of War** promotion from 150% to 130%
- <s>major changes in .md files yet again, i guess it's always gonna happen at this point lol</s>
### Removed Features
- **Base** no longer "provides" the bonus of using 1 movement point to dis/embark (it never worked anyways)
- **Base** no longer provides the **Rejuvenation** promotion for non-Missile Military units (replaced with **Panacea's Gift**)
- Atomic Bombers no longer gain the **Rejuvenation** promotion

## v1.4 (September 12, 2021 Update)
*don't you just hate it when you run out of ideas and leave the mod hanging for some time*
### Major Changes
- New units can now move immediately after getting bought once **Enhancement** has been built
- All enemy Military units can now be captured when killed once **Enhancement** (instead of **Military+**) has been built
### Minor Changes
- Damage taken from interception is now reduced by 90% with **Brilliant Detonation** to accommodate for the Atomic Bombers
- Increased capital-only and universal Faith generation from 360 and 180 to 540 and 270, respectively
- Increased **Enhancement**'s universal percent increase for Food, Gold, Culture, Science, and Production from 75% to 90%
- Increased **Better Wayfinding**'s visibility range bonus from 3 to 4
- Reduced **Improved Radar**'s range bonus from 6 to 4
### Bugfixes
- Fixed naval Military units not gaining the **Better Wayfinding** promotion when **Military+** exists in the city they came from
- Fixed missile units gaining the **Rejuvenation** promotion which is not supposed to happen
### Removed Features
- Atomic Bombers can no longer gain multiple promotions except **Rejuvenation** and **Brilliant Detonation**

## v1.3 (September 10, 2021 Update)
*mod not op enough*, <s>*pls buff*</s> *also how is this the first update with the first bugfix*
### Major Changes
- Added **UnHax Mode - Enhancement**, which provides many assorted bonuses
- Added a civilian-only unit promotion, which can be obtained by new units when **Base** is built
- **Rejuvenation** can now be obtained by Military units that are obtained by any method other than training
- Enemy non-air military units can now be captured when **Military+** is built
- Land units now use up only 1 movement point to dis/embark when **Base** is built
- Melee units no longer use up all movement points for pillaging when at least one **Military+** is built
- Great General combat bonuses are now doubled when at least one **Military+** is built (whether the bonus stacks is uncertain)
- Civilian units that are bought with Faith now cost 50% less to buy when **Religion** is built
### Minor Changes
- Increased **Brilliant Detonation**'s Strength bonus from 350% to 365%
- Great General is now earned 80% faster with **Brilliant Detonation** (from 75%)
- Increased **Improved Radar**'s range bonus from 3 to 6
- Reduced the amount of damage healed provided by **Mastery of War** and **Air Superiority** from 100 to 60
- Reduced the visibility range of **Enhanced Vision** and **Better Wayfinding** from 7 and 8, to 2 and 3, respectively
### Bugfixes
- Fixed bugs regarding **Enhanced Vision** and **Better Wayfinding**'s visibility range bonuses not functioning
### Removed Features
- **Improved Radar** and **Brilliant Detonation** no longer provide visibility range bonuses (it was useless)

## v1.2 (September 9, 2021 Update)
*mod too op,* <s>*pls nerf*</s>
### Major Changes
- Added **UnHax Mode - Military+**, which can be bought in cities connected to the capital
- Added six new unit promotions, all of which can only be obtained with **Military+** in cities
### Minor Changes
- Transferred city health and city strength increase from **Base** to **Military+**
- Transferred free **Morale** and **Great General I** promotions from **Base** to **Military+**
- Increased city strength and city health increases of **Military+** from 290/2900 to 360/3600
- **Religion**'s building cost has been increased to 420 million worth of production (from basically free)
- Reduced great person points generation from 77 to 40
- Reduced Faith generation from 777 to 360, and universal Faith bonus is reduced from 777 to 180
- <s>Getting this changelog a major change and its own file</s>
### Removed Features
- **Base** no longer reveals the whole map
- Missiles no longer gain the **Morale** and **Great Generals I & II** promotions
- **Religion** no longer generates Great Prophet points (it is somehow unnecessary)

## v1.1 (September 6, 2021 Update)
*I might have gone overboard making this update, but it's a cheat mod anyways, so...*<br>
**Warning: Incompatible with games that use UnHax v1.0**
### Major Changes
- Renamed **UnHax Mode** to **UnHax Mode - Base** (referred to as **Base** in this changelog)
- Added **UnHax Mode - Religion** (referred to as **Religion**), which is available only when religion is enabled
- Added free **Great General I** promotion for all new military units on **Base**
- Unit XP and free promotions now apply for new military units *in all cities*, not just the capital city
- Increases in all seven stats now apply *in all cities*, with the capital gaining double the increase (except Gold)
### Minor Changes
- Transferred Faith generation and immediate Pantheon founding from **Base** to **Religion**
- Reduced **Base** maintenance cost from 69420 to 4200 <s>(nice)</s>
- Increased great person points generation from 69 <s>(also nice)</s> to 77 <s>(not nice)</s>
- Increased Production provided by **Base** from 420 to 690 <s>(triply nice)</s>


## v1.0 (September 5, 2021 Update)
*Initial Release*
### Major Changes
- Added **UnHax Mode**
