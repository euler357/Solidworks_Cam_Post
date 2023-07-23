# SolidCam_Post
Solidworks SolidCAM Post Processor for Shapeoko 5 Pro using GRBL

I’m using Solidworks for Makers (Cockrum Studios is non-commercial) with SolidCAM to generate the g-code for this and it works well now. There were issues finding a SolidCAM post-processor that works without having to modify the gcode manually. When I tried the free one from Hawk Ridge Systems, it kept generating a G2 P2 command that is known not to be supported by GRBL so I had to delete that line each time. I tried this one from msbealo on GitHub but it kept sending the machine to Z -2 (maybe for some tool change for their particular machine). I went ahead and used the UPG-2 from Camworks to generate my own post processor that seems to work well so far. I posted it on GitHub here in case someone else can make use of it.


Details: 
https://cockrumstudios.com/cnc-banjo-fretboard-with-laser-engraved-mother-of-pearl-made-with-a-shapeoko-5-pro-and-omtech-polar-lase
