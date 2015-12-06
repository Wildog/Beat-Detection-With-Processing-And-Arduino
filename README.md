#arduino-beat-detection
==========================================

A simple Processing + Arduino project modified from FrequencyEnergy to detect the beat(Kick, Snare, Hi-Hat) from the buffer and then illuminate different LEDs on your Arduino according to the beat by using the StandardFirmata to communicating Arduino and Processing. 

Need Arduino and Minim libraries for Processing 1.5.1. 

Remember to change the ``ledPin`` value and ``mp3 file path`` to your owns then make 'em glow! 

Details and an example here: http://limbo.space/2013/07/11/arduino-processing-beat-detect/

一个简单的 Arduino + Processing 工程，用 Minim 库中的 BeatDetect 实时读取 Buffer 中的数据并采集音频频率识别 Kick、Snare 和 Hi-Hat 三种鼓点，通过 Arduino 的 Firmata 库驱动 LED 发光。
