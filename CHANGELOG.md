# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## Unreleased

- 'Super Instrument Rack' could be added on default tracks for PERCUSSION, KEYS etc - see [Ableton 11 Create a Drum Selector in Drum Rack on YouTube](https://www.youtube.com/watch?v=k6o83jFjiPo&list=PL6f18ohG-J_LVkv0bq7N-yqpMhJm7pLCl), [The Last Drum Rack You'll Ever Have to Make on YouTube](https://www.youtube.com/watch?v=8TO3z8LtP5U&list=PL6f18ohG-J_LVkv0bq7N-yqpMhJm7pLCl) and [Super Instrument Rack Tutorial on YouTube](https://www.youtube.com/watch?v=PwLmS1dAyNg&list=PL6f18ohG-J_J764vWhJJJXiDjYaNBt8I3)
- For the PERCUSSION group should we add further default tracks for the common drum elements, the Kick, Snare etc and create a 'Super Instrument Rack' for each? Could also set these tracks up with set panning so we don't have to adjust each time
- MIDI effects could be added to the KEYS group - MIDI effects like arpeggiators, chord generators and note repeaters can help you generate new musical ideas

## [1.1.0] - 2023-03-25

### Added
- Additional Utility added to all vocal tracks and armed by default, this is to be used for automation purposes as the current Utility at the end of the vocal rack is already mapped to the rack and in use
- Key mapped Previous Locator, Next Locator and Add Locator as per [this tutorial by Patches](https://patches.zone/key-mapping-in-ableton-live-tutorial)
- Added an EQ and Drum Buss to the Percussion group
- Added an EQ and Glue Compressor to all other groups
- 'MISC' group now has a couple of empty tracks for placing any backup audio or MIDI

### Changed
- Set the Utility on each track to armed by default
- All reference tracks are now armed, when adding reference tracks place sequentially in the timeline so that they don't overlap
- Additional Limiter added to the Master Buss
- Default file description changed from 'Song Title Project' to 'Song Title - Ableton Live Project'
- Updated some of the info text on individual tracks

### Deprecated
- Deleted all the blank tracks at the end of each coloured group as they take up space and not everybody uses them
- Deleted a bunch of unnecessary vocal groups, the only groups in use are now 'Lead' and 'Backing'

### Fixed
- Added the Analyser Rack to the Master and key mapped the same keys so it's now possible to toggle between the master and reference track using the backslash key
- The first filter on the EQ Eight was set to high shelf instead of low cut by mistake, have changed it on all tracks
- Updated the EQ in the Master Bus Rack as it wasn't updated with the new version last time

## [1.0.0] - 2022-11-10

### Added

- Utility called 'Temp +6 dB' added to Master, see [How to Get a Perfect -6 dB Mixdown With Gain Staging on YouTube](https://www.youtube.com/watch?v=nM3cjFmjOi0&list=PL6f18ohG-J_J764vWhJJJXiDjYaNBt8I3)
- Macro added to record button, press ‘r’ to punch in and out of recording

### Changed

- All tracks reduced to a default of -16 dB to account for the addition of the Utility on the Master
- Default EQ Rack updated

### Fixed

- Auto Filters on the Analyser Rack were both set to Lowpass, have changed one to High-pass
- Revised the numbering system to adhere to [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
- v1.0 and v1.1 renamed as v0.0.1 and v0.0.2

## [0.0.2] - 2022-04-06

### Removed

- Youlean Loudness Meter plugin removed so template should now open without any error message 

## [0.0.1] - 2021-12-23

### Added

- First public release
