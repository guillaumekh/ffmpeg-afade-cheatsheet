# FFmpeg afade (audio fade filter) curves cheatsheet

The Ffmpeg afade filter is great but its documentation can be a little opaque if you have trouble figuring what a 'double-exponential sigmoid' curve is. This cheat sheet is here to help.

All curves were drawn in OS X's Grapher.app, with equations ported straight from [afade's code](https://github.com/FFmpeg/FFmpeg/blob/master/libavfilter/af_afade.c). The Grapher file is included in repo for reference.

| afade argument  | Meaning       | Curve         |
| --------------- |:-------------:|:-------------:|
| tri|triangular, linear slope (default)|![curve](https://raw.githubusercontent.com/guillaumekh/ffmpeg-afade-cheatsheet/master/images/tri.gif)
| qsin|quarter of sine wave|![curve](https://raw.githubusercontent.com/guillaumekh/ffmpeg-afade-cheatsheet/master/images/qsin.gif)
| hsin|half of sine wave|![curve](https://raw.githubusercontent.com/guillaumekh/ffmpeg-afade-cheatsheet/master/images/hsin.gif)
| esin|exponential sine wave|![curve](https://raw.githubusercontent.com/guillaumekh/ffmpeg-afade-cheatsheet/master/images/esin.gif)
| log|logarithmic|![curve](https://raw.githubusercontent.com/guillaumekh/ffmpeg-afade-cheatsheet/master/images/log.gif)
| ipar|inverted parabola|![curve](https://raw.githubusercontent.com/guillaumekh/ffmpeg-afade-cheatsheet/master/images/ipar.gif)
| qua|quadratic|![curve](https://raw.githubusercontent.com/guillaumekh/ffmpeg-afade-cheatsheet/master/images/qua.gif)
| cub|cubic|![curve](https://raw.githubusercontent.com/guillaumekh/ffmpeg-afade-cheatsheet/master/images/cub.gif)
| squ|square root|![curve](https://raw.githubusercontent.com/guillaumekh/ffmpeg-afade-cheatsheet/master/images/squ.gif)
| cbr|cubic root|![curve](https://raw.githubusercontent.com/guillaumekh/ffmpeg-afade-cheatsheet/master/images/cbr.gif)
| par|parabola|![curve](https://raw.githubusercontent.com/guillaumekh/ffmpeg-afade-cheatsheet/master/images/par.gif)
| exp|exponential|![curve](https://raw.githubusercontent.com/guillaumekh/ffmpeg-afade-cheatsheet/master/images/exp.gif)
| iqsin|inverted quarter of sine wave|![curve](https://raw.githubusercontent.com/guillaumekh/ffmpeg-afade-cheatsheet/master/images/iqsin.gif)
| ihsin|inverted half of sine wave|![curve](https://raw.githubusercontent.com/guillaumekh/ffmpeg-afade-cheatsheet/master/images/ihsin.gif)
| dese|double-exponential seat|![curve](https://raw.githubusercontent.com/guillaumekh/ffmpeg-afade-cheatsheet/master/images/dese.gif)
| desi|double-exponential sigmoid|![curve](https://raw.githubusercontent.com/guillaumekh/ffmpeg-afade-cheatsheet/master/images/desi.gif)
