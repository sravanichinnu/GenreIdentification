# GenreIdentification
Project on genre identification and determining song similarity
---
In the era of commercialization, music streaming services are pre-labelling songs to their respective genres,
either based on the artists’ recommendation, to cater to the sponsors, or to garner quick and broad reach
through the statistics & analysis of the platform, to push for more hits on their application. This has led to
the forced tweaking of playlists where songs that are not similar are in the same playlist. This was a breach
of private space on the global and individual levels because a playlist caters to an individual personally. To
overcome this, we decided to implement a modelling algorithm that identifies the genre of the song.
We shall study how to visualize sound, understand what we hear and identify the features that determine
and differentiate one song from another. This study uses feature extraction and classification to help group
songs on a genre basis – songs that are highly similar instead of manual tags. The model identifies the
similar song based on the input song. This enhances user experience and increases artist recognition.
Dataset (the GTZAN dataset has 4 files)
genres original - A collection of 10 genres with 100 audio files each, all having a length of 30 seconds.
images original - A visual representation for each audio file.
2 CSV files - Containing features of the audio files. Over 3sec duration and 30 sec durations of each audio
file (this way increasing 10 times the amount of data for the 3 sec split as input to our classification models).
