
# Aprenderer Arm64 UPnP/DLNA Renderer for rAudio 64bit
Install with one line:
>
> cd /tmp && wget https://albumplayer.ru/linux/aprenderer-arm64.tar.gz && tar -zxf /tmp/aprenderer-arm64.tar.gz --overwrite -C /usr && ln -fs /usr/aprenderer/aprenderer.service /etc/systemd/system/aprenderer.service && systemctl daemon-reload && systemctl restart aprenderer.service && systemctl enable aprenderer.service && systemctl status aprenderer.service
>
# Aprenderer Arm32 UPnP/DLNA Renderer for rAudio 32bit
>
> cd /tmp && wget https://albumplayer.ru/linux/aprenderer-arm32.tar.gz && tar -zxf /tmp/aprenderer-arm64.tar.gz --overwrite -C /usr && ln -fs /usr/aprenderer/aprenderer.service /etc/systemd/system/aprenderer.service && systemctl daemon-reload && systemctl restart aprenderer.service && systemctl enable aprenderer.service && systemctl status aprenderer.service
>
-----------------
Aprenderer Setting at port http://ip:7779
>
# LMS
Active plugin the UPnP/DLNA bridge
>
Use UPnP/DLNA players in LMS, suppot play from LMS to MPD(UPNP) rAudio and to Aprenderer(UPNP)
>
Support thread is here:
https://forums.slimdevices.com/forum/user-forums/3rd-party-software/100256-announce-upnpbridge-integrate-upnp-dlna-players-with-lms-squeeze2upnp?103728-Announce-UPnPBridge-integrate-UPnP-DLNA-players-with-LMS-(squeeze2upnp)=
