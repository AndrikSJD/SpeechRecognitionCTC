# Speech Recognition using Connectionist Temporal Classification Loss
Welcome to our audio-to-text transcription project, designed to interpret and convert user requests in real-time using advanced artificial intelligence techniques. This system employs a Connectionist Temporal Classification (CTC) model, chosen for its ability to handle sequences of variable length without requiring precise alignment between audio inputs and text outputs.

Our dataset, created specifically for this project, consists of 100 audio samples, with 10 samples for each of 10 keywords, recorded at a moderate speaking pace. The primary objective of this project is to accurately identify and transcribe these 10 keywords. This approach allows us to offer a robust and efficient solution, adapting to various speech variations and improving the accuracy in recognizing specific keywords. Our goal is to provide a tool that facilitates natural and precise interaction through voice recognition.

## Project dependencies
* `Python` 3.10.10
* `Tensorflow<2.11`
* `conda-forge`
* `cudatoolkit` 11.2
* `cudnn` 8.1.0

You have to create a virtual enviroment in anaconda, there is one link that can help you with the process
[Tutorial for enviroment](https://www.youtube.com/watch?v=QUjtDIalh0k&ab_channel=KGPTalkie)


For the execution of this project, the following complements must be installed:
```
$> pip install jiwer
$> pip3 install chardet
$> pip install librosa
$> pip install pandas
$> pip install numpy
``` 
For the audio dataset that we created, we only use one voice to record all the audios, each audio is a phrase that contains one keywords and there is 10 keywords and 10 audios per keywords for a total of 100 audios, we recommend using `Audacity` to record them on Mono channel with a sampling frequency of 22050Hz and default sample format of 16 bits
