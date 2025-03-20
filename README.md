# Mint-BGRT-Plymouth
A BGRT Plymouth Theme (Spinner) for Linux Mint.

After adding the spinner-mint to "/usr/share/plymouth/themes/"
run 
```
sudo update-alternatives --install /usr/share/plymouth/themes/default.plymouth default.plymouth /usr/share/plymouth/themes/spinner-mint/spinner-mint.plymouth 100

```
then select the theme spinner-mint via 
```
sudo update-alternatives --config default.plymouth
```
