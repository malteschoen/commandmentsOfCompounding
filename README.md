# 50 basic things to understand about compounding

### Fully or partially filled state - which task for which state?
- Successful compounding requires the following needs to be met:
  - a) intake
  - b) degassing
  - c) dispersive mixing
  - d) distributive mixing
  - e) pump-out
- Intake and degassing can only be be done in partially filled, non-pressurized screw sections of the extruder. Consequently, any good compounding machine has these non-pressurized screw sections. 
- Mixing takes place in both fully and partially filled sections. As only fully filled sections can meaningfully provide the residence time needed for most mixing tasks, these sections do most of the mixing work (but not all).
- Pump-out requires some pressure and is hence is only possible in fully filled sections.

### Which fill state is present where?

- There are two class of screw sections: either the local drag flow exceeds the current volumetric machine throughput or it does not. Screw sections of the second class always become flow restrictions that are fully filled and pressurized (as pressure is necessary for material to flow through them). Note that high throughputs or low screw speeds may cause any element to fall ino the second class!
- Screw elements with no drag flow ('neutral' or '90 degree' kneading discs) or negative drag flow (backwards/reverse/left-handed elements) are always in the second class, regardless of operating conditions. For our purposes, the equipment downstream of the screw tip (melt pipe, gear pump, extrusion die...) are considered a single section of the second class. 
- In spite of their drag flow exceeding the throughput, screw sections of the first class can become filled and pressurized if they are upstream of a flow restriction. The pressure present in the flow restriction pushes material both forwards through the restriction (downstream direction towards the screw tip) and backwards (upstream direction towards the hopper). Backwards flow causes material to flow backwards and fully fill the extruder in a certain region we call the 'backed-up filled lenght'.
- The following tables try to give an overview. They assume 'flow moving left to right' as well as fixed screw speeds and viscosities.

 Table 1 | Section I, classified as having positive drag flow; located far away from section III  | Section II, classified as having positive drag flow; located directly upstream of III | Section III, classified as having zero or negative drag flow
------------- | ------------- | ------------- | ------------- 
Scenario 1: 'low throughput'  | partially filled, no interaction with pressure  |   short backed-up filled lenght which is fully filled and pressurised, 'builds a small amount of pressure' | fully filled and pressurised, serves as flow restriction, 'consumes a small amount of pressure'
Scenario 2: 'high throughput' | partially filled, no interaction with pressure  |  long backed-up filled lenght which is fully filled and pressurised 'builds a large amount of pressure'| fully filled and pressurised, serves as flow restriction, 'consumes a large amount of pressure'

- Take-away message: Upstream of flow restrictions, you will have 'backed-up filled lenghts'. Low drag flows (usually caused by slow screw speeds) and high throughputs and as well as stronger flow restrictions (e.g. closing of a valve) cause the length to grow. Take care you don't fully fill and pressurize screw sections that are open to the environment...


### Intake
- Intake is reasonably easy: have a feed opening in the barrel and feed in materials. You must not feed in more m³/s through than can be conveyed away from the opening. For very high filler volumes, you'll have to sequentially add the materials through multiple feed openings, squeezing out entrained air inbetween.
- [TBC] Add some notes about what you should not add together with the raw polymer pellets: avoid fibres (will be shortened, avoid slippery substance (will hinder melting) [TBC]

### Degassing
- Almost all added materials contain some volume of air. This air needs to be removed from the compound together with any solvents, residual moisture etc. 
- There are openings for non-vacuum ('atmospheric') degassing and vacuum degassing, both called vents. The polymer pellet feed hopper is your first atmospheric vent, the exit past the screw tip is the second one. It is always benefical to have fully filled zone as a 'melt seal' between vents. Vacuum vents strictly require a seal.
- Good degassing primarily needs surface renewal, meaning high rotation speeds per throughput (i.e. low degree of fill). You can support this by raising the temperature and hence partial pressure of the gas you want to vent and by pulling a lower vacuum.

### Dispersive mixing

- Dispersive mixing needs time-integrated stress. 
- Example use-case fibre dispersion
- Example use-case carbon black dispersion.
- Example use-case blending of PS in PE matrix.

### Distributive mixing

- Distributive mixing needs total strain which is time-integrated shear rate.
- In contrast to dispersive mixing, viscosity has no influence here!
  
### Pump-out

- Pump-out always works against flow restrictions and hence benefits from screw channels with low volume (low pitch and/or low channel depth).

### Other process limits
- Insufficient torque
- Insufficient volume
- Excessive temperature
- Poor melting/mixing

### Residence time, throughput and temperature

### More involved consideration of 'backed-up filled lenght'
- The force in the restriction 'points upstream' and is balanced out by pressure flow upstream, more precisely by the shear stresses and pressure gradient resulting from that flow. As the shear rate of this upstream pressure flow is fixed (pressure flow in m³/s is exactly the excess of drag flow over the volumetric machine throughput) and melt viscosity can be assumed as constant in this filled volume, the pressure gradient is also fixed and the 'backed-up filled lenght' is the only variable available to balance the forces. 
- The pressure will drop linearly across the lenght of the 'backed-up filled lenght' until it reaches 1 bar. At this point, the screw section is partially filled again. Drag flow still exceeds throughput, but now the difference is not made up by pressure flow, but by 'empty volume' in the channel.
- Take note that the classification of 'Does drag flow exceed throughput?' might change with the operating conditions: drag flow varies with screw speed, machine throughput can be adjusted by the feeders. A bad combination can 'flip' a screw section from the first class into the second class.  Also: temperature and shear rate (among others) affect viscosity and hence both pressure in the flow restriction and the backed-up filled lenght.
