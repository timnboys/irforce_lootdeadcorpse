# esx_irforce_lootdeadcorpse

this is my very first script

it allows specific jobs to loot dead corpse, of course with a cute animation by pressing 'E'.

### Prerequisites

only works with ESX

## Installing

after download/clone rename the folder from 
```
irforce_lootdeadcorpsee-master
```
to
```
irforce_lootdeadcorpse
```
then goto to the address below and change the jobs name of your liking
```
irforce_lootdeadcorpse/client/main.lua:29
```
just replace the "jobname-here" with the job name you like
for example:
```
if IsControlJustReleased(0, 38) and ( ESX.PlayerData["job"]["name"] == "fbi" or ESX.PlayerData["job"]["name"] == "police" ) then
```
and for the final step put the line below in your server.cfg file
```
start irforce_lootdeadcorpse
```
## Enjor it🤩
## Contributing

Please read [CONTRIBUTING.md](https://github.com/H0ssein/irforce_lootdeadcorpse/blob/master/CONTRIBUTING.md) for more information.
