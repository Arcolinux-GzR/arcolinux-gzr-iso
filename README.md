Arcolinux-GzR
=============

Based on the work here 
           https://github.com/arcolinuxb
specically here
           https://github.com/arcolinuxb/arco-xfce

We are coming up with our own design persay changing things here and there to suit our likes and to make it as easy as possible to download setup and compile android. Not quite ready for primetime yet but it builds and boots. 
The heart of the project is still arco it'll just be as they are promoting built to our tastes.

Special thanks to the team for their assistance and give them all the support they deserve. 
-------------------------------------------------------------------------------------------------

Have a visit ....learn a lil
"Knowledge is Power"           
https://arcolinux.com/

--------------------------------------------------------------------------------------------------

To Build
========
Simply enough arco and ourselves will be doing most of the work all you'll have to do is

- To download:   git clone https://github.com/Arcolinux-GzR/arcolinux-gzr-iso to your home folder (Doesn't really need to be but i've had adverse affects at times if not)
- Give the folder ownership to root (Either right click on folder and give ownership or the alternative sudo chown -R root:root arcolinux-gzr-iso in terminal)
- As root navigate inside the archiso folder and type the command ./build.sh -v (Don't forget the -v which is verbose otherwise you'll be looking at a non moving terminal and we all like to see progression)

Once build completes the iso will be in your "out" folder 

- Reminder between every build the work and out folders must be removed. Easier and quicker through terminal with the rm -rf command

