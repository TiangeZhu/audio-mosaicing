# audio-mosaicing
The project is based on Frederic Font's project(https://github.com/ffont/amplab-freesound)

What I did:
Step1:
Replaced API key with mine, changed the labels to get the audios I want from Freesound API
Step2:
Using onset detection to slice the source files
Using beat tracking to slice the target files
Using key detection to filter source samples
Algorithms are both from Essentia.
Step3:
Applied randomization before K-nearest neighbour algorithm, just for fun

Note that since I'm using beat tracking, the target file should have clear beats. 
