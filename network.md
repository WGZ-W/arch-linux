


# choice 1:

- sudo pacman -S networkmanager
- sudo systemctl enable NetworkManager
- sudo systemctl start NetworkManager



# choice 2


- sudo pacman -S wpa_supplicant
- wpa_passphrase networkname passphrase > example.conf
- wpa_supplicant -B -i interface -c example.conf
