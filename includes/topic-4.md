Topic 4

Course 1 / Module 1 / Lesson 1 / Topic 4

[Previous][]

--------------------

# required metadata #

![wit-walk-cert2.gif][]

title: \[ARTICLE TITLE | SERVICE NAME\] description: keywords: author: \[GITHUB USERNAME\] manager: \[ALIAS\] ms.date: 04/28/2016 ms.topic: article ms.prod: ms.service: ms.technology: ms.assetid: \[GET ONE FROM guidgenerator.com\]

SOME TEXT IN THE MIDDLE

 

# optional metadata #

\#ROBOTS: \#audience: \#ms.devlang: \#ms.reviewer: \[ALIAS\] \#ms.suite: ems \#ms.tgt\_pltfrm: \#ms.custom:

--------------------

# Metadata and Markdown Template #

This docs.ms template contains examples of markdown syntax, as well as guidance on setting the metadata. It is available in the root directory of each EM Pilot repository (e.g. ~/Azure-RMSDocs-pr /template.md) and is meant to be read as a markdown file, although you can refer to [the published version][] to see how the markdown examples rendeer.

When creating a markdown file you shluld copy the template to a new file, fill out the metadata as specified below, set the H1 heading above to the title of the article, and delete the content.

## Metadata ##

The full metadata block is above, divided into required fields and optional fields; see the [OPS metadata cheatsheet][] for more details. Some key notes:

 *  You **must** have a space between the colon (:) and the value for a metadata element.
 *  If an optional metadata element does not have a value, comment out the element with a \# (do not leave it blank or use "na"); if you are adding a value to an element that was commnted out, be sure to remove the \#.
 *  Colons in a value (e.g., a title) break the metadata parser. In their place, use the HTML encoding of : (e.g., "title: Azure Rights Management: the basics | Azure RMS").
 *  **title**: This title will appear in search engine results. The title should end with a pipe (|) followed by the name of the service (e.g. see above). The title need not (and probably should not) be identical to the title in your H1 heading. It should be roughly 65 characters (including | SERVICE NAME)
 *  **author**, **manager**, **reviewer**: The author field should contain the **Github username** of the author, not their alias. The "manager" and "reviewer" fields, on the other hand, should contain aliases. ms.reviewer specifies the name of the PM associated with the article or service.
 *  **ms.assetid**: This is the GUID of the article from CAPS. When creating a new markdown file, get a GUID from https://www.guidgenerator.com.
 *  **ms.prod**, **ms.service**, **ms.technology**, **ms.devlang**, **ms.topic**, **ms.tgt\_pltfrm**: Possible values for these elements can be found [here][].

## Basic Markdown and GFM ##

All basic and Github-flavored markdown is supported. For more information on these, see:

 *  [Baseline markdown syntax][]
 *  [Github-flavored markdown (GFM) documentation][Github-flavored markdown _GFM_ documentation]

## Headings ##

Examples of first- and second-level headings are above.

There **must** be only one first-level heading in your topic, which will be displayed as the on-page title.

Second-level headings will generate the on-page TOC that appears in the "In this article" section underneath the on-page title.

### Third-level heading ###

#### Fourth-level heading ####

##### Fifth level heading #####

###### Sixth-level heading ######

## Text styling ##

*Italics*

**Bold**

~~Strikethrough~~

## Links ##

To link to a markdown file in the same repo, use [relative links][].

 *  Example: What is Azure Rights Management

To link to a header in the same markdown file, view the source of the published article, find the id of the head (e.g. `id="blockquote"`, and link using \# + id (e.g. `#blockquote`).

 *  Example: [Blockquotes][]

To link to a header in a markdown file in the same repo, use relative linking + hashtag linking.

 *  Example: technical overiew of the sign-up process

To link to an external file, use the full URL as the link.

 *  Example: [Github][]

If a URL appears in a markdown file, it will be transformed into a clickable link.

 *  Example: http://www.github.com

## Lists ##

### Ordered lists ###

1.  This
2.  Is
3.  An
4.  Ordered
5.  List

#### Ordered list with an embedded list ####

1.  Here
2.  comes
3.  an
4.  embedded
    
    1.  Miss Scarlett
    2.  Professor Plum
5.  ordered
6.  list

### Unordered Lists ###

 *  This
 *  is
 *  a
 *  bulleted
 *  list

##### Unordered list with an embedded lists #####

 *  This
 *  bulleted
 *  list
    
     *  Mrs. Peacock
     *  Mr. Green
 *  contains
 *  other
    
    1.  Colonel Mustard
    2.  Mrs. White
 *  lists

## Horizontal rule ##

--------------------

## Tables ##

| Tables | Are | Cool | | ------------- |:-------------:| -----:| | col 3 is | right-aligned | $1600 | | col 2 is | centered | $12 | | col 1 is default | left-aligned | $1 |

## Code ##

### Codeblock ###

``````````
function fancyAlert(arg) {
  if(arg) {
    $.docs({div:'#foo'})
  }
}
``````````

### In-line code ###

This is an example of `in-line code`.

## Blockquotes ##

The drought had lasted now for ten million years, and the reign of the terrible lizards had long since ended. Here on the Equator, in the continent which would one day be known as Africa, the battle for existence had reached a new climax of ferocity, and the victor was not yet in sight. In this barren and desiccated land, only the small or the swift or the fierce could flourish, or even hope to survive.

## Images ##

### Static Image ###

![this is the alt text][]

### Linked Image ###

[![alt text for linked image][this is the alt text]][alt text for linked image_this is the alt text]

### Animated gif ###

![animated gif][]

## Alerts ##

### Note ###

\[!NOTE\] This is NOTE

### Warning ###

\[!WARNING\] This is WARNING

### Tip ###

\[!TIP\] This is TIP

### Important ###

\[!IMPORTANT\] This is IMPORTANT

## Videos ##

### Channel 9 ###

### Youtube ###

## docs.ms extentions ##

### Button ###

\[!div class="button"\] button links

### Selector ###

\[!div class="op\_single\_selector"\]

 *  foo
 *  bar

### Step-By-Step ###

\[!div class="step-by-step"\] [Pre][] [Next][Pre]


[Previous]: /content/microsoft-learning/course-1/module-1/lesson-1/reference-to-cf.html
[wit-walk-cert2.gif]: /content/dam/lessons/IntuneDocs/intune/media/wit-walk-cert2.gif
[the published version]: https://stage.docs.microsoft.com/en-us/rights-management/template
[OPS metadata cheatsheet]: https://ppe.msdn.microsoft.com/en-us/ce-csi-docs/ops/ops-onboarding/managing-content/content-meta-data
[here]: https://microsoft.sharepoint.com/teams/STBCSI/Insights/_layouts/15/WopiFrame.aspx?sourcedoc=%7b7A321BF1-0611-4184-84DA-A0E964C435FA%7d&file=WEDCS_MasterList_CSIValues.xlsx&action=default
[Baseline markdown syntax]: https://daringfireball.net/projects/markdown/syntax
[Github-flavored markdown _GFM_ documentation]: https://guides.github.com/features/mastering-markdown
[relative links]: https://www.w3.org/TR/WD-html40-970917/htmlweb.html#h-5.1.2
[Blockquotes]: #blockquote
[Github]: http://www.github.com
[this is the alt text]: ./media/AzRMS_elements.png
[alt text for linked image_this is the alt text]: https://azure.microsoft.com
[animated gif]: ./media/hololens.gif
[Pre]: https://www.example.com