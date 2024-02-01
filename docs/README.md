# Video streaming protocols
## Inleiding
In dit hoofdstuk worden verschillende videostreaming protocols voor de communicatie tussen de edge-server en microcontroller/sbc onderzocht. 

## Doel
Het doel is om verschillende videostreaming protocols te zoeken en te vergelijken. Bij het vergelijken word gelet op het toepassen van het protocol op een microcontroller of sbc (bandbreedte, overhead, onderliggend transport protocol (tcp/udp), responstijd).


## Beschikbare protocollen

Na wat vooronderzoek heb zijn o.a. de volgende protocollen gevonden, die mogelijk gebruikt kunnen worden voor videostreaming:
- RTP (o.a. gebruikt voor IP-camera's)
- RTMP
- HLS
- MPEG-DASH
- WebRTC
- RAW TCP (with JPEG/BMP stream)
- RAW UDP (with JPEG/BMP stream)

### RTP




## Bronnen
https://getstream.io/blog/streaming-protocols/

https://github.com/rossumur/espflix/tree/master

https://www.atomic14.com/2023/09/30/a-faster-esp32-jpeg-decoder.html

https://github.com/atomic14/esp32-tv/tree/main

https://softvelum.com/nimble/mpegts/

