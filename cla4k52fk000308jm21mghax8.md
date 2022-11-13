# Introduction to Web and HTML

# **Introduction about Web Server and Live Server**

### **Web Server**
Whatever we see on the internet is nothing but a web page and these web pages are mainly created through HTML and CSS.

Basically, we create a web page in our local environment i.e, in our system. But, if we want to display our page to the entire world then we have to host our page. And for fulfilling this purpose of hosting and rendering or publishing the created page on the internet web server plays an important role.

So, what is a **web server**?

A web server is a software or hardware which stores and delivers the content for a website to a client that requests it. Apache ang Nginx are couple of examples of web servers.

![pexels-realtoughcandycom-11035538.jpg](https://cdn.hashnode.com/res/hashnode/image/upload/v1667681477219/pfgil5BIj.jpg align="left")

**Apache** is one of the most famous open-source web server which is used by many hosting applications for rendering the web sites.

### Live Server
When we want to view the page after creating a html file, we have to open the file and every time we make any changes in the code we have to manually reload the page as the page is served through system's memory. To overcome this job of reloading an extension named **Live Server** was created. Live Server does this task of reloading just by tracking the status of the code which is written or modified.

One of the most famous Live Server extension is **Live Server by *Ritwick Dey***.

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1667682550354/d2CsKDpiy.png align="left")

# HTML and HTML tags

![pexels-pixabay-270404.jpg](https://cdn.hashnode.com/res/hashnode/image/upload/v1667683259151/yQ2v5Neux.jpg align="left")

HTML stands for **HyperText Markup Language** which is used for creating a basic structure of a web page.

A HTML file is either saved by using .html extension or by using .htm extension and also we should follow the coding standards and name this HTML file as index.html or default.html. We should use either of these two names because in web servers all files are saved in the location /var/html/www and by default index.html or default.html are served to the web server.

### Basic HTML Tags

The following snippets shows the skeleton of a html file.

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1667684366423/YtkTmLkGe.png align="left")

- **```
<html></html>
```** - Every html file begins and ends with this tag. Whatever code we write should be inside this tag.

- **```
<head></head>
```** - This tag is contains all the meta information about the document. These informations are not visible to the end users but it loads up.

- **```
<body></body>
```** - This tag is the main part of the html file as all the informations which are displayed to the end users are inside this tag only. Whatever we want to display on the web page should be written inside this tag.

- **```
Heading tags
```** - There are 6 types of heading tags ```
<h1>
``` to ```
<h6>
```. h1 being the largest and h6 being the smallest. Refer the below snapshot for code snippet and it's output.

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1667686259632/bCIkDHC2M.png align="center")

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1667686756802/4tRtg9J5M.png align="center")

- ```
<p></p>
``` - This is a paragraph tag. Any amount of text which we want to display in a paragraph in written inside this tag.

- ```
<br>
``` - This tag is used for creating a line break in the web page.

- ```
<img>
``` - This tag is used for displaying the image on the web page. We mainly use src and alt attribute of this tag. src attribute is used for the path of the image file and alt attribute is used to display any text in case the image is not displayed.

```
<img src="./image.png" alt="image" />
```

If you want to read in depth about the ```
<img>
``` tag. Follow this [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img).

- ```
<a>
``` - This anchor tag is used to insert hyperlink on the web page for linking one page to another. Most commonly attribute of this tag is href which indicates the link's destination.

```
<a href="https://www.youtube.com/">youtube</a>
```
lorem - If we want to generate lorem ipsum texts on the webpage then we use this. For example: 
```
lorem20 will generate lorem ipsum texts with 20 words.
lorem50 will generate lorem ipsum texts with 20 words.
```
Similarly, if we write any number after lorem, then the same number of words will be displayed.
### Thanks for reading. Hope this helps. 























