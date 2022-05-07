# Raid Sims

A collection of custom raid event scripts and apls for raid bosses that warrant specialized optimization effort but can't accurately be simmed with existing fight styles.

## For use with Raidbots

- Copy your /simc input into the profile box and set up the sim using the Raidbots sim options like normal.

- Enable Expert Mode in Raidbots in whatever tab you want to sim.

Each encounter directory will contain a `encounter.simc` which holds all relevant raid events and sim-wide options to make the sim work.
- Copy the entire text of this into the **Footer** box of Expert Mode.

Alongside that are spec specific apls that should be used, such as `mm-apl.simc`. These have been reasonably optimized to use cooldowns and trinkets according to the encounter script. They also include default settings for options and external buff declarations that make the sim more accurate. The readme for each encounter directory has a description of them all and justification for their default values.
- Copy the entire text of your chosen spec into the **Custom APL and SimC Options** box.
