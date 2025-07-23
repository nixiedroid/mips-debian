# mips-debian
Debian for mips

IDK
##steps used

```sh
sudo apt update && sudo apt-get install binfmt-support qemu qemu-user-static debootstrap bzip2
mkdir debian-mips
cd debian-mips
git clone https://github.com/ZubairLK/mkdebianrfs
cp mkdebianrfs/mkdebianrfs.sh .
mkdir rootfs
sudo ./mkdebianrfs.sh mipsel wheezy rootfs


```


