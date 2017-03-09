# dConsole

dConsole is a custom way to send console messages for JavaScript

### The function is divided into 3 parts (parameters):

* **Message**			(Example: "Shreek is an ogre")
* **Background Color**	(Example: "crimson")
* **Text Color**		(Example: "#fff")

---

### To call the default function:

```javascript
dConsole ("I have an apple");
```

Here's the result:

![alt tag](https://raw.githubusercontent.com/dcy987/dConsole/master/screenshots/screenshot-01.png)

(As you can see, if you only send the **message without custom styles**, the function is called using the **default style**)

---

### To call the custom color function:
You can add `any color` to the last 2 parameters 

```javascript
dConsole ("Shrek is an ogre", "crimson", "#fff");
```
And here's the result of the custom style:

![alt tag](https://raw.githubusercontent.com/dcy987/dConsole/master/screenshots/screenshot-02.png)
