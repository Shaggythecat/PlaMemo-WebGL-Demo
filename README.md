# Plastic Memories WebGL Demo 『プラスティック・メモリーズ』Web体験版
This Project aims to preserve and make the Plastic Memories Costume & Interaction Mode Web Demo, and hopefully add in the dialouge text from the
Plastic Memories English Pacth released by the Isla Exacution Squad for PC and PS Vita.

The demo can be accessed here: https://shaggythecat.github.io/PlaMemo-WebGL-Demo/webgl/index.html

『プラスティック・メモリーズ』“ふれあい＆お着替えモード”のWeb体験版 (Japanese Title)

## Current Issues
The demo was made for Unity WebGL 5.4.0, and as far as I can tell the data file is unmoddable due to metadata checks and a lack of tools that
can mod WebGL games. Most likely global-metadata is located in the 'webgl.data' file, and one of the other files for the demo checks for global-metadata
at a specific offset.

When trying to scroll the game will throw an error but will continue to run.

## Fixed Issues
The game will not boot. -Files were misnamed on Mages' website

### Disclamers
This project is not associated with or authorized by MAGES./5pb. 
Plastic Memories is owned by MAGES./5pb.
