# One of a kind Spirit box
This spirit box uses static and environmental noise from your microphone to generate text inside your terminal based off of training 
on one of hugging face's GGML models.  No faking, no "word banks", chopped audio clips, radio sweeps, absolutely none of that.
Pure static coming from your microphone.
However: you may notice that the GGML does use pre-training based off of hundreds of thousands of youtube videos, audio clips, but that can be adjusted
and heavily modified.
It uses several parameters set inside whisper's CPP repository that you can adjust to fit your sessions.
this is not an audio engine, as doing so will treat this as mandatory audio feedback through your microphone, unless
if you used the AI enigne as the source input audio (not available yet).
This uses Port audio, whisper.cpp repository, and a ggml model you must download in order for this to work. Please see installation section for more details.


# In short:
the device attempts to hallucinate itself based off of chaotic noise parameters, and common AI-training parameters found 
in engines like Stable diffusion, and attempts to search the best tokens associated with a blip of noise, speech, etc,
once done, it then outputs a series of words, short phrases and perhaps even sentences.

Some things may not make sense, and stuff can repeat.  If you see too much stuff being repeated, you will need to slide, tap on your microphone hard, or use some 
alternative method with your microphone.  to reset the tokenizations/memories that are kept track.  You can also adjust the main.cpp file inside this repository to fit as mentioned.

# Installation:
1.  [Copy one of these models listed here into SpiritBox.exe's directory](https://huggingface.co/ggerganov/whisper.cpp/blob/main/)
2.  Run cmd and do the following (name of the model would be the one you just downloaded:
3.  `SpiritBox.exe "PathToYourModel.bin"`

# What was found while I was doing a session

1.  It managed to find a random prompt that decoded to a phrase saying this: "[Mei Crying"].  Which meant it could actually say people's names, perhaps from the many video games, youtube videos, etc.
that you all could have watched!  Also:
2.  I actually read something on google while vibing this relating to "circuit breaker" when gemini made this for me, and suddenly:
The app decoded/said "circuit breaker" in the terminal.

It may take a couple of minutes for this app to fully hallucinate, and once it is finished, you will experience a LOT of weird stuff!

PLEASE BE CAREFUL!
I am not responsible for any "bad" stuff happening to you, such as unusal activity, or "demons", or other supernatural symptoms.  Dont be fooling around, and always be proper, and respectful to the other.
Honorable Mentions:
Steve Huff.
