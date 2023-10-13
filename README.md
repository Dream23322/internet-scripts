# internet-scripts
A collection of simple console scripts for silly online games like cookie clicker [Hacks]

# How to use?
To open the console on your browser, click CTRL+Shift+C, then click the console tab, paste the script in, and have fun!

## Cookie Clicker

**Simple AutoClicker:**
```javascript
var autoclicker = setInterval(function(){
  try {
    Game.lastClick -= 1000;
    document.getElementById('bigCookie').click();
  } catch (err) {
    console.error('Stopping auto clicker');
    clearInterval(autoclicker);
  }
}, 1);
```

<details>
  <summary>Other Cookie Clicker Scripts</summary>
  
- ```Game.Earn(<cookie amount>);``` - earn as many cookies as you want, on top of your current total
  
- ```Game.cookies=1000;``` - set your total cookies to whichever number you want
  
- ```Game.cookies= Game.cookies + <number>;``` - adds the desired amount of cookies to your current total

Set your cookies per second

```javascript
var setPS = setInterval(function(){
  try {
    Game.cookiesPs=<number>;
  } catch (err) {
    clearInterval(setPS);
  }
}, 1);
```

- ```Game.Achievements['<achievement name>'].won=1;``` - unlocks the achievement of your choice

- ```Game.Ascend(1);``` - ascend to a heavenly space, turning your cookies into Heavenly Chips and Prestige

- ```Game.AscendTimer=<time>;``` - change the Ascend Timer

- ```Game.bakeryName="<bakery name>";``` - set a name for your bakery

- ```Game.bakeryNameRefresh();``` - refresh your bakery name

- ```Game.BuildAscendTree();``` - build the Ascend Tree

- ```Game.buyBulk=<1/10/100>;``` - changes your X# buy amount

- ```Game.CalculateGains();``` - calculates gains

- ```Game.computedMouseCps;``` - computes your mouse Cps (mouse cookies per second amount)

Change your mouse Cps

```javascript
var setCPS = setInterval(function(){
  try {
    Game.computedMouseCps=<your desired mouse Cps amount>;
  } catch (err) {
    clearInterval(setCPS);
  }
}, 1);
```

- ```Game.dragonLevel=<level>;``` - set your dragon level

- ```Game.gainLumps(<amount of lumps>);``` - add as many lumps as you want

- ```Game.Has('<achievement name>');``` - check if you have a certain achievement

- ```Game.killShimmers();``` - removes all shimmers

- ```Game.LoadSave();``` - load a saved file

- ```Game.LoadSave(local);``` - load a local save file

- ```Game.localStorageGet(Game.SaveTo);``` - save your game locally

- ```Game.MaxSpecials();``` - get the max amount of specials

- ```Game.Milk = <amount>;``` - change your milk amount

- ```Game.milkProgress = <milk amount>;``` - change your milk progress

- ```Game.mousePointer=0;``` - change your mouse pointer

- ```Game.particlesUpdate();``` - update particles

- ```Game.popups=0;``` - remove the game's popup notifications

- ```Game.RuinTheFun(1);``` - unlock everything)

- ```Game.santaLevel=<level>;``` - set the game's santa level

- ```Game.sesame=0;``` - turn sesame on or off

- ```Game.SesameReset();``` - reset the game

- ```Game.SetAllAchievs(1);``` - unlock all achievements

- ```Game.SetAllUpgrade(1);``` - get all upgrades

- ```Game.Win('<achievement name>');``` - another way to unlock an achievement of your choice

- ```Timer.track('milk');``` - lets you track the milk timer
</details>
<details>
  <summary>Debug Codes</summary>
    <body>If you have issues with your game, use these!</body>
  
- ```Game.DebuggingPrestige=false;``` - debugs your prestige
  
- ```Game.debugTimersOn=<0 or 1>;``` - turns the debug timers off or on
  
- ```Game.DebugUpgradeCpS();``` - debugs your Upgrades Cps
  
- ```Game.GetAllDebugs();``` - get all the possible debugs
  
- ```Game.HardReset(2);``` - hard reset your game
</details>


# Wordle Bypass

[Credit](https://github.com/pog5/nealpasswordgame/blob/main/CHEATS.md)

Probably the easiest one of them all.

Replace `DATE` with today's date in the format `YYYY-MM-DD`:
`https://neal.fun/api/password-game/wordle?date=DATE`

Alternatively, you can paste the following one-liner into the developer console (F12):
```js
d=new Date().toISOString().split('T')[0],fetch(`https://neal.fun/api/password-game/wordle?date=${d}`).then(r=>r.json()).then(d=>console.log(d.answer))
```


# Ortiel Legacy Game

A good cheat for that game can be found [here](https://github.com/geekahedron/heritage/tree/master)
