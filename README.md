# THIS MOD HAS BEEN FIXED BY TYPPI

I TRIED TO REACH OUT TO MURGH MULTIPLE TIMES WITH NO LUCK. IF HE WANTS THIS REMOVED, IT WILL BE REMOVED.

**WARNINGS: THIS STILL HAS A LOT OF MOD CONFLICTS AND BUGS. THIS MAY BE FIXED AT A LATER TIME IF I GET FREE TIME**

So you got the riot under control, now what? Clean up the mess afterward in an elegant way! Have a little Cemetery in the forest to bury dead people.

## If this helps you, please support

![Support](https://steamuserimages-a.akamaihd.net/ugc/1826773857050284023/B38E3C7378BC98B0C716BE37AD45EB3BB9ED2A9B/)

Once a person is buried, a photo will appear on the grave to remember him/her. And of course, a relative will come to bring some flowers. The flowers are considered rubbish by the workmen, but if you are quick enough you can sell them with the Sell Object.

## Every now and then a Visitor will come to put some fresh flowers on an occupied Grave, to keep your workmen or prisoners busy. Please make sure the tiles around the Graves are accessible for them, otherwise they will spawn but don't move

When a Grave is occupied it will be cleaned up after 60 days, so it can be used again. Meanwhile, you cannot dismantle it. Have some respect for the dead!

## RESEARCH

- You will need to research Health before you can use the graves.
- Prison Labour research is required to have prisoners produce Coffins in a Coffin Workshop.

## NEW OBJECTS

- Crematorium, in case you rather like to burn the dead.
- Coffin, to store dead people.
- Coffin Table, to produce Coffins in a Coffin Workshop.
- Morgue Table, to store empty coffins.
- Parlour Table, to store loaded coffins at the Funeral Parlour where they are closed before they get buried or cremated.
- Parlour Altar, to store loaded coffins which get a funeral ceremony before they get buried or cremated.
- Parlour Altar (Staff), to store staff coffins which get a funeral ceremony.
- Parlour Chair, where friends of the deceased can take place to join the funeral ceremony.
- Empty Grave (for prisoners only).
- Empty Staff Grave (for all other people).
- GraveStone (eyecandy).
- Urn, the remainders of a cremation which goes to the relatives via Exports.
- Hearse Remover, a little invisible tool to never let a Hearse spawn to pick up the dead. Place it somewhere near the top of the road.

## NEW ROOMS

- Coffin Workshop, where prisoners assemble Coffins from six pieces of Wood.
- Funeral Parlour, where a funeral ceremony can take place.
- Cemetery, where filled Coffins are buried or cremated.

## NEW STAFF

- Gravedigger, will lead the reform programs and do jobs at the Cemetery.

## NEW REFORM

- Grave Digging, teach prisoners how to dig holes.
- Coffin Production, teach prisoners how to make their own Coffins.

## NEW GRANTS

- Offers 6 new grants from building your Morgue to burying a prisoner.

## NEW JOBS

- Close Coffin, Dig Hole, Bury Entity, Place Stone, Tend Grave, Tend GraveStone, Clean Grave: these jobs can be done by prisoners or Gravediggers working at the Cemetery.
- Start funeral ceremony, Give speech, Place funeral wreath: these jobs are handled by a Spiritual Leader when a Parlour Altar is used.
- Visit funeral parlour, Say goodbye, Visit grave: things that friends of the deceased will do.

## BONUS MATERIALS

Since this mod adds Big holes / special Cemetery PavingStone / Stone tiles for the ground and modifies the tileset.png, it would have been a waste if some other mods with floor materials wouldn’t be included as well, since you can have only one mod altering the floors at the same time. So various floor mods have been merged into this one, including Chinook, Deployment Lines, Materials+ and C.U.R.B. which is made into materials instead of objects, and you also get various bonus fences which can be used to replace a wall from a foundation (some of them at least).

## USAGE

Build a Cemetery room somewhere outside, and fill it up with Empty Graves, Empty Staff Graves, and some eyecandy GraveStones (but don’t pace those on the empty graves!). If you run a prison with many deaths per day, then you should place a Crematorium. Also place some Morgue Tables in the Morgue and place some Empty Coffins, they will be stored on these tables. Last but not least, you will need a Funeral Parlour. Full coffins will be brought here before they go to the Cemetery. You have several choices here:

- Put a Parlour Altar to give a single dead PRISONER a funeral ceremony.
- Put the Parlour Altar (Staff) to give a dead STAFF MEMBER a ceremony.
- Put one or more Parlour Tables, to just close the coffins and bury them quickly.
- The Altar will always be used first, and it starts a ceremony. If no Altars were placed (or free), the empty tables will be filled up to quickly bury the rest of the bodies.

## Coffins are sellable since they can also be produced in the Coffin Workshop: if you place more Coffins than can be stored on the Morgue tables, then those will go to Exports

Dead people are stored in the Coffins, then brought to the Funeral Parlour where the coffins get closed before they go to the Cemetery.

The Graves can bury any entity from the game, including new and unknown entities from other mods. Those are called John Doe and get a generic photo. Unfortunately, it’s not possible to copy the face and body of dead prisoners, so they get a generic photo as well, just with their security level colour.

## PRIORITY

The priority of dead people changes with this mod:

1. Store in Coffin at the Morgue on a SmallTable (Morgue)
2. Store in MorgueSlab at the Morgue
3. Bring to Hearse. A Hearse will NEVER spawn when you placed a Hearse Remover on the map.

## COMPATIBILITY

This mod is compatible with The Sneezer / Psych Ward, and downwards compatible until Update 14 of Prison Architect. If you are playing with an older (off-line) version of the game, then this mod will NOT work.

This mod is compatible with the Advanced Roads, Chinook and Metro Stations mods for building island prisons.

Due to several new features this mod is INCOMPATIBLE with the older Cemetery mod. Please disable the old mod first if you have it already, before activating this mod. If you don’t do that, I cannot guarantee that you won’t get script errors or things not working like they should. But hey, stubborn people will always be there so see if I care if you want to go yolo.

Having troubles with dead people not being moved to a Cemetery or Morgue? Check the Deployment screen if the area is Shared and not StaffOnly, or if it has the same security level as the dead prisoner. Dead MaxSec prisoners won’t be brought to a MedSec Morgue/Cemetery for instance.

## File List

<p> # Here is a list of files included in this repository:</p>

<ul><h2>LUA</h2>
<li><a href="https://github.com/Nick2bad4u/Cemetery2.0-Fixed/blob/main/data/grants.lua" style="color: #027e9e;">data\grants.lua</a></li>
<li><a href="https://github.com/Nick2bad4u/Cemetery2.0-Fixed/blob/main/data/scripts/Crematorium.lua" style="color: #c7c9c1;">data\scripts\Crematorium.lua</a></li>
<li><a href="https://github.com/Nick2bad4u/Cemetery2.0-Fixed/blob/main/data/scripts/DelOccupiedGrave.lua" style="color: #1cbb83;">data\scripts\DelOccupiedGrave.lua</a></li>
<li><a href="https://github.com/Nick2bad4u/Cemetery2.0-Fixed/blob/main/data/scripts/DelOccupiedStaffGrave.lua" style="color: #252467;">data\scripts\DelOccupiedStaffGrave.lua</a></li>
<li><a href="https://github.com/Nick2bad4u/Cemetery2.0-Fixed/blob/main/data/scripts/Ghost.lua" style="color: #932ce8;">data\scripts\Ghost.lua</a></li>
<li><a href="https://github.com/Nick2bad4u/Cemetery2.0-Fixed/blob/main/data/scripts/Grave.lua" style="color: #f99d7c;">data\scripts\Grave.lua</a></li>
<li><a href="https://github.com/Nick2bad4u/Cemetery2.0-Fixed/blob/main/data/scripts/GraveCoffin.lua" style="color: #674ae6;">data\scripts\GraveCoffin.lua</a></li>
<li><a href="https://github.com/Nick2bad4u/Cemetery2.0-Fixed/blob/main/data/scripts/GraveCoffinParlour.lua" style="color: #086038;">data\scripts\GraveCoffinParlour.lua</a></li>
<li><a href="https://github.com/Nick2bad4u/Cemetery2.0-Fixed/blob/main/data/scripts/GraveCoffinParlourStaff.lua" style="color: #728d36;">data\scripts\GraveCoffinParlourStaff.lua</a></li>
<li><a href="https://github.com/Nick2bad4u/Cemetery2.0-Fixed/blob/main/data/scripts/GraveLoaded.lua" style="color: #42e4f4;">data\scripts\GraveLoaded.lua</a></li>
<li><a href="https://github.com/Nick2bad4u/Cemetery2.0-Fixed/blob/main/data/scripts/GraveStaffLoaded.lua" style="color: #2ae183;">data\scripts\GraveStaffLoaded.lua</a></li>
<li><a href="https://github.com/Nick2bad4u/Cemetery2.0-Fixed/blob/main/data/scripts/GraveStaffUnderConstruction1.lua" style="color: #fccb75;">data\scripts\GraveStaffUnderConstruction1.lua</a></li>
<li><a href="https://github.com/Nick2bad4u/Cemetery2.0-Fixed/blob/main/data/scripts/GraveStaffUnderConstruction2.lua" style="color: #e1bee4;">data\scripts\GraveStaffUnderConstruction2.lua</a></li>
<li><a href="https://github.com/Nick2bad4u/Cemetery2.0-Fixed/blob/main/data/scripts/GraveStone2.lua" style="color: #c286a2;">data\scripts\GraveStone2.lua</a></li>
<li><a href="https://github.com/Nick2bad4u/Cemetery2.0-Fixed/blob/main/data/scripts/GraveStoneSpawner.lua" style="color: #754b74;">data\scripts\GraveStoneSpawner.lua</a></li>
<li><a href="https://github.com/Nick2bad4u/Cemetery2.0-Fixed/blob/main/data/scripts/GraveStoneStaff2.lua" style="color: #de25a3;">data\scripts\GraveStoneStaff2.lua</a></li>
<li><a href="https://github.com/Nick2bad4u/Cemetery2.0-Fixed/blob/main/data/scripts/GraveUnderConstruction1.lua" style="color: #504a40;">data\scripts\GraveUnderConstruction1.lua</a></li>
<li><a href="https://github.com/Nick2bad4u/Cemetery2.0-Fixed/blob/main/data/scripts/GraveUnderConstruction2.lua" style="color: #58cf05;">data\scripts\GraveUnderConstruction2.lua</a></li>
<li><a href="https://github.com/Nick2bad4u/Cemetery2.0-Fixed/blob/main/data/scripts/Hearse.lua" style="color: #13ac46;">data\scripts\Hearse.lua</a></li>
<li><a href="https://github.com/Nick2bad4u/Cemetery2.0-Fixed/blob/main/data/scripts/ParlourAltar.lua" style="color: #09d02f;">data\scripts\ParlourAltar.lua</a></li>
<li><a href="https://github.com/Nick2bad4u/Cemetery2.0-Fixed/blob/main/data/scripts/ParlourAltarStaff.lua" style="color: #b85872;">data\scripts\ParlourAltarStaff.lua</a></li>
<li><a href="https://github.com/Nick2bad4u/Cemetery2.0-Fixed/blob/main/data/scripts/SmallTableMorgue.lua" style="color: #68d3ba;">data\scripts\SmallTableMorgue.lua</a></li>
<h2></h2>
<li><a href="https://github.com/Nick2bad4u/Cemetery2.0-Fixed/blob/main/.gitignore" style="color: #7da395;">.gitignore</a></li>
<li><a href="https://github.com/Nick2bad4u/Cemetery2.0-Fixed/blob/main/.pre-commit-config.yaml" style="color: #cb5a4b;">.pre-commit-config.yaml</a></li>
<li><a href="https://github.com/Nick2bad4u/Cemetery2.0-Fixed/blob/main/CNAME" style="color: #b853ee;">CNAME</a></li>
<li><a href="https://github.com/Nick2bad4u/Cemetery2.0-Fixed/blob/main/file_list.html" style="color: #cc7381;">file_list.html</a></li>
<li><a href="https://github.com/Nick2bad4u/Cemetery2.0-Fixed/blob/main/generate_file_list.py" style="color: #48e016;">generate_file_list.py</a></li>
<li><a href="https://github.com/Nick2bad4u/Cemetery2.0-Fixed/blob/main/manifest.txt" style="color: #d2818e;">manifest.txt</a></li>
<li><a href="https://github.com/Nick2bad4u/Cemetery2.0-Fixed/blob/main/README.md" style="color: #f79e1e;">README.md</a></li>
<li><a href="https://github.com/Nick2bad4u/Cemetery2.0-Fixed/blob/main/sitemap.xml" style="color: #777396;">sitemap.xml</a></li>
<li><a href="https://github.com/Nick2bad4u/Cemetery2.0-Fixed/blob/main/thumbnail.png" style="color: #fa6268;">thumbnail.png</a></li>
<li><a href="https://github.com/Nick2bad4u/Cemetery2.0-Fixed/blob/main/_config.yml" style="color: #71fdb0;">_config.yml</a></li>
<h2>data</h2>
<li><a href="https://github.com/Nick2bad4u/Cemetery2.0-Fixed/blob/main/data/jobs.txt" style="color: #ef1411;">data\jobs.txt</a></li>
<li><a href="https://github.com/Nick2bad4u/Cemetery2.0-Fixed/blob/main/data/materials.txt" style="color: #0fbbc4;">data\materials.txt</a></li>
<li><a href="https://github.com/Nick2bad4u/Cemetery2.0-Fixed/blob/main/data/production.txt" style="color: #c67d14;">data\production.txt</a></li>
<li><a href="https://github.com/Nick2bad4u/Cemetery2.0-Fixed/blob/main/data/reform_programs.txt" style="color: #fd40ce;">data\reform_programs.txt</a></li>
<li><a href="https://github.com/Nick2bad4u/Cemetery2.0-Fixed/blob/main/data/sprites.png" style="color: #aa8446;">data\sprites.png</a></li>
<li><a href="https://github.com/Nick2bad4u/Cemetery2.0-Fixed/blob/main/data/tileset.png" style="color: #2abe75;">data\tileset.png</a></li>
<h2>data\language</h2>
<li><a href="https://github.com/Nick2bad4u/Cemetery2.0-Fixed/blob/main/data/language/base-language.txt" style="color: #e18b41;">data\language\base-language.txt</a></li>
<h2>data\language\french</h2>
<li><a href="https://github.com/Nick2bad4u/Cemetery2.0-Fixed/blob/main/data/language/french/base-language.txt" style="color: #2b8fdd;">data\language\french\base-language.txt</a></li>
<h2>.github</h2>
<li><a href="https://github.com/Nick2bad4u/Cemetery2.0-Fixed/blob/main/.github/dependabot.yml" style="color: #b910eb;">.github\dependabot.yml</a></li>
<h2>.github\workflows</h2>
<li><a href="https://github.com/Nick2bad4u/Cemetery2.0-Fixed/blob/main/.github/workflows/ActionLint.yml" style="color: #4bc074;">.github\workflows\ActionLint.yml</a></li>
<li><a href="https://github.com/Nick2bad4u/Cemetery2.0-Fixed/blob/main/.github/workflows/dependency-review.yml" style="color: #7772d5;">.github\workflows\dependency-review.yml</a></li>
<li><a href="https://github.com/Nick2bad4u/Cemetery2.0-Fixed/blob/main/.github/workflows/scorecards.yml" style="color: #411bac;">.github\workflows\scorecards.yml</a></li>
<li><a href="https://github.com/Nick2bad4u/Cemetery2.0-Fixed/blob/main/.github/workflows/sitemap.yml" style="color: #713dcc;">.github\workflows\sitemap.yml</a></li>
<h2>.vscode</h2>
<li><a href="https://github.com/Nick2bad4u/Cemetery2.0-Fixed/blob/main/.vscode/settings.json" style="color: #4a9a3a;">.vscode\settings.json</a></li></ul>
