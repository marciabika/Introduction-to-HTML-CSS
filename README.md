# Introduction-to-HTML

Understanding the fundamental syntax of HTML elements-HTML element components. 
HTML forms a foundation of website and web app development, it is a language that allows you to make sure your content is understandable to both people and computers.
HTML serves as a chanel for different types of content like words, images, videos, audio, forms, and interactive expiriences. 
Essentially, it forms a solid foundation for everything else in the digital realm.
HTML has a straight forward structure without any programming logic, loops or functions. It is a devlarative language. It is all about using the right vocabulary and making declarations.
HTML can handle a lot of abuse and still deliver a functional result.
If HTML is broken because of a bug in a code, the browser guesses what you meant, and does its best to fix the bug itself. 
HTML element is defined by an open tag<> and closing tag</>. There are empty elements without a closing tag like<br>(break).


Formatting and styling content in HTML.
Formatting elements were designed to desplay special types of text. 
The purpose of HTML markup is to give meaning to the content and help computers understand it. HTML contains several elements for defining text with a special meaning.
These are the different types of elements used to format and style text:

p-paragraph

h1 to h2-headings

i-making a text italic

em-to emphasise on a text

strong-to show importance to a certain word

b-To make a text bold

ul-Unordered list

ol-Ordered list(usually the list is in numbers

li-List

dl-Difnition list

dt-Unordered difnition list

dd-Ordered difnition list

form-for creating a form
To create a form, we start with the form element, which informs the browser about the presence of a form using opening and closing tags. In the newsletter signup form, there will be two fields: name and email. These field names can be turned into labels using the label element. 
Use the input element to provide places for users to input their name and email. Unlike other elements, the input element does not have a closing tag due to its older structure. It acts as a marker for the browser to bring in functionality and place it there. This is where the form's magic happens. 
Now, a button is needed for users to submit the form. Use the button element for this. The text on the button can be customized to whatever is required. Although the form looks good visually, it currently lacks functionality. To make it work, we need to connect it to a backend. We can add an action and method attribute to make a demo work, although using the "get" method is not secure and is not recommended for real websites.
Once set up, land on the response page, but the data that was entered does not appear. This is because the input fields need a "name" attribute to report the data. Add "name=name" to the first input element and "name=email" to the second. The name attribute can be customized as desired. After making these changes, the form works successfully, but only if you interact with it using a screen and a mouse. 
To make it accessible to everyone, we need to address the issue of the label and input elements not being connected. There are two options to achieve this. 
1.	Add a "for" attribute to the label that matches the "id" attribute of the input. 
2.	Wrap the input with the label. 
Both methods work, and it is a matter of choosing the desired markup structure. You can test the connection by clicking on the label and ensuring that the focus jumps to the corresponding input. This is crucial for accessibility, as many people rely on this connection. Clicking on the label is a quick way to verify its functionality. 

nav-List of links like home, contact us, about us e.t.c
The nav tag is used for defining navigation sections on a
webpage. It serves to organize and present links that facilitate
user navigation within or outside the current webpage which helps
users move around the website with ease.



Incorporating time and date inputs.


Working with graphics and Adding images into HTML pages.
There are four main file formats commonly used on the web these days, each with its own strengths and weaknesses when it comes to compressing images. 
GIF-GIFs are great for compressing illustrations that have large areas of the same color, but it falls short when it comes to photographs. It only supports 256 colors, and images can end up looking pixelated, unless you want that retro vibe. 

JPG-JPGs are a popular choice for compressing photographs. Most digital cameras save images in JPG format, but when placed on the web, it is important to resize and compress them appropriately. 

PNG-PNG is a newer format that works well when you need transparency in a photograph. It sometimes outperforms both GIF and JPG in compressing certain types of images.

SVG-SVGs are perfect for logos, icons, and other types of illustrations. Unlike GIF, SVG is a vector file that contains instructions for drawing rather than individual pixels. This means it can be scaled to any size without losing quality, and the file size remains small. 

Workng with figures and figcaption elements. 

Establishing hyperlinks and creating clickable links.

Utilizing global HTML attributes.

Working with the audio and video element.

Developing navigation menus and structures. 

Organizing and structuring content effectively. 

Contsructing interactive forms.

Creating tables to display data.

Functions of HTML.

HTML capabilities (Trouble shooting and debugging of code).

Reviewing broken code.

Learning how to make comments in HTML.

Discovered how to get an embedded link from Youtube and working with the iFrame element and considering security aspects related to the iframe element when builing a website. 

Using code inspector to debug HTML.

Creating URLs.

Working with the lang(language of a webpage) and charset(character set) attributes to help indicate the language of your content.
