# luci-theme-pink
A new Luci theme for LEDE/OpenWRT  
Argon is a clean HTML5 theme for LuCI. It is based on luci-theme-material and luci-theme-argon
Suitable for Openwrt 18.06.4 (for test) And Lean Luci (stable)  

The old version is still in another branch call old. If you need that you can checkout that branch.


## How to use

Enter in your openwrt/package/lean  or  other

```
git clone https://github.com/virualv/luci-theme-pink.git
make menuconfig #choose LUCI->Theme->Luci-theme-argon
make -j1 V=s
```
## ~~Install~~
```
opkg install https://github.com/jerrykuku/luci-theme-argon/releases/download/V1.3/luci-theme-argon_1.3-01-20191111_all.ipk
```

## Update log 20191109
1. Minimal background file size.
2. Automatically detect the number of background images.
3. Delete unused image and file.

## Screenshots
![pc1](/Screenshots/pc/pink1.png)
![pc2](/Screenshots/pc/pink2.png)




## Thanks to 
luci-theme-argon: git clone https://github.com/jerrykuku/luci-theme-argon.git
