# Speech Diarization

End Semester project for B.Tech S6 (2023-2025) AIE. 
Speaker diarization (or diarisation) is the process of partitioning an audio stream containing human speech into homogeneous segments according to the identity of each speaker.

Speaker diarization enhances the readability of automatic speech transcriptions by structuring the audio stream into speaker turns. It answers the question “who spoke when?” and can provide the true identity of each speaker when used with speaker recognition systems.

## Process:
Speaker Segmentation: Identifies speaker change points in the audio stream.

Speaker Clustering: Groups speech segments based on speaker characteristics.

Gaussian Mixture Models (GMM): A popular method models each speaker using GMMs and assigns frames to speakers using Hidden Markov Models.

Clustering Strategies:
Bottom-Up: Splits audio content into clusters and merges redundant ones to identify real speakers.

Top-Down: Starts with a single cluster and iteratively splits it until reaching the correct number of speakers.

Recent Advances:
Neural networks and deep learning have improved speaker diarization using large-scale GPU computing.

Open-source tools like pyannote.audio, Audioseg, and ALIZE Speaker Diarization facilitate speaker diarization tasks.

## What is in this project:
We concentrate on the basics. Starting from a blank slate we tried to model a basic diarization system using various clustering algorithms namely:
<ul>
<li>K-means Clustering</li>
<li>Gaussian Mixture Models</li>
<li>Hidden Markov Models</li>
</ul>

## Group Members:

```
Bollam Shiva Shankara Varaprasad - AM.EN.U4AIE21122
Guttikonda Phanidhar Reddy - AM.EN.U4AIE21133
Lekha Sathvik Devabathini - AM.EN.U4AIE21140
Pallesi Charan Sai Reddy - AM.EN.U4AIE21149
Satvik Choulapally - AM.EN.U4AIE21157
Yasin Syed - AM.EN.U4AIE21169
```
