
Processing fadecandy perlin fire
--------------------------------

Cmd Line
--------

rem Windows

    path %PATH%;D:\Apps\processing-3.5.4
    processing-java.exe --sketch=%cd%\Processing_fadecandy_perlin_fire --run exit=60

\# raspi (vnc)

    processing-java --sketch=./Processing_fadecandy_perlin_fire --run exit=60

\# raspi (ssh i.e. headless)

    xvfb-run processing-java --sketch=./Processing_fadecandy_perlin_fire --run exit=60


Thanks to
---------

Luis Gonzalez for Perlin Noise Fire Effect
https://www.openprocessing.org/sketch/112601/#
