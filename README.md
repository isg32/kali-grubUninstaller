# kali-grubUninstaller

Open windows CMD line and paste this

` bcdedit /enum firmware `

Then proceed to look for Your Linux Distro name, kali

Then select the key of that distro, May look like this

` {d6exxxxx-2ax9-1xee-bexa-38fxab8xb8x6} `

then proceed to delete by entering the following command:

` bcdedit /delete {d6exxxxx-2ax9-1xee-bexa-38fxab8xb8x6} `

<hr>

## Done, The kali(any linux) grub entry from boot partition has been removed, Now you can freely delete the Kali parition from the partition manager

Thanks to [SavvyNick](https://www.youtube.com/c/savvynik) For the method.
