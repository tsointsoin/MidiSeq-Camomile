# MidiSeq-Camomile

To be used as a plugin with Camomile (https://github.com/pierreguillot/Camomile)

Requires at least Camomile v1.0.5 to work correctly

This sequencer is heavily based on the sequencer of the Roland SH-101, i.e: time data and note data are separated.
Usage: Put MidiSeq just before a midi plugin (synth, drum, whatever) and send some midi notes. The pitch of the notes is irrelevant, only the rhythm counts.
Basically, the sent notes serve as a trigger for the sequencer.

This was tested successfully in Bitwig v2.3.4
