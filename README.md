# winezgui-flathub
preparing winezgui for flathub

#### Get latest build from releases

#### Build
```
git clone https://github.com/fastrizwaan/winezgui-flathub.git
cd winezgui-flathub/WineZGUI
./install bundle
```

Install command:
```
flatpak --user remote-add --if-not-existsflathub https://flathub.org/repo/flathub.flatpakrepo
flatpak install flathub org.winehq.Wine
flatpak install --user io.github.fastrizwaan.WineZGUI_0.92.8_20230227.flatpak
```
