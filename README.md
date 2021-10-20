# Modder's Best Friend aka MBF21 v1.4
MBF21 is the next step in the classical / conservative feature progression from doom to boom to mbf. The project has these goals:

- Fix bugs and miscellaneous issues in mbf.
- Maintain backwards compatibility with the features of mbf.
- Make it easy to modify previously hard-coded elements of the engine.
- Add "low hanging fruit" features for maps and dehacked that are in demand.
- Make changes that are easy to adapt into existing source ports and tools.
- Maintain the classical / conservative flavour of boom / mbf.

### Directory

The specification is available in different formats to suit different audiences:

- [Full specification](./docs/spec.md).
- Specification for [developers](./docs/developer_spec.md).
- Specification for [level editors](./docs/level_editor_spec.md).
- OPTIONS lump [examples](./docs/options.md).

### Version History
- v1.4
  - Added comp_reservedlineflag option (ignore extended flags when set).
- v1.3
  - Added comp_voodooscroller option (fix voodoo doll speed on slow scrollers).
- v1.2
  - Added FULLVOLSOUNDS thing flag, which uses full volume for the see / death sounds.
- v1.1
  - Scrolling specials 1024-1026 now divide the offsets by 8 when calculating the speed, to allow for more fine-grained control.
- v1.0
  - Original release

##### About the Project
The formal effort officially began in [March 2021](https://www.doomworld.com/forum/topic/120616-lets-talk-about-mbf-a-new-complevel/). Following extensive discussions and investigations, kraflab and Xaser delivered the first implementation of the specification in [dsda-doom](https://github.com/kraflab/dsda-doom) two months later.

##### Collaborators
- AlexMax
- Altazimuth
- dewsome
- Keyboard_Doomer
- kraflab
- MTrop
- skillsaw
- Xaser
