
# Aprenderer-arm64 for rAudio 64bit
Install with one line:
>
> cd /tmp && wget https://albumplayer.ru/linux/aprenderer-arm64.tar.gz && tar -zxf /tmp/aprenderer-arm64.tar.gz --overwrite -C /usr && ln -fs /usr/aprenderer/aprenderer.service /etc/systemd/system/aprenderer.service && systemctl daemon-reload && systemctl restart aprenderer.service && systemctl enable aprenderer.service
>
# Aprenderer-arm64 for rAudio 32bit
>
> cd /tmp && wget https://albumplayer.ru/linux/aprenderer-arm32.tar.gz && tar -zxf /tmp/aprenderer-arm64.tar.gz --overwrite -C /usr && ln -fs /usr/aprenderer/aprenderer.service /etc/systemd/system/aprenderer.service && systemctl daemon-reload && systemctl restart aprenderer.service && systemctl enable aprenderer.service
>
# LMS
Active plugin: UPnP/DLNA bridge
Use UPnP/DLNA players in LMS, suppot play from LMS to MPD(UPNP) rAudio and to Aprenderer(UPNP)
