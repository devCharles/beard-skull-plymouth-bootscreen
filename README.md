# beard skull plymouth boot screen

This is a minimalist boot screen for use with plymouth


## installation

- clone this repo or download it
```bash
  git clone git@github.com:devCharles/beard-skull-plymouth-bootscreen.git
```
then you can move the whole folder in your plymouth theme folder.
```bash
  mv beard-skull-plymouth-bootscreen /usr/share/plymouth/themes
```
if you don't have plymouth installed checkout this [link](https://miguelmenendez.pro/en/articles/install-plymouth-debian-graphical-boot-animation-while-boot-shutdown.html)

once you have moved this folder you wolud be able to see a theme called 'charles' when you list the avialabe plymouth themes using
```bash
  plymouth-set-default-theme --list
```
now you can choose the charles plymouth theme using
```bash
  plymouth-set-default-theme charles
```
So that we can now save the changes typing
```bash
  update-initramfs -u
```
Now you can reboot your computer and enjoy your new elegant boot screen

## NOTES
if you have problems with plymouth installation or configuration or even saving changes please refer to this [link](https://miguelmenendez.pro/en/articles/install-plymouth-debian-graphical-boot-animation-while-boot-shutdown.html), there you will se a complete guide of installing and configuring plymouth in debian but is very similar in other linux distros

## Personalizing boot screen
You are able to change anything you want, if you want to change the background you would justa have to replace the' backgroung.png' with another image and the same with the logo changing the 'debian_logo.png' just concider that you have to keep the same name in order to keep it working.
