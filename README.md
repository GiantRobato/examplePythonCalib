# examplePythonCalib
for Shannon

Usage
=====

In cmdline, go to the python sub-folder and run the following command:

``` bash
python calibrate.py
```

the output should look something like this:

``` bash
processing ../data/left06.jpg... ok
processing ../data/left02.jpg... ok
processing ../data/left09.jpg... ok
processing ../data/left07.jpg... ok
processing ../data/left13.jpg... ok
processing ../data/left14.jpg... ok
processing ../data/left04.jpg... ok
processing ../data/left11.jpg... ok
processing ../data/left03.jpg... ok
processing ../data/left12.jpg... ok
processing ../data/left01.jpg... ok
processing ../data/left05.jpg... ok
processing ../data/left08.jpg... ok

RMS: 0.196334505289
camera matrix:
 [[ 532.80990768    0.          342.49522241]
 [   0.          532.93344826  233.88792572]
 [   0.            0.            1.        ]]
distortion coefficients:  [ -2.81325825e-01   2.91151901e-02   1.21234424e-03  -1.40823847e-04
   1.54861062e-01]

Undistorted image written to: ./output/left06_chess.png_undistorted.png
Undistorted image written to: ./output/left02_chess.png_undistorted.png
Undistorted image written to: ./output/left09_chess.png_undistorted.png
Undistorted image written to: ./output/left07_chess.png_undistorted.png
Undistorted image written to: ./output/left13_chess.png_undistorted.png
Undistorted image written to: ./output/left14_chess.png_undistorted.png
Undistorted image written to: ./output/left04_chess.png_undistorted.png
Undistorted image written to: ./output/left11_chess.png_undistorted.png
Undistorted image written to: ./output/left03_chess.png_undistorted.png
Undistorted image written to: ./output/left12_chess.png_undistorted.png
Undistorted image written to: ./output/left01_chess.png_undistorted.png
Undistorted image written to: ./output/left05_chess.png_undistorted.png
Undistorted image written to: ./output/left08_chess.png_undistorted.png
```

Contact
=======
Dustin Mendoza (penguindustin@gmail.com)
