# Valorant Randomizer
A simple and funny software idea for my friends. Simply generates a random weapon &amp; agent to use depending on multiple factors, with maybe some... twists I guess?  
Oh, and tested the randomizer with my friends & they loved it!

##

### THE EXECUTABLE IS BEING DETECTED AS A VIRUS & IS A FALSE WARNING!
(YOU CAN CHECK THE SOURCE FILES ZIP IN THE RELEASES)

- [Releases Section](https://github.com/j-2k/Valorant-Randomizer-Quest/tags) > [v0.9](https://github.com/j-2k/Valorant-Randomizer-Quest/releases/tag/v0.9) (First Release) 

##

### CURRENT ISSUES ON VERSION PRE-RELEASE 0.9!
- Money is IGNORED when generating with the secondary toggle ON
- When Shield Toggles are ON, Money is IGNORED again.
  - To elaborate, if no toggles are enabled, you will recieve a single random weapon from the list of weapons that is ENABLED, however, the generated weapon is taking into consideration the current amount of money set (that means if you have 900 & assume you have all weapons highlighted except pistols, you will always get a bucky). Now if you set on shields you can recieve a weapon with a shield type that can exceed your current amount of money, this is the issue.
- There are some other very minor bugs I saw at the start when my friends tested but im not sure iirc how to reproduce them.

##

## Pictures of the project:
Logo of the exe & BG picture is from the anime "The Fable"!


### Main Features: (Priority/100% included)
- Generate a random choice of the following categories:
  - Agents
    - Select specific **agents** to draw into the pool for random generation
  - Loadout
    - Select specific **menu items** to draw into the pool for random generation
    - Any single weapon only (main) OR Primary & Secondary weapon (option)
    - Consider shields into the mix (option)
    - ~~Should primary take priority with current money over secondary in randomization if both primary & secondary option is chosen???~~ (thinking of adding this not sure yet)


### Extra Features: (Not a priority/might not be included)
- Consider the money when random generating
  - Primary Weapon
  - Primary & Secondary Weapon
  - Shields
  - All together (Primary, Secondary, Shields)
  - Should there be a priority queue for money spent??? or should it be all equal???
  - etc
- Generate a random choice of the following categories:
  - Abilities
  - Rules?
  - Playstyles
  - Quests

---

## Build/Repository information for nerds

### Original Project Plans:
- Desktop Application (web is better but I want to learn desktop garbage)
- Target Windows 10 & 11
-  ~~Planning to use either imgui (cpp) or winUI3 (c#) for UI framework.~~
- Welp, I decided to use WF because I need to learn it for work.

### Building the project:
Notes:  
- I used VS 2022 & .NET Framework 4.8
- Tested on different machine while using VS 2019 still works fine!
  
Steps:
1) Open solution (.sln) file with visual studio (pref 2022)... thats it.  
(Try building the project, it "should" work... unless you get funny building error moment)

