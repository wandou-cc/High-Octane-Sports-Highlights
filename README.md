
<h1 align="center">:football: High Octane Sports Highlights Generator :cricket:</h1>

<div align="center">

<br>

[![made-with-python](https://forthebadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

<br>

</div>


Whether it's cricket, or football, do you wish to have the highlights from a match you missed or favourite matches ready at your convenience? Generate them with ease with this project! :smile:

This project enables to derive highlights from the complete match recording, and the best part about it is that it doesn't warrant any knowledge of *computer vision and NLP!* Sounds amazing, isn't it? 

While we may perceive the creation of these videos to be a domain of advanced technologies such as deep learning, what if we could do it without that, instead by implementing simple concepts of energy threshold in sound waves and still manage to get a decent highlight reel? :grin:

The key motivation behind this project was to familiarize myself with video and audio processing libraries in Python3.6.

### TODOs:

* [ ] Develop a GUI to upload a full video and press download for highlights.
* [ ] Automatically generate the audio file for the video file uploaded by user.
* [ ] Make the variable parameters like sample rate,filename,chunk size, threshold, etc. settable via Terminal/GUI.
* [ ] Reduce the latency time by splitting the video and then parallelizing the process of highlight extraction.
* [x] Automatically delete the highlight subclips being generated.

For a sample video and audio, please click [here](https://drive.google.com/open?id=1bWfQat17fmmpBo92w698C2sxRxBEztnk). This contains two match video and audio files and also the script generated highlights:

1. India vs Australia 2007 World Cup Indian Powerplay.
2. KKR vs RCB (RCB 49 All out).

## To run this project:
* [Fork](https://github.com/wandou-cc/High-Octane-Sports-Highlights) this Repository.
* Open Terminal and enter the folder 'High-Octane-Sports-Highlights'.
* `pip3 install -r requirements.txt`
* Download the full match video and it's audio file in the present working directory.