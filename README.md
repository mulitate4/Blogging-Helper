# Blogger.com Helper
Just a simple script I wrote for helping me with blogger.com's inconveniences. In fancier terms, I would call it a text processor engine, but I dunno how far that applies to this project.


# What it does
It takes in input through the article.txt, does some python magic and outputs a out.txt file with the converted text. It uses symbols as the first word for it's conversion.

an example: <br>

[article.txt](https://github.com/mulitate4/script_Blogging_helper/files/6448082/article.txt)
```txt
p bruh moment
# lol


p some text here *too*
```

to <br>
[out.txt](https://github.com/mulitate4/script_Blogging_helper/files/6448084/out.txt)
```html
<span style="font-family: Comfortaa; font-size: medium;">bruh moment</span><br>
<span style="font-family: Comfortaa; font-size: xx-large;">lol</span><br>
<br>
<br>
<span style="font-family: Comfortaa; font-size: medium;">some text here <b>too</b></span><br>
```


----
# What do the symbols mean?
The symbols borrow their origin partially from Markdown (a file type).

| Symbol      | Description  |
| ----------- | ------------ |
| #           | Huge Title   |
| ##          | Smaller Title|
| p           | Paragraph    |
| \*text\*    | Bold Text    |
| \[link-title\]\(link) | Links |

Currently, this is the scope for the Script. I'll probably add more features in the near future as and when I need them!

----
# Usage
The script has no dependencies, so just <br>
```git 
git pull https://github.com/mulitate4/script_Blogging_helper
```
and then type in your text in article.txt. One thing to keep in mind is that, every line needs to begin with a symbol from the table above, and then the text after space after the symbol. This is kinda like Markdown, so if you're familiar with it, you should be able to grasp this too. Not a lotta people would use this but I might just make a .exe version for this.
