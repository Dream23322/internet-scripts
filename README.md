# internet-scripts
A collection of simple console scripts for silly online games like cookie clicker [Hacks]
# How to use?
To open the console on your browser, click CTRL+Shift+C then click the console tab, paste the script in and have fun!

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

**Single Line Scripts**

Game.Achievements[‘<achievement name>’].won=1; - unlocks the achievement of your choice

Game.Ascend(1); - ascend to a heavenly space, turning your cookies into Heavenly Chips and Prestige

Game.AscendTimer=<time>; - change the Ascend Timer

Game.bakeryName=”<bakery name>”; - set a name for your bakery

Game.bakeryNameRefresh(); - refresh your bakery name

Game.BuildAscendTree(); - build the Ascend Tree

Game.buyBulk=<1/10/100>; - changes your X# buy amount

Game.CalculateGains(); - calculates gains

Game.computedMouseCps; - computes your mouse Cps (mouse cookies per second amount)

Game.computedMouseCps=<your desired mouse Cps amount>; - change your mouse Cps

Game.dragonLevel=<level>; - set your dragon level

Game.gainLumps(<amount of lumps>); - add as many lumps as you want

Game.Has(‘<achievement name>’); - check if you have a certain achievement

Game.killShimmers(); - removes all shimmers

Game.LoadSave(); - load a saved file

Game.LoadSave(local); - load a local save file

Game.localStorageGet(Game.SaveTo); - save your game locally

Game.MaxSpecials(); - get the max amount of specials

Game.Milk = <amount>; - change your milk amount

Game.milkProgress = <milk amount>; - change your milk progress

Game.mousePointer=0; - change your mouse pointer

Game.particlesUpdate(); - update particles

Game.popups=0; - remove the game's popup notifications

Game.RuinTheFun(1); - unlock everything)

Game.santaLevel=<level>; - set the game's santa level

Game.sesame=0; - turn sesame on or off

Game.SesameReset(); - reset the game

Game.SetAllAchievs(1); - unlock all achievements

Game.SetAllUpgrade(1); - get all upgrades

Game.Win(‘<achievement name>’); - another way to unlock an achievement of your choice

Timer.track(‘milk’); - lets you track the milk timer
