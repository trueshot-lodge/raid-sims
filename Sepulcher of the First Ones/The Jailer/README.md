# The Jailer

Cooldowns are used on pull and then saved whenever possible for cleave when it can do so without losing a use. The second Trueshot is up for debate though and some builds prefer a use at 2 minutes over others preferring a delay until 3 minutes. Using it as early as possible does let it benefit from CA and a Azerite Radiation buff while not risking being interrupted by getting chosen by the mind control, but will not have a chance to cleave the first mind control set. The apl has a variable to control that decision `cooldown_at_2`. To change the default of 1, search for the line in the apl and change the `value=1` to `value=0`.
>actions+=/variable,name=cooldown_at_2,op=set,value=0

or
>actions+=/variable,name=cooldown_at_2,op=set,value=1

Simming the Boon of Azeroth buff is done with this external option:
>external_buffs.boon_of_azeroth_mythic=388
That value applies the buff at 6:28.

Forcing an extra Bloodlust after 10 minutes has to be done with this external option:
>external_buffs.forced_bloodlust=610
That value applies a new Bloodlust at 10:10.

Also consider how ground effect uptimes might suffer on this fight due to movement, important covenant buff uptimes should be altered with sim options.
These were made to match some averages from logs. While there are actually no Theotar logs the uptime is assumed based on the Blossoms uptimes that have been possible, then diminished a bit due to it being a random proc:
>shadowlands.field_of_blossoms_duration_multiplier=0.5

>shadowlands.soothing_shade_duration_multiplier=0.75
