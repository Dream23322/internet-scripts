# internet-scripts\n
A collection of simple console scripts for silly online games like cookie clicker [Hacks]\n

# How to use?\n
To open the console on your browser, click CTRL+Shift+C, then click the console tab, paste the script in, and have fun!\n

## Cookie Clicker\n

**Simple AutoClicker:**
- Game.Earn(<cookie amount>) - earn as many cookies as you want, on top of your current total\n
- Game.cookies=1000 - set your total cookies to whichever number you want\n
- Game.cookies= Game.cookies + <number> - adds the desired amount of cookies to your current total\n
- Set your cookies per second\n
- Game.Achievements['<achievement name>'].won=1 - unlocks the achievement of your choice\n
- Game.Ascend(1) - ascend to a heavenly space, turning your cookies into Heavenly Chips and Prestige\n
- Game.AscendTimer=<time> - change the Ascend Timer\n
- Game.bakeryName="<bakery name>" - set a name for your bakery\n
- Game.bakeryNameRefresh() - refresh your bakery name\n
- Game.BuildAscendTree() - build the Ascend Tree\n
- Game.buyBulk=<1/10/100> - changes your X# buy amount\n
- Game.CalculateGains() - calculates gains\n
- Game.computedMouseCps - computes your mouse Cps (mouse cookies per second amount)\n
- Change your mouse Cps\n
- Game.dragonLevel=<level> - set your dragon level\n
- Game.gainLumps(<amount of lumps>) - add as many lumps as you want\n
- Game.Has('<achievement name>') - check if you have a certain achievement\n
- Game.killShimmers() - removes all shimmers\n
- Game.LoadSave() - load a saved file\n
- Game.LoadSave(local) - load a local save file\n
- Game.localStorageGet(Game.SaveTo) - save your game locally\n
- Game.MaxSpecials() - get the max amount of specials\n
- Game.Milk = <amount> - change your milk amount\n
- Game.milkProgress = <milk amount> - change your milk progress\n
- Game.mousePointer=0 - change your mouse pointer\n
- Game.particlesUpdate() - update particles\n
- Game.popups=0 - remove the game's popup notifications\n
- Game.RuinTheFun(1) - unlock everything\n
- Game.santaLevel=<level> - set the game's santa level\n
- Game.sesame=0 - turn sesame on or off\n
- Game.SesameReset() - reset the game\n
- Game.SetAllAchievs(1) - unlock all achievements\n
- Game.SetAllUpgrade(1) - get all upgrades\n
- Game.Win('<achievement name>') - another way to unlock an achievement of your choice\n
- Timer.track('milk') - lets you track the milk timer\n

## Debug Codes\n
If you have issues with your game, use these!\n
- Game.DebuggingPrestige=false - debugs your prestige\n
- Game.debugTimersOn=<0 or 1> - turns the debug timers off or on\n
- Game.DebugUpgradeCpS() - debugs your Upgrades Cps\n
- Game.GetAllDebugs() - get all the possible debugs\n
- Game.HardReset(2) - hard reset your game\n

# Wordle Bypass\n
[Credit](https://github.com/pog5/nealpasswordgame/blob/main/CHEATS.md)\n
Probably the easiest one of them all.\n
Replace DATE with today's date in the format YYYY-MM-DD:\n
https://neal.fun/api/password-game/wordle?date=DATE\n
Alternatively, you can paste the following one-liner into the developer console (F12):\n
d=new Date().toISOString().split('T')[0],fetch(`https://neal.fun/api/password-game/wordle?date=${d}`).then(r=>r.json()).then(d=>console.log(d.answer)\n

# Ortiel Legacy Game\n
A good cheat for that game can be found [here](https://github.com/geekahedron/heritage/tree/master)\n
