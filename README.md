Hello! This is the repo to go along with the Eyeo workshop on Turning Data into Sound and Music.

There are three examples in this repo: two (related) examples in Python, and one in p5.js.

### Schedule (ish):

#### 9-10:15 
Introduce myself, what I do. Intro to data sonification in general - what kind of data works best, what kind of mappings work for which type of data? What kind of choices can be made? 

We'll talk about the dataset we'll be working with (ufo sightings!), and go through any other datasets that participants brought in.

We'll go over (really) basic music theory.

#### 10:15-10:45 
Setup and installation (see installation section below). 

#### 10:45-11 
BREAK

#### 11-12 
We'll go through two Python examples. 

#### 12-1
We'll go through one p5.js example.

#### 1-2 
LUNCH

#### 2-4:15 
Independent/group work on your own sonifications/compositions.

#### 4:15-5 
Presentations of final work (optional) for anyone who wants to show and get feedback. Questions, discussion of anything interesting you learned.

<br>

# Installation and Downloads

We will help you with any difficulties during this section.

## 1) Download this repo

Click on the green 'clone or download' button. To clone using terminal, type:

`git clone https://github.com/handav/workshop.git` 

and then

`cd workshop` to enter the folder.

Otherwise, download the zip file to the location of your choosing.

## 2) Check your Python version and install requirements

In your terminal, type `python -V` to see your Python version. There are examples here for use with Python 2 and Python 3.

To install requirements, type `pip install -r requirements.txt`

If that doesn't work, you can type:

`pip install midiutil`
and
`pip install scipy`

## 3) Download MuseScore if you haven't already

Please download MuseScore (https://musescore.org/en) or a midi sheet music reader of your choice.

## 4) Get Fluidsynth

Check this link to see how to best get FluidSynth: 
https://sourceforge.net/p/fluidsynth/wiki/Download/

For Mac users who have Homebrew, type:
`brew install fluidsynth`

If you need to install Homebrew: 
https://brew.sh/

## 5) Find some cool sound samples

Our p5.js example will work with samples - there are some included in this repo, but you are also free to download some you like better. I suggest NASA's free library of space sounds: 

http://cdm.link/2014/10/nasa-posts-huge-library-space-sounds-youre-free-use/

https://soundcloud.com/nasa (must be logged in to SoundCloud to download).
