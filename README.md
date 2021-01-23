# PiRadioMusic

##Song List

#####Jack Johnson
Upside Down


#####Tones and I
Dance Monkey

starting the music

```
sudo ./fm_transmitter -f 96.1 UpsideDown.wav
sudo ./fm_transmitter -f 96.1 DanceMonkey.wav
```

Convering cmd
```
sox my-audio.mp3 -r 22050 -c 1 -b 16 -t wav DanceMonkey.wav
```