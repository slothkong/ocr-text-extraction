# OCR Text Extraction

I am not actively supporting this script. It was just an experiment.

Processes an image to extract the text portions. Primarily
used for pre-processing for performing OCR.

Implemented in `Python 2` using `OpenCV`.

Based on the paper "Font and Background Color Independent Text Binarization" by
T Kasar, J Kumar and A G Ramakrishnan
http://www.m.cs.osakafu-u.ac.jp/cbdar2007/proceedings/papers/O1-1.pdf

Copyright (c) 2012, Jason Funk <jasonlfunk@gmail.com>

**NOTE**: Changing the value of the `DEBUG` flag in the script will save 
a series of intermediate preprocessing results and display stats
of which pixels are thresholded.
