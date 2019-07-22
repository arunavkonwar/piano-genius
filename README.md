# Become a GENIUS Piano Player with AI

This is an AI-powered piano which makes you feel like a GENIUS while playing it.

The machine learning model understands your keystrokes and improves upon it by the experience it has previously gained through training on thousands of MIDI piano pieces played by master piano players.

Press buttons numbered 1 to 8 to play the piano embedded in the browser.

NOTE: PLEASE MAXIMIZE THE WINDOW FOR THE BEST EXPERIENCE


It might take some time (depending on your connection) to download the model and the weights, and then when it's ready you can go ahead and play with it.


The underlying machine learning model is an LSTM which is implemented using tensorflow.js at the core. The vanilla model has been tuned to fit certain new characteristics unique to this project. Further improvements can be made by finetuning it on a bigger and diverse database of MIDI piano data.

Currently, the model cannot be trained while playing but a future version of this project might involve training it live with thousands of concurrent players around the world. The result would be interesting to see but there are technical challenges that I'm looking to overcome before I can implement it.


TIP: After randomly playing around a bit, try pressing the same set of keys continuously and see the Piano play different improvised tones for you.