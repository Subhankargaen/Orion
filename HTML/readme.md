# Basic Terminology :- 
1. Browser :- IT is an application or a software i.e used to communicate with the server that is present around the World Wide Web (WWW).
2. Website :- It is a collection of realted web pages.
3. Webpage :- It is a collection of HTML , CSS , JS , PHP , Java , XML etc.
4. Domain Name :- It is the name given for the website.
5. URL :- It is Uniform resource Locator .
6. HTTP :- It is the protocol used for communication between client and server .

# HTML :-
- Stands For Hyper Text Mark Up language .
- It is a mark up language used to create  an raw elements like image ,  text , audio , video , forms etc in the web pages.
- HTML is known as the collection of static web pages.

# Structure of HTML :-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>

* <!DOCTYPE html>
      -declares the document types as HTML5

* <html lang="en">
    - Root elements of the html document , specifying  the language as English .

* <head>
    - contains metadata about the document

* <meta charset="UTF-8">
    - Specifies the character encoding for document as UTF-8

* UTF-8
is a character encoding standard that supports a wide range of language and characters .

- <meta name="viewport" content="width=device-width, initial-scale=1.0">
controls the zooming and scaleing of the web page on different devices.

- <title>Document</title>
 sets the title of webpage appearing in the browser's title bar and search engine results.

- <body>
body contains the content of HTML documents .

## Basic Tags Of HTML :-

# Heading Tag:-
- It is used to create text in bolder & bigger size compared normal text .
- It has 6 types of heading tages :- h1,h2,h3,h4,h5,h6
- h1 is the highest heading tag and h6 is the lowest heading tag.

# Paragraph Tag :-
- It is used to create a text in normal size
- <p> </p>

# Break Tag :-
- It is single tag used to create  break a line . 
- It breaks the line and moves the cursor to the next line .
- <br>

# Horizontal Tag :-
- It is a single tag used to create a horizontal line .
- It breaks the line and move the cursor to next line , but before moving the cursor to the next line it creates a horizontal line through out page  .
- <hr>

# SPAN Tag :- (<span> </span>)
- It is used to create to a block to text .
- It is an in-line elements .

## Basic Styles In HTMl :- 
1. bgcolor :- It is used to change the background color of the HTML page .
2. text :- It is used to change the text colour of the web page .
3. algin :- It is used align the content of the page (left,right,center)

   ( # NOTE :- ALL THE ABOVE PROPERTIES USED INSIDE THE TAG)

## Text Styles in Html :-
- <b> It is Used to create bold text,
- <i> It is used to create a italic text.
- <em> It is used to emphasized or italic text.
- <u> It is used to create a underline text.
- <ins> It is used to create a insert/underline text.
- <del>  It is used to create a delete text.
- <sub>  It is used to create a subscript text.
- <sup>  It is used to create a superscript text.
- <mark>  It is used to create a marked text.
- <small>  It is used to create a small text.
- <big>  It is used to create a big text.

## PRE tag :- <pre>........</pre>
- It is used to display the structure of the element the way they are created in code edition .

## Multimedia Tags in HTML :- 
- Multimedia tags are used to add images, audios , videos etc in html.

## Image Tag :-
- <img> tags are used to display a image on web page .

## Attributes / Properties :-
1. src :- It is uses to specify the source of image .
2. alt :- It is uses to specify the alternative text of the image .
3. height :- It is uses to specify the height of the image .
4. width :- It is uses to specify the width of the image .

# syntax :-
<img src="image url" alt="alternative name" >

## Audio Tag :-
- <audio> tag is used to display an audio on web page .

## Attributes / Properties :- 
1. src :- It is used to specify the source of audio .
2. controls :- It gives the option to play/pause , playback speed, volume etc.
3. preload :- it is used to specify the preload of the audio (metadata,none,auto)

# syntax :-
<audio src="audio url" controls preload ="metadata"></audio>

## Video Tag :-
- <Video> tag is used to display an Video on web page .

## Attributes / Properties :- 
1. src :- It is used to specify the source of video .
2. controls :- It gives the option to play/pause , playback speed, volume etc.

# syntax :-
<audio src="audio url" controls preload ="metadata"></audio>

## Iframe Tag :-
- Iframe stands for inline frmae where we can use <iframe> tag to display the content of another website in our web site
## syntax
<iframe width="560" height="315" src="url" title="YouTube video player" frameborder="0"></iframe>

## Hyper Link :-
- Anchor tag is used to create a hyperlink that navigate to another webpage or

## Attributes/Properties :-
1. href :- stands for Hyperlink Reference. It is used to specify the destination of the hyperlink.
2. target :- It is used to specify the target of the hyperlink(_self, _blank).

- _self :- It is used to open the hyper link in the same tab.
- _target :-It is used to open the hyper link in the a new tab.

## syntax:-
<a href ="url" target ="_blank">Link Text</a>

## List :-
- In HTML , a list is structured way to display a collection of items. there are there three types of list avaliable in html .
i. Ordered List (ol)
ii. Unordered List (ul)
iii. Defination List (dl)

## i. Ordered List :-
- It is a type of list , to structuriess the elements in some specific order , either in ascending or decending.
- <ol> tag is used to created list .

# Attributes :-
- type :- It is used to specify the type of the ordered list.(1,a,A,i).
- start :- Starting index e.g :- start = 5. it starts the list from particular position
 e.g:-
 <ol type ="i" start="10">

 ## un-ordered list(ul)
 -<ul> tag is to create ordered list.
 - Un-ordered list can not specify the type of the order items.

 #Attribute:-
 type- disc/circle/square
 e.g:-
  <ul type="circle">
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
 </ul>

 ## Defination list:- <dl>.....</dl>
 -It is used to create a number of defination text &their description & meaning.
 -<dl>tag is used to create defination list.
 -<dd>...</dd> & <dt>...</dt> tags are used to create defination description and  defination text respectively.
 e.g-