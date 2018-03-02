# h5p-todo

I thought it might be a good idea to better keep track of my ideas and todos related to H5P -- why not make that publicly?

## Coming next ...
- Finish H5P Dictation
- Create H5P Bingo just for fun/Anja Lorenz

## Issues for my existing stuff
I already use github issues to keep track of bugs, ideas, etc. for stuff that I have created. Please have a look there.
- [H5P Agamotto](https://github.com/otacke/h5p-agamotto)
- [H5P Dictation](https://github.com/otacke/h5p-dictation)
- [H5P Essay](https://github.com/otacke/h5p-essay)
- [H5P Juxtaposition](https://github.com/otacke/h5p-image-juxtaposition)
- [H5P Text Utilities](https://github.com/otacke/h5p-text-utilities)
- [H5PxAPIkatchu](https://github.com/otacke/h5pxapikatchu)

## Ideas and todos

### H5P Bingo
- Content type for playing bingo at boring conferences -- create your bingo sheet, share, enjoy ;-)
- Enter pool of bingo words, content type will randomly generate an x by x bingo sheet

### Add setAudio function to H5P Question (already in prototype state)
H5P Question is a library that offers common functionality to question-like content types. It already features setImage and setVideo for easily including an image or a video for the content types introduction, but setAudio is missing.

### Set slide duration for Course Presentation
It was nice if one could set a period of time after which a course presentations jumps to the next slide automatically. Might be fun for petcha kutcha or similar things. I already had some code to do this, but it got lost :-/

### Improve Copyright Handling
Needs details ...

### H5P Paint
Just a content type to create some doodles and store them -- might be interesting to wrap images in xAPI ;-)

### H5P Annotate
Container like content type that will put something like a timeline-ish comment section next to other content types for (collaborative) annotation. Would need some mechanism for sharing data among users

### H5P Mandelbrot
Just for fun, a generator for fractals

### H5P Swipe
A content type/(library for other content types?) to answer yes, no, foo or bar by swiping left, right, up or down

### H5P GraphQuiz
I wrote that on a sheet of paper, but I cannot remember what I wanted to create named this way ;-)
Might have been something like Capira offered: Teachers can draw a graph as a sample, and learners have to draw a graph that's similar enough. Could as well have been something such as https://quickdraw.withgoogle.com/

### Optionally store state in cookies
There's a save content state option that stores the state of a content type if the user is logged in. Might be useful to optionally use cookies (web storage API), so this feature could work for anonymous users, too. https://h5p.org/comment/14994#comment-14994

### Timer
I have already created a general timer library for H5P, quite versatile, but I do not even dare to look at that old piece of code ;-) Maybe I'll write something new, tiny and focussed and ready for adding a timer (maybe as an overlay) to any H5P library that needs one. Could also go into H5P-Question.
