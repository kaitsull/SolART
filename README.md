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

# The Team  
**Brianna Bristow** - Master's Student at the University of British Columbia studying cells and circuits in memory. Her expertise lies in biochemistry and she mainly utilizes R for the analysis of microscopy data.  
**Derek Merryweather, _MSc._** - PhD Student in Neuroscience at the University of British Columbia studying brain circuits involved in memory. He underwent his Master's degree in Biology at New York University, wherein his thesis focussed upon the effects of cocaine use on the straital system. His primary coding language is in R for analysis of electrical recordings of neuronal activity.  
**Johnathon Bryce** - Front-end web developer with experience in Javascript, React, HTML, and CSS.  
**Kaitlin Sullivan** - PhD Candidate in Neuroscience at the University of British Columbia studying the cellular and molecular underpinnings of fear memory. She has extensive experience in image analysis and big data analysis in R, Shiny App development, and a burgeoning interest in machine learning implementation in Python.   
**Victoria Foing, _MSc._** - Machine Learning Engineer at Sylvera with extensive Python experience, currently working with deep learning models to understand deforestation. Completed a Master's degree in AI at the University of Amsterdam, wherein her thesis focussed on the application of machine learning to characterize stellar activity and exoplanet transits in lightcurve data.   
  




