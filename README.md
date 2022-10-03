# SolART
SolART is a web application created by our team - 'The Hackletes' - for the [NASA 2022 Space Apps Hackathon](https://2022.spaceappschallenge.org/challenges/2022-challenges/creative-data-display/teams/the-hackletes/project). This app  turns solar weather data from NASA into synth tones and moving artwork.   
  
By feeding real-time data from NASA into an AI artwork generator ([Lucid Sonic Dreams](https://github.com/mikaelalafriz/lucid-sonic-dreams)), SolART aims to create beautiful visualizations that change in response to proton flux caused by solar activity. SolART further aims to sonificates the data by representing solar activity as pitch.  
  

# The Project  
Our project was in response to NASA's Hackathon Challenge: [Creative Data Display with the Parker Solar Probe](https://2022.spaceappschallenge.org/challenges/2022-challenges/creative-data-display/details)  
  
SolART allows for the creative visualization and sonification of [real-time solar flare data](https://api.nasa.gov/). This app provides an engaging audiovisual feed for non-visual data, to provide users with an experience of scientific phenomena through the lens of AI generated art.  
  
Our main language used throughout is Python, with some R and Javascript implementation. In particular, much inspiration was drawn from one package utilized called Sonic Lucid Dreams. This package was originally created to make beautiful videos that morph generated AI artwork to the audio waveform of a song.  
  
We were inspired by this - and other audiovisualizers - to instead feed in real-time solar flare data from the Parker Solar Probe. Essentially, the proton flux of a given moment is read into the GAN, altering the weights of the neural net, thus creating artwork that morphs in concert with the current solar weather. We provide options for different styles of artwork as well, all from [Justin Pinkney's pre-trained art GANs](https://github.com/justinpinkney/awesome-pretrained-stylegan2), which are [NVLabs StyleGAN2](https://github.com/NVlabs/stylegan2)s.  
  
We added in a further toggle-able audio option for sonification of the data using PyAudio, wherein pitch represents the current proton flux.  
  
While our app was unable to be completed within the allotted time, our team had a lot of fun brainstorming and beginning the creation of this application. As such, will continue to develop it despite the end of the Hackathon drawing near! Stay tuned to see the finished product!  
