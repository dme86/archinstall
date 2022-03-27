# archinstall

I'm using *archinstall* for speeding up my installations.
Booting from latest [arch ISO](https://archlinux.org/download/) an just run *archinstall* like this:

    archinstall --config user_configuration.json --creds /root/user_credentials.json --disk_layouts=/root/user_disk_layout.json

The installer will now ask for disk encryption, swap on zram, root and additional users:

![enter image description here](https://pbs.twimg.com/media/FO3yIsJXIAAc6jo?format=jpg&name=4096x4096)

All of them are optional. Just hitting *Enter* 4 times will start the installation process.
I'm using *Btrfs* with different subvolumes and *zsh* with *oh-my-zsh* for all my installations.
