# FilmgrainPlus
Comparison of presets from Dogway's FilmGrainPlus script.

Cycled through all the current FilmGrain+ v2.4 Presets and saved each frame with AVSPmod's built in Image Save command.
Will do the same for a live action movie, once I decide which one to use.

Script used:

ffms2("Inno.mkv")

crop(2,22,-2,-22)

convertbits(16)

FilmGrainPlus(preset="Vision3 5219 500T")

converttorgb48(matrix="709:l")
