                                                       ☣️ **Spanner Machine** ☣️ 


# ⚒️ Hacking Environment Based on Openbox ⚒️

---

<p align="center">
<a href="https://github.com/tmcybers/a01-injection_exploit-owasp-top-10"><img src="https://img.shields.io/badge/python-3-yellowgreen">
<a href="https://github.com/tmcybers/a01-injection_exploit-owasp-top-10"><img src="https://img.shields.io/badge/downloads-34-green">
<a href="https://github.com/tmcybers/a01-injection_exploit-owasp-top-10"><img src="https://img.shields.io/badge/releases-1.0-red">
<a href="https://github.com/tmcybers/a01-injection_exploit-owasp-top-10"><img src="https://img.shields.io/badge/contributors-1-orange">
<a href="https://github.com/tmcybers/a01-injection_exploit-owasp-top-10"><img src="https://img.shields.io/badge/open%20issues-0-blue">
<a href="https://github.com/tmcybers/a01-injection_exploit-owasp-top-10"><img src="https://img.shields.io/badge/discussions-1-orange">
<a href="https://t.me/+l5WYQySOL-0yMDQ0"><img src="https://img.shields.io/badge/chat-online-brightgreen?style=plastic&logo=telegram">
<a href="https://twitter.com/tmcybers"><img src="https://img.shields.io/badge/folow-tmcyber-blue?style=plastic&logo=twitter">
<a href="https://ioc.exchange/@tmcyber"><img src="https://img.shields.io/badge/folow-tmcyber-blue?style=plastic&logo=mastodon">
<a href="https://tmcybers.github.io/blog"><img src="https://img.shields.io/badge/Write%20ups-Blog-red?style=plastic&logo=hackthebox">
  <a href="https://wakatime.com/@tmcyber"><img src="https://img.shields.io/badge/Developer-Blog-orange?style=plastic&logo=python">
<a href="https://tmcybers.github.io/Donate"><img src="https://img.shields.io/badge/support-tmcyber-blue?style=plastic&logo=donate">
<a href="https://ko-fi.com/tmcyber"><img src="https://img.shields.io/badge/Support%20me-Ko--Fi-brightgreen?style=plastic&logo=ko-fi">

</p>

* 🗿 My custom of what y use every day for 💉 hacking and threat hunting 🔫 is based on Debian/Parrot Os ↪️ Openbox tilling window*

                                              ↘️↘️↘️↘️↘️↘️↘️`Why openbox`↘️↘️↘️↘️↘️↘️↘️

### 🕶️ Openbox is the most lightweight tilling window [openbox offers you the freedom 🕶️ to work with shortcuts or mouse, your choice is your choice 🏆

  
              ☢️ `Never automate the installation of this type of customs can be broken depending on your system dependencies` ☢️
  
  
  
  ## Instalation proceed
```
sudo apt update
sudo parrot-upgrade
sudo apt install openbox
sudo apt install obconf lxinput
sudo apt install snapd
sudo snap install lsd
sudo apt install bat
sudo apt install kitty
sudo apt install rofi

```
  
 ## Wallpaper manager
  
```
sudo apt install nitrogen
  
```
  
## Manger for Menu/Custom Themes and Icons
  
```
sudo apt install lxappearance lxappearance-obconf

```
  
## Wallpapers for Nitrogen

[positron-dream nord themes]( https://imgur.com/a/qrgtyDU)
  
  
# Important Step! we are going to create the `autostart` , so that everything starts at startup.
---

##### If just in case some of the directories you have, then go to the next level.
  
```
cd /home/tmcyber/.config
mkdir openbox
cd openbox
touch autostart 
geany autostart
  
```
### This is like mine is, it like an example, will add more later.
  
```
nitrogen --restore &

picom &

setxkbmap us
  
```
  
* `In this folder you must also find the rc.xml file, which is the shortcuts file that we are going to tune with our personal shortcuts later on`
  

## Polybar Tun!!ing
  
[Polybar-themes](https://github.com/adi1090x/polybar-themes)
 
```
git clone --depth=1 https://github.com/adi1090x/polybar-themes.git
cd polybar-themes
chmod +x setup.sh
  
```
  
### Run setup.sh and select a style
``` 
 ./setup.sh
```
```
[*] Installing Polybar Themes...

[*] Choose Style -
[1] Simple
[2] Bitmap

[?] Select Option : 1

[*] Installing fonts...
[*] Creating a backup of your polybar configs...
[*] Successfully Installed.
```
### Launch the bar
*To launch the bar with the selected theme, Just...*

Open the terminal and enter the following command

```
bash ~/.config/polybar/launch.sh
```

### Usage : launch.sh --theme

Available Themes :
--blocks    --colorblocks    --cuts      --docky
--forest    --grayblocks     --hack      --material
--panels    --pwidgets       --shades    --shapes

### Now, select your theme and launch the bar
  
```
bash ~/.config/polybar/launch.sh --hack
```
  
#### Im using --forest as theme
  
**Paste this comand into `autostart` that we have create at the start.
  
  

  
  
  
