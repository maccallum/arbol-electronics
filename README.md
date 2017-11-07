# El &#193;rbol de la noche triste

## Requirements
* Max/MSP >6
* [odot](https://github.com/CNMAT/CNMAT-odot.git)
* A MIDI fader box such as the Behringer BCF2000, Korg Nano, etc.
* A sound card

## Operation
1. Open arbol.maxpat.
1. Configure Max's audio system for your sound card.
1. Configure the patch for your MIDI fader box---consult [p bcf2000] for an example.
1. Turn on the dac~.
1. the subpatch [vla_tuner] may be used to help the performer tune to the scordatura.
1. Enter the section number you wish to start from.
1. The space bar advances to the next section, escape stops.
1. The 6 left-most faders control the different sounds throughout the piece. They are not documented in the score. Generally, they can be balanced and then adjusted throughout the performance.
