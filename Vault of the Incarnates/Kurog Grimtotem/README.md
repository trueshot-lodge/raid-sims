# Kurog Grimtotem

The combination of the merge_enemy_priority_dmg=1 option and raid events for the Flamewrought Eradicator and Earthwrought Smasher using the type=add_boss option force the damage done to these 3 enemies to show collected in the "Priority Target/Boss Damage" chart in the detailed report. If you want to also collect intermission damage to the Thundering Ravager, Blazing Fiend, Frozen Destroyer, or Tectonic Crusher in that metric, add the type=add_boss option to the end of their spawn events.

The included MM apl prevents Aimed Shot target swapping for Serpent Sting multidotting in the last phase to maximize boss damage since the Frostwrought Dominator damage is irrelevant.