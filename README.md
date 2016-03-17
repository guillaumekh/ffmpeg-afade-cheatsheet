# FFmpeg afade (audio fade filter) curves cheatsheet

The Ffmpeg afade filter is great but its documentation can be a little opaque if you have trouble figuring what a 'double-exponential sigmoid' curve is. This cheat sheet is here to help.

* tri (triangular, linear slope (default))

![capture_rename](https://raw.githubusercontent.com/guillaumekh/ffmpeg-afade-cheatsheet/master/tri.gif)

* qsin (quarter of sine wave)

![capture_rename](https://raw.githubusercontent.com/guillaumekh/ffmpeg-afade-cheatsheet/master/qsin.gif)

* hsin (half of sine wave)

![capture_rename](https://raw.githubusercontent.com/guillaumekh/ffmpeg-afade-cheatsheet/master/hsin.gif)

* esin (exponential sine wave)

![capture_rename](https://raw.githubusercontent.com/guillaumekh/ffmpeg-afade-cheatsheet/master/esin.gif)

* log (logarithmic)

![capture_rename](https://raw.githubusercontent.com/guillaumekh/ffmpeg-afade-cheatsheet/master/log.gif)

* ipar (inverted parabola)

![capture_rename](https://raw.githubusercontent.com/guillaumekh/ffmpeg-afade-cheatsheet/master/ipar.gif)

* qua (quadratic)

![capture_rename](https://raw.githubusercontent.com/guillaumekh/ffmpeg-afade-cheatsheet/master/qua.gif)

* cub (cubic)

![capture_rename](https://raw.githubusercontent.com/guillaumekh/ffmpeg-afade-cheatsheet/master/cub.gif)

* squ (square root)

![capture_rename](https://raw.githubusercontent.com/guillaumekh/ffmpeg-afade-cheatsheet/master/squ.gif)

* cbr (cubic root)

![capture_rename](https://raw.githubusercontent.com/guillaumekh/ffmpeg-afade-cheatsheet/master/cbr.gif)

* par (parabola)

![capture_rename](https://raw.githubusercontent.com/guillaumekh/ffmpeg-afade-cheatsheet/master/par.gif)

* exp (exponential)

![capture_rename](https://raw.githubusercontent.com/guillaumekh/ffmpeg-afade-cheatsheet/master/exp.gif)

* iqsin (inverted quarter of sine wave)

![capture_rename](https://raw.githubusercontent.com/guillaumekh/ffmpeg-afade-cheatsheet/master/iqsin.gif)

* ihsin (inverted half of sine wave)

![capture_rename](https://raw.githubusercontent.com/guillaumekh/ffmpeg-afade-cheatsheet/master/ihsin.gif)

* dese (double-exponential seat)

![capture_rename](https://raw.githubusercontent.com/guillaumekh/ffmpeg-afade-cheatsheet/master/dese.gif)

* desi (double-exponential sigmoid)

![capture_rename](https://raw.githubusercontent.com/guillaumekh/ffmpeg-afade-cheatsheet/master/desi.gif)

Source: https://github.com/FFmpeg/FFmpeg/blob/master/libavfilter/af_afade.c
