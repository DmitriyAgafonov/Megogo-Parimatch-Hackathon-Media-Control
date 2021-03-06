# Megogo-Parimatch-Hackathon-Media-Control
Voice assistant app for managing media content. Application as developed during Megogo Parimatch Hackathon

___Issue:___ Users may experience inconvenience when interacting with media content.

___Relevance:___ according to statistics, more and more people use voice assistants.

As a result, I came to the conclusion that a good ___solution___ would be a voice assistant for controlling the media player

## App schema

<img src="https://github.com/DmitriyAgafonov/Megogo-Parimatch-Hackathon-Media-Control/blob/master/docs/app_schema.png" width="100%" height="100%">

## How it works
1) Еhe microphone works in streaming mode, waiting for a keyword followed by the main command.
2) Sound filters applied. We used libraries for working with signals, implemented filters based on the Fourier transform, spectral analysis.
3) Voice2text transformation and embedding (translating the text into multidimensional vectors).
4) The user has the ability to give a command that is close in meaning, and not pre-set thanks to the BERT model.
5) Calculating semantic similarity by cosine distance allows to capture the meaning of user`s command.
6) After passing the action to the player, the program waits for the keyword again.

<img src="https://github.com/DmitriyAgafonov/Megogo-Parimatch-Hackathon-Media-Control/blob/master/docs/img1.png" width="100%" height="100%">

---

___Business part___ was calculated approximately. ___Key metrics___ were established and substantiated.

## Application preformance demo
Demo video speed up


https://user-images.githubusercontent.com/31970304/150819871-5e951e7d-56a8-4baf-828d-137bfde69197.mp4



