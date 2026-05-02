# Community Parts Titles Evolved, for Kerbal Space Program (KSP 1)

The goal of this mod is to bring a sanitization and standardization to parts
naming within Kerbal Space Program. In particular, it aims to sort parts with a
similiar purpose together, to allow a separation of the "thinking about what
parts means" from the rocketship building parts of KSP, and also to allow
easily picking up additional mods into an existing (modded) game (or mod pack).

In general, naming is *prefix* (corresponding to a the part's use) -- *size* --
*capacity/useful property*.

For a simple example, consider the built-in stack decouplers, now called:

    - TR-06 Stack Decoupler (formerly the "TR-02V Stack Decoupler")
    - TR-12 Stack Decoupler (formerly the "TR-18A Stack Decoupler")
    - TR-25 Stack Decoupler (formerly the "TR-20 Rockomax Brand Decoupler")
    - TR-37 Stack Decoupler (formerly the "TR-38D Stack Decoupler")

"TR" is the prefix for a decoupler (carried forward from stock KSP naming, in
this case), and the number represents diameter of the decoupler. In a fully
stock game with only these four decouplers, it probably isn't too hard to find
what you need. But as you add more mods, you can tell at a glace it a 5.0m
decoupler has been added (because it will be labelled "TR-50 ...").

For a slightly more involved example, consider a selection of stock fuel tanks:

    - FL-12-100 Liquid Fuel Tank (formerly the "FL-T100 Fuel Tank")
    - FL-12-200 Liquid Fuel Tank (formerly the "FL-T200 Fuel Tank")
    - FL-12-400 Liquid Fuel Tank (formerly the "FL-T400 Fuel Tank")
    - FL-12-800 Liquid Fuel Tank (formerly the "FL-T800 Fuel Tank")
    - FL-25-800 Rockomax Fuel Tank (fomerly the "Rockomax X200-8 Fuel Tank")
    - FL-25-k02 Rockomax Fuel Tank (fomerly the "Rockomax X200-16 Fuel Tank")
    - FL-25-k03 Rockomax Fuel Tank (fomerly the "Rockomax X200-32 Fuel Tank")
    - FL-25-k06 Rockomax "Jumbo" Fuel Tank (fomerly the "Rockomax Jumbo-64 Fuel Tank")
    - FL-37-k07 Kerbodyne Fuel Tank (fomerly the "Kerbodyne S3-7200 Tank")
    - FL-37-k04 Kerbodyne Fuel Tank (fomerly the "Kerbodyne S3-3600 Tank")
    - FL-37-k14 Kerbodyne Fuel Tank (fomerly the "Kerbodyne S3-14400 Tank")
    - FL-50-k06 Kerbodyne Fuel Tank (fomerly the "Kerbodyne S4-64 Fuel Tank")
    - FL-50-k13 Kerbodyne Fuel Tank (fomerly the "Kerbodyne S4-128 Fuel Tank")
    - FL-50-k26 Kerbodyne Fuel Tank (fomerly the "Kerbodyne S4-256 Fuel Tank")
    - FL-50-k51 Kerbodyne Fuel Tank (fomerly the "Kerbodyne S4-512 Fuel Tank")

"FL" is the prefix for "fuel tanks", the first number represents the tank
diamter, and the third number represents the tank size. This way, all tanks are
sorted together, we can quickly tell that the "FL-12..." tanks with match the
"TR-12" decoupler (because they have the same diamter), and we can quickly
compare tank capacities ("k" as a prefix means "thousand", so "k02" means a
capacity of ~2,000).

For perhaps the most complex example, consider a selection of stock engines:

    - LB-12-017/265 "Reliant" Engine (formerly the "LV-T30 "Reliant" Liquid Fuel Engine")
    - LB-12-024/295 "Vector" Engine (formerly the "S3 KS-25 "Vector" Liquid Fuel Engine")
    - LB-25-018/280 "Twin Boar" Engine (formerly the "LFB KR-1x2 "Twin-Boar" Liquid Fuel Engine")
    - LB-25-023/285 "Mainsail" Engine (formerly the "RE-M3 "Mainsail" Liquid Fuel Engine")
    - LB-37-025/295 "Mammoth" Engine Cluster (formerly the "S3 KS-25x4 "Mammoth" Liquid Fuel Engine")
    - LS-03-014/293 "Spark" Engine (formerly the "48-7S "Spark" Liquid Fuel Engine")
    - LS-06-013/285 "Swivel" Engine (formerly the "LV-T45 "Swivel" Liquid Fuel Engine")
    - LS-12-017/315 "Dart" Aerospike Engine (formerly the "T-1 Toroidal Aerospike "Dart" Liquid Fuel Engine")
    - LS-12-021/300 "Skipper" Engine (formerly the "RE-I5 "Skipper" Liquid Fuel Engine")
    - LS-18-018/273 "Rhino" Engine (formerly the "Kerbodyne KR-2L+ "Rhino" Liquid Fuel Engine")
    - LZ-03-315/002 "Ant" Engine (formerly the "LV-1 "Ant" Liquid Fuel Engine")
    - LZ-06-345/060 "Terrier" Engine (formerly the "LV-909 "Terrier" Liquid Fuel Engine")
    - LZ-18-350/250 "Poodle" Engine (formerly the "RE-L10 "Poodle" Liquid Fuel Engine")
    - LZ/o-R-250/020 "Puff" Monopropellant Engine (formerly the "O-10 "Puff" MonoPropellant Fuel Engine")

With rockets, we want different types of engines for different parts of our
flight, and so the engines are broken into three prefixes: "LB" for "booster"
(to provide raw thrust that we want for our first stage to get off the launch
pad), "LS" for "sustainers" (to keep us moving up through the atmosphere, with
better effeciency than our boosters), and finally "LZ" for vacuum rated engines
(where efficency is prized more than raw thrust).

With numbering, we can tell as a glance that the "Vector" engine is more
powerful than the "Reliant"; the actual values mean that the "Vector" engine
has a Thrust-to-Weight Ratio (TWR) of 24, vs the "Reliant"'s 17.


The part number remains open to revision; if you would like to suggest changes
to make it more intuitive or to expland it to additional mods, please feel free
to contribure!


## Installation

The easiest installation is probably through CKAN: search for "Community Parts
Titles Evolved".

Alternately, you can [download a release directly from
GitHub](https://github.com/minchinweb/ksp-CommunityPartsTitles/releases) and
place the files in your "GameData" folder.

Note that this mod is considered incompatible with the original "Community
Parts Titles", and the two should not be installed at the same time.


## History

This mod was originally created by *flart* in 2018, who has maintained it for
many years. See [original
thread](https://forum.kerbalspaceprogram.com/topic/174189-112-community-parts-titles-2025-06-07/).

However, I found I was contributing more and more of the additional mod support
myself, and my contributions seems to be taking a lot of effort to get merged
upstream, so in 2026 I launced this "Evolved" edition to manage the releases
myself.

In particular, this edition has expanded to include support for engines, more
consistency for RCS blocks, and support for Sterling Systems mods.

## Changelog

See
[Changelog.md](https://github.com/minchinweb/ksp-CommunityPartsTitles/blob/master/ChangeLog.md).

## Naming Spec / Prefixes in Use

### General Notes

#### Diameters

Sizes are given in decimeters; therefore, 2.5m diameter is given as *25*. 10m
is given as *A0*, which is 100 in hexadecimal. Radial mounts are given a
"diameter" of *R*.

Typical sizes thus are given as *03*, *06*, *12*, *18*, *25*, *37*, *50*, *75*,
*A0*.

Parts intended for use in airplanes are sometimes denoted as *Mk0*, *Mk1*,
*Mk2*, or *Mk3*.

*Kerbodyne S3* is *37*, *Kerbodyne S4* is *50*.

If an item is two different sizes at the two ends, typically both sizes are
given, e.g. *12-25*. If an adapter has several mounting plates on one end, the
count of these plates is also provided; e.g. *37-25x4*.


#### Magnitude

For volumes and ranges, a prefix of *k* means that the given number is in
thousands, and a prefix of *m* means the given number is in millions. Note that
these are prefixed, so sorting works as expected (e.g. "*XX-k03*).


#### Source Designation

For commonly-provided parts (such as fuel tanks), often an abbreviation for the
source mod will be added after the part title, in parenthesis; e.g. *(RS+)*.

(Selected) designations thus used:

- FTP -- Fuel Tanks Plus
- Kerbonov
- Mk2+ -- Mk 2 Expansion
- Mk3+ -- Mk 3 Expansion
- N-Series -- Near Future Launch Vehicles
- Orion -- Stockish Project Orion
- SpaceY
- SR -- USI Sounding Rockets
- SSR -- MicroSat
- RLA -- RLA Reborn
- RS+ -- ReStock Plus


### Pods

*RC* ("Remote Control") is used as a prefix for probe cores.


### Engines

Engines have yet to be thoroughly standardized and thus still use a variety of
naming conventions.

If in doubt, you can use:

- *LV* ("Liquid Vector") for liquid fuel + oxidizer engines,
- *O* (the letter after *N*, rather than the number) for monopropellant
engines,
- *J* for jet engines,
- *IX* for Ion engines,

The exception is solid rocket boosters, that are named "SRB-*diameter*-*fuel
amount*".


### Tanks

Tanks are named "*prefix*-*diameter*-*volume* 'nice' name".

(Selected) prefixes used:

- *FL* ("Fuel Level") -- regular liquid fuel + oxidizer tanks
- *FS* -- single-ended liquid fuel + oxidizer tanks
- *FV* -- adapter liquid fuel + oxidizer tanks; i.e. tanks that have different
  diameters top and bottom
- *OL* -- for monopropellant tanks
- *Ar* -- for Argon tanks
- *Li* -- for Lithium tanks
- *Xe* -- for Xenon tanks
- *UH* -- Holding tanks (for Ore)
- *NL* ("Nuclear Liquid") -- liquid fuel only tanks, for use with Nuclear engines
- *YD* -- Hydrogen Tanks


### Other Parts

- *Adapter* -- Adaptor Plates. Multiple sizes are split by a vertical bar, listed from smallest to largest, e.g. "Adapter 50-12|25|37"
- *AE-FF* -- Fairings
- *AN* -- Nose Cone
- *AV* -- Fins and (Basic) Wings. Number is "realive wing area" x 10. (c.f. *Wing* and *XL*)
    - *AV-B* -- basic fins
    - *AV-D* -- 
    - *AV-R* -- 
    - *AV-T* -- 
    - *AV-U* -- deployable fins, e.g. AIRBRAKES or grid fins
- *C* -- Antennas (stock); Number is the antenna class, based on antenna power:

  | Class | Power | Limits          | Class | Limits          | Class | Limits        |
  |-------|-------|-----------------|-------|-----------------|-------|---------------|
  | C0    | 5k    | 0 - 5.5k        | C0+   | 5.5k - 249k     | C0++  | 249k - 449k   |
  | C1    | 500k  | 449k - 549k     | C1+   | 549k - 4.499M   |       |               |
  | C2    | 5M    | 4.499M - 5.499M | C2+   | 5.499M - 494M   | C2++  | 494M - 1.996G |
  | C3    | 2G    | 1.996G - 2.004G | C3+   | 2.004G - 14.96G |       |               |
  | C4    | 15G   | 14.96G - 15.04G | C4+   | 15.04G - 99G    |       |               |
  | C5    | 100G  | 99G - 101G      | C5+   | 101G - 996G     |       |               |
  | C6    | 1T    | 996G - 1.004T   | C6+   | 1.004T - 9.96T  |       |               |
  | C7    | 10T   | 9.96T - 10.04T  | C7+   | 10.04T - ...    |       |               |
  
- *CO* -- Omnidirectional Antennas (with RemoteTech)
- *CD* -- Directional Antennas (dishes) (with RemoteTech)
- *G* -- Hinge
- *HS* -- Heat Shield
- *I* -- Lights ("Illuminator")
- *IN* -- Intakes (like for air for jet engines)
- *KX* -- Solar Panels, surface/radial mounted (that don't require deployment) (c.f. *OX* and *SP*)
- *LT* -- Landing Legs/Landing Struts
- *LY* -- Landing Wheels (e.g. for planes)
- *Nb* -- Cargo-packed Parachutes
- *Nc* -- Radial-mounted Parachutes
- *Nk* -- Nosecone or Inline-mounted Parachutes; suffix with *D* for Drogue parachutes
- *OX* -- Solar Panels, requiring deployment (that can't be retracted) (c.f. *KX* and *SP*)
- (WIP) *RL* -- RSC blocks (or engines) running on Liquid Fuel + Oxidizer. Numbers as per *RV*. (c.f. *RV*) 
- (WIP) *RV* -- RCS blocks, Monopropellant Fuels. First value is thrust x10, followed by "x" and the (maximum) number of ports. Use a suffix of "A" for angled thrusters, and a suffix of "B" (for "booster") for higher than normal Isp (100s at Sea Level, 240s in Vacuum). (c.f. *RL*)
- *SEQ* -- Storage Containers. First value is diameter, and second combined value is slots/volume.
- *SM* -- Service Module
- *SP* -- Solar Panels, that can be deployed and retracted (c.f. *KX* and *OX*)
- *TB* -- Structural Tube/Structural Fuselage ("tube")
- *TD* -- (stack) decoupler (c.f. *TS*)
- *TF* -- Fuel Decoupler
- *TS* -- (stack) separater (c.f. *TD*)
- *TT* or *TY-RD* -- radial decoupler (*TT* us also used for launch supports)
- *Wing* -- Modular Wings (c.f. *AV* and *XL*)
- *WR* -- Reaction Wheels / Gyroscope
- *WZ* -- Tail Connector (the opposite of a "nose cone")
- *XL* -- large Wings and Control Surfaces (c.f. *AV* and *Wing*)
- *XR* -- Radiator Panel (radial mounted) (c.f. *XT*)
- *XT* -- Thermal Control System / Radiator Panel (extendable) (c.f. *XR*)
- *Z* -- Battery (flat mount)
- *Zs* -- Battery (inline stack)
- *ZZ* -- Capacitor (flat mount)
- *ZZs* -- Capacitor (inline stack)

## Contriubtions

If you would like to add support for an additional mod or have suggestions on
how to make the naming more consistent or intuitive, please open an [issue on
GitHub](https://github.com/minchinweb/ksp-CommunityPartsTitles/issues).

The code is managed on GitHub -->
<https://github.com/minchinweb/ksp-CommunityPartsTitles>
