# Piano Note Recognizer

This is a personal projects that aims to recognize and transcribe a piano recording into a music score using only Digital Signal Processing.

My first assumption was use FFT transform, but seems that for music, a better transform is a [cqt](https://en.wikipedia.org/wiki/Constant-Q_transform) 
implemented in [librosa](https://librosa.github.io/librosa/generated/librosa.core.cqt.html)

The generic problem is called Automatic Music Transcription

In the way of doing this, I found some interesting projects

### Interesting projects

- [pyknon](https://github.com/kroger/pyknon): A library to generate music, also comes with a pretty interesting book called
[Music for Geeks and Nerds](https://pedrokroger.net/mfgan/)
- [pytheory](https://github.com/Zelgius/pytheory): An interesting library to generate chord information 

### Some similar projects

- [sanjeev1996/Musical-Note-Identification](https://github.com/sanjeev1996/Musical-Note-Identification)
- [mnschmit/piano-note-recognition](https://github.com/mnschmit/piano-note-recognition)
- [radixvinni/transcribe-piano](https://github.com/radixvinni/transcribe-piano)
- [Agerrr/Automated_Music_Transcription](https://github.com/Agerrr/Automated_Music_Transcription)
- [jshankman/Automatic-Music-Transcription](https://github.com/jshankman/Automatic-Music-Transcription)
- [aliadnani/Monophonic-Audio-Transcription-Python](https://github.com/aliadnani/Monophonic-Audio-Transcription-Python)
- [aniawsz/rtmonoaudio2midi](https://github.com/aniawsz/rtmonoaudio2midi)

