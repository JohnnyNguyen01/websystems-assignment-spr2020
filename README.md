# websystems-assignment-spr2020

Practical Assignment
--------------------

### Weighting:

25% of your final marks

### Due Dates:

Draft Website (2% bonus):   5:00pm, Friday Week 6

Final Website (19%):  5:00pm, Friday Week 7

Peer marking  (5%):   5:00 pm, Friday Week 8

### Assignment objectives:

Design and implement a web site

### Task

To write a home page for yourself including information about your past, future aspirations and a reflection on your design.

This assignment tests 2 main skills - creating a live working web site and demonstrating some basic HTML/CSS skills.

* * * * *

Requirements
------------

You will make a website which is about yourself. This should follow the following specification.

Your site will consist of 4 pages & 1 css file structured as follows:

-   /websystems/index.html
-   /websystems/past.html
-   /websystems/future.html
-   /websystems/comments.html
-   /websystems/websystems.css

You should place any extra files such as images (jpg, png etc) into the /websystems directory. They can also optionally be in subdirectories for neatness (e.g. /websystems/images for pictures etc).

Your website must not depend on Javascript and should work even if CSS is disabled. It should also be usable if images are disabled, so no "mystery meat" navigation!

### Minimum requirements

1.  HTML 4.01 or higher
2.  CSS 2.1 or higher
3.  No embedded styles (including deprecated tags such as font or formatting attributes) or use of  @import. ALL styles must be in websystems.css
4.  You must provide navigation between pages using HTML hyperlinks.
5.  At least:

1.  5 CSS classes
2.  1 CSS id
3.  1 div
4.  1 span
5.  1 table (NOT CSS tables)
6.  1 list (any one of ordered, unordered, definition)
7.  1 image  (should not be large size e.g. under 1Mb in size)

#### Page descriptions

#### index.html

This home page should be a short introduction to yourself and your website. Do not post private information here as this page will be public.

You must link to the other 3 pages from this page to the other 3 pages (past.html, future.html, comments.html). You must as a minimum use HTML anchors for this, but can also add other navigation methods if you wish, for example, clickable images etc.\
You should include links back to this page from the following sub-pages as well. Even better is a consistent navigation method such as a menu bar on all pages on this site.

You are permitted to obfuscate your personal information in the index/past pages as we respect your rights to privacy.

#### past.html

This page should describe your experiences with computing so far (eg: mention your HSC experience, past work experience, etc.).

#### future.html

This page should describe what you want to do with computing in the future.

#### comments.html

This page is where you need to comment on:

1.  A short, personal reflection on your overall design
2.  The technical aspects of your website: eg: describe the structure of your website, what CSS selectors/id's etc you used and why you used them.(about half a page)
3.  The aesthetics of your website - eg: how users should perceive your page and what effects you were trying to achieve (about half a page).\
    An introduction to the aesthetics of Web design can be found here: [http://alistapart.com/article/the-web-aesthetic](http://en.wikipedia.org/wiki/Html#Transitional_versus_strict) and [http://www.webstyleguide.com/wsg3/](http://en.wikipedia.org/wiki/Html#Transitional_versus_strict)
4.  The accessibility aspects of your website - eg: how you made your web site usable by disabled users\
    A quick guide to accessibility can be found at[ https://www.w3.org/standards/webdesign/accessibility](http://en.wikipedia.org/wiki/Html#Transitional_versus_strict) and at[ http://webaim.org/intro/](http://en.wikipedia.org/wiki/Html#Transitional_versus_strict)

#### websystems.css

This shall contain all the CSS styles used by your website. 

-   Do NOT use @import as the marking program will not detect this.
-   You should try to make this web site as appealing as possible, using style sheets only.\
    You will lose marks for embedded or inline styles.
-   You must NOT use 3rd party CSS frameworks such as bootstrap, w3.css, foundation, etc
-   Your site should also be accessible to visually impaired users and screen readers (see comments.html accessibility requirements)

* * * * *

Testing
-------

You can develop initially using your personal computer by creating and editing the files on your local filesystem. You use your browser (e.g. chrome, safari, firefox) to open the pages.

You may use a HTML/CSS syntax aware editor such as Notepad++, EMACS, Visual Studio Code, Bluefish etc..

You MUST check the validation of your website at http://validator.w3.org/ and your style sheet at http://jigsaw.w3.org/css-validator/. Generally you can ignore 'information' messages, but warnings and especially errors are penalised.

You can also set up a web server on your own machine. The choices are many, see [https://en.wikipedia.org/wiki/Comparison_of_web_server_software.](https://en.wikipedia.org/wiki/Comparison_of_web_server_software)

-   We generally recommend Apache httpd, nginx, or lightspeed.
-   Windows 10 users can set up the Windows Subsystem for Linux to set up a development environment. We recommend using WSL 1 (not 2) for the moment, using Ubuntu, and then installing the appropriate HTTP server. See <https://docs.microsoft.com/en-us/windows/dev-environment/>
-   You can also use a "virtual machine" to run Linux under windows such as Vmware workstation player (recommended) or Virtualbox. Note that students planning to do the Internetworking or Software based majors should consider installing VMware as this is used in many later classes.
-   Mac users can refer to <https://discussions.apple.com/docs/DOC-3083> for discussions on how to activate the built in web server.
-   Or you could install a "WAMP" stack on your machine (<https://en.wikipedia.org/wiki/WampServer>)  if you intend to do more advanced web development in the later subjects such as Programming on the Internet, Interface Design etc.
-   Finally, it is highly recommended that you set up an external web server on one of the many external "virtual hosting" providers [(https://en.wikipedia.org/wiki/Virtual_private_server](https://en.wikipedia.org/wiki/Virtual_private_server)).\
    UTS is a member of the Amazon Web Services (AWS) Academy and can provide $50 free credit for Web Systems students if you have a AWS developer account <https://aws.amazon.com/developer/>   (See Web Sites tab).  We highly recommend the Amazon Lightsail all-in-one service

* * * * *

Submission
----------

-   You must submit via [EdStem](https://edstem.org/) system by marking and submitting before the draft and final deadlines.
-   The draft submission can be very preliminary in terms of content, but the key files and the correct directory structure must be there, and should be error free.
-   Your assignment will be copied to a faculty web server for peer marking (to be announced later)
-   If you are late, you will need to email the subject coordinator  to get your site copied to the faculty web server. This may result in a late penalty as specified in the subject outline
-   You will get zero (0) marks for websites email'ed, submitted on UTS online, or demonstrated by using the browser to directly load a HTML file (ie: using File -> Open, c:\ or file:// URL's.).

    ANYTHING ELSE WILL NOT BE MARKED!
-   Do not change the web site after the submission date - everthing is data stamped so we will know. Your tutor may take up to 2 weeks to finalise the marking.

### Prohibitions

-   Do NOT use visual WYSIWYG tools such as Dreamweaver, Microsoft Expression, Microsoft Word, online HTML editors.
-   Do NOT use 3rd party templates for your website
-   Do NOT use any tool that generates HTML/CSS code
-   Do NOT use third party CSS/HTML/javascript libraries such as w3.css, bootstrap etc.
-   Do NOT work as a group, this is an individual assignment.
-   Your tutor may ask you to prove that you wrote this assignment by hand and not with assistance.

* * * * *

### Mark breakdown:

| Category | Marks allocated |
| Technical - validated? meets requirements? uses CSS for styles? | 7 |
| Comments page: reflection on your design, technical, aesthetics, accessibility | 8 |
| Quality: pleasant to look at?, easy to use? | 4 |
| Peer Marking:based on participation and feedback | 6 |
| TOTAL: | 25 |

Bonus Marks:    you will be awarded 2 bonus marks for submitting a valid draft by the due date.   The marks will be awarded if the key files, and structure as described above, are present and if they can be viewed when copied to the public website. The detailed content does not have to be there, but some placehoder titles, at a minimum, should be in place for each webpage.

### General marking comments:

-   You MUST have the site layout exactly as described above.
-   Do NOT change the filenames or directory location as we use an automated marking checker.
-   Make sure your files are in the websystems directory. And make sure all file names and href/src attributes are in lower-case. Do NOT capitalise the first letter of the filenames
-   Watch out for "smart quotes" especially if you cut and paste from Microsoft Word. 
-   Minimum HTML 4.01 Strict and CSS 2.1 - our checker can handle most HTML5 and CSS3, but best to check with OUR online assignment checker.
-   Do NOT use vendor specific tags or attributes -- eg --webkit- -moz- etc as the validator may penalise you for this.
-   Do NOT use deprecated tags or attributes. See <http://en.wikipedia.org/wiki/Html#Transitional_versus_strict> for a list of deprecated tags and attributes.
-   Do NOT use frames or iframes (this causes problem for my validator/assignment checker)
-   Additional marks WILL NOT be granted for features such as Flash, fancy graphics, animations, audio/video etc.
-   Don't bother using CSS positioning or anything else not covered in lectures, labs or tutorials.
-   You MUST acknowledge graphic files downloaded from the internet. It is sufficient to put them in a HTML comment adjacent to the image tag. This is for legal copyright reasons as well as ethical ones.
-   You MUST use styles sheets to format your page. This MUST be in one CSS file, websystems.css - dont use @import since the assignment checker won't pick this up.
-   Do NOT hard-code your page URL's inside your pages - your website should be "relative" ie. any href's should NOT start with "http://" & will be penalised.
-   You do not need to use advanced CSS, e.g: CSS positioning, it is not essential to use them to layout your web pages
-   Your web site MUST be easy to navigate and read (consider your target audience).
-   We expect to be able to point and click, and not press the 'BACK' key on the browser, or type in any extra URL's in the address bar.
-   Unreadable or unusable web sites will also be penalised. You MUST test your web site with graphics and Javascript turned off. Is it still usable?
-   Don't put advertisements or animations on your web site.
-   Do not put private information on your web site eg date of birth, home address, credit card details. This is a PUBLIC website.
-   Don't use bad colour combinations (for example, red on black, purple on black, purple on red, blue on purple, black on red). If your tutor can't read it, you will lose marks.
-   Don't become a site on [http://webpagesthatsuck.com](http://en.wikipedia.org/wiki/Html#Transitional_versus_strict)
-   Make font sizes reasonable, use style sheets to manage them. Consider what will happen if your marker uses a smaller screen (eg: 800x600).
-   Do not have large image files - keep pictures to less than 100kb, and anything larger will attract penalties.
-   Watch out for large JPG from cameras - use a tool to reduce the size e.g. Microsoft Paint or Photoshop or GIMP etc.
-   Do not use BMP or TIF files - these arent web friendly.
-   Do not make pages so wide that they can't be read unless you scroll horizontally.
-   You will lose marks if a tutor cannot read the web page. I recommend a maximum screen size should be 1024x768, though you should design your web site to cope with larger (and smaller) screens.
-   You MUST NOT use style sheets or designs from anyone else - this includes open source and commercial style sheets and frameworks eg bootstrap!
-   You SHOULD check your web site on the 2 of the following browsers - Chrome, Firefox, Safari and/or Microsoft Edge; do NOT rely on the web preview function for final testing!
-   You SHOULD check your website using a mobile device
-   You SHOULD read the feedback from the automatic marker - don't ignore them, as there are deductions for errors, warnings and access errors.\
    The deductions are:   Error: -0.5,  Warning: -0.2, CSS Errors: -0.2, Access: (embedded style):  -0.1  per item.
-   This assignment is an individual assessment. No group work is permitted.You must not copy past assignments. Students suspected of cheating will have an academic misconduct allegation made to the university.