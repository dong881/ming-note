# Ming
# Set up my Ubuntu Laptop

- sway
- clipman


```bash
sudo apt install sway
sudo apt install clipman
# In ~/.config/sway/config
exec wl-paste -t text --watch clipman store --no-persist
# In ~/.config/foot/foot.ini
font=monospace:size=24
```

# Reference

- [clipman](https://wiki.archlinux.org/title/sway)
