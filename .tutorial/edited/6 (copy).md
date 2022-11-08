# 6. Adding Styles

**Learning Goal**:
1. Learn how to style a page using `<style>` tag and a language called **CSS**.


**Time**: 5 mins

![](https://youtu.be/QQm2i6J_Slw)




## 👉 TRY IT : ......

1. Add this to the end of your code. Feel free to choose different colors, fonts, or sizes:

```html
<style>
p {
	font-family: sans-serif;
	font-size: 24px;
	color: red;
	background-color: yellow;
}
</style>
```

and guess what it'll do to your web page...

<details>
<summary>See what Mark did:</summary>
	
![Mark's hotdog-themed site](images/hotdog.png)
</details>




- If we want a specific style for one specific `<p>` element, we need another type of selector here, the ID selector.

2. Try changing the code above to this:

```html
<style>
#purple {
	color: #ff00ff;
}
</style>

<p>this text is not purple</p>
<p id="purple">this text is not purple</p>
```

## Let's summarize:
- **CSS** (**C**ascading **S**tyle **S**heets) code is written inside `<style>` tag. CSS looks like this:

```css
selector {
	key1: value1;
	key2: value2;
	key3: value3;
}
```

- **Selector**:
  - what elements do the following styles apply to (e.g. `<p>` means applying to all `<p>` tags). 
- **Key**:
  - name of the style rule like {`font-family`}
- **Value**:
  - value of the style rule like {`sans-serif`}

- Don't forget curly braces  `{` `}`.
### Look at this code:

```css
p {
	font-family: sans-serif;
	font-size: 24px;
	color: #ff0000;
	background-color: #ffff00;
}
```

We're defining some styles for all elements with `<p>` tag, and we're changing the following style rules:
- `font-family`: to change the font
  - `sans-serif` is a font style that's built-in to browsers
- `font-size`: to change the font size
  - `24px` means our font size is **24 pixels**
- `color`: to change the foreground color
  - `#ff0000` is the hex code for color **red**
- `background-color`: to change the background color
  - `#ffff00` is the hex code for color **yellow**

There are a ton of CSS rules to customize a ton of styles, we'll learn a lot of common ones in this tutorial, but here's the [MDN Documentation on CSS](https://developer.mozilla.org/docs/Web/CSS/Reference) if you want a more thorough list!


### You have created a basic webpage. Now let's share it with the community!