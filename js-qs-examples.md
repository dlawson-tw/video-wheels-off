# JS Video Quickstart

## Default JS Video Quickstart - RM0841c3a848e44ffdfbe341b6ff943903

Basic room

[RM0841c3a848e44ffdfbe341b6ff943903-quickstart.png](./js-qs-examples/RM0841c3a848e44ffdfbe341b6ff943903-quickstart.png)

## Bandwidth Constraints - RMfc107e34f9907c724fcd938a4ba5beea

BW shown in `bps`

[RMfc107e34f9907c724fcd938a4ba5beea-bw-const-a64k-v512k.png](./js-qs-examples/RMfc107e34f9907c724fcd938a4ba5beea-bw-const-a64k-v512k.png)
- Audio set to 64000 max
- Video set to 512000 max

[RMfc107e34f9907c724fcd938a4ba5beea-bw-const-a16k-v64k.png](./js-qs-examples/RMfc107e34f9907c724fcd938a4ba5beea-bw-const-a16k-v64k.png)
- Audio set to 16000 max
- Video set to 64000 max

## Local Video Snapshot

[RM-local-video-snapshot.png](./js-qs-examples/RM-local-video-snapshot.png)

- local only, no Room SID

## Codec Preferences - RMe11da08652391a0e4bd5c7b8b5dcd06e

[RMe11da08652391a0e4bd5c7b8b5dcd06e-no-prefs.png](./js-qs-examples/RMe11da08652391a0e4bd5c7b8b5dcd06e-no-prefs.png)
- default (no preferences set), used Opus/VP8

### Audio Codecs

[RMe11da08652391a0e4bd5c7b8b5dcd06e-PCMU.png](./js-qs-examples/RMe11da08652391a0e4bd5c7b8b5dcd06e-PCMU.png)
- Audio preference set to PCMU, selected was PCMU
- Video used VP8

[RMe11da08652391a0e4bd5c7b8b5dcd06e-ISAC.png](./js-qs-examples/RMe11da08652391a0e4bd5c7b8b5dcd06e-ISAC.png)
- Audio preference set to ISAC, selected was OPUS
- Video used VP8

[RMe11da08652391a0e4bd5c7b8b5dcd06e-PCMU.png](./js-qs-examples/RMe11da08652391a0e4bd5c7b8b5dcd06e-PCMU.png)
- Audio preference set to PCMU, selected was Opus
- Video used VP8

### Video Codecs

[RMe11da08652391a0e4bd5c7b8b5dcd06e-H264.png](./js-qs-examples/RMe11da08652391a0e4bd5c7b8b5dcd06e-H264.png)
- Audio used Opus
- Video preference set to H264, selected was H264

[RMe11da08652391a0e4bd5c7b8b5dcd06e-VP8.png](./js-qs-examples/RMe11da08652391a0e4bd5c7b8b5dcd06e-VP8.png)
- Audio used Opus
- Video preference set to VP8, selected was VP8

[RMe11da08652391a0e4bd5c7b8b5dcd06e-VP9.png](./js-qs-examples/RMe11da08652391a0e4bd5c7b8b5dcd06e-VP9.png)
- Audio used Opus
- Video preference set to VP9, selected was VP8

## Dominant Speaker - RM8d6a53ff0e18fcafe4af75013c66a9c4

[RM8d6a53ff0e18fcafe4af75013c66a9c4-dominant-speaker-alice.png](./js-qs-examples/RM8d6a53ff0e18fcafe4af75013c66a9c4-dominant-speaker-alice.png)

## Network Quality - RM44ea7ded530c27bb9928bd9f5cb085b2

Two screenshots to capture:

- [RM44ea7ded530c27bb9928bd9f5cb085b2-NQ-top.png](./js-qs-examples/RM44ea7ded530c27bb9928bd9f5cb085b2-NQ-top.png)
- [RM44ea7ded530c27bb9928bd9f5cb085b2-NQ-bottom.png](./js-qs-examples/RM44ea7ded530c27bb9928bd9f5cb085b2-NQ-bottom.png)

## Remote Participant Reconnection States - RM45ecc1529959c4684058ef785c5a20d5

[RM45ecc1529959c4684058ef785c5a20d5-reconnecting.png](./js-qs-examples/RM45ecc1529959c4684058ef785c5a20d5-reconnecting.png)

## Video Track Manual Controls

I had errors in the dev console, shown in the screenshot

[RM-video-track-controls-01.png](./js-qs-examples/RM-video-track-controls-01.png)

## Local Video Filter - 

This wasn't working correctly in Chrome, but did switch in FF. Checked each option:

- [RM-local-video-filter-nofilter.png](./js-qs-examples/RM-local-video-filter-nofilter.png)
- [RM-local-video-filter-blur.png](./js-qs-examples/RM-local-video-filter-blur.png)
- [RM-local-video-filter-grayscale.png](./js-qs-examples/RM-local-video-filter-grayscale.png)
- [RM-local-video-filter-sepia.png](./js-qs-examples/RM-local-video-filter-sepia.png)

## Media Device Selection - RM804d61e172f6ac74ce37b2b404736d1b

[RM804d61e172f6ac74ce37b2b404736d1b-01.png](./js-qs-examples/RM804d61e172f6ac74ce37b2b404736d1b-01.png)
- Showing default list on joining room

[RM804d61e172f6ac74ce37b2b404736d1b-audio-devices.png](./js-qs-examples/RM804d61e172f6ac74ce37b2b404736d1b-audio-devices.png)
- List of audio devices available (hardware and virtual)

[RM804d61e172f6ac74ce37b2b404736d1b-video-devices.png](./js-qs-examples/RM804d61e172f6ac74ce37b2b404736d1b-video-devices.png)
- List of Video devices available

[RM804d61e172f6ac74ce37b2b404736d1b-audio-output.png](./js-qs-examples/RM804d61e172f6ac74ce37b2b404736d1b-audio-output.png)
- List of audio output devices (hardware and virtual)

## Share Your Screen

[RM-share-screen.png](./js-qs-examples/RM-share-screen.png)
- Showing second window (FF browser with video filter page up)

## Reconnection States and Events 

[RM-reconnect-01.png](./js-qs-examples/RM-reconnect-01.png)
- Default state, creating room

[RM-reconnect-02.png](./js-qs-examples/RM-reconnect-02.png)
- Room created, reconnecting after dropping network connection

[RM-reconnect-03.png](./js-qs-examples/RM-reconnect-03.png)
- Reconnect while joined to room

## Enabling and Disabling Tracks

[RM-local-media-audio-off.png](./js-qs-examples/RM-local-media-audio-off.png)
- Default, both audio and video are on

[RM-local-media-both-on.png](./js-qs-examples/RM-local-media-both-on.png)
- Audio off, video on

[RM-local-media-video-off.png](./js-qs-examples/RM-local-media-video-off.png)
- Audio on, video off

## Data Tracks

[RM-data-tracks-joined-P1-P2.png](./js-qs-examples/RM-data-tracks-joined-P1-P2.png)
- Initial join

[RM-data-tracks-messages.png](./js-qs-examples/RM-data-tracks-messages.png)
- Messages between participants, includes P2 joining

[RM-data-tracks-messages-rejoin.png](./js-qs-examples/RM-data-tracks-messages-rejoin.png)
- P1 dropped, message only sent to P2
- P1 rejoined and P2 can see updates

## Video Track Automatic Controls

[RM-video-track-auto-control-01.png](./js-qs-examples/RM-video-track-auto-control-01.png)
- Video on, full bitrate

[RM-video-track-auto-control-02.png](./js-qs-examples/RM-video-track-auto-control-02.png)
- Video off, bitrate bottoms out

[RM-video-track-auto-control-03.png](./js-qs-examples/RM-video-track-auto-control-03.png)
- Video set to 176x144, shows the lower bitrate


