# UCSB Web Accessibility Guidelines

> “Building an accessible Website is a necessity as the Web becomes an everyday tool for
communication, work, and play. Electronic "curb cuts"—accessible Web design
elements—need to be addressed in all Website construction. It now appears that our
nation has reached a significant crossroad where our policies, technology, and purchasing
choices will determine whether or not every person will participate in the digital
economy. The impact is systemic and reaches all sectors of our economy. Rather than
promoting a digital divide, we must address accessible Web design so that everyone can
participate, regardless of age, disability, or the limitations of the available technology.”
– Cynthia Waddell

## Introduction

As the “Information Age” has progressed, the capability of sharing data across vast
distances at incredible speeds has become possible. Increasingly, however, the disabled
population is being left behind as part of a group which has been termed “The Digital
Divide”: those who do not have equal access to digital communication either by choice,
by financial constraints, or by other constraints such as disability. While a barrier to
access such as a building without an elevator, an elevator without a Braille panel, an
auditory alarm system without a visual component or stairs without an accompanying
ramp may seem like a pretty obvious barrier to access to most of us, poorly designed web
pages or computers are less noticeable to those who do not have a disability. It is the
goal of these guidelines to outline ways in which the UCSB campus and especially those
who create digital content for members of this campus should better facilitate access to
electronic data.

## Reasoning Behind Accessibility

Accessibility is a Civil Rights issue and inaccessible websites violate the “effective
communications” requirement of the Americans with Disabilities Act (ADA) as well as
provisions of Section 504 and 508 of the Rehabilitation Act (you can read more about
these pieces of legislation by following the links in the appendix).

The power of technology and the web in particular is to make our lives easier by
automating processing, facilitating data retrieval, expediting orders of both merchandise
and services and in general, allowing us to more quickly and efficiently take care of
everyday tasks. Just as the rights of disabled people are ensured by providing closed
captioning for television programs, auditory crosswalk indicators or elevators and ramps
in buildings with stairs, so too is it our obligation and responsibility to similarly
accommodate the needs of the disabled when it comes to accessing electronic systems
and data.

Additionally, many of the guidelines contained herein, which are designed to assist
people with various disabilities, will also help people who are not necessarily disabled
but who may be accessing electronic information through a slower modem, a text-only
browser, web-enabled cell phone or a PDA (Personal Digital Assistant). Ensuring
accessibility for the disabled also helps other groups such as children and those who are
not fluent in English. Finally, not only does this enable your web pages to be used in a
wider range of environments, but it also provides search engines with a greater ability to
index your content.

## What Do I Need to Do?

Your web page needs to be accessible to people with disabilities. This means that they
must be able to obtain the same information in an adaptable format that is available to
persons who do not have a disability and who are not using adaptive technology. Your
web page also needs to take reasonable measures to ensure you are not causing undue
harm to persons with disabilities. A summary of key accessibility issues with respect to
web pages are listed below. If you have any questions regarding your responsibility for
designing or maintaining an accessible web page or if you feel that you are unable to
access a web page on campus because it lacks the required accessible features, please
contact one of the following individuals:

**Mark Grosch**
Adaptive Technology Specialist and ADA Web Compliance Officer
grosch-m@sa.ucsb.edu

**Farfalla Borah**
Disability Compliance Officer and Whistleblower Coordinator
farfallah.borah@sa.ucsb.edu

**Gary White**
Acting Director, Disabled Students Program
white-g@sa.ucsb.edu

## Guidelines

Please note that these guidelines are always changing as new technology and markup
standards are created. The following guidelines are summarized from the W3C Content
Accessibility Guidelines version 2.0 and Section 508 of the Rehabilitation Act. They
focus on four premises:

1. Content must be perceivable
2. Interface elements in the content must be operable
3. Content and controls must be understandable
4. Content must be robust enough to work with current and future Web technologies

These premises are further elaborated below:

### A. Content Must be Perceivable

#### 1. Provide text equivalents to all non-text elements

Perhaps one of the most important standards is the concept of a text equivalent for images
displayed on every web page. What this means is that when information is
communicated graphically, there must be alternative textual information available which
communicates the same information as the graphic. This is most commonly accomplished
by using an “alt txt” or “longdesc” tab within the web page. Not only does this help
individuals using screen reading software to understand the information presented on
your page, but it also makes your site more accessible to web crawlers which index
content on the web and make it easier to find via search engines. If a graphic does not
contain any information, tag it using a null tag (empty quotes) in order to avoid
distracting persons using a screen reader. An example of this would be: &lt;IMG
SRC="bluebar.gif" ALT=""&rt;

##### Provide Multimedia Alternatives

This standard also applies to any multimedia
presentation such as a video of an important speaker, news broadcast or other
presentation where the lack of hearing inhibits the understanding of what is being
presented. Information on captioning multimedia presentations can be found in
Appendix VII.

#### 2. Do not rely on color alone to convey information.

Information conveyed by color alone is inaccessible to individuals who are color blind as
well as people who are using a screen reader to convey web information. For instance,
instructions such as “click on the green button to continue” should not be used unless the
green button is identified in a format accessible to persons with colorblindness or other
disabilities which do not allow them to distinguish colors. A better method would be to
use an emphasized elment &lt;em&gt;&lt;/em&gt; or strong element &lt;strong&gt;&lt;/strong&gt; or mark the
item with an * as well as a color.

#### 3. Use markup and style sheets and do so properly. Pages must transform gracefully

Markup sheets should be used according to W3C standards and not simply for
presentation effect (i.e. to achieve a specific font or text size). Pages should still be able
to be read without the associated style sheet – i.e. the content should be arranged in a
logical order.

A page should either be useable without scripts, applets and other programming objects
or an identical alternate page should be readily available which doesn’t require such
objects.

#### 4. Create tables that transform gracefully.

Data tables should have table headers and use attributes such as scope or id and headers
to associate table data with the right headers.
Data tables should feature three items:

* A caption (use the &lt;caption&gt; tag) acting as a title for the table
* A summary attribute (contained within the opening &lt;table&gt; tag
* Table headers

Tables should be used for data and not to lay out pages unless the page will still make
sense when linearized.

#### 5. Ensure that your web page can be viewed by people with color blindness.

For more information on testing your page for “color accessibility: go to
http://colorfilter.wickline.org/ or http://www.vischeck.com (both pages have a filter
though which you can run your web page to test for color discernability). Some other
simple techniques for testing color combinations are to print your web page on a black
and white printer and see if any information is difficult or impossible to discern.
Alternatively, turn the colors all the way down on your monitor and make the same
observation.

#### 6. Repeat image map links as text somewhere else on the page.

Not every web browser can properly interpret image links and in the case of very small
image links, they can be difficult to click on by someone with limited dexterity. Listing
the alternate text links at the bottom of the page is acceptable but closer to the image in
question is preferable.

### B. Interface Elements Must be Operable

#### 7. Design for device-independence.

Your page should be navigable via either a mouse, keyboard, by voice or by a head wand.
Items which only appear during a mouse-over are generally inaccessible to people using
screen readers. Generally speaking, any page which can be navigated via the keyboard
only can also be navigated by voice and by anyone using a screen reader.

#### 8. Ensure user control of time-sensitive content changes.

Do not use automatic client-side redirection or refreshing. If you must use automatic
refreshing, provide ample time between refreshes (a general guideline is 20 seconds for
every line of text. Even better would be to include a button that allows one to disable or
turn off automatic refreshing and redirection. Screen readers are unable to read moving
text.

Try to avoid using the &lt;blink&gt; or &lt;marquee&gt; tags at all costs, but especially between 2
and 55 times per second as this can induce seizures in users with epilepsy or other seizure
disorders. If motion is crucial to your page, you need to allow a user to easily stop the
motion or skip it altogether.

#### 9. Provide mechanisms to help users find content, orient themselves within it, and navigate through it.

Such mechanisms may include site specific search engines, site outlines, tree diagrams,
and the use of proper HTML techniques such as tagging elements as tables, headers, lists
and forms.

When using tables, title each frame to facilitate navigation and describe the frame and
their relationship to the other frames in the table if it is not readily apparent.

Avoid ambiguous navigation tags such as: “Click here”, “More info”, or “Skip intro”.
Wherever possible, use a “title” attribute to further clarify the destination of a link.

It is also helpful to allow users to skip redundant navigation links (i.e. identical links that
appear at the top of every subpage). While a visual user can simply skip over these links,
a person using a screen reader must tab through each link before they can access content.

One technique is to make an anchor at the start of your content:
&lt;a name="content"&gt;&lt;/a&gt;

Then make the first link on the page a link to this anchor. This page can be white on
white if needed to preserve graphical design issues:
&lt;a href="#content"&gt;Skip to Page Content&lt;/a&gt;

Any links which use the same text should go to the same page (i.e. “Link to Our Home
Page” or “Link to Email Us”).

Provide a means to skip over ASCII art and calendars.

#### 10. Use interim solutions.

The following guidelines will change as adaptive technology enables the user to override
certain web page features which adaptive technology users might find problematic:

Do not use pop-up windows. They inhibit the ability of screen readers to read the desired
active screen.

Use a non-link item between links when listing links in a row:
Weather | People | Find | Job Opportunities

#### 11. Use W3C technologies and guidelines.

Use accessible technology specified by W3C such as HTML and CSS while avoiding
PDF and Shockwave which is not as readily accessible. When utilizing PDF documents
provide an alternative HTML page wherever possible. Alternatively, PDF documents
may be used PROVIDED they meet the accessible PDF guidelines listed below.

Text only web pages should be used ONLY as a last resort, as they are invariably not
updated with the same frequency and regularity as the main graphical page.

### C. Content and Controls Must be Understandable

#### 12. Ensure that documents are clear and simple.

Use consistent page layout and clear, simple language.

#### 13. Clarify natural language usage

Identify the natural language of content using the “lang” attribute in HTML or the
"xml:lang" tag in XML in order to facilitate correct pronunciation by screen readers.
This includes specifications for language which are read

#### 14. Provide links to plug-ins and applets

If a page requires the use of a plug-in or applet, there must be a link to the plug-in or
applet from the page requiring it.

#### 15. Use accessible Flash files:

See Appendix V for information on creating accessible Flash files.

#### 16. Use accessible PDF files:

See Appendix VI for information on creating accessible PDF files.

#### 17. Use accessible multimedia files:

See Appendix VII for information on captioning multimedia files.

## Guidelines Specific to the Use of CSS

### Guideline: Decrease maintenance and increase consistency

* Use a minimal number of style sheets for your site
* Use linked style sheets rather than embedded styles, and avoid inline style sheets.
* If you have more than one, use the same "class" name for the same concept in all
of the style sheets.

### Guideline: User override of styles

Allow user specified guidelines (i.e. “important!” style) to override any author-generated
style sheets. This is important for overriding small font sizes as well as undesired color
combinations.

### Guideline: Units of measure

Use relative rather than absolute units of measurement (em or %).

### Guideline: Generated content

Ensure that important content appears in the document object. Text generated by style
sheets is not part of the document source and will not be available to assistive
technologies that access content through the Document Object Model Level 1
([[DOM1]).

### Guideline: Fonts

Instead of using deprecated presentation elements and attributes, use the many CSS
properties to control font characteristics: 'font-family', 'font-size', 'font-size-adjust', 'fontstretch', 'font-style', 'font-variant', and 'font-weight'. If you must use HTML elements to
control font information, use BIG and SMALL, which are not deprecated.

### Guideline: Text style effects

Avoid causing text to blink until such time that this can be overridden by the user.

### Guideline: Text instead of images

Use text instead of images containing text wherever possible. If it is necessary to render
text via an image, an alternate text tag must be provided.

### Guideline: Text formatting and position

Use style sheets to control layout and presentation

### Guideline: Colors

Ensure background and foreground colors provide appropriate contrast. Ensure
information is not in color alone.

### Guideline: Providing contextual clues in HTML lists

Markup lists and list items appropriately.

### Guideline: Layout, positioning, layering, and alignment

Use style sheets to control layout and presentation. Do not use tables for layout unless
table data makes sense when linearized.

### Guideline: Rules and borders

Organize documents so they may be read without style sheets.

### Guideline: Using style sheet positioning and markup to transform gracefully

Removal of associated style sheets should still allow tabular data to be read in a way
which makes logical sense.

### Guideline: Creating movement with style sheets and scripts

Until it is possible for users to freeze moving content, avoid using movement in pages.

### Guideline: Aural Cascading Style Sheets

The following properties are part of CSS2's aural cascading style sheets.

* 'volume' controls the volume of spoken text.
* 'speak' controls whether content will be spoken and, if so, whether it will be
spelled or spoken as words.
* 'pause', 'pause-before', and 'pause-after' control pauses before and after content is
spoken. This allows users to separate content for better comprehension.
* 'cue', 'cue-before', and 'cue-after' specify a sound to be played before and after
content, which can be valuable for orientation (much like a visual icon).
* 'play-during' controls background sounds while an element is rendered (much like
a background image).
* 'azimuth' and 'elevation' provide dimension to sound, which allows users to
distinguish voices, for example.
* 'speech-rate', 'voice-family', 'pitch', 'pitch-range', 'stress', and 'richness' control the
quality of spoken content. By varying these properties for different elements,
users can fine-tune how content is presented aurally.
* 'speak-punctuation' and 'speak-numeral' control how numbers and punctuation are
spoken, which has an effect on the quality of the experience of aural browsing

## Resources

### The World Wide Web Consortium

The worldwide web consortium is an excellent resource for both accessibility guidelines
and web standards in general. Their website is: http://www.w3.org/WAI/ . They have
many resources for specific questions related to accessible web design, and they should
be referenced in order to more fully familiarize yourself with web accessibility. For now,
we will touch on several important W3C Guidelines that you should know about when
designing and maintaining a website:

### WebAIM (Web Accessibility In Mind)

WebAIM is a non-profit organization at Utah State University organized within their
Center for Persons with Disabilities. Their goal is to “…expand the potential of the Web
for people with disabilities by providing the knowledge, technical skills, tools,
organizational leadership strategies, and vision that empower organizations to make
their own content accessible to people with disabilities.” Their website is
http://webaim.org/

## Appendix I: Links to Relevant Case Law

The rights of disabled individuals in the United States are covered under several laws.
These laws are in turn enforced by several agencies:

### Section 504 of the Rehabilitation Act of 1973

(Text: http://www.nationalrehab.org/website/history/act.html )

“Section 504 states that "no qualified individual with a disability in the United States
shall be excluded from, denied the benefits of, or be subjected to discrimination under"
any program or activity that either receives Federal financial assistance or is conducted
by any Executive agency or the United States Postal Service.

Each Federal agency has its own set of section 504 regulations that apply to its own
programs. Agencies that provide Federal financial assistance also have section 504
regulations covering entities that receive Federal aid. Requirements common to these
regulations include reasonable accommodation for employees with disabilities; program
accessibility; effective communication with people who have hearing or vision
disabilities; and accessible new construction and alterations. Each agency is responsible
for enforcing its own regulations. Section 504 may also be enforced through private
lawsuits. It is not necessary to file a complaint with a Federal agency or to receive a
"right-to-sue" letter before going to court.” (Source:
http://www.usdoj.gov/crt/ada/cguide.htm#anchor65610 )

### Section 508 of The Rehabilitation Act of 1973:

(Text: http://www.section508.gov/index.cfm?FuseAction=Content&ID=14 )

“In 1998, Congress amended the Rehabilitation Act to require Federal agencies to make
their electronic and information technology accessible to people with disabilities.
Inaccessible technology interferes with an individual's ability to obtain and use
information quickly and easily. Section 508 was enacted to eliminate barriers in
information technology, to make available new opportunities for people with disabilities,
and to encourage development of technologies that will help achieve these goals. The law
applies to all Federal agencies when they develop, procure, maintain, or use electronic
and information technology. Under Section 508 (29 U.S.C. ‘ 794d), agencies must give
disabled employees and members of the public access to information that is comparable
to the access available to others. It is recommended that you review the laws and
regulations listed below to further your understanding about Section 508 and how you
can support implementation.” For more information, see http://www.section508.gov

### Section 255 of The Telecommunications Act of 1996:

(Text: http://www.fcc.gov/cgb/dro/telecom_language.html )

“The Federal Communications Commission (FCC) has rules requiring
telecommunications manufacturers and service providers to make their products and
services accessible to people with disabilities, if readily achievable. These rules
implement Section 255 of the Communications Act. Where it is not readily achievable to
provide access, Section 255 requires manufacturers and providers to make their devices
and services compatible with peripheral devices and specialized customer premises
equipment that are commonly used by people with disabilities, if such compatibility is
readily achievable.” For more information, see
http://www.fcc.gov/cgb/dro/section255.html

### The Americans with Disabilities Act of 1990:

(Text: http://www.usdoj.gov/crt/ada/pubs/ada.txt )

“The ADA prohibits discrimination on the basis of disability in employment, State and
local government, public accommodations, commercial facilities, transportation, and
telecommunications. It also applies to the United States Congress.

To be protected by the ADA, one must have a disability or have a relationship or
association with an individual with a disability. An individual with a disability is defined
by the ADA as a person who has a physical or mental impairment that substantially limits
one or more major life activities, a person who has a history or record of such an
impairment, or a person who is perceived by others as having such an impairment. The
ADA does not specifically name all of the impairments that are covered.” (Source:
http://www.usdoj.gov/crt/ada/cguide.htm#anchor62335 ).

## Appendix II: The Agencies Who Enforce Access

### The United States Access Board:

The United States Access Board covers Accessible Design and sets standards for
architecture and design. They set rules and standards for such things as size, distribution
and arrangement of disabled parking spaces, wheelchair access for theatres, design
guidelines for talking or chirping crosswalk indicators, etc.
http://www.access-board.gov/

### U.S. Department of Education:

Section 504 is enforced by the U.S. Department of Education, Office for Civil Rights
enforces Section 504 as it applies recipients of Federal Funding for education.
http://www.ed.gov/about/offices/list/ocr/index.html

### The Department of Justice:

Section 508 requires all federal government bodies and their contractors to make
Information Technology accessible for the disabled.
http://www.usdoj.gov/crt/508/508home.html

### The Federal Communications Commission (FCC):

Section 255 of The Telecommunications Act is coordinated by the FCC. They require
the telecommunications industry to make equipment readily accessible or, alternatively
make equipment compatible with assistive technology devices.
http://www.fcc.gov/cgb/dro/section255.html

## Appendix III: Software

Some examples of adaptive software are listed below:

### JAWS Family
(http://www.freedomscientific.com/index.html):

#### Connect Outloud
Internet access through speech or Braille output; designed for the beginning blind
or low-vision user

#### MAGic
Screen magnification software

#### Open Book
OCR and text-to-speech software

#### JAWS for Windows:
Screen reading software for use with Windows

### ZoomText/AI Squared Family
(http://www.aisquared.com):

#### ZoomText Magnifier
Screen magnification software

#### ZoomText Reader
Screen magnification and screen reading software

### Dragon Systems Family
(http://www.scansoft.com):

#### Dragon NaturallySpeaking
Voice recognition software for dictating documents and controlling computer
applications via voice.

### Window-Eyes Family
(http://www.gwmicro.com):

#### Window-Eyes
Screen reading software for use with Windows

## Appendix IV: Designing Accessible Flash PAGES

Macromedia has an excellent guide for creating accessible Flash pages. It can be found
here: http://www.macromedia.com/resources/accessibility/ .

General standards, many of which are equally as applicable to standard HTML
applications, are as follows:

### Hearing disabilities
* Provide synchronized captions for any audio that conveys content

### Photo epilepsy
* Remove strobing content that flashes between 2 and 55 times per second

### Motor disabilities
* Ensure the Flash content is keyboard accessible
* Do not require fine motor skills

### Cognitive disabilities
* Give users control over time sensitive content
* Provide easy to use controls and navigation schemes
* Be consistent
* Use the clearest, simplest language appropriate to the content

### Low vision
* Provide plenty of contrast
* Allow the Flash content to scale to a larger size

### Blindness
* Ensure screen reader accessibility or provide an accessible alternative
* Ensure keyboard accessibility
* Do not interfere with screen reader audio or keyboard commands
* Provide textual equivalents for all non-text elements that convey content
or provide a function.

Please note: In order to be fully accessible to screen readers, the content must have been
developed for accessibility using Flash MX or newer.
Source: http://www.webaim.org/techniques/flash/

## Appendix V: Designing Accessible PDF Documents

Adobe has some very good information on designing accessible PDF Documents. This
information can be found online at:
http://www.adobe.com/enterprise/accessibility/main.html

The full set of guidelines for designing accessible PDF Documents can be found here:
http://www.adobe.com/enterprise/accessibility/pdfs/acro7_pg_ue.pdf

These guidelines are very useful to anyone who is familiar with creating PDF Documents
in Adobe Acrobat. They include information for adding Alt-tags to images inside a PDF,
suggestions for which fonts to use, as well as…

To summarize the most important parts of the document:

* When creating a PDF, make sure you are making a searchable text file and not
just a scan of the document.
* Provide alt-tags for images that convey the same information conveyed by the
image itself.
* Use proper tags to denote headers, figures, text, tables, etc. Although this is
usually easier to do from the original source document than it is from within
Adobe Acrobat, it can be done (see Section 9 of the previously mentioned guide).
* If document is a form, use accessible, fillable form fields, and include
descriptions of the form fields.
* Make sure your document has a logical reading structure.
* Configure your security settings so that they do not interfere with screen readers
(i.e. make sure you’ve enabled the option: “Enable Text Access for Screen Reader
Devices For the Visually Impaired”).

Conclusion:

Adobe has gone to a lot of effort to provide a guide on creating accessible PDFs. It is
updated on a regular basis as newer versions of Adobe Acrobat are released and
should be considered one of the definitive resources for this process.

## Appendix VI: Designing Accessible Multimedia Files

There are a variety of recommended methods for making multimedia files and web pages
accessible. One of these is the W3C group’s Synchronized Multimedia Integration
Language. These lengthy guidelines can be found here:
http://www.w3.org/TR/2005/REC-SMIL2-20051213/

WebAim also has many resources for learning skills such as captioning multimedia
presentations to make them accessible to Deaf and hard of hearing populations:
http://www.webaim.org/techniques/

## Appendix VII: Tools for Validating Accessibility of Web Pages

W3C List of Accessibility Tools:
http://www.w3.org/WAI/ER/existingtools.html

W3C Validator Tool:
http://validator.w3.org/

University of Minnesota List of Accessibility Tools:
http://www.d.umn.edu/goto/tools#accesstools

Web Developer plugin for Firefox Browsers:
https://addons.mozilla.org/extensions/moreinfo.php?id=60

WebXACT Validator:
http://webxact.watchfire.com

Cynthia Says Validator:
http://www.contentquality.com/
