# Kali-Jessie-Keys
Backup of the Debian Jessie Archive Keys used in the old Kali-archive-keyring, removed by default in the newest Kali-archive-keyring
#
# Install the keys
To install the keys its as easy as 1, 2, 3, 4!
    
1.        git clone https://github.com/Morsmalleo/Kali-Jessie-Keys
2.        cd Kali-Jessie-Keys
3.        sudo mv debian-archive-jessie-stable debian-archive-jessie-security debian-archive-jessie-automatic /etc/apt/trusted.gpg.d
4.        sudo apt-get update
