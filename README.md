# Maester courses

Created at #SFB2B Startup Weekend on June 6-7, 2014. Public domain.

## Course creation instructions

 * List of courses is kept in courses.json. Format:
   * **name**: Name of the course
   * **imageUrl**: Relative url of the course cover image, ~ 320x240px. Jpeg & Png supported.
   * **courseUrl**: Relative url of the course contents json (see below).

 * Course contents file is kept in f.ex. yura-course/course.json. Format:
   * **name**: Name of the course (should be the same as in courses.json).
   * **slides**: Array of course slides. Format of slide (all parameters optional):
     * **text**: Main text or question.
     * **imageUrl**: Relative url of the slide picture, ~500x700. Will be resized as needed to fill the screen.
     * **backgroundColor**: Color of the background, in usual CSS format (#abcdef)
     * **textColor**: Color of main text.
     * **answers**: Array of possible answers. Format:
       * **text**: Answer text.
       * **correct**: Is this answer correct (true or false, without quotes).
       * **hint**: Text to show to the user when they've chosen this answer.
     * **buttons**: Array of buttons. Format:
       * **text**: Button text.
       * **action**: Either a full url to open in browser, or 'close' - to close the course.






