# DanceabilityPredictor

CNN that tries to predict Danceability of Nicolas Jaar's publicly available discography.

This was my final project for my CSE 190 class, Machine Learning for Music and Audio.  It took Danceability (and tried some other parameters as well), publically available through Spotipy's song attributes database, and tried to predict it after listening to 30 second windows of songs.  The end resulting networks performed well on the training data, but failed to generalize effectively at all.  I suspect it was due to the highly varied nature of the audio data, having many stretches with ambient sounds and no drums that lasted for longer than 30 seconds.

In the future, if I find a more consistent dataset, I may try to come back to this and see how it can perform, though likely with significant architectural changes.
