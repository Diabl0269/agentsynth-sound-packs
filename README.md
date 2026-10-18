# AgentSynth sound packs

Free sound packs for the [AgentSynth](https://github.com/Diabl0269/agentsynth) Sampler. The app lists these packs in Settings > Sound packs and installs one when you ask it to (or when an AI song wants its sounds). You can also unzip a pack into the app's SoundPacks folder yourself (on macOS, ~/Library/Application Support/Agent Synth/SoundPacks).

Each pack is a release of this repository. The release holds the pack as a zip and a `.sha256` file that the app checks before installing. `index.json` lists every pack with its version, size, download link and checksum.

## Packs

| Pack | Instruments | Size | Licence |
|---|---|---|---|
| Core instruments | Upright piano, string section, trumpet, French horn, flute, clarinet, plucked double bass, electric guitar, acoustic drum kit | 33 MB download, 36 MB installed | CC0 1.0 (public domain) |
| Animals | Whale call, crow caw, owl hoot, frog call, wolf howl (one call each) | 0.3 MB download, 0.4 MB installed | CC0 1.0 (public domain) |

## Credits

The Core instruments pack is built from public-domain (CC0) recordings:

- **VSCO 2 Community Edition** by Versilian Studios: strings, brass, woodwinds and plucked bass. The upright piano is by Simon Dalzell of Ivy Audio.
- **Virtuosity Drums** by Versilian Studios: drummer Austin McMahon, recorded at Virtuosity Musical Instruments.
- **Black and Green Guitars** by Karoryfer Samples: recorded by Brian Wood.

The Animals pack is built from public-domain and CC0 field recordings:

- **Whale call**: humpback whale vocals (mother and calf), recorded by the US National Park Service in Glacier Bay, Alaska, June 2020 (public domain).
- **Crow caw**: "Hooded Crow: Cawing" by Mish7913 on Freesound (CC0).
- **Owl hoot**: "Great Horned Owl Duet at Canaveral Seashore" by felix.blume on Freesound (CC0).
- **Frog call**: a tree frog calling, by kvgarlic on Freesound (CC0).
- **Wolf howl**: one wolf howling in Alaska, by betchkal on Freesound (CC0).

Each animal recording was cut to one call, band-limited, cleaned of background noise and saved as FLAC with a one-shot SFZ that plays the call as recorded on every key.

For AgentSynth, the instrument recordings were trimmed, looped, level-matched and compressed to FLAC, and new SFZ maps were written for them. These packs are not the original libraries, and their makers do not endorse them. Each pack's `LICENSES/` folder has the original licence texts and a `SOURCES.md` that lists every file used and what was changed.

## Licence

The packs are CC0 1.0, like their sources. This repository's own files (README, index) are also CC0.
