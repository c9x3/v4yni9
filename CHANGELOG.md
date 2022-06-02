<!-- Please note that later versions of Hydrogen should normally include features from earlier versions of Hydrogen (if the features are still relevant.) -->

# Hydrogen v1.6.5:

- One version of Hydrogen to rule them all! Hydrogen online now contains fallback dependencies so Hydrogen offline is no longer needed. Unless you want to host the dependencies another way, Node.js IS still required for offline use.
- Continuity update. Most of the body section for Hydrogen v1.0 and the latest version of Hydrogen should now be the same. (This excludes the UI changes from versions of Hydrogen higher than v1.0.)
- Node.js has been updated to the latest version and also has more information about the Node.js project. 
- Updated readme for dependencies. 

# Hydrogen v1.6.4:

- Updated GUI. 
- Created new HTML file for Hydrogens project information.
- Added new HTML file for Hydrogens project information to the GUI for user convenience. 

# Hydrogen v1.6.3:

- Hydrogen now hosts its own dependencies! 
- Updated licensing site. 
- Updated change-log site.
- Updated license.
- Updated change-log.

# Hydrogen v1.6.2:

- Updated change-log structure to be easier to read.
- Corrected spelling mistakes with Hydrogen v1.6.1. 
- Re-added Youtube tutorial for people who need a more visual approach to learning Hydrogen! :)
- Updated Hydrogen to use more realistic maximum values. When using high values, it MAY break the URL. 
- e.tempoMin=1.
- e.tempoMax=999.
- e.maxEnvelopeCount=75.
- e.pitchChannelCountMax=75.
- e.noiseChannelCountMax=75.
- e.modChannelCountMax=75.

# Hydrogen v1.6.1:

- De-cluttered the GUI so you have a lot less distraction. 
- Considering removing a css, "dependency" that may or may not be useful. 

# Hydrogen v1.6:

- Hydrogen is now based upon Jummbox 2.5. 
- In addition, Hydrogen now has some new themes for you to enjoy! :)

# Hydrogen v1.5:

- Updated Hydrogens GUI to make getting involved with the Hydrogen project easier for the user. 

# Hydrogen v1.4:

- Updated offline-instructions within Hydrogen GUI. 

# Hydrogen v1.3:

- Updated readme. 
- Updated changelog. 
- Both, "HydrogenOffline.tar.gz" and, "NodeServer.tar.gz" have been split up so that you don't have to download the, "NodeServer.tar.gz" file each time you want to update the Hydrogen offline. 
- Added changelog to Hydrogen GUI. 
- Attempt at keeping offline support for earlier versions of Hydrogen. 

# Hydrogen v1.2:

- Updated license. 
- Updated readme.
- Updated html for online and offline versions of Hydrogen.

# Hydrogen v1.1:

- Hydrogen has been updated to include Jummbox v2.5 and its new GUI elements. This however does NOT include the new themes as getting these themes working for Hydrogen is largely a work in progress effort. 

- e.maxEnvelopeCount=999.

# Hydrogen v1.0 (Jummbox 2.4) and under:

- TempoMin=1.

- TempoMax=999.

- PitchChannelCountMax=999.

- NoiseChannelCountMax=999.

- ModChannelCountMax=999.

# No longer relevant: # 

## Hydrogen v1.1:

- e.patternInstrumentCountMax=999

- e.layeredInstrumentCountMax=999.

Reason:

- The graphical user interface becomes very unusable when more than the default amount of Max Instruments are used. 

Solution: 

- Use more channels. 

## Hydrogen v1.0 (and under:)

- InstrumentsPerChannelMax=999 

Reason:

- In Jummbox 2.5, "InstrumentsPerChannelMax=" is no longer relevant (that I am aware) because of the graphical user interface overhaul.

Solution: 

- Either use older versions of Hydrogen (1.0 and under) or use more channels. 

# Miscellaneous:

- Working offline support through Node.js! 

- De-cluttered code. :) 

