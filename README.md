# Raspalarm-public
Raspberry Pi Spotify Alarm.

## Configuration 

Raspberry Pi OS August 2020 is required for this software due to chromium version update on next release: [download here](https://downloads.raspberrypi.org/raspios_full_armhf/images/raspios_full_armhf-2020-08-24/2020-08-20-raspios-buster-armhf-full.zip)

Add [Spotify keys](https://developer.spotify.com/dashboard) inside `/back/.env` file :

```
SPOTIFY_PUBLICKEY=<YOUR PUBLIC KEY>
SPOTIFY_PRIVATEKEY=<YOUR PRIVATE KEY>
```

## Build

Run build command to build appliction with your keys :

```
npm run build
```

This action will create `/build` folder, the root folder where `Raspalarm` is launched.

## Install

Just `git clone` your repository to your raspberry pi and launch setup command :

```
npm run setup
```

Raspberry pi will reboot and launch `Raspalarm` in chromium kiosk mode !

## More

For more details, contact me !

