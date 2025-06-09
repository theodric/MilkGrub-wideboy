# 🥛 Milk Outside A Bag Of Milk Grub Theme

![Showcase](./preview.png)

### 🛠️ Manual Installation

```
git clone https://github.com/gemakfy/MilkGrub
sudo cp -r MilkGrub /boot/grub/themes/
```

```
sudo nano /etc/default/grub
```
Find the line `GRUB_THEME=` then change it to `GRUB_THEME="/boot/grub/themes/theme.txt"`

Then save the file.

### ✔️ Update the grub.
```
sudo grub-mkconfig -o /boot/grub/grub.cfg
```
