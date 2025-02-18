# OpenVPN server set up for Linux

=================================

### Step 0

Download the script using `wget` or `curl`.

```
wget https://github.com/fhdaax/scripts/raw/main/openvpn/openvpn-install.sh
```

### Step 2

Run it, leave `sudo` if you are already logged in as `root`.

```
sudo bash openvpn-install.sh
```

### Step 3

Follow the command and provide necessary informations.

### Step 4

Copy the generated `/root/<client>.ovpn` file and use it with your [OpenVPN client](https://openvpn.net/vpn-client).
In Linux, you'll be able to connect with just importing the file in the `Settings`.

## Done, congratulations!

=================================

## Original script

Sometimes it fails to download [EasyRSA-x.x.x.tgz](https://github.com/OpenVPN/easy-rsa/releases/download/v3.0.8/EasyRSA-3.0.8.tgz). So I edited [this script](https://git.io/vpn) and pointed to the `EasyRSA-x.x.x.tgz` in this directory.

## $100 free credit in DigitalOcean

DigitalOcean is providing you $100 free credit for two months to use their products including VPS droplets starting from $5/m. Signup with my referral image to redeem the offer.

[![DigitalOcean Referral Badge](https://web-platforms.sfo2.cdn.digitaloceanspaces.com/WWW/Badge%201.svg)](https://www.digitalocean.com/?refcode=93f03a33b121&utm_campaign=Referral_Invite&utm_medium=Referral_Program&utm_source=badge)
