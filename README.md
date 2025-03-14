# h5p-todo
I thought it might be a good idea to better keep track of my ideas and todos related to H5P -- why not make that publicly?

## In the pipeline ...

### Content types not yet on the H5P Hub
- **Bingo:** [in release](https://h5ptechnology.atlassian.net/browse/HFP-2386)
- **Pick the Symbols:** [filed for review](https://h5ptechnology.atlassian.net/browse/HFP-2944)
- **Combination Lock:** [filed for review](https://h5ptechnology.atlassian.net/browse/HFP-3624)
- **Completion Confirmation:** [filed for review](https://h5ptechnology.atlassian.net/browse/HFP-3263)
- **Content Compiler** [filed for review](https://h5ptechnology.atlassian.net/browse/HFP-3665)
- **Discrete Option Multiple Choice:** [filed for review](https://h5ptechnology.atlassian.net/browse/HFP-3681)
- **Image Choice Rounds:** [filed for review](https://h5ptechnology.atlassian.net/browse/HFP-3517)
- **Image Zoom:** [filed for review](https://h5ptechnology.atlassian.net/browse/HFP-3480)
- **Jigsaw Puzzle:** [filed for review](https://h5ptechnology.atlassian.net/jira/core/projects/HFP/issues/HFP-3478)
- **Portfolio:** [filed for review](https://h5ptechnology.atlassian.net/browse/HFP-3612)
- **Seesaw:** [proof of concept](https://www.olivertacke.de/labs/2022/04/16/see-i-saw-a-seesaw-for-h5p/)
- **Tabs:** [filed for review](https://h5ptechnology.atlassian.net/browse/HFP-3613)
- **Timekeeper:** [filed for review](https://h5ptechnology.atlassian.net/browse/HFP-3614)
- **Transcript:** [filed for review](https://h5ptechnology.atlassian.net/browse/HFP-3611)
- **X-ray:** [filed for review](https://h5ptechnology.atlassian.net/browse/HFP-3489)

### Pull requests for bugfixes and new features for core components and plugins
Here's a list of my pull reququest to the H5P project since June 2021. Didn't keep track of those that were opened before since 2016.

I know of some pull requests that now raise merge conflicts as the original code was changes in the same spot. I have marked those that I know of with ![merge-conflict](https://img.icons8.com/color/18/conflict.png). Common practice dictates that I as the pull request owner should update this - but I will most likely will not do this anymore. I have done so very often, but given that my pull requests are completely ignored, I am going to wait until I get some feedback knowing that the pull request is actually appreciated.
- [x] **H5P CLI:** _[Fix]_ Fix not loading h5p-core-button.css ([pull request](https://github.com/h5p/h5p-cli/pull/51))
- [x] **H5P CLI:** _[Fix]_ Add application specific style for editor iframe ([pull request](https://github.com/h5p/h5p-cli/pull/52))
- [x] **H5P CLI:** _[Fix]_ HFP-3901 Add mission fileIcon definition ([pull request](https://github.com/h5p/h5p-cli/pull/76))
- [x] **H5P CLI:** _[Fix]_ Exclude node_modules from livereload ([pull request](https://github.com/h5p/h5p-cli/pull/86))
- [x] **H5P CLI:** _[Fix]_ HFP-4040 Fix file extension detection ([pull request](https://github.com/h5p/h5p-cli/pull/91))
- [x] **H5P CLI:** _[Fix]_ HFP-4059 Add missing file type checking ([pull request](https://github.com/h5p/h5p-cli/pull/92))
- [x] **H5P CLI:** _[Fix]_ HFP-4060 Fix resetting state after content changed ([pull request](https://github.com/h5p/h5p-cli/pull/96))
- [x] **H5P CLI:** _[Feature]_ HFP-4061 Add reset button for sessions ([pull request](https://github.com/h5p/h5p-cli/pull/97))
- [x] **H5P CLI:** _[Feature]_ HFP-4063 Add support for user configuration file ([pull request](https://github.com/h5p/h5p-cli/pull/98))
- [x] **H5P CLI:** _[Fix] HFP-4093 Improve color code detection ([pull request](https://github.com/h5p/h5p-cli/pull/111))
- [ ] **H5P CLI:** _[Fix] HFP-4163 Fix H5P core fullscreen button not showing up ([pull request](https://github.com/h5p/h5p-cli/pull/122))
- [ ] **H5p CLI:** <strike>_[Fix] HFP-4151 Fix allowed type detection for files ([pull request](https://github.com/h5p/h5p-cli/pull/113))</strike> was ignored and re-implemented
- [ ] **H5P core:** _[Feature]_ Respect doNotTrack setting ([pull request](https://github.com/h5p/h5p-php-library/pull/98))
- [ ] **H5P core:** _[Fix]_ Fix uncaught exception when accessing localStorage ([pull request](https://github.com/h5p/h5p-php-library/pull/66))
- [x] **H5P core:** _[Fix]_ Replace deprecated FILTER_SANITIZE_STRING ([pull request](https://github.com/h5p/h5p-editor-php-library/pull/148))
- [ ] **H5P core:** _[Feature]_ Trigger set user data more often to ensure state transmission ([pull request](https://github.com/h5p/h5p-php-library/pull/107))
- [ ] **H5P core:** _[Feature]_ Add contentId to initialized event ([pull request](https://github.com/h5p/h5p-php-library/pull/134))
- [ ] **H5P core:** _[Fix]_ HFP-3649 Fix confirmation dialog button positioning ([pull request](https://github.com/h5p/h5p-php-library/pull/144))
- [ ] **H5P core:** _[Fix]_ HFP-3650 Fix semi-fullscreen impact by integration CSS ([pull request](https://github.com/h5p/h5p-php-library/pull/145))
- [x] **H5P core:** _[Feature]_ Add reduced motion mode to confirmation dialog ([pull request](HFP-3815 https://github.com/h5p/h5p-php-library/pull/160))
- [ ] **H5P core:** _[Chore]_ HFP-3843 Remove obsolete full screen handling ([pull request](https://github.com/h5p/h5p-php-library/pull/162))
- [ ] **H5P core:** _[Chore]_ Increase intelligibility of ifEmpty function ([pull request](https://github.com/h5p/h5p-php-library/pull/164))
- [ ] **H5P core/integrations:** _[Feature]_ Save content state in browser local storage ([pull request 1](https://github.com/h5p/h5p-php-library/pull/81)) ([pull request 2](https://github.com/h5p/h5p-wordpress-plugin/pull/112))
- [ ] **H5P core/integrations:** _[Fix]_ Fix deletion of view-editor-entangled libraries ([HFP-3065](https://h5ptechnology.atlassian.net/browse/HFP-3065)) ([pull request 1](https://github.com/h5p/h5p-php-library/pull/101), [pull request 2](https://github.com/h5p/h5p-wordpress-plugin/pull/125))
- [ ] **H5P Hub client:** _[Feature]_ Turn update available hint into a link ([H5P-1982](https://h5ptechnology.atlassian.net/browse/HFP-1982)) ([pull request](https://github.com/h5p/h5p-hub-client/pull/9))
- [ ] **H5P Hub client:** _[Feature]_ Add 'by' prefix for owner in content type details in order to make clear who created the content type ([pull request](https://github.com/h5p/h5p-hub-client/pull/10))
- [ ] **H5P Hub client:** _[Fix]_ Fix ignoring other library owner in license view ([pull request](https://github.com/h5p/h5p-hub-client/pull/21))
- [ ] **H5P editor core:** _[Fix]_ Fix resize of CKEditor instance ([pull request](https://github.com/h5p/h5p-editor-php-library/pull/132))
- [ ] **H5P editor core:** _[Fix]_ Fix CKEditor base path ([pull request](https://github.com/h5p/h5p-editor-php-library/pull/125))
- [ ] **H5P editor core:** _[Fix]_ Fix z-index of add file dialog ([pull-request](https://github.com/h5p/h5p-editor-php-library/pull/120))
- [ ] **H5P editor core:** _[Fix]_ Fix accessing patch_version_in_folder_name ([pull request](https://github.com/h5p/h5p-editor-php-library/pull/158))
- [x] **H5P editor core:** <strike>_[Feature]_ Add accessibility improvements (Allow to flag video as sign language [pull request](https://github.com/h5p/h5p-editor-php-library/pull/146))</strike> _rejected despite pre-qualification_
- [ ] **H5P editor core:** _[Feature]_ Add event on list item moved ([pull request](https://github.com/h5p/h5p-editor-php-library/pull/113))
- [ ] **H5P editor core:** _[Feature]_ Allow to retrieve configuration of list widget ([H5P-3599](https://h5ptechnology.atlassian.net/browse/HFP-3599)[pull request](https://github.com/h5p/h5p-editor-php-library/pull/164))
- [ ] **H5P (editor) core:** _[Fix]_ Fix step validation of number field ([pull request 1](https://github.com/h5p/h5p-editor-php-library/pull/115), [pull request 2](https://github.com/h5p/h5p-editor-php-library/pull/115))
- [ ] **H5P editor core:** _[Fix]_ Fix use of spectrum parameter allowEmpty ([pull request](https://github.com/h5p/h5p-editor-color-selector/pull/5))
- [ ] **H5P editor core:** _[Fix]_ HFP-3851 Fix select field validation ([pull request](https://github.com/h5p/h5p-editor-php-library/pull/193))
- [ ] **H5P editor core:** _[Fix]_ HFP-3852 Fix number field validation ([pull request](https://github.com/h5p/h5p-editor-php-library/pull/196))
- [ ] **H5P editor core:** _[Feature]_ Add field name to library select field classname ([pull request](https://github.com/h5p/h5p-editor-php-library/pull/194))
- [ ] **H5P editor core:** _[Fix]_ HFP-3870 Prevent crash if H5P Integration does not provide file icon ([pull request](https://github.com/h5p/h5p-editor-php-library/pull/209))
- [x] **H5P editor core:** _[Fix]_ HFP-3957 JI-6152 Stop focussing edit image button on content load ([pull request](https://github.com/h5p/h5p-editor-php-library/pull/250))
- [ ] **H5P editor core** _[Fix]_ HFP-3989 Fix programmatically removing a list item ([pull request](https://github.com/h5p/h5p-editor-php-library/pull/255))
- [ ] **H5P editor core** _[Feature]_ HFP-3989 Use removeItem for removeAllItems (list) ([pull request](https://github.com/h5p/h5p-editor-php-library/pull/256)) 
- [ ] **H5P editor core** _[Fix]_ HFP-4034 Fix using default value for library widget ([pull request](https://github.com/h5p/h5p-editor-php-library/pull/258))
- [ ] **H5P editor core** _[Feature]_ HFP-4174 Allow Panopto videos to be used from self-hosted Panopto instanced ([pull request](https://github.com/h5p/h5p-editor-php-library/pull/310))
- [ ] **H5P Joubel-UI:** _[Fix]_ Make scorebar progress unselectable ([pull request](https://github.com/h5p/h5p-joubel-ui/pull/11))
- [ ] **Report:** _[Feature]_ Support questions where answers are neither right nor wrong (choice interaction) ([pull request](https://github.com/h5p/h5p-php-report/pull/5))
- [ ] **ShowWhen:** _[Feature]_ Trigger field below triggered field ([pull request](https://github.com/h5p/h5p-editor-show-when/pull/5)) ![merge-conflict](https://img.icons8.com/color/18/conflict.png)
- [ ] **ShowWhen:** _[Feature]_ Relay changes from followed field ([pull request](https://github.com/h5p/h5p-editor-show-when/pull/3)) ![merge-conflict](https://img.icons8.com/color/18/conflict.png)
- [ ] **ShowWhen:** _[Feature]_ Make more robust for multi-value rules ([pull request](https://github.com/h5p/h5p-editor-show-when/pull/2))
- [ ] **ShowWhen:** _[Feature]_ HFP-4196 Pass trough children property of field instance ([pull request](https://github.com/h5p/h5p-editor-show-when/pull/12))
- [ ] **VerticalTabs:** _[Feature]_ Hide buttons based on min/max setting ([H5P-3599](https://h5ptechnology.atlassian.net/browse/HFP-3599)[pull request](https://github.com/h5p/h5p-editor-vertical-tabs/pull/3))
- [ ] **WordPress plugin:** _[Feature]_ Set generous HTTP feature policy ([pull request](https://github.com/h5p/h5p-wordpress-plugin/pull/114))
- [x] **WordPress plugin:** _[Fix]_ Fix check for "install_recommended_h5p_libraries" capability ([pull request](https://github.com/h5p/h5p-wordpress-plugin/pull/109))
- [x] **WordPress plugin:** _[Fix]_ Add overflow-x scrollbar for data views that are too narrow ([pull request](https://github.com/h5p/h5p-wordpress-plugin/pull/108))
- [x] **WordPress plugin:** _[Fix]_ Fix export file not being deleted with content ([pull request](https://github.com/h5p/h5p-wordpress-plugin/pull/146))
- [x] **WordPress plugin:** _[Fix]_ Fix SQL for extra fields in results ([pull request](https://github.com/h5p/h5p-wordpress-plugin/pull/148))
- [ ] **WordPress plugin:** _[Feature]_ Add support for the H5P OER Hub ([pull request](https://github.com/h5p/h5p-wordpress-plugin/pull/150))
- [x] **WordPress plugin:** _[Fix]_ H5P-3773 Fix potential memory issue ([pull request](https://github.com/h5p/h5p-wordpress-plugin/pull/162))
- [x] **WordPress plugin:** _[Fix]_ Fix sorting contents by author ([pull request](https://github.com/h5p/h5p-wordpress-plugin/pull/167))
- [ ] **WordPress plugin:** _[Feature]_ Use language defined in user profile, not general site language ([pull request](https://github.com/h5p/h5p-wordpress-plugin/pull/181))
- [x] **WordPress mod plugin:** _[Fix]_ Fix deprecated use of "implode" argument order ([pull request](https://github.com/h5p/h5pmods-wordpress-plugin/pull/6))

### Pull requests for bugfixes and new features for existing content types
I know of some pull requests that now raise merge conflicts as the original code was changes in the same spot. I have marked those that I know of with ![merge-conflict](https://img.icons8.com/color/18/conflict.png). Common practice dictates that I as the pull request owner should update this - but I will most likely will not do this anymore. I have done so very often, but given that my pull requests are completely ignored, I am going to wait until I get some feedback knowing that the pull request is actually appreciated.
- [ ] **Accordion:** _[Feature]_ HFP-4137 Use H5P.Column for content ([pull request](https://github.com/h5p/h5p-accordion/pull/41))
- [x] **Accordion:** _[Fix]_ Fix word-wrap in button ([pull request](https://github.com/h5p/h5p-accordion/pull/74))
- [ ] **Accordion:** _[Feature]_ (HFP-3819 Allow sorting of panels by title [pull request](https://github.com/h5p/h5p-accordion/pull/80))
- [ ] **Arithmetic Quiz:** _[Fix]_ Fix behavior of selected answers ([pull request](https://github.com/h5p/h5p-arithmetic-quiz/pull/55))
- [x] **Audio:** _[Fix]_ HFP-3776 Catch play promise error ([pull request](https://github.com/h5p/h5p-audio/pull/86))
- [ ] <strike>**Audio:** _[Fix]_ HFP-3826 Add icon ([pull request](https://github.com/h5p/h5p-audio/pull/93))</strike> _was ignored and re-implemented_
- [ ] **Audio:** _[Fix]_ Fix full player height for Chromium based browsers if fitToWrapper is set ([pull request](https://github.com/h5p/h5p-audio/pull/48))
- [ ] **Audio:** _[Feature]_ Add Audio Recorder Extension ([pull request](https://github.com/h5p/h5p-audio/pull/38))
- [x] **Audio:** _[Fix]_ Remove flowplayer remnants ([pull request](https://github.com/h5p/h5p-audio/pull/85))
- [ ] **Audio Recorder:** _[Fix]_ Add non-optional default parameters in constructor ([pull request](https://github.com/h5p/h5p-audio-recorder/pull/42))
- [ ] **Audio Recorder:** _[Fix]_ Fix closing of AudioContext that is already closed ([pull request](https://github.com/h5p/h5p-audio-recorder/pull/41))
- [ ] **Blanks:** _[Fix]_ HFP-3792 Fix trimming ([pull request](https://github.com/h5p/h5p-blanks/pull/135))
- [ ] **Blanks:** _[Feature]_ HFP-3862 Add completion/sucess flag to xAPI result ([pull request](https://github.com/h5p/h5p-blanks/pull/138))
- [ ] **Branching Question** _[Feature]_ HFP-3831 Add question media ([pull request](https://github.com/h5p/h5p-branching-question/pull/52))
- [ ] **Branching Question (Editor)** _[Feature]_ HFP-3831 Add question media ([pull request](https://github.com/h5p/h5p-editor-branching-question/pull/20))
- [ ] **Branching Scenario** _[Fix]_ Fix label of proceed button ([pull request](https://github.com/h5p/h5p-branching-scenario/pull/150))
- [x] **Chart:** _[Fix]_ Fix HTML encoding in charts labels ([HFP-2041](https://h5ptechnology.atlassian.net/browse/HFP-2042)) ([pull request](https://github.com/h5p/h5p-chart/pull/34))
- [ ] **Column:** _[Feature]_ Remove Twitter user feed from content type options ([pull request](https://github.com/h5p/h5p-column/pull/43))
- [ ] **Column:** _[Fix]_ Set activity started only if Column is main content ([pull request](https://github.com/h5p/h5p-column/pull/50))
- [ ] **Column:** _[Fix]_ HFP-3673 Hide fullscreen button for video/DQ of all Columns ([pull request](https://github.com/h5p/h5p-column/pull/63))
- [ ] **Course Presentation:** _[Feature]_ Add scoring with pass grade and overall feedback ([pull request](https://github.com/h5p/h5p-course-presentation/pull/171))
- [ ] **Course Presentation:** _[Fix]_ HFP-3825 Do not send xAPI completed on resume ([pull request](https://github.com/h5p/h5p-course-presentation/pull/286))
- [ ] **Course Presentation:** _[Fix]_ HFP-3918 Fix small bugs with GoToSlide ([pull request](https://github.com/h5p/h5p-course-presentation/pull/303))
- [ ] **Course Presentation:** _[Fix]_ HFP-4215 Replace Twitter User Feed ([pull request](https://github.com/h5p/h5p-course-presentation/pull/315))
- [ ] **DialogCards:** _[Feature]_ Update InteractiveVideo integration ([pull request](https://github.com/h5p/h5p-dialogcards/pull/43)) ![merge-conflict](https://img.icons8.com/color/18/conflict.png)
- [ ] **Dialogcards:** _[Feature]_ Allow the author to set every page of a card individually: text and/or image and/or audio ([pull request](https://github.com/h5p/h5p-dialogcards/pull/86))
- [ ] **Dialogcards:** _[Feature]_ Allow to add videos to cards ([pull request](https://github.com/h5p/h5p-dialogcards/pull/43)) ![merge-conflict](https://img.icons8.com/color/18/conflict.png)
- [x] **Documentation Tool:** _[Fix]_ Fix focus on resume ([pull request](https://github.com/h5p/h5p-documentation-tool/pull/64))
- [ ] **Document Export Page:** _[Fix]_ HFP-3888 Fix buttons (a11y) ([pull request](https://github.com/h5p/h5p-document-export-page/pull/56))
- [ ] **Document Export Page:** _[Fix]_ HFP-4089 Fix category labels on preview ([pull request](https://github.com/h5p/h5p-document-export-page/pull/59))
- [ ] **Drag and Drop:** _[Feature]_ Add audio on drag and drop ([pull request](https://github.com/h5p/h5p-drag-question/pull/92))
- [ ] **Drag and Drop:** _[Fix]_ Fix maximum score being higher than points achievable ([pull request](https://github.com/h5p/h5p-drag-question/pull/116))
- [ ] **Drag and Drop:** _[Fix]_ Use user defined hover text for images in tasks ([pull request 1](https://github.com/h5p/h5p-editor-drag-question/pull/13)) ([pull request 2](https://github.com/h5p/h5p-drag-question/pull/45))
- [ ] **Drag and Drop:** _[Fix]_ HFP-3610 Do not change element position if already in dropzone (([H5P-3610](https://h5ptechnology.atlassian.net/browse/HFP-3610))[pull request](https://github.com/h5p/h5p-drag-question/pull/140))
- [x] **Drag the Words:** _[Feature]_ Add option to add distractors ([pull request](https://github.com/h5p/h5p-drag-text/pull/51))
- [ ] **Drag the Words:** _[Feature]_ Add option to always display solution texts below content ([pull request](https://github.com/h5p/h5p-drag-text/pull/50))
- [ ] **Drag the Words:** _[Fix]_ Fix LaTeX support ([pull request](https://github.com/h5p/h5p-drag-text/pull/89))
- [ ] **Drag the Words:** _[Fix]_ Add margin if dropzone container has tip ([pull request](https://github.com/h5p/h5p-drag-text/pull/102))
- [x] **Drag the Words:** _[Fix]_ JI-3673 Fix npm script for 'watch' ([pull request](https://github.com/h5p/h5p-drag-text/pull/127))
- [x] **Drag the Words:** _[Fix]_ HFP-3656 Exclude package-lock.json from h5p library ([pull request](https://github.com/h5p/h5p-drag-text/pull/134))
- [ ] **Drag the Words:** _[Fix]_ HFP-3658 Improve a11y focus on "Check" and "Show Solutions" ([pull request](https://github.com/h5p/h5p-drag-text/pull/135))
- [ ] **Drag the Words:** _[Fix]_ HFP-3797 Fix draggable styling incl. color contrast ([pull request](https://github.com/h5p/h5p-drag-text/pull/143))
- [ ] **Drag the Words:** _[Feature]_ HFP-1816 Add support for alternative answers ([pull request](https://github.com/h5p/h5p-drag-text/pull/147))
- [ ] **Drag the Words:** _[Fix]_ HFP-3847 Improve draggable handling accessibility ([pull request](https://github.com/h5p/h5p-drag-text/pull/149))
- [ ] **Fill in the Blanks:** _[Feature]_ Add option to keep correct answers on retry ([pull request](https://github.com/h5p/h5p-blanks/pull/103))
- [ ] **Fill in the Blanks:** _[Feature]_ Improve performance ([pull request](https://github.com/h5p/h5p-blanks/pull/45))
- [ ] **Fill in the Blanks:** _[Fix]_ HFP-3655 Improve a11y focus on "Check" and "Show Solutions" ([pull request](https://github.com/h5p/h5p-blanks/pull/129))
- [ ] **Find the Hotspot:** _[Feature]_ Make wrappable in other content types ([pull request](https://github.com/h5p/h5p-image-hotspot-question/pull/49))
- [ ] **Find the Hotspot:** _[Feature]_ Add default "correct" message ([pull request](https://github.com/h5p/h5p-image-hotspot-question/pull/37))
- [ ] **Find the Hotspot:** _[Feature]_ Make incorrect hotspot reset task on click ([pull request](https://github.com/h5p/h5p-image-hotspot-question/pull/24))
- [x] **Flashcards:** _[Feature]_ Add option to randomize cards ([pull request](https://github.com/h5p/h5p-flashcards/pull/17))
- [x] **Flashcards:** _[Feature]_ Add option to use alternative solutions separated by | ([pull request](https://github.com/h5p/h5p-flashcards/pull/43))
- [ ] **Flashcards:** _[Fix]_ Fix optional solution ([HFP-2067](https://h5ptechnology.atlassian.net/browse/HFP-2067)) ([pull request](https://github.com/h5p/h5p-flashcards/pull/63))
- [ ] **Flashcards:** _[Feature]_ Add optional audio button ([pull request](https://github.com/h5p/h5p-flashcards/pull/64))
- [ ] **Flashcards:** _[Feature]_ Change xAPI verb from 'completed' to 'answered' ([pull request](https://github.com/h5p/h5p-flashcards/pull/20))
- [ ] **Flashcards:** _[Fix]_ HFP-3818 remove enforced capitalization ([pull request](https://github.com/h5p/h5p-flashcards/pull/114))
- [x] **Flashcards:** _[Fix]_ HFP-3644 Update usage description in translation files ([pull request](https://github.com/h5p/h5p-flashcards/pull/115))
- [x] **Goals Assessment Page:** _[Fix]_ Improve accessibility: Add labels to goals list ([pull request](https://github.com/h5p/h5p-goals-assessment-page/pull/41#event-8708714127))
- [ ] **Goals Page:** _[Feature]_ HFP-3860 Add option for predefined goals([pull request](https://github.com/h5p/h5p-goals-page/pull/47))
- [ ] **GoToQuestion:** _[Fix]_ HFP-3919 Remove title attribute from button ([pull request](https://github.com/h5p/h5p-go-to-question/pull/40))
- [x] **Image:** _[Fix]_ Fix alt and title attribute ([pull request](https://github.com/h5p/h5p-image/pull/55))
- [ ] **Image:** _[Feature]_ Allow alt tags with up to 1024 characters ([pull request](https://github.com/h5p/h5p-image/pull/58))
- [x] **Image Choice:** _[Fix]_ HFP-3682 Improve getAnswerGiven ([pull request](https://github.com/h5p/h5p-multi-media-choice/pull/51))
- [ ] **Image Hotspots:** _[Fix]_ Fix non-HTML5-videos resizing ([pull request](https://github.com/h5p/h5p-image-hotspots/pull/91))
- [ ] **Image Hotspots:** _[Feature]_ HFP-3873 Add customizing options for popups ([pull request](https://github.com/h5p/h5p-image-hotspots/pull/42))
- [ ] **Image Hotspots:** _[Fix]_ HFP-4077 Improve CSS specificity ([pull request](https://github.com/h5p/h5p-image-hotspots/pull/115))
- [ ] **Image Slider:** _[Feature]_ Add slideshow functionality ([pull request](https://github.com/falcon-git/h5p-image-slider/pull/3))
- [ ] **Image Slider:** _[Feature]_ Add audio to slides ([pull request](https://github.com/falcon-git/h5p-image-slider/pull/21))
- [ ] **Interactive Book:** _[Fix]_ Fix decrementing tasks left for non-task exercises ([pull request](https://github.com/h5p/h5p-interactive-book/pull/70))
- [x] **Interactive Book:** _[Feature]_ HFP-3768 Add option to enable/disable "Restart" button ([pull request](https://github.com/h5p/h5p-interactive-book/pull/131))
- [ ] **Interactive Video:** _[Feature]_ Add option to disable submit button until video ended ([pull request](https://github.com/h5p/h5p-interactive-video/pull/152/)) ![merge-conflict](https://img.icons8.com/color/18/conflict.png)
- [x] **Interactive Video:** <strike>_[Feature]_ Allow to add custom audio tracks and sign language videos ([pull request](https://github.com/h5p/h5p-interactive-video/pull/233))</strike> _rejected despite pre-qualification_
- [ ] **Interactive Video:** _[Feature]_ Allow author to hide playback rate chooser ([pull request](https://github.com/h5p/h5p-interactive-video/pull/236))
- [ ] **Interactive Video:** _[Fix]_ Fix muted videos on mobile ([pull request](https://github.com/h5p/h5p-interactive-video/pull/255))
- [x] **Interactive Video:** _[Fix]_ HFP-3646 Fix skipping message overflow ([pull request](https://github.com/h5p/h5p-interactive-video/pull/271))
- [ ] **Interactive Video:** _[Fix]_ Add package-lock.json to .h5pignore ([pull request](https://github.com/h5p/h5p-interactive-video/pull/318))
- [ ] **Interactive Video:** _[Feature]_ HFP-4219 Add listener to allow "tap to start/pause" on video container ([pull request](https://github.com/h5p/h5p-interactive-video/pull/337))
- [ ] **Interactive Video:** _[Fix]_ HFP-4221 Fix default text track is not selected properly ([pull request](https://github.com/h5p/h5p-interactive-video/pull/338))
- [ ] **Interactive Video:** _[Fix]_ HFP-4222 Fix keydown in Freetext interfering with global keys ([pull request](https://github.com/h5p/h5p-interactive-video/pull/339))
- [x] **Interactive Video Editor:** _[Fix]_ Fix styling the non-form parts of the H5P Hub ([pull-request](https://github.com/h5p/h5p-editor-interactive-video/pull/72))
- [x] **IV Hotspot:** _[Fix]_ Fix label HTML encoding ([pull request] https://github.com/h5p/h5p-iv-hotspot/pull/42)
- [ ] **Link:** _[Fix]_ Fix ampersand & being html encoded ([pull request](https://github.com/h5p/h5p-link/pull/19))
- [ ] **Mark the Words:** _[Fix]_ HFP-3661 Improve a11y focus on "Check" and "Show Solutions" ([pull request](https://github.com/h5p/h5p-mark-the-words/pull/105))
- [x] **Mark the Words:** _[Fix]: HFP-3907 Fix answer given state always being true ([pull request](https://github.com/h5p/h5p-mark-the-words/pull/111#event-13788688210))
- [ ] **Matching:** _[Fix]_ Fix HTML encoding for l10n and pair texts ([pull request](https://github.com/h5p/h5p-matching/pull/24))
- [x] **Memory Game** _[Fix]_ HFP-3758 Fix row break application on resize ([pull request](https://github.com/h5p/h5p-memory-game/pull/86))
- [x] **Memory Game** _[Feature]_ HFP-3770 Add resetTask function ([pull request](https://github.com/h5p/h5p-memory-game/pull/88))
- [ ] **Memory Game** _[Fix]_ HFP-3990 HFP-3990 Fix label instructions ([pull request](https://github.com/h5p/h5p-memory-game/pull/101))
- [ ] **Memory Game** HFP-4202 MemoryGame: fix calling getXAPIData on incomplete content crashing ([pull request](https://github.com/h5p/h5p-memory-game/pull/109))
- [x] **Multiple Choice:** <strike>_[Fix]_ HFP-3645 Fix calls to showSolutions or resetTask ([pull request](https://github.com/h5p/h5p-multi-choice/pull/157))</strike> _pull request ignored, implemented differently_
- [ ] **Question:** _[Fix]_ HFP-3654 Fix trailing "dot" for screen readers ([pull request](https://github.com/h5p/h5p-question/pull/16))
- [ ] **Question** _[Fix]_ Fix aria label of image expand/collapse button ([pull request](https://github.com/h5p/h5p-question/pull/27))
- [x] **Question:** _[Fix]_ HFP-3824 Add fix for dialog on embedded fullscreen ([pull request](https://github.com/h5p/h5p-question/pull/23))
- [ ] **Question Set:** _[Fix]_ Fix intro image scaling if used in compound content types ([pull request](https://github.com/h5p/h5p-question-set/pull/55))
- [x] **Questionnaire:** _[Fix]_ Exclude package-lock.json from h5p library ([pull](https://github.com/h5p/h5p-questionnaire/pull/65))
- [ ] **Shape:** _[Fix]_ Add missing dependency to H5PEditor.RadioGroup ([pull request](https://github.com/h5p/h5p-shape/pull/18))
- [ ] **Single Choice Set:** _[Fix]_ Stop giving away correct answers in page source ([pull request](https://github.com/h5p/h5p-single-choice-set/pull/53))
- [ ] **Single Choice Set:** _[Fix]_ HFP-4137 Add completion/success flags ([pull request](https://github.com/h5p/h5p-single-choice-set/pull/120))
- [ ] **Single Choice Set:** _[Fix]_ HFP-4224 Fix cursor after selection answer option ([pull request](https://github.com/h5p/h5p-single-choice-set/pull/129))
- [ ] **Single Choice Set:** _[Feature]_ HFP-4225 Optionally allow user to navigate backwards ([pull request](https://github.com/h5p/h5p-single-choice-set/pull/130))
- [ ] **Speak the Words Set:** _[Feature]_ Implement question type contract ([pull request](https://github.com/h5p/h5p-speak-the-words-set/pull/22))
- [ ] **Speak the Words Set:** _[Feature]_ Make includable in other content types ([pull request](https://github.com/h5p/h5p-speak-the-words/pull/26))
- [x] **Speak the Words Set:** _[Fix]_ Fix missing l10n string for finish button ([pull request](https://github.com/h5p/h5p-speak-the-words-set/pull/50))
- [ ] **Standard Page:** _[Feature]_ HFP-3861 Add H5P.CheckboxList and H5P.DropdownField ([pull request](https://github.com/h5p/h5p-standard-page/pull/48))
- [ ] **Summary:** _[Fix]_ Fix re-creating state for user responses ([pull request](https://github.com/h5p/h5p-summary/pull/69))
- [ ] **Summary:** _[Fix]_ HFP-4137 Add completion/success flags ([pull request](https://github.com/h5p/h5p-single-choice-set/pull/120))
- [ ] **Timeline:** _[Fix]_ H5P-3663 Add observer for attaching TimelineJS ([pull request](https://github.com/h5p/h5p-timeline/pull/68))
- [ ] **TrueFalse:** _[Fix]_ HFP-3821 Interpret checking answer as answer was given ([pull request](https://github.com/h5p/h5p-true-false/pull/124))
- [x] **Video:** <strike>_[Feature]_ Add "save content state" for time ([pull request](https://github.com/h5p/h5p-video/pull/25))</strike> _pull request ignored, implemented differently_
- [ ] **Video:** _[Feature]_ Use undocumented no-cookie option for YouTube videos ([pull request](https://github.com/h5p/h5p-video/pull/35))
- [x] **Video:** <strike>_[Feature]_ Allow to flag videos as sign language and support alternative videos for YT ([pull request](https://github.com/h5p/h5p-video/pull/69))</strike> _rejected despite pre-qualification_
- [ ] **Video:** _[Fix]_ Stop calling pause() before play promise resolved ([pull request](https://github.com/h5p/h5p-video/pull/68))
- [x] **Video:** _[Fix]_ HFP-4037 Fix sanitization of visual parameters ([pul request](https://github.com/h5p/h5p-video/pull/129))
- [ ] **Video:** _[Feature]_ HFP-3684 Prevent playback rate spoofing ([pull request](https://github.com/h5p/h5p-video/pull/87))
- [x] **Video** _[Fix]_ HFP-3868 Fix treating extras as mandatory ([pull request](https://github.com/h5p/h5p-video/pull/119))
- [ ] **Video** _[Feature]_ HFP-4174 Allow Panopto videos to be used from self-hosted Panopto instanced ([pull request](https://github.com/h5p/h5p-video/pull/148))
- [x] **Virtual Tour** _[Fix]_ HFP-3218 Stop setting focus on startup ([pull request](https://github.com/h5p/h5p-three-image/pull/92))

## Issues for my existing stuff
I already use github issues to keep track of bugs, ideas, etc. for stuff that I have created. Please have a look there.

### Content types
See https://www.olivertacke.de/labs/h5p-content-types/

### Other things
- [H5PxAPIkatchu](https://github.com/otacke/h5pxapikatchu) Plugin for WordPress to catch xAPI statements
- [H5P User Score](https://github.com/otacke/h5p-user-score) Plugin for WordPress to display H5P scores in pages and posts
- [H5P Resize Pulse](https://github.com/otacke/wp-h5p-resize-pulse) Plugin for WordPress to hackish-ly fix issues with H5P in lightboxes, tabs, or accordions

## Ideas and todos

### Replace 'title' attribute
In all content types, replace use of 'title' attribute where used with H5P.Tooltip or remove alltogether if not necessary.

### Course Presentation
  - Transitions
  - Duration
  - Style (e. g. slide (as now), over black, nothing, ...)
  - Auto-progress: It was nice if one could set a period of time after which a course presentations jumps to the next slide automatically. Might be fun for petcha kutcha or similar things. I already had some code to do this, but it got lost :-/

### H5P Paint
Just a content type to create some doodles and store them -- might be interesting to wrap images in xAPI ;-)

### H5P Annotate
- Container like content type that will put a timeline-ish comment section next to other content types for (collaborative) annotation, e.g. next to video or audio.
- Allow to jump from comment to video/audio and vice-versa.
- Would need some mechanism for sharing data among users in collaboration mode.

### H5P Mandelbrot
Just for fun, a generator for fractals

### H5P Swipe
A content type/(library for other content types?) to answer yes, no, foo or bar by swiping left, right, up or down

### H5P GraphQuiz
I wrote that on a sheet of paper, but I cannot remember what I wanted to create named this way ;-)
Might have been something like Capira offered: Teachers can draw a graph as a sample, and learners have to draw a graph that's similar enough. Could as well have been something such as https://quickdraw.withgoogle.com/

### H5P OnSite
In order so support blended learning scenarios that use xAPI statements, an on-site tool might be useful. It it's simplest version it could just trigger an xAPI statement for "attended" when someone (within a particular group/range) clicks a button. A more sophisticated version could also offer some audience response system features.

### Word cloud
Simple content type (with possibly complex variations for fun): Create a word cloud from a list of words similar to https://www.wordclouds.com/

### IFTTT connection
Having an option to trigger IFTTT recipes based on xAPI statements could be real fun!

### Question Set
Allow multi-tier-questions, cmp. https://h5p.org/node/204840

### Code feedback
Is there a service with an open API that could be used to unit test code and return some results to H5P? ...
- Possibly, something feasible is mentioned in https://h5p.org/node/310680

### Variable system
There might be cases where you want to (semi-)dynamically create content instead of creating several instances.
- Add variables, e. g. ${foo} that should not conflict with other texts.
- Add json file with possible values for a variable to h5p scheme.
- Big question: How to edit the files?

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
- Some numeric input, Likert scaled

### Link-Widget
Check if link exists while it is entered

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
Content type that is similar to the [Image Slider](https://h5p.org/image-slider), but for content types -- which would be similar to Question Set, but is not supposed to take care of scoring. Could use the engine of ImageChoiceRounds.

### alter_metadata hook
Metadata can already be altered using the alter_params hook, but only for subcontent. The meta data for the content type itself is not exposed as it doesn't reside in the params object. It was nice to be able to alter metadata, too, e.g. set a different default license, so it would not have to be set manually each time. An alter_metadata hook might help (could either only give access to the metadata object in extras or pass a reference to all metadata objects in extras and params). Alternatively, an alter_extras hook might help, too.

### ToBeNamed
- Tool to design a network of nodes that process numerical inputs and return numerical outputs.
- Processing in nodes can be controlled by widgets (e. g. "sum" to add all inputs and return the sum as output.
- Nodes can also be inputs (number input field, slider, ...)
- Nodes can also be outputs (numbers, colors, sounds, ...)

### WordPress-PlugIn
- Add option to override the list of allowed content types in the settings (as in Drupal)
- Add support for the Gutenberg editor
- Add "view_h5p_contents" capability: If set, users should at least be able to view the list of H5P contents (including the buttons that should be visible for viewing results and for editing content based on the other capabilities).
- Add contentId obfuscation: Use UUID instead of auto-incremented index
- Improve tracking of results incl. support for https://github.com/h5p/h5p-php-report
- Add option reset task for specific users
- Add option to not reset the state when editing content
- Improve content management capabilities (by replacing the list of contents with a different solution in the official plugin or by replacing it with a custom plugin - possible, done before :-))
  - Better filtering
  - Delete content(s) in list directly
  - Batch export/import
  - ...
- Endpoint to display H5P content on a plain page including QR code generation to point to.

#### WP-H5P-Leaderboard
PlugIn that allows to add a leaderboard to a post based on the scores achieved for a H5P content type.
- logged in users only based of H5P internal scores? Or use xAPI from xAPIkatchu, if available, for anonymous users, too?
- setting for maximum number of scores displayed (paged possibly)
- setting for anonymous users
- for logged in users: have their position highlighted
- modes: all scores vs. just next/previous user + score vs. gap to the top vs. ...
- Show a leaderboard below a content type (show/hide on xAPI answered)
- Different views: full vs. next one ahead / below
- pages for long boards

#### WordPress-Plugin: Timed questions
- As an author, I want to set a maximum time for H5P content in order to limit the amount of time that people can spend with the content.
  - Could call "showSolutions" via H5P question type contract
  - Could block editing by injecting an overlay (on same server)
  - Could show a timer (positioning?)
  - Optionally implement functions in H5P core (approval needed)

#### WP-H5P-Themer
- Add options to style H5P content globally
  - GUI for common styles like JoubelUI
  - (file) template based fields for content types

#### WP-H5P-Resume
- Plugin that optionally stores/restores the previous State in/from localStorage
- Would work for users that are not logged in, too

### Memory
- Add videos -- but keep an eye on the editor, should probably be improved UX-wise.
- Add text
- Optionally enlarge images on click on card that was turned already
- Check stylesheet for error

### Arithmetic Quiz
Set number ranges, cmp. https://sommenprinter.nl/basisrekenenplusmin10.php

### Dialog Cards
Improve retention by implementing something as described in http://pad.o-e-r.de/p/oercamp19-WS4-04

### Core/Plugins
- Per content type, allow to select users whose state should be reset.
- In editor (plugin integration), add option to skip resetting after changing - can be useful if you simply changed a typo or something minor.

### ChemJax
Look into supporting ChemJax (similar to MathJax)

### Linked List Widget
Editor widget for lists that knows the current entity's index and can link to other list entities using select field that only contains existing nodes and updates the fields on changes (e. g. update the links when a node in between has been removed).

### Label exercise
Have a background image and drag text input fields onto the image in order to have an exercise for labeling; could also feature strokes to link to labels next to the image

### Dice Roller
Just a simple die/dice content type:
* Fullscreen (useful for smartphones)
* Number of facets
* Number of dice
* Color of dice
* Color of dice facet
* Custom images (but still numbers internally)
* Trigger result via external dispatcher, so other content types can work with the result

### Image-Widget
- Add option to include link to image.

### Metadata retrieval
Look into ways to retrieve metadata from media and use them in H5P directly. 

### Circuit Simulator content type
Why not have a (simple) wrapper for https://github.com/kazuhikoarase/simcirjs?

### Margin widget for images
Widget that allows to add a margin around images (particularly useful for Drag and Drop)
- margin top, right, bottom and left
- background color for the margin
- preview of the proportions

### Magnifying option for H5P.Image
Add an option to magnify parts of an image similar what's common in web shops.

### Taboo
Content Type for the (reversed) Taboo game.
- Like dialog cards, add cards with taboo words
- Have a reversed mode where words must be included and need to be checked

### DragQuestion
- Add option to keep correct items in place.
- Add white space next to image for putting draggables there

### Whats5P ;-)
Content type that's similar to a Question Set, but that has a vertical layout resembling a chat window including texts in between exercises.
- Could get a separate reporting class for more sophisticated analysis across exercises.
- Cmp. https://toolbot.glitch.me/
- Cmp. https://learningsnacks.de

### Categorizator
Compound Content Type that allows to add content types (media), attach tags to them and then allow to filter them for the tags, etc.

### General Feedback
Allow links, could facilitate paths

### Multiple Choice
Option for "neither right nor wrong"

### Audio
- Add text2speech option (text/language/params)
- Add Audio Recorder?

### Content Type: Spreadsheet Question
Pretty straightforward: have a table with some filled/unfilled cells - and the latter to be filled

### Drag the Words
Allow alternatives, keep xAPI extension/correct responses pattern in mind

### Likert widget

### Scuh
Point-and-Click-Adventure-like (probably too much effort for teachers to create those)
* Rooms (image background with hotspots + NPCs)
* Inventory (items)
actions = use item + (item / hotspot / NPC)

### Spot the mistakes
The teacher can write a text including deliberately misspelled words/wrong punctuation marks. The student needs to spot the mistakes, mark and correct them.

### Content Type: Visualization
Wrapper for https://www.chartjs.org to have multiple chart options in one content type.

### (Collaborative) Post-it organizer
Could be something like GoogleKeep, but open (Multiplayer API needed)

### DialogCards
Support other algorithms such as SM2 in Anki or SuperMemo.

### Multiple Choice
- Make : escapable as \\:

### Content type for group finding
With the Multiplayer API: Have a tool where the teacher can define groups and rules and students can assign themselves to, be assigned to, etc. 

### Fill in the Blanks
- Make : escapable as \\:
- Make / escapable as \\/
- Make * escapable as \\*

### Drag and Drop
- Add Shapes

### Repetitor
New content type that works like blending QuestionSet and DialogCards:
- Allow to set question type content
- Use each content's result as grounds for a repetition mode
- Different modes possible, e.g. classic Leitner, http://pad.o-e-r.de/p/oercamp19-WS4-04, ...
- Time limits

### MathDisplay
Add KaTeX support

### Image
Add option to use link instead of uploading image

### Image Hotspots: individual color
- https://h5p.org/node/1018665

### Content Type: Text correction/Work with Text
Spot mistakes in a text and correct them. Could become a feature of Highlight the Words (the code is ugly) or a spin-off.

### Interactive Video: Countdown
- As an author, I want to be able to add a countdown to interactions that will automatically check the task/close the interaction overlay when the timer reaches zero.
  - Check vs close (disable retry if check or it doesn't make much sense)
  - Visual timer vs. hidden timer (where to put the timer?)

### H5P Interactive Video
Fix size of popups that start as a button, not as a poster

### Scratchy (Somebody else already on it)
- https://twitter.com/Seppi04748866/status/1393905629274820612
- https://t.co/aQ8NPNFKry https://t.co/hrFXKFHtde

### Copyright View
Make it look nice :-) See https://h5ptechnology.atlassian.net/browse/HFP-1902

### Typing Trainer
Content type to train typing, obviously.
- Research research on best methods ...

### Yet Another Image Gallery :-D
No comment

### Map Chart Generator
Something similar to https://mapchart.net/

### H5P.Credits
Content type for generating credits similar to movie credits.
- sections with HTML fields
- optional background music
- speed setting
- visual theming options

### Shuffled tile puzzle
- Just for fun: one of the puzzles where one tile is missing, so you can move one tile at a time to an adjacent position in order to complete the puzzle.

### H5P.Checklist
Simple checklist app that stores the state.
- As an author, I can set predefined items on a checklist in order to allow users to check/uncheck them.
- As an author, I can decide whether a user can edit or remove predefined items.
- As an author, I can decide whether a user can add/remove own items to the list.
- As a user, I can check/uncheck items on the list.
  - xAPI "interacted" (http://adlnet.gov/expapi/verbs/interacted) when item state changes
  - xAPI "completed" when all items are checked.
- As a user, I can sort items on the list.
- As a user, I can actively save the list state (in addition to common H5P state management).

### Reading Trainer
Cmp. https://t.co/1rBAGXgRU1 but without the prephase that would require machine learning support or a free and open service to be used.
Could actually be done by optionally amending Speak the Words. 

### MiniCourse
Help to make ready for release. 

### Tamagochi Teacher
- Allow authors to define a pool of exercises.
- Users can earn points for completing exercises.
- Points can be used to take care of a tamagochi like avatar, e. g. feeding, playing, etc.
- Will store the state and users will need to check the tamagochi regularly
- Have a max points per day limit, so users are required to come back regularly

### Piano
Simple content type that allows to play a piano :-)
- Externally:
  - Would be nice: 25 keys (~2 octaves), 15 white, 10 black (playable with mouse, yuks)
  - Realistic: 12 white, 8 black - that can be played with keyboard keys.
- Internally: Could be all piano keys
- Support for MIDI devices
- Allow to set octave
- Allow to define samples and switch between them.
- Metronome feature
- Volume control
- Cmp. https://recursivearts.com/virtual-piano/ or https://virtualpiano.eu/

### Rythm composer
Something like a stripped down digital version of a [Roland TR-909](https://en.wikipedia.org/wiki/Roland_TR-909]) ;-)
- Allow to have a 16 slot sequence
- Assign samples to slots
- Flexible BPM
- Low pan
- High pan
- "Infinite" rows of sequences or maybe just 4?
- Volume control per sequence
- Global volume control
- Cmp. https://hitgroove.com/

### Looper
Something like a stripped down digital version of a [Boss RC-505](https://www.boss.info/de/products/rc-505/) ;-)
- Volume control
- Cmp. https://github.com/alex-milanov/js-loop-station

### Drum Pad
- Some simple Drum Pad
- 8 pads
- volume control
- Support for MIDI devices
- Cmp. https://github.com/nikhil-web/Drumpad-Vanilla-JS-DEMO

### Music Foo
- Allow to combine "Piano", "Rythm Composer", "Looper" and "Drum Pad"
- Potentially arrange layout
- Potentially even have more elements to assign to and to control others (volume control, ...)

### Piano Question
New content type, basically a multiple choice question or sequence of questions, but using a piano keyboard as input. In extreme: "Piano Hero" :-D

### Content checker
Tool to check H5P contents for missing mandatory fields, metadata, etc.

### Automated user flow test environment
Should be done by H5P Group, but it's quite simple to set up a basic environment for the H5P CLI tool with Playwright or Selenium or ...

### Simple timeline
Cmp. bottom of https://h5p.org/roadmap (quite nice, but not a content type)

### Long Reads
A content type that allows to easily create "Long Reads" such as https://www.bbc.co.uk/news/resources/idt-sh/war_in_the_desert

### Duolingo clone
There are already content types that can replace Duolingo exercises, e.g. Dictation and Drag the Words. Close the gaps ...

### Documentation Tool: Checklist module
- As an author, I can add a predefined list of items that users can check off
- As an author, I can decide whether the checklist should be accompanied by a progress bar
- As an author, I can decide whether the user is allowed to handle extra items
- As a user, I can check off items from a list
- As a user, I can add extra items (if allowed to handle extra items)
- As a user, I can remove extra items (if allowed to handle extra items)
- Needs to support resume (store all items (incl. label for extra items) and checked state)

### Content type for placement testing
Could be an amendmend of QuestionSet, but there may be too many restrictions. So ...
- Allow to use different subcontents.
- Collect different scores based on the outcome of subcontents, so for each subcontent:
  - "As an author, I can assign different categories to a subcontent."
  - "As an author, I can define what score range for the subcontent leads to what score for the category."
- Have result similar to personality quiz based on the total category (=personality) scores

### Click the Words
Content type similar to Drag the Words, but instead of dragging words to dropzones, clicking on a word would move it to the next available slot or back to its original position if it already is inside a slot.

### Persona
Content type that allows to add an image next to a speech bubble where the speech bubble can contain text and audio. 

### Storyteller
Content type set that allows to add "Persona", "Image", "Video", "Text".
- Can have background music for the whole set and for each subcontent.
- Allows automated progression
- Allows fullscreen
- Allows audio toggling

### Content Reveal
Allow to add a trigger warning or similar before actually viewing content.

### Point-to-point drawing
Classic point-to-point drawing puzzle
- Optionally assign words (instead of numbers) to points, so students need to construct sentences
- When a "sequence" is done, do something nice visually 

### H5Pacman
While the H5P Hub is fine for installing and updating content types, there's room for improvement
to package management:
- Different places to do content type management
  - Installing can be done via the H5P Hub or the H5P library settings page of the H5P integration.
  - Updating content types can be done via the H5P Hub only.
  - Deleting content types can be done via the H5P library settings page of the H5P integration only.
- Bugs (or questionable implementation)
  - The H5P integration for moodle does not allow to delete libraries.
  - Circular dependencies are not resolved, so it may never be possible to delete content types, even though they are not used anymore (despite a 3 year old pull request, https://h5ptechnology.atlassian.net/browse/HFP-3065).
  - Moodle's custom H5P integration in moodle's core allows to delete all libraries regardless of whether they are still required or not.
- Lack of features
  - Moodle's custom H5P integration has an auto-update feature that allows to automatically fetch and install content type library updates. Some admins hate (as they don't like to let others' code be deployed automatically), others love it. Either way, no other H5P integration features this.
  - h5p.org is the only fixed content type source, so it's very inconvenient to keep track of updates to other creators' content types - and hard to discover new content types in the first place.
 
Potentially to the rescue: H5Pacman, a package manager for H5P content types. Compare the idea to package managers known in the Linux world.
- Encapsulated core functionality (in PHP)
  - Can be reused in different H5P integrations (the latter basically only need to implement the bridge to the database and the file system), so it should be quite simple to create a plugin for the PHP based platforms that offer H5P support (moodle, WordPress, Drupal, EdLib, ILIAS, Stud.IP).
  - Ports to node.js (or other programming languages) for supporting Lumi are possible, of course.
- Keep content type management in one place (install, update, delete).
- Allow to add/remove other package sources than h5p.org and can handle all of them
  - Simplest case: Use URLs to alternative h5p content type servers
  - allow to configure auto-update/priority per source, etc.
  - Requires a content type server that
    - implements the (very simple) API that h5p.org uses together with the H5P Hub.
    - supports release management of content types (but could use a simple file system based approach to get started).
    - would not be "bound" to be created in PHP
- Allow proper deletion of libraries (if possible only vs. enforced with warning, take care of circular dependencies)
- Extra functionality
  - Auto-update
  - Revert to older conent type versions (can break existing content though!)

### Spyhole content type
Content type that allows the author to upload an image. For the user, the image is hidden and parts of it will sequentially be uncovered - either on click or timer based. Optionally a correct solution can be defined and scores can be awarded when the correct solution is given, based on how fast the answer was given. Also optionally, the author can define the sequence of image parts that will be revealed, but that would probably require a visual editor and thus more time to develop. Could be a two-step process.
Could be used for the "spyhole method" where students only see a part of the image and should interpret it, and re-evaluate after they see more of the image. Could also be used as a game.

### Forker ###
Server-side tool (with client-side frontend) to modify content type parameters to match a forked version. Would need to:
0) Do a sanitization check, e.g. check if versions to upgrade from is right, etc.
1) read h5p.json and content.json
2) Update/replace entries in h5p.json
3) Run an upgrade-script on content.json if required
4) write h5p.json and content.json
5) Return the new file.

### DONE via separate content type<strike>3D model support</strike>
<strike>Add 3D model support to H5P.Image and the core widget using an appropriate library.</strike>

### DONE <strike>"GameMap"</strike>
<strike>Compound Content Type similar to Image Hotspots, but ...
- allow any kind of content type
- allow to track progress
- allow to define prerequisites for enabling hotspots
- display the current "position"
- think of it as the map in Super Mario World</strike>

### DONE <strike>Kewar: Add "description" field</strike>
<strike>Add "description" field to QR code that can be displayed along with the QRCode</strike>

### DONE <strike>Datepicker widget for editor</strike>
<strike>Says it all :-)</strike>

### DONE as Jigsaw Puzzle <strike>Puzzle Game</strike>
<strike>- Upload an image, define the dimensions, and let people puzzle
- Design option: https://h5ptechnology.atlassian.net/browse/HFP-1730
- :-)</strike>

### DONE as separate content type <strike>Add images as answer option to multiple choice?</strike>
<strike>Use images instead of text for answers. Might need some UX expertise</strike>

### DONE <strike>H5P Bingo</strike>
<strike>
- Content type for playing bingo at boring conferences -- create your bingo sheet, share, enjoy ;-)
- Enter pool of bingo words, content type will randomly generate an x by x bingo sheet
</strike>

### DONE <strike>Add setAudio function to H5P Question (already in prototype state)</strike>
<strike>H5P Question is a library that offers common functionality to question-like content types. It already features setImage and setVideo for easily including an image or a video for the content types introduction, but setAudio is missing.</strike>

### DONE <strike>Add video option to dialog cards</strike>
<strike>Currently, dialog cards can contain images, but not videos. Having videos as well, could e.g. enable support for sign language.</strike>

### <strike>H5P.PDF</strike>
<strike>Simple PDF-Viewer content type, could be based on [PDF.js](https://github.com/mozilla/pdf.js). Rather not to prevent even more PDF overuse.</strike>

### DONE <strike>DialogCards</strike>
<strike>
- cmp. https://www.indiegogo.com/projects/unlock-spaced-repetition-for-h5p-dialog-cards/x/824080
- Save Content State
- Reset button for repetition mode to start over again
</strike>

### DONE BY SOMEONE ELSE <strike>Hangman</strike>
<strike>Self-explanatory. Maybe score + timing would be nice.</strike>

### DONE <strike>Auto-Progression for Image Slider</strike>
<strike>- Option to progress to the next image automatically after a given time period (should be reset after interaction?)
- Option to jump from last to first/first to last image instead of stopping (normal and automatic)</strike>

### DONE Support Cornell Notes
<strike>Implement support for Cornell Notes, https://m.wikihow.com/Take-Cornell-Notes</strike>

### DONE <strike>by serettig in Advanced Fill in the Blanks Select for Fill in the blanks</strike>
<strike>
Instead of free text blanks, fill in the blanks might also be used to optionally present a select input field with different options
</strike>

### DONE <strike>QuestionSet</strike>
<strike>Check ImageScaling for intro inside column</strike>

### DONE <strike>Bugfix: Text size in DialogCards inside Course Presentations</strike>
<strike>Cannot reproduce</strike>

### DONE <strike>Optionally store state in cookies/localStorage</strike>
<strike>There's a save content state option that stores the state of a content type if the user is logged in. Might be useful to optionally use cookies (web storage API), so this feature could work for anonymous users, too. https://h5p.org/comment/14994#comment-14994</strike>

### DONE <strike>WP-H5P-Resize-Hack</strike>
Simple H5P-Plugin for WordPress that continuously triggers a resize event on the window.

### DONE <strike>Content Type: Paragraph Writing Structure Strips</strike>
<strike>- Have multiple text input fields and a "strip" next to it indicating the suggested length of a paragraph in relation to other paragraphs, cmp. https://www.tes.com/teaching-resource/paragraph-writing-structure-strips-for-gcse-english-literature-aqa-11821384 or https://www.pinterest.de/pin/463307880411263982/ or https://jivespin.wordpress.com/2017/07/20/structure-strips-stripping-literacy-to-the-basics/ or https://doingsocialstudies.com/2018/02/22/structure-strips-seriously-where-have-you-been-hiding/</strike>
<strike>- Allow to set the weight of each paragraph</strike>
<strike>- Allow to set the color of a paragraph strip</strike>
<strike>- Allow to set some slack. e.g +/- 10 % of characters or words</strike>
<strike>- Allow to customize feedback messages if a paragraph subceeds/exceeds</strike>
<strike>- Save content state for revision, cmp. Cornell Notes</strike>

### DONE <strike>ImageHotspots</strike>
<strike>Add Audio</strike>

### DONE <strike>Transcript library</strike>
<strike>A library that can be used to use (not create) transcripts with audio content or video content.
- Show transcript of an audio file/video file (based on .vtt captions or similar)
- Show currently used text phrase as audio/video progresses (on "caption" update, trigger with time as data)
- Jump to position in audio/video on clicking on the text (on click, trigger with time as data)</strike>

### DONE <strike>Tabs</strike>
<strike>Like Accordion, but using Tabs</strike>

### DONE <strike>Timer Content Type</strike>
<strike>Just a simple stop watch / countdown timer content type.</strike>

### DONE <strike>Timer</strike>
<strike>I have already created a general timer library for H5P, quite versatile, but I do not even dare to look at that old piece of code ;-) Maybe I'll write something new, tiny and focussed and ready for adding a timer (maybe as an overlay) to any H5P library that needs one. Could also go into H5P-Question.</strike>

### DONE as new content type<strike>Multiple-Choice</strike>
<strike>
- Add discrete option mode, cmp. https://h5p.org/node/204855
- Add confidence weighting mode
</strike>

### DONE as new content type <strike>Interactive Video: Chapter Marks</strike>
<strike>YouTube added a chapter feature by using the description for marks. Check if it is possible to retrieve those and use them to build chapters in H5P automatically.</strike>

### DONE <strike>3D model display</strike>
<strike>It might be an interesting option to have a "3D image" content type that takes a standard 3D model file as input (research: what's standard?) and just displays it with some basic interaction options such as rotating or zooming. I bet there's already an open implementation for that (based on ThreeJS) that could be wrapped and used in H5P.</strike>
