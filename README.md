**LAST UPDATED:** 	2018/12/18

---

# Information:

While there is a 'minipro-git' package on Arch User Repository (AUR), its PKGBUILD is not updated since circa 2016. This is the PKGBUILD necessary for building the latest version of the MiniPro TL866A and TL866CS for Arch Linux to be installed with pacman.

The following might interest you:

* [MiniPro open source project page](https://gitlab.com/DavidGriffith/minipro)
* [MiniPro open source AUR package](https://aur.archlinux.org/packages/minipro-git)

# Instructions:

1. Do a `$ git clone https://github.com/jfcandidofilho/minipro-aur` in the place of your preference

2. Proceed normaly like with any other AUR package you wish to install:

	```shell
	$ cd minipro-aur
	$ makepkg
	# pacman -vU minipro-aur-*.xz
	```

3. Profit


**NOTE:** If the original maintainer make the 'minipro-git' up-to-date, you can just go to AUR. If not, stick here! :)
