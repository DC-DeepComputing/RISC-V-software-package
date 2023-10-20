Riscv installation package
1. Chromium 
wget http://120.92.155.32:8082/artifactory/tools/chromium-103.0.5060.114.deb
sudo apt-get install ./chromium-103.0.5060.114.deb
2. gcc  clang make
sudo apt-get install gcc clang make
3. office
wget http://120.92.155.32:8082/artifactory/tools/LibreOffice_7.5_riscv64.zip
unzip LibreOffice_7.5_riscv64.zip
sudo apt-get install ./LibreOffice_7.5_riscv64.deb
4. cheese
sudo apt-get install cheese
cheese -d  /dev/video0
5. docker 
sudo apt-get update
sudo apt-get install -y systemd systemd-sysv sudo net-tools ethtool ifupdown iputils-ping vim ssh bash-completion parted apt-transport-https ca-certificates curl gnupg-agent software-properties-common
sudo apt-get install fuse-overlayfs docker.io
6. electron23
wget http://120.92.155.32:8082/artifactory/tools/electron/electron-23_23.3.11-1_riscv64.deb
sudo apt-get install ./electron-23_23.3.11-1_riscv64.deb
7. nodejs npm
sudo apt-get install nodejs npm
8. firefox
wget https://github.com/starfive-tech/Debian/releases/download/v0.8.0-engineering-release-wayland/firefox_105.0_202305_riscv64.deb
sudo apt-get install ./firefox_105.0_202305_riscv64.deb
other
wget https://github.com/starfive-tech/Debian/releases/download/v0.9.0-engineering-release-wayland/codec.tar.gz
wget https://github.com/starfive-tech/Debian/releases/download/v0.9.0-engineering-release-wayland/ffmpeg-deb.tar.gz
wget https://github.com/starfive-tech/Debian/releases/download/v0.9.0-engineering-release-wayland/gst-omx-deb.tar.gz
wget https://github.com/starfive-tech/Debian/releases/download/v0.9.0-engineering-release-wayland/vlc-deb.tar.gz
wget https://github.com/starfive-tech/Debian/releases/download/v0.9.0-engineering-release-wayland/libsdl2-2.0-0_2.26.1+dfsg-1_riscv64.debware
