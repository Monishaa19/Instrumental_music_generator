# Instrumental_music_generator
I tried to generate instrumental from mp3

workflow 

1.  create a python virtual environment with python 3.8.x
2.  install ffmpeg and fluidsynth and paste thier bin paths to system variables
3.  allow fluidsynth.exe ( available in its bin ) all read and execute permissions in properties>security tab
4.  run the index.ipynb alongside pip installing required dependencies
5.  make sure that you have a song.mo3 and soundfont.sf2 in your system


  These commands may be helpful sometime : 
 $env:Path += ";E:\fluidsynth download\bin" - add to path temporarily
 & "E:\fluidsynth download\bin\fluidsynth.exe" --version
