# Thrive-MLSide
This is ML model for Thrive, a mobile application leveraging Artificial Intelligence (AI) to detect potential signs of depression or other mental health conditions through speech analysis. Users can record or upload short audio samples of speech, and the app will analyze vocal characteristics like pitch, intonation, and speech disfluencies. By employing machine learning models trained on a comprehensive dataset of labeled voice recordings, the app aims to identify patterns potentially associated with depression or mental health concerns. 

# Dataset: EATD-Corpus
The EATD-Corpus is a dataset consist of audio and text files of 162 volunteers who received counseling.

How to download
The EATD-Corpus can be downloaded at https://1drv.ms/u/s!AsGVGqImbOwYhHUHcodFC3xmKZKK?e=mCT5oN. 
Password: Ymj26Uv5

How to use
Training set contains data from 83 volunteers (19 depressed and 64 non-depressed).

Validation set contains data from 79 volunteers (11 depressed and 68 non-depressed).

Each folder contains depression data for one volunteer.

{positive/negative/neutral}.wav: Raw audio in wav

{positive/negative/neutral}_out.wav: Preprocessed audio. Preprocessing operations include denoising and de-muting

{positive/negative/neutral}.txt: Audio translation

label.txt: Raw SDS score

new_label.txt: Standard SDS score (Raw SDS score multiplied by 1.25)

