# Sound Recording sp33d

**On how to record voices with almost full autonomy, for voice over, podcast, etc.**

Prerequisite : being in the sound studio, having someone talking in the record studio.

## 1. Connection

The sound card must be connected to the computer :

![Carte son](./images/img1.jpg)

it must be turned on :

![Carte son](./images/img2.jpg)

And there must be cables connected to it :

![Carte son](./images/img3.jpg)

To adjust the gain on the mic (to have an adequat volume if you are recording yellings or whisperings for example), you can turn the first potentiometer on the left on the front side of the sound card.

![carte son](./images/entree_focusriteEN.png)

<details><summary> The difference between gain and volume</summary>
Gain is the amplification of the input signal (how much sound the mic get), and volume is the amplification of the output signal (how loud are the speakers).
</details>

You can increase or decrease the gain of the control room mic (which allows you to talk with the person in the recording room) or the gain of the recording room mic (the one you record), the volume of the monitoring speakers in the control room, as well as the volume of the recording room headphone. You can also adjust the volume of the second output if you use headphones in the control room.

Be careful to lower the speakers volume if you use the control room mic to avoid larsen effects.

You also need to turn on the speakers, with the button behind it :
![Enceintes](./images/img4.jpg)

## 2. Record with Reaper

Open Reaper.

// photo

Click on "Still Evaluating".

Create a new track with `Track` > `Insert new track`.

![nouveau track](./images/screen1.png)

To be able to record on the track, click on the record button ⏺️ on the track either in the track list on the top left, or on the bottom left in the mix control pannel.

![nouveau track](./images/screen2.png)
![nouveau track](./images/screen3.png)

The sound level of the microphone is then shown in the meters.

To record the sound from the mic on the track, click on the main record button ⏺️ and re-click to stop the recording.

![nouveau track](./images/screen4.png)

To crop the recording, you can either select the part of the recording to keep and right-click > `Crop project to selection`.
Or you can remove parts of the recording by selecting them and right-click > `Remove contents of selection`.

![nouveau track](./images/screen5.png)

To export the recording, click on `File` > `Consolidate/Export tracks...` .

![nouveau track](./images/screen6.png)

Manage export settings :

![nouveau track](./images/screen7.png)

Choose the file format with `Consolidate to` (WAV, AIFF, MP3), and the location of the export with `Output consolidated files to directory:`.

## 3. Record with FL Studio

### Set up in FL Studio

Open FL Studio.

Open `Audio Settings` in `Options`.

![Carte son](./images/capture2.png)

In the `Device` liste, select the sound card `Focusrite USB ASIO`.

![Carte son](./images/capture3.png)

*Be careful of selecting the Focusrite in the `Asio Device` part of the list.*

Here's the interface when everything is well connected :

![Carte son](./images/capture4.png)

### Recording

Click on the mic 🎙️ in the top right area.

![Carte son](./images/capture1.png)

Choose `Into Edison audio editor/recorder`.

![Carte son](./images/capture5.png)

Click on the record button ⏺️ to start the recording.

![Carte son](./images/capture6.png)

The record button ⏺️ becomes red, and you can click on the stop button ⏹️ to stop the recording.

![Carte son](./images/capture7.png)

To save the recording, click on the floppy disk button 💾 and choose `Save sample as`.

![Carte son](./images/capture9.png)

To create a new recording, click on the floppy disk button 💾 and choose `New`.

![Carte son](./images/capture8.png)# SoundRecording_sp33d
