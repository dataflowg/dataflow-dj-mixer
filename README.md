# Dataflow DJ Mixer
A modified version of [Dataflow DJ](https://github.com/dataflowg/dataflow-dj) implementing a multichannel audio mixer and sample pad, written entirely in LabVIEW.

Click the image below to see a short video of it in action.
[![Dataflow DJ Mixer - Click for video](resources/Screens/dataflow-dj-mixer.png?raw=true)](https://www.youtube.com/watch?v=CoCA8toGVOs "Dataflow DJ Mixer - Click for video")

## Usage
This software works best with audio stems - individual instruments and tracks from a complete song. These can then be played together and mixed to create a new version of a song.

To use the mixing functionality:
* Browse to the location of your audio stem files using the tree browser.
* Drag each stem on to the PLAY button of a channel. This will then load the audio file. Repeat for each stem.
* Click the PLAY button in the upper left transport control section. This will begin simultaneous playback of all 8 channels.
* Adjust each channel's volume, filter, and effects to suit.
* To stop playback, press the transport PLAY button again.
* To reset the playback position, drag the position slider of each channel's waveform all the way to the left (tedious I know, but was one of the features I never got around to)
* To record your mix, press the RECORD transport button. This will automatically begin playback and record to a WAV file on disk. Press the RECORD button again to stop.

To use the sample pad:
* Load samples in to the sample pad by clicking and dragging an audio file on to an individual sample pad button.
* Once loaded, clicking the button will play it. Clicking the button again while playing will reset its playback position to 0, retriggering the sample.
* The sample will stop playing once it has reached the end.
* The keypad keys 1-9 are mapped to the top left 3x3 buttons of the sample pad grid, and can be used to trigger playback. Handy for playing drum patterns.

## Future Development
This project was mostly an experiment in how far the original DJ software could be pushed. I was happy to learn it could comfortably handle the increased number of channels, and additional sample pad channels. I probably won't do much more with the multichannel mixer, but the sample pad might be a fun addition to Dataflow DJ.
