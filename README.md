# cocos2dx-programers-guide-sample
this is a linux build for cocos2d-x programers guide sample.

The original sample repo doesn't come with Linux build. It's a bit shame they don't support it.
All I did was just set up the build so we can build and run linux binary on our beloved linux machine.

And you need cocos2d-x 3.14.1 most of all since that is what I've used to create a project!

To build it,

a) setup cocos2d-x as documented on their web site.
b) clone this report and cd into it.
c) cocos compile -c -p linux -m release
   
   or
   cd linux-build && make
   
Guess it is really a good sample to learn cocos2d-x on Linux.
Happy coding until next time!
