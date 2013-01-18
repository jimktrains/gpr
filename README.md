cat dat | perl test.gnuplot | gnuplot > output.png && gthumb output.png

Where dat contains:
(key):(val)

Right now, val needs to be [1,5] but it wouldn't be hard to fix that
