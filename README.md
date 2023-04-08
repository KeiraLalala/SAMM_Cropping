# SAMM_Cropping
This project is used to crop the micro-expression samples from the SAMM dataset by using the Pytorch face-alignment and Local Weighted Mean(LWM) transformation.

There is one Example file (**Example_face_alignment.ipynb**) to show how the library detect the 68 facial point, and a file that crop samples of one video (**LWM_crop.ipynb**)

Beside, I also tried to use the Dlib to do the normalization work without LWM, but the performance is not so ideal.

## One way to quick install the Dlib in anaconda:
```
pip install CMake
pip install Boost
pip install Dlib
```

This is the most convenient way that I tried to install the Dlib successfully

## Citation
```
@inproceedings{bulat2017far,
  title={How far are we from solving the 2D \& 3D Face Alignment problem? (and a dataset of 230,000 3D facial landmarks)},
  author={Bulat, Adrian and Tzimiropoulos, Georgios},
  booktitle={International Conference on Computer Vision},
  year={2017}
}
```
```
@Article{Davison2018,
  author  = {Davison, Adrian K. and Lansley, Cliff and Costen, Nicholas and Tan, Kevin and Yap, Moi Hoon},
  title   = {SAMM: A Spontaneous Micro-Facial Movement Dataset},
  journal = {IEEE Transactions on Affective Computing},
  year    = {2018},
  volume  = {9},
  number  = {1},
  pages   = {116-129},
  doi     = {10.1109/TAFFC.2016.2573832},
}
```

