# h5p-todo

I thought it might be a good idea to better keep track of my ideas and todos related to H5P -- why not make that publicly?

## In the pipeline ...
- Update to Essay ([in code review](https://h5ptechnology.atlassian.net/browse/HFP-1879))
- Bingo ([in code review](https://h5ptechnology.atlassian.net/browse/HFP-2386))
- Question: Add setAudio function ([pull request](https://github.com/h5p/h5p-question/pull/4))
- Audio: a11y improvements ([pull request](https://github.com/h5p/h5p-audio/pull/17))
- MathDisplay: Finish implementation of KaTeX support (code cleaning needed)
- DialogCards: Update InteractiveVideo integration ([pull request](https://github.com/h5p/h5p-dialogcards/pull/43))
- DialogCards: Add save content state (crowdfunding campaign at https://www.indiegogo.com/projects/unlock-spaced-repetition-for-h5p-dialog-cards, successful, [in review](https://h5ptechnology.atlassian.net/browse/HFP-2738))
- Agamotto: Fix a11y, add loading spinner, add option to set the transparency color ([in code review](https://h5ptechnology.atlassian.net/browse/HFP-2666))
- Dictation: Add a couple of new features: RTL for solution view, autosplitting, alternate words, headlines ([in code review](https://h5ptechnology.atlassian.net/browse/HFP-2554))
- FlashCards: Add randomization ([pull request](https://github.com/h5p/h5p-flashcards/pull/17))
- Video: Add "save content state" for time ([pull request](https://github.com/h5p/h5p-video/pull/25))
- Course Presentation: Fix for presenter sticks that trigger F5 on using the laser pointer.([pull request](https://github.com/h5p/h5p-course-presentation/pull/81))
- Question Set: Add option to show/hide retry button on summary screen ([pull request](https://github.com/h5p/h5p-question-set/pull/39))

## Issues for my existing stuff
I already use github issues to keep track of bugs, ideas, etc. for stuff that I have created. Please have a look there.
- [H5P Agamotto](https://github.com/otacke/h5p-agamotto)
- [H5P Dictation](https://github.com/otacke/h5p-dictation)
- [H5P Essay](https://github.com/otacke/h5p-essay)
- [H5P Juxtaposition](https://github.com/otacke/h5p-image-juxtaposition)
- [H5P Text Utilities](https://github.com/otacke/h5p-text-utilities)
- [H5PxAPIkatchu](https://github.com/otacke/h5pxapikatchu)

## Ideas and todos

### DONE <strike>H5P Bingo</strike>
<strike>
- Content type for playing bingo at boring conferences -- create your bingo sheet, share, enjoy ;-)
- Enter pool of bingo words, content type will randomly generate an x by x bingo sheet
</strike>

### DONE <strike>Add setAudio function to H5P Question (already in prototype state)</strike>
<strike>H5P Question is a library that offers common functionality to question-like content types. It already features setImage and setVideo for easily including an image or a video for the content types introduction, but setAudio is missing.</strike>

### DONE <strike>Add video option to dialog cards</strike>
<strike>Currently, dialog cards can contain images, but not videos. Having videos as well, could e.g. enable support for sign language.</strike>

### DONE <strike>DialogCards</strike>
<strike>
- cmp. https://www.indiegogo.com/projects/unlock-spaced-repetition-for-h5p-dialog-cards/x/824080
- Save Content State
- Reset button for repetition mode to start over again
</strike>

### DONE BY SOMEONE ELSE <strike>Hangman</strike>
Self-explanatory. Maybe score + timing would be nice.

### Set slide duration for Course Presentation
It was nice if one could set a period of time after which a course presentations jumps to the next slide automatically. Might be fun for petcha kutcha or similar things. I already had some code to do this, but it got lost :-/

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

### Optionally store state in cookies/localStorage
There's a save content state option that stores the state of a content type if the user is logged in. Might be useful to optionally use cookies (web storage API), so this feature could work for anonymous users, too. https://h5p.org/comment/14994#comment-14994

### Timer
I have already created a general timer library for H5P, quite versatile, but I do not even dare to look at that old piece of code ;-) Maybe I'll write something new, tiny and focussed and ready for adding a timer (maybe as an overlay) to any H5P library that needs one. Could also go into H5P-Question.

### H5P OnSite
In order so support blended learning scenarios that use xAPI statements, an on-site tool might be useful. It it's simplest version it could just trigger an xAPI statement for "attended" when someone (within a particular group/range) clicks a button. A more sophisticated version could also offer some audience response system features.

### Support Cornell Notes
Implement support for Cornell Notes, https://m.wikihow.com/Take-Cornell-Notes

### Word cloud
Simple content type (with possibly complex variations for fun): Create a word cloud from a list of words similar to https://www.wordclouds.com/

### IFTTT connection
Having an option to trigger IFTTT recipes based on xAPI statements could be real fun!

### Select for Fill in the blanks
Instead of free text blanks, fill in the blanks might also be used to optionally present a select input field with different options

### Question Set
Allow multi-tier-questions, cmp. https://h5p.org/node/204840

### Multiple-Choice
- Add discrete option mode, cmp. https://h5p.org/node/204855
- Add confidence weighting mode

### Code feedback
Is there a service with an open API that could be used to unit test code and return some results to H5P? ...
- Possibly, something feasible is mentioned in https://h5p.org/node/310680

### 3D model display
It might be an interesting option to have a "3D image" content type that takes a standard 3D model file as input (research: what's standard?) and just displays it with some basic interaction options such as rotating or zooming. I bet there's already an open implementation for that (based on ThreeJS) that could be wrapped and used in H5P.

### Variable system
There might be cases where you want to (semi-)dynamically create content instead of creating several instances.
- Add variables, e. g. ${foo} that should not conflict with other texts.
- Add json file with possible values for a variable to h5p scheme.
- Big question: How to edit the files?

### Transcript library
A library that can be used to use (not create) transcripts with audio content or video content.
- Show transcript of an audio file/video file (based on .vtt captions or similar)
- Show currently used text phrase as audio/video progresses (on "caption" update, trigger with time as data)
- Jump to position in audio/video on clicking on the text (on click, trigger with time as data)

### Make rewind in IV more flexible
- Set time for rewinding

### Content type for JSMOL
[JSMOL](https://sourceforge.net/projects/jmol/) seems 
to be a library for rendering molecules in HTML5. Creating an H5P content type that displays the corresponding files is probably simple. The more challenging, but also cooler part would be to implement a decent editor.

### Text utilities
The text utilities library could also benefit from some syllable/word/sentence counting capabilities (+Flesch-Kincaid, ...), might be some extra library, too.

### Add video option for flash cards
Currently, flash cards can contain images, but not videos. Having videos as well, could e.g. enable support for sign language.

### Create general import interface (the name is not accurate, but an insider joke ;-))
There are many great sources for all kinds of input on the internet, but there's no way to utilize them to automatically create H5P content. It still needs to be done manually. Things to think about:
- "all" that needs to be done is to transform input into a valid content.json file, basically mapping input fields to the right places.
- semantics.json contains all the information about the structure of H5P content, needs to be taken into account for mapping input, because the structure may change. Field names are unique for each level - but may be nested and fields may contain arrays aka lists.
- If there are no arrays/lists containing arrays/lists themselves (as in Essay for example with a list of words containing a list of alternatives), this could be represented using a table structure with each row containing the field name (and a certain data type implicitly) and columns covering list items if multiple items are possible. Groups could be represented as fieldname.groupitemname. The table structure could easily be made editable using common spreadsheet software.
- Alternatively, create an editor that first parses the current semantics file, allows to define sources and take fields from then and where to map them to.

### Create a set of learning elements for sign language
Cmp. https://morr.cc/anki-dgs/

### Tic Tac Toe
Just some finger gymnastics :-)

### setWhen
Similar to showWhen widget. Set a field property based on rules

### H5P Questionnaire
Some new libraries that could be used
- Media (Image, Audio, Video) as interstitial between pages
- Some numeric input, could be a slider or something similar

### Add images as answer option to multiple choice?
Use images instead of text for answers. Might need some UX expertise

### Link-Widget
Check if link exists while it is entered

### Leaderboard plugin for WordPress
- Show a leaderboard below a content type (show/hide on xAPI answered)
- Different views: full vs. next one ahead / below
- pages for long boards

### xAPI for DialogCards
No technical challenge, but modeling is tricky, especially for the repetition mode.

### Spaced Repetition for FlashCards
- same mechanics as for DialogCards
- xAPI

### Customization functions
- Add some helper functions for semantics customization
  - e.g. find a semantics field by path/best effort
  - maybe even some WordPress admin settings

### Enhance copyright view
- Add machine readable license information, cmp. [OERHoernchen](https://oerhoernchen.de/about)

### Content Slider
Content type that is similar to the [Image Slider](https://h5p.org/image-slider), but for content types -- which would be similar to Question Set, but is not supposed to take care of scoring.

### Auto-Progression for Image Slider
- Option to progress to the next image automatically after a given time period (should be reset after interaction?)
- Option to jump from last to first/first to last image instead of stopping (normal and automatic)
