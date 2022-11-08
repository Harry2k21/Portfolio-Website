# 3. Images

**Learning Goal**:
1. Learn how to add an image to your repl.
2. Discover how to manage files.
3. Share your website url with others.

**Time**: 10 mins

![](https://youtu.be/CI4noac5ibE)




## 👉 TRY IT : ......
1. Add this line to the end of your code:

```html
<img src="mark.png">
```

You should see Mark's face popping out. (Yes, at Replit we call this little guy *Mark*)

![our first image](images/image.png)



2. Try to achieve this:

![multimark](images/multimark.png)

<details>
<summary>See what Mark did:</summary>

```html
<img src="mark.png">
<img src="mark.png">
<img src="mark.png">
<img src="mark.png">
<img src="mark.png">
<img src="mark.png">
<img src="mark.png">
```

</details>





3. Look at the sidebar on the left side. You are currently in the `Tutorial` (the icon with the book).
4. The second icon (page with the folded corner) is the `files` tree.
5. Click on `Files` to see what it looks like and then come back here (to `Tutorial`)
6. `Files` is where we store all our files.
7. You can see we're currently editing `index.html`, which is the code for our web page, and there's a `mark.png`, which is the image we just imported.

![click the second icon on the sidebar to enter Files tab](images/files.png)



8. Upload your image (drag it into the file or choose `add file`) and rename it..
  
![Upload and rename](images/UploadFiles.gif)


9. After uploading your own image, change the `<img` code to match the file name.
10. Remember, the words inside `""` here must be the same name you gave to your file in the file tree. 

```html
<img src="mark.png">
```



11. Add a description of the image using `alt` and add `width` and `height`. 

```html
<img src="mark.png" alt="an image of mark" width="640" height="240">
```
<details>
<summary>See what Mark did:</summary>

Here's what Mark has:

```html
<h1>Hello!</h1>
<p>My name is Mark</p>
<p>I like <b>boxing</b> and <i>fishing</i></p>
<p>My favorite band is <b>Can</b>, my favorite album is <i>Ege Bamyasi</i></p>
<p>I've won prizes in <b>3</b> fishing competitions</p>
<p>I have a best friend. His name is <b>Bean</b></p>
<img src="mark.png" alt="an image of mark" width="640" height="240">
```

![more about Mark](images/moreaboutmark.png)
 
</details>

12. You have a working website already! Share it with others. Click the URL in the webview header and copy and share it with people.

![open in new tab](images/ext.png)

## Check out this Replit user:
Check out this [Repl link](https://replit.com/@slmjkdbtl/lilfang) to see a new user's [photo album of my cat lil fang](https://lilfang.slmjkdbtl.repl.co/) created using only what we have learned:

![only using what we've already learned!](images/lilfang.png)


## Let's summarize:
- You can drag and drop an image into the files pane (or choose `add file` icon). Make sure the name of your image and the source are listed (jpg, png, gif, etc.).
- `<img` is the tag used when adding an image. This tag has a second part called an `src` (stands for "source") attribute which is where the name of the file is written (don't forget the source too...gif, jpg, etc.).
- `<img` does not need a closing tag.
- `<alt>` allows you to add text that matches the image (this helps people who use a screen reader and can't see the image).
- The `width=` and `height=` can be adjusted for your image.
- Open and share your website using the link in the `output` pane.

![tags with attribute](images/imgtag.png)


> Don't forget to add quotation marks around attribute values!
>
> -- Amjad Masad, CEO man

### Now let's learn how to add links!