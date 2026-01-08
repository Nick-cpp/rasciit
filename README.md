if you use arch by the way you can download this package from AUR ( yay -S ratyper )

compilation from source code:

step 1: you need installed gcc and git package ( Gnu Complier Collection )
```
$ sudo apt install gcc git - debian-based

$ sudo pacman -S gcc git - arch-based
```
step 2: download the project repository
```
$ git clone https://github.com/Nick-cpp/ratyper
```
step 3: compilation & installation
```
$ cd ratyper/

$ g++ -std=c++17 ratyper.cpp -o ratyper

$ sudo mv ratyper /usr/bin/ratyper
```
step 4: program launch
```
$ ratyper
```
Use ~/.config/ratyper/ratyper.conf to create ASCII arts to type
