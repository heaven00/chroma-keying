Background
==========

Chroma Keying/ Keying / Digital Matting, basically means replacing  the current background with another background. This is generally a hard problem because of the number of unknowns thus we use a permanent color as background. Thus this also got the name as Blue screen matting or Green screen Matting.

The reason to choose green/blue for live chroma keying is because of the contrast it has to the skin color, but it does cause a problem if the person infornt is wearing the same color as the background. 

I have tried a very naive implementation just to see how it works out, and it did not work out very well I must say. The problem with computer vision is that a simple thing as lighting can affect  a lot. I was able to get bearable results with static image with a blue background. The boundary of the figure in the middle came out to be blurred, but live chroma keying has its own problems :(


How To Use
==========

Even though you can check my results by simply doing,

        python run.py
        

I did not try out more stuff around this, not enough motivation and I am a bit lazy. You will need to have OpenCV running on your machine. Just follow the instructions under requirements.

REQUIREMENT
-----------


You need python 2.7, opencv, numpy & pandas running perfectly on your machine.

For py 2.7, numpy, pandas its easier to just install Anaconda if you are on Windows, if you are on linux well I trust you already know what to do. :) :fingers_crosses:

Now, to setup opencv get a [prebuilt version](http://www.lfd.uci.edu/~gohlke/pythonlibs/#opencv) and install it using wheel.

If you don't have wheel do

    pip install wheel


 and then install the downloaded python version using

    pip install path/to/the/file.whl
