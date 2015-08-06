arm-linux-androideabi-5.1-sabermod

UBUNTU
==============================================================================

sudo apt-get install libcloog-isl-dev libcap-dev texinfo

On Ubuntu 14.04+ you have to link a isl library using root:
sudo ln -s /usr/lib/x86_64-linux-gnu/libisl.so.10.2.2 /usr/lib/x86_64-linux-gnu/libisl.so.13

Install library files in the extras folder.