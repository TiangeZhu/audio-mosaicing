# audio-mosaicing
The project is based on Frederic Font's project(https://github.com/ffont/amplab-freesound)

What I did to "improve":

Step1:

Replaced API key with mine, changed the labels to get the audios I needed from Freesound API. 

Step2:

Using onset detection(from Essentia) to slice the source files

Using beat tracking(from Essentia) for slicing the target files

Using key detection(from Essentia) for filtering source samples. 

Step3: 

Applied randomization before K-nearest neighbour algorithm, just for fun...

Note that since I'm using beat tracking, the target file should have clear beats. 
