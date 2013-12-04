Instructions to add the Propeller Development Stick to PropGcc.

1. Add the PropDevStick.cfg file to C:\propgcc\propeller-load\
2. Open the boards.txt file in that directory. There should be a list like the following.

```
# 
# This is a board selection file. 
# To enable a board, all that's needed is the 
# board cfg filename somewhere in the text here 
#  
activityboard.cfg      # this is the Propeller Activity board type
eeprom.cfg             # this is the default 64KB EEPROM board type
rcfast.cfg             # the generic rcfast clock setting
rcslow.cfg             # the generic rcfast clock setting
c3.cfg                 # this is the default C3 type
c3f.cfg                # this is the C3 type where only flash is used for code
demoboard.cfg          # demoboard type
hydra.cfg              # hydra type
propboe.cfg            # propboe type
propstick.cfg          # propstick type
quickstart.cfg         # quickstart type
spinstamp.cfg          # spinstamp type
synapse.cfg            # synapse type

```

3. Past the followling line at the bottom of the list. 

```
PropDevStick.cfg	   # this is the Propeller Development Board
```

4. Save 
