# Voron-V0.1-extruder-upgrades

== work in progress ==

I am fascinated by how much choice there is if I want to upgrade my voron v0.1 mini afterburner. I guess I am not the only one, so I created this documents to share my findings.

## Stock: Mini Afterburner (Mini AB)
https://github.com/VoronDesign/Voron-0

Cons (things to be improved):
- High chamber temperature results in fan overheating, ultimately leads to blower fan failure.
- Adjusting the position of extrusion gear can be tricky in the beginning.
- Filament path is in a strange angle, making it not possible to optically inspect filament path.
- In case of heat creep/ grinding gear / any other filament jam happening below the extrusion gear, it is very difficult to take the extruder apart.
- Looks less cool comparing with other mods here.

Below I listed 4 options that I found relavent.

## Option 1: Mini Stealthburner (Mini SB)
https://github.com/VoronDesign/Voron-0

Pros:
- Very modern polygon looking.
- Upgrade is mostly straight-forward and do not require new 
- Inclusion of fan saver should protect the blower fans from overheating.
- Adjusting extrusion gears is way easier. Filament path is also straight now.

Cons:
- Needs to change the X-carriage and re-tighten belt. Could be a pain if you have not seen this trick: https://www.youtube.com/watch?v=d77Zsg4DETU
- If you still use endstops for homing, remember to print a different X-carriage https://www.printables.com/model/517984-v02-voron-02-x-carriage-with-x-endstop-and-a-drive
- Reported cased of overheating fans in extreme cases.

## Option 2: Mini Afterssherpa (Mini AS) moded from Mini AB
https://github.com/PrintersForAnts/Mini-AfterSherpa

Similar concept: https://www.printables.com/model/169127-voron-0-sherpa-mini-mount

Pros:
- Looks very cool. Mini sherpa is also very easy to assemble and adjust.
- No need to purchase new fans.
- No need to unmount the X-carriage.

Cons:
- Fan overheating risk not solved.


## Option 3: Mini AS moded from Mini SB
https://www.printables.com/model/451261-voron-02-r1-sherpa-mini-micro-stealthburner

Pros: 
- Even more modern looking.
- Adapted the fan saver from the MiniSB. This could potentially solve the fan overheating issue.
- No need to purchase new fans.

Cons:
- Need to change X-carriage and hence re-tighten belt.
- The MiniSB motor backplate do not necessarily fit the screwholes on Sherpa Mini. Use the MiniAB strain relieve.
- Some overheating cases are still reported


## Option 4: Dragon Burner (DB)
https://github.com/chirpy2605/voron/tree/main/V0/Dragon_Burner

Previous version available if you do not wish to change X-carriage

https://github.com/chirpy2605/voron/tree/main/V0/Dragon_Burner/Old_Versions/v4

Pros: 
- Easy integration of nozzle LEDs. Loads of custom mods exist.
- Larger 4010 fans for better nozzle cooling. This also further prevents fan overheating.
- Overall the best upgrade so far, if you dig into the look.

Cons:
- Extra purchase of 4010 fan required.

Verdict:

If you just want an easy, stylish and practical upgrade
--> Mini AS moded from Mini AB

If you would like to improve on fan overheating and extruder assembly:
--> Mini SB, or
--> Mini AS moded from Mini SB

If you would like an all-around improvement
--> DB
