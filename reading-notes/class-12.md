# Readings-Notes-Repository

## Class 12 notes for my Readings in Code Fellows 301 Course

[Back To Main](README.md)


### Reading
[EJS Partials](https://medium.com/@henslejoseph/ejs-partials-f6f102cb7433)

* The first example code for a EJS partial is [here](https://medium.com/@henslejoseph/ejs-partials-f6f102cb7433#9367)
* The above shows 
> <!-- views/partials/navbar.ejs -->
>    <div class="header clearfix">
>        <nav>
>            <ul class="nav nav-pills pull-right">
>                <li role="presentation"><a href="/">Home</a></li>
>            </ul>
>            <h3 class="text-muted">Node.js Blog</h3>
>        </nav>
>    </div>
* from that being stored in the file in the location noted in the comment you'd be able to use ```<%- include( PARTIAL_FILE ) %>``` because <%- %> tags allow you to output the unescaped content onto the page

* Tags and Explanation of 'Includes'
![Tags](/tags-includes.jpg)


### Videos
[Watch EJS tutorial from WalkThroughCode on YouTube, Video 7, Partials](https://www.youtube.com/watch?v=3_xEEH4fTEk&t=0s&index=7&list=PL7sCSgsRZ-slYARh3YJIqPGZqtGVqZRGt)

This is a short, 3-minute video.