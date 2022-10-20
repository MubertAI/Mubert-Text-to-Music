# Mubert-Text-to-Music
Colab notebooks demonstrating prompt-based music generation via Mubert API

[**WATCH DEMO**](https://youtu.be/YJu0iXn-T_U)

### [Mubert Text-to-Music](Mubert_Text_to_Music.ipynb)

A simple demo offering music generation by prompt and duration

### [Stable Diffusion + Mubert](Deforum_Stable_Diffusion_Mubert.ipynb)

A demo of instant prompt-based music video generation based on Deforum Stable Diffusion colab

* music by www.mubert.com/

We’re glad to present you our new Text-to-Music demo interface.
Now as a Google Colab, and soon we’ll add this feature as a simple form on our website. This has already gone viral, so the community has questions about how everything works

People ask how generative this music really is. Each time you send a request, our API generates a unique combination of sounds. The probability of repetition is extremely small. Music is not taken from the database of finished tracks, it is created at the time of the request.

How are sounds selected for generation? The input prompt and Mubert API tags are both encoded to latent space vectors of a transformer neural network. Then the closest tags vector is selected for each prompt and corresponding tags are sent to our API for music generation.

All sounds (separate loops for bass, leads etc.) are created by musicians and sound designers, they are not synthesized by any neural network. Our paradigm is "from creators to creators". We are musicians ourselves and it is important for us that musicians stay in the equation.

Our proprietary technology is able to analyze and select relevant sounds, as well as build arrangements and compositions from them. In this demo, you can set up what you need, a looped track or a track with a start and end.

A custom license works for colab. You can use the music for free with attribution to sync with images and videos, but you can't release it on DSPs as your own. We also ask you to mention @mubertapp and hashtag #mubert. If you need a commercial license — please contact us.

This is our first step towards creating a more complex and accurate generation algorithm, but for this we will need time and resources. All your feedback will be very useful, so feel free to write us in the replies or in a PM about your user experience. Have fun!
