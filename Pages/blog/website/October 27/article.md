<font color="white">


# How i write my articles with HTML & Markdown?

<font size="4">

#### Straight Forward Answer

So the type of format i use is through a script i found on stackoverflow you can find it [here](https://stackoverflow.com/questions/37770620/how-to-include-markdown-md-files-inside-html-files) if you scroll down you can find it within the Answers


### Overall

Through the script <a href="https://zerodevx.github.io/zero-md/">< zero-md ></a> im able to create a folder under my Blog path and what i do is i create a folder (the date) kinda like for this one "October 27" and i add article.html and article.md and within the main html file i add the following.



```markdown
<!DOCTYPE html>
<html lang="en">

  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Resources</title>
    <link rel="stylesheet" href="../../../../scripts/CSS.css">
    <link rel="stylesheet" href="../../scripts/grid.css">
    <link rel="stylesheet" href="../../scripts/article.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css">
    <script src="https://cdn.jsdelivr.net/npm/@webcomponents/webcomponentsjs@2/webcomponents-loader.min.js"></script>
    <script type="module" src="https://cdn.jsdelivr.net/gh/zerodevx/zero-md@1/src/zero-md.min.js"></script>
  </head>
  <body>
    <div class="topnav">
        <a href="../../about.html">Back</a>   
      <h3>Resources</h3>
    </div>
<br>
<font color="white">
    <zero-md src="article.md" class="article"></zero-md>
</font>
    <br>
  </body>
</html>
```

Within this HTML file format you can see under the the ```<head>``` tag the first 2 meta tags are just standard html and then title etc and then the next 3 link stylesheets link to the css files in order to style the website and then the 4th one is for logos in order to use the ones from font awesome and the way i used it was on the homepage for the social medida logos and kinda just copy and pasted it for other webpages 


### Main Markdown Code
Then line 13 - 14 for the script source thats what connects the scripts that made it so im able to create a "article.md"

```markdown
<script src="https://cdn.jsdelivr.net/npm/@webcomponents/webcomponentsjs@2/webcomponents-loader.min.js"></script>
<script type="module" src="https://cdn.jsdelivr.net/gh/zerodevx/zero-md@1/src/zero-md.min.js"></script>
```
Then after linking it within the head tag im able to add the following that links to the article.md aka the markdown file.

```
<font color="white">
    <zero-md src="article.md" class="article"></zero-md>
</font>
```

the main code is the ```<zero-md src>``` etc but i just put the font color=white in order for it not to blend into the background.

then you just simply write your article within the article.md file kinda like <a href="raw.txt">this</a>

this article is just to show you how to connect html to markdown and not how to write markdown so if you have not yet learned it its pretty standard and easy but if you need help dont be afraid to reach out! good luck have fun!



# Writer & Credit

<font size="5">
<a href="../../../../index.html">Electric</a> <font size="3">(all socials are on bottom bar)</font>
</font>

</font>




</font>

<br>
