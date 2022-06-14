# sygic-uk-safety-cameras-poi
Sygic navigation safetey camera POIs for UK region

# igo to sygic code conversion
igo| sygic
--|--
1 - fixed speed camera | 1 - RADAR_STATIC_SPEED
2 - red light and speed camera / build-in|6 - RADAR_STATIC_RED_LIGHT_SPEED
3 - red light camera|2 - RADAR_STATIC_RED_LIGHT , 7 - RADAR_MOBILE_RED_LIGHT
4 - average speed camera|4 - RADAR_STATIC_AVERAGE_SPEED ,8 - RADAR_MOBILE_AVERAGE_SPEED
5 - mobile speed camera, lasers, hand-held radars and other |5 - RADAR_MOBILE_SPEED
6 - railroad crossing|
7 - bus line camera |0 - RADAR_SYMBOL
8 - high accident zone / dangerous way|11 - RADAR_DANGEROUS_PLACE
9 - school zone|16 - RADAR_SCHOOLZONE
10 - town entry point|
11 - red light and speed camera|6 - RADAR_STATIC_RED_LIGHT_SPEED
12 - toll booth|
13 - hospital, ambulance|
14 - fire station|
15 - congestion charge zone|12 - RADAR_CONGESTION
30 - stickers camera|10 - RADAR_INFO_CAMERA
31 - dangerous area|11 - RADAR_DANGEROUS_PLACE
35 - Average speed check|4 - RADAR_STATIC_AVERAGE_SPEED ,8 - RADAR_MOBILE_AVERAGE_SPEED

```
## mapping
```
1=1,2=6,3=2,4=4,5=5,7=0,8=11,9=16,11=6,15=12,30=10,31=11,35=4
```

# Installation
download, copy "offlinespeedcams.dat" to \Android\Data\com.sygic.aura\files\maps\speedcams
