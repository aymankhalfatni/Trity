# Trity
Trity is an advanced pentesting framework dedicated to everything from vulnerability testing to cryptography.

## Installation & Usage

In order to install this program, it is crucial that you are on a __Linux-based__ distro, preferably __Kali-Linux__ or __BackBox__.

First, `git clone`.

    git clone https://github.com/aymankhalfatni/Trity.git

Change directory, and then run the installer script (Must be root or have superuser permissions):

    cd path/Trity
    sudo python install.py

The `install.py` script will install of the necessary dependencies for you. Other platforms will be supported in the future.

Once finished, execute with:

    trity


### FAQ
#### What if I get ImportError: no module named x
##### Make sure you have Internet and try manually installing it by executing: pip install x (whatever x is)
---------------------------
#### Will Trity work on Windows?
##### No
---------------------------
#### Will Trity work on Mac OSX
##### I am not sure because there is no way for me to test it, but if someone would like to and told me the results I would greatly appreciate it :-) Except that you would have to install the modules manually.
