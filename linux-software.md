# Apps Linux

## Essential apps
- Kernel: linux linux-hardened linux-zen
- Boot-loader: grub refind systemd-boot lilo barebox cloverbootloader limine opencorepkg burg syslinux  yaboot bootmanager
- Init-system: launchd systemd openrc runit sysv
- Display-manager: sddm light-dm lxdm gdm ly
- Display-server: wayland xorg
- Window-manager:
	- Floating-window-manager: budgie cinnamon cutefish cwm deepin dusk fvwm3 icewm leftwm kwin jwm openbox 
	- Tiling-window-manager: awesomewm bspwm dwm herbstlufwm hyprland qtile spectrwm sway wmdrland xmonad

## Drivers
- Audio-drivers: pipewire pulseaudio kpipewire helvum jack
- Video-drivers: alsa-firmware nvidia nvidia-open mesa vulkan xf86-video-intel xf86-video-nouveau xf86-video-amdgpu xf86-video-ati xf86-video-vesa xf86-video-openchrome xf86-video-fbdev 
- Ethernet-drivers: realtek networkmanager
- Bluetooth-driver: bluedevil blueman bluez blueberry
- RGB-driver: openrgb
- Printer-driver: cups ghostscript gsfonts foomatic-db gutenprint system-config-printer hplip, libcups
- Samba: samba

### Theming
- Cursors: capitaine-cursors mcmojave-cursors layan-cursor-theme sweet-cursor-theme xcursor-breeze
- Fonts: awesome-terminal-fonts comic mono fira-code iosevska noto-sans nerd-fonts-source-code-pro ttf-anonymus-pro ttf-bitstream-vera ttf-hack
- Themes: ayu-theme breeze kvantum-theme layan-kde materia-gtk-theme materia sweet-theme-git

##  [Desktop environments](Linux-DE.md)
- DE: Budgie GNOME KDE LXDE XFCE
*Desktop Environmnet are formed by DisplayManger + WindowManger + VideoDrivers + BasicApps*

## Desktop applications
- AI-tools: upscaler
- Backup: clonezilla FreeFileSync rsync
- Cleaner: BleachBit PC Decaprifier Privazer
- Compressor: 7zip ark peazip untar tar
- Communication: discord skype telegram-desktop
- Development: electron git electron
- Disk: filelight gparted
- Downloader: qBitorrent
- Encryptor: AESCrypt AXCrypt Fort File Encryption VeraCrypt
- Editor: emacs neovim vscodium
- Fonts: awesome-terminal-fonts gsfonts nerd-fonts-source-code-pro noto-fonts terminus-font ttf-dejavu ttf-fira-code ttf-hack
- Games: veloren
- Editors:
	- 3D-animation: blender
	- 2D-animation: coreldraw firealpaca inkscape krita mediabang paint opentoonz synfig
	- Audio: Audacity Oceanaudio Qtractor Rosergarden Reaper WavePad LMMS
	- Game-engine: godot stencil scratch unity unrealengine
	- Photo-editor: gimp paint.net
	- Photo-light: darktable photoscapeX rawtherapee
	- Recorder:
		- Audio-recorder: ardour
		- Screen-recorder: Bandicam obs-studio Screencastify
		- Screenshot: flameshot spectacle
		- Terminal-recorde: asciinema
		- Webcam: cheese kamoso
	- Video-editor: Davinci Resolve Fxhome KDEnlive Natron2 Olive Openshot Shotcut
	- Text:
		- IDE: apache-netbeans code mediawiki obsidian sublimetext vscode vscodium
		- Office-editor: libreoffice lnlylffice WPSOffice
		- Latex-editor: basic-miktex texmaker
		- Text-editor: emacs kate sublimtext3 vim neovim
- ISO-bootloader: Imgburn Isoburn etcher rufus unetbootin
- File-restore: testdisk
- Games: aisleriot supertux supertuxkart veloren warsow 
- Manager:
	- File-manager: caja dolphin mc nautilus nemo pcmanfm ranger thunar
	- Game-launcher: gamemode legendary lutris mangohud minigalaxy playonlinux steam
- Monitor-system: btop htop
- Multimedia: audacity audacious blender elisa gimp godot  inkscape kdenlive lmms picard
- Package-manager: brew flatpak npm snap pamac
- Player:
	- Audio-player: elisa foobar mp audacious cmus spek
	- Image-viewer: digikam irfanview gwenview
	- PDF-viewer: okular pdf-xchange
	- Video-player: mpv vlc
- Remote-desktop: teamviewer 10
- Terminal: alacritty cmatrix kitty tmux
- Tools: arch-linux-tweak-tool flatseal
- Transcoder: handbrake
- Utilities: clonezilla bottles findutils 
	- CLI: cmus fatresize feh file flex git gzip htop hugo mesa neofetch polkit samba sed tree wget wine
	- Disk-utility: ddrescue gparted filelight partitionmanager testdisk
- Virtual-machine: virtualbox virt-manager vmware
- Web-browser: chromium ungoogled-chromium firefox librewolf opera vivaldi

## Apps not develop for Linux
- Adobe Creative Suite
- Affinity suite
- Apple software (iTunes, Safari, Final Cut Pro, Logic Pro, iMovie, GarageBand, Pages, Numbers, Keynote, Xcode)
- Autodesk software (AutoCAD, Inventor Professional, Revit MEP, 3ds Max, Maya, Alias AutoStudio, Moldflow, Robot Structural Analysis Professional, Navisworks)
- Avid Technology (Pro Tools, Media Composer)
- Corel Corporation (CorelDRAW, PaintShop Pro)
- Dassault Systèmes (SolidWorks)
- Microsoft Office Suite
- Games:
	- Blizzard (World of Warcraft, Diablo series)
	- Epic Games (Fortnite, Unreal Engine)
	- Electronic Arts Sports (Madden NFL, FIFA series)
	- RIOT (LOL, VALORANT, etc)

## Ways to use apps from other OS (Windows, macOS) on Linux
- Compatibility layer: WINE for Windows, Darling for macOS.
  - Apps for manage WINE prefixes: Bottles, Lutris, Proton, Heroic Games Launcher
- Containers: Docker or Podman
- Virtual Machine: Qemu+virt-manager, Virtualbox

## References
- [List of apps | Arch Linux Wiki](https://wiki.archlinux.org/title/List_of_applications)
- [Arch packages](https://archlinux.org/packages)
- [AUR packages](https://aur.archlinux.org/packages)
