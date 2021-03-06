# dConsole

dConsole is a very lightweight tool that displays custom console messages on your browser (JavaScript code).

### The function is divided into 3 parts (parameters):

* **Message**: Anything you want to type, including variables. (Example: "Shrek is an ogre")
* **Background**: The background color or gradient. (Example: "crimson")
* **Color**: The text color. (Example: "#fff")

```javascript
dConsole ("message","background","color");
```

---

### To call the default function:

```javascript
dConsole ("I have an apple", "background", "color");
```

Here's the result:

![Screenshot 01](https://raw.githubusercontent.com/dcy987/dConsole/master/screenshots/screenshot-01.png)

You can also send the **message without the 2nd and 3rd parameter** to use the **default style**
```javascript
dConsole("I have an apple");
```

---

### To call the custom color function:

```javascript
dConsole ("Shrek is an ogre", "crimson", "#fff");
```

You can add **any color** to the last 2 parameters

And here's the result of the custom style:

![Screenshot 02](https://raw.githubusercontent.com/dcy987/dConsole/master/screenshots/screenshot-02.png)

---
### To call the Gradient function:

You can make a 2 color gradient by typing `"gradient-color1-color2"` in the **2nd parameter** (**Background Color**)
So here's what you would type:

```javascript
dConsole("2 Color Gradient", "gradient-indigo-royalblue");
```

And here's what it looks like:

![Screenshot 03](https://raw.githubusercontent.com/dcy987/dConsole/master/screenshots/screenshot-03.png)

### Extra:
**To call the Gradient Rainbow function:**

You can add a gradient rainbow by typing `"rainbow"` in the **2nd parameter** as well

So this would be the code:

```javascript
dConsole("Color Spectrum", "rainbow");
```

And here's what it looks like:

![Screenshot 04](https://raw.githubusercontent.com/dcy987/dConsole/master/screenshots/screenshot-04.png)

---

### How to install it?

This works just like a framework

1. **Download** the **dconsole-min.js** file from the **js** folder in this repository.
2. Link it in your HTML head like this:

```html
<head>
	<!-- dConsole -->
	<script src="js/dconsole-min.js"></script>
</head>
```
