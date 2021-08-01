## template
  
template wallpapers  
  
Automatic install/update:
  
```shell
bash -c "$(curl -LSs https://github.com/wallpapermgr/template/raw/main/install.sh)"
```
  
Manual install:
  
```shell
git clone https://github.com/wallpapermgr/template "$HOME/.local/share/wallpapers/template"
```
  
Manual update
  
```shell
git -C "$HOME/.local/share/wallpapers/template" pull https://github.com/wallpapermgr/template  
```
