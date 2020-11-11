# Computational Photography
Goal: Learn more about computational photography
Goal: Use computational photography on at least a simple example

## Specific Interests
Ben:
Upon starting my primary interest is in low light work and maybe HDR with wider brackets. 
I like panoramas, but I am not sure if there is a need due to existing software and wide angle hardware being in our pockets, not telephoto.
Maybe the better set of techniques would be astrophotography based, but the last time I tried that I couldn't get any software to work across Windows, Mac or Linux.

# Notes
What would be a good aberivation for "Computational Photography"? CP brings forth unpleasent words.

# Background Material

## DP Review - What is CompPhoto?
[DP Review What is CompPhoto](https://www.dpreview.com/articles/9828658229/computational-photography-part-i-what-is-computational-photography)

Stacking is the base operation for everything. 

[Epsilon Photography]https://en.wikipedia.org/wiki/Epsilon_photography)
This is the idea that you take lots of pictures and change parameters so that you have flexability later to combine. 
Think about changing the apature while taking a bunch of pictures.

Applications are: "focal stack photography,[clarification needed] High dynamic range (HDR) photography, lucky imaging, multi-image panorama stitching and confocal stereo."
These are exciting items to me.
The HDR is very useful due to the limitations of digital sensors.
Lucky imaging is a technique that I know from Astrophotography where they record video of the object and simply take the frames that have the least amount of atmospheric distortion and use those.

As these techniques can require a great many images "Compressive Epsilon Photography" takes fewer images and the intermediate images are generated.

"A modern smartphone camera starts taking photos as soon as you open it. 
Which is logical, since it should show the image on screen somehow. 
But in addition to that, it saves high-resolution images to its cyclic buffer and stores them for a couple more seconds."

And at the end lifts some content from the Google Pixel blog posts.

## Google Pixel blog posts
[HDR+](https://ai.googleblog.com/2018/02/introducing-hdr-burst-photography.html)

[Associated Dataset to HDR+](http://hdrplusdata.org/dataset.html)

[Intro to Night Sight](https://www.blog.google/products/pixel/see-light-night-sight/)

[Night Sight detail](https://ai.googleblog.com/2018/11/night-sight-seeing-in-dark-on-pixel.html)

## Marc Levoy
Marc Levoy is amazing in that he changes areas every decade because he solved the big problems. He lead the photography team at Google Pixel and has a good deal of content on the web.

[Publications](https://scholar.google.com/citations?user=gbVh3PEAAAAJ&hl=en)

[Curated list of Publications](http://graphics.stanford.edu/~levoy/publications.html)

[Google Lectures on Digital Photography](https://www.youtube.com/playlist?list=PL7ddpXYvFXspUN0N-gObF1GXoCA-DA-7i)

[Slides from Technical Talks](http://graphics.stanford.edu/talks/)

[Course via Google](https://sites.google.com/site/marclevoylectures/)

TODO: Go through above links and pull out specific items to be reviewed. Place in sub-sub-section.

# Courses

## Udacity
[Udacity version of GT class (I think)](https://www.udacity.com/course/computational-photography--ud955)

## Northwestern
[Northwestern](https://www.mccormick.northwestern.edu/computer-science/academics/courses/descriptions/331.html)

### REQUIRED TEXTS 
Computational photography is a new and exciting field. No standard texts on this topic are available yet. Optional texts include:

• Forsyth and Ponce. Computer Vision: A Modern Approach. Pearson. 2002.

• Richard Szeliski. Computer Vision: Algorithms and Applications. Springer. 2010.

• Berthold K. P. Horn. Robot Vision. The MIT Press. 1986.

• R. Hartley and A. Zisserman. Multiple View Geometry in Computer Vision, Cambridge Press, Cambridge, UK, 2000.

### DETAILED COURSE TOPICS

• Image formation: pinhole camera, lens camera model, sensor noise

• Lenses: focusing, zoom, field of view, aberrations

• Color: color filter arrays, demosaicking

• Radiometetry and photometry

• Metering: autofocusing, auto-exposure

• Image processing: Fourier Transform, blur, convolution

• Camera projective modeling and calibration

• Depth estimation: stereo matching, photometric stereo, depth from defocus

• Material acquisition: BRDF acquisition, multispectral/hyperspectral capture

• High dynamic range imaging

• Light field capture and rendering

• Computational illumination: image relighting, light transport

• Compressive imaging: super-resolution, compressive video/light field capture

• Novel displays: 3D displays, HDR displays

## CMU
[CMU](http://graphics.cs.cmu.edu/courses/15-463/)
There are some slides, assignments ** This is running NOW! **
There are recorded lectures, but they are behind a CMU login screen

The pre-reqs include image and video processing, which requires Signals and Systems which requires Fundamentals of Signal Processing. 
So let's not get hung up in that math stuff, and see what we can do before we figure out what math to learn.
I am wonder if addition and division are going to be key components with maybe some rotation.

### Textbooks
Readings will be assigned primarily from relevant papers. Readings will be posted at the last slide of each lecture.
Additionally readings may be assigned from the following textbooks, which can also be useful references in general. 
All of them are available online from the CMU library:

Computer Vision: Algorithms and Applications, by Richard Szeliski.

Multiple View Geometry in Computer Vision, by Richard Hartley and Andrew Zisserman.

Computer Vision: A Modern Approach, by David Forsyth and Jean Ponce.

Foundations of 3D Computer Graphics, by Steven Gortler.

Digital Image Processing, by Rafael Gonzalez and Richard Woods.

Photography, by Barbara London and John Upton




# Practical (Programs and Programming)

It looks like there is a mix of approaches to actually do.
The projects that use Python and OpenCV look appealing from a easy to install standpoint, as well as a likly ease of use. 
One project was based on C++ and I am not doing that.
