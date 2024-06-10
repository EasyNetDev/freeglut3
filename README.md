# freeglut3
freeglut3 trasitional package to libglut3.12

Some old programs, like FlyWithLua, is using old lib /usr/lib/x86_64-linux-gnu/libglut.so.3. Because newer version of Debian is moving to libglut3.12 the new lib is called /usr/lib/x86_64-linux-gnu/libglut.so.3.12. This package is creating a symlink /usr/lib/x86_64-linux-gnu/libglut.so.3 to /usr/lib/x86_64-linux-gnu/libglut.so.3.12 and is not necessary to install freeglut3 package.
