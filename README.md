# Implementation of the Tomasi-Kanade method

## Demo

Tomasi-Kanadde method can reconstruct a 3D object from 2D observations.

For example, from the 2D points like below...

![](images/projected2d-1.png)
![](images/projected2d-2.png)
![](images/projected2d-3.png)
![](images/projected2d-4.png)

Tomasi-Kanadde method can reconstruct the 3D object.

![](images/reconstructed-1.png)
![](images/reconstructed-2.png)
![](images/reconstructed-3.png)

## Install dependencies

```
pip3 install -r requirements.txt
```

## Run reconstruction

1. Download [bunny.ply](https://raw.githubusercontent.com/opencv/opencv/master/samples/cpp/tutorial_code/viz/bunny.ply)
2. Run `run_reconstruction.py bunnpy.ply`

## Citation

```
[1] Tomasi, Carlo, and Takeo Kanade. 
"Shape and motion from image streams under orthography: a factorization method." 
International Journal of Computer Vision 9.2 (1992): 137-154.
```

```
[2] Timo Zinßer, Jochen Schmidt, and Heinrich Niemann. 
"Point set registration with integrated scale estimation." 
International conference on pattern recognition and image processing. 2005.
```