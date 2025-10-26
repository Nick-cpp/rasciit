if you use arch by the way you can download this package from AUR ( yay -S rasciit )

compilation from source code:

step 1: you need installed gcc and git package ( Gnu Complier Collection )

$ sudo apt install gcc git - debian-based

$ sudo pacman -S gcc git - arch-based

step 2: download the project repository

$ git clone https://github.com/Nick-cpp/rasciit

step 3: compilation & installation

$ cd rasciit/

$ g++ -std=c++17 rasciit.cpp -o rasciit

$ sudo install -Dm755 rasciit "$pkgdir/usr/bin/rasciit"

step 4: program launch

$ rasciit
