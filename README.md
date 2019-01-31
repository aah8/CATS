CATS: Convert Audio to Score
======
The purpose of this project is to generate sheet music from audio.
  
## Completed 

* Take "clean" audio file as input -- generated on computer so all pitches are perfect and there is no background noise. Recognize single notes and output names of those notes.
  * In MATLAB 
  ![matlab_spectrogram](https://user-images.githubusercontent.com/3399941/52029251-783c4200-24e0-11e9-843e-07b19b909dd5.png "MATLAB: Spectrogram with note names")
  * In Python 
  ![python_spectrogram](https://user-images.githubusercontent.com/3399941/52029249-783c4200-24e0-11e9-9e63-a4d85ec38202.png "Python: Spectrogram with note names")
 
* Recognize multiple notes
  * Harmonic removal algorithm

## Goals
  
* Recognize basic rhythms
  * Recognize complex rhythm
  * Recognize "dirty" audio files, taken from real recordings

## Requirements
 * Python 2.7
 * matplotlib
 * numpy

## FAQ
* Where are the examples? They are not included in the git repository. You have to run generateExamples.py to create them.
