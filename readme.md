# Notation for Live coding 
- in order to play e.g. tidal cycles live with pre-written material or record a written track it might be helpful to have some notation of the coarse temporal sequence (apart from experimentation)
- this is an experiment on some notation
- file naming ".nan" short for "not a notation"

## requirements
- note instruments played with its key parameters
- note temporal sequence (start and end of instruments/channels, pauses and timing)
- make sequence easyly visible
- make notation work in paper/handwritten and text-editor format

## elements
- channel number as int "1, 2, 3, .."
- turn on/off chanel as "+" and "="
- params and values by their names as string and numbers
- temporal flow by signs for 
  - short pause "##"
  - imediate follow up "->"
  - group/temporal proximity/musical proximity by tabbed indentation (only used in conjunction with "##" and "->"
  - large pause or hush/end of track by "[ # ]" or "<-->" (test!)
  - maybe use blank lines for visual clarity
  
  
## example

[channel/orbit | I/O  | params | value/comment]

| 1  |  + | gain | 0.4 >> 0.7 fade in

| ## |	2 |  +   | fast 2 | not used

| -> |  3 |  =   | gain   | 0.4 >> out

<-->

## open questions
- [ ] can this notation work as a meta language which can be used as a makro to autmatically play a track?
- [ ] can I find variants of the notation which are more graphic -> such as graphb theory notation??

## NEXT steps
- [ ] test with GCB tracks (live and recording)
