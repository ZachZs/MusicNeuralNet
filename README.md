# Music Neural Network

This is a collaborative project during our final semester at graduate school. We were tasked with finding a data set to learn how to create neural nets with, and our choice was to use song lyrics to determine genres.

---

### Dataset

[380,000+ lyrics from MetroLyrics](https://www.kaggle.com/gyani95/380000-lyrics-from-metrolyrics/)

### Content

- Lyrics: 266,556
- Genres: 10
- Artists: 14,543

---

### Goal

**Assigning genres using song lyrics and spectroscopy**

**Problem 1:** Do humans correctly identify the genre of every song? Can we create a model that is able to cluster these song lyrics and spectroscopy without knowing the genre of each song and cluster them together as is done with genre’s?

**Problem 2:** Can we develop a neural network to classify genre of songs by lyrics/spectroscopy, instead of putting everything by one artist under one genre? This would enable playlist curation to be more fine-tuned, allowing for artists to spread their music to different audiences.

**Neural Network Framework:** Our preliminary research indicates that a Convolutional Recurrent Neural Network would work best for sequences of words.

Use the dataset of Lyrics to create a Document Term Matrix (DTM)