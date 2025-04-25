# IFrames

**`<iframe>`**
- An **`iframe`** is like a little window that has been cut into your page - and in that window you can see another page. The term **`iframe`** is an abbreviation of **inline frame**.
- One common use of **iframes** is to embed a Google Map into a page. The content of the **`iframe`** can be any html page (either located on the same server or anywhere else on the web).

An iframe is created using the **`<iframe>`** element. There are a few attributes that you will need to know to use it:
**`src`**
- The **`src`** attribute specifies the URL of the page to show in the frame.

**`height`**
- The **`height`** attribute specifies the height of the iframe in pixels.

**`width`**
- The **`width`** attribute specifies the **`width`** of the iframe in pixels.

---
- *Example:*
```html
<iframe
width="450"
height="350"
src="http://maps.google.co.uk/maps?q=moma+new+york
&amp;output=embed">
</iframe>
```

---
- *Result:*

<iframe
width="450"
height="350"
src="http://maps.google.co.uk/maps?q=moma+new+york
&amp;output=embed">
</iframe>

---

**`scrolling`**
- The **`scrolling`** attribute will not be supported in HTML5. In HTML 4 and XHTML, it indicates whether the **`iframe`** should have scrollbars or not. This is important if the page inside the iframe is larger than the space you have allowed for it (using the height and width attributes).
- Scrollbars allow the user to move around the frame to see more content. It can take one of three values: 
	- **`yes`** (to show scrollbars),
	- **`no`** (to hide scrollbars) and 
	- **`auto`** (to show them only if needed)

**`frameborder`**
- The **`frameborder`** attribute will not be supported in HTML5. In HTML 4 and XHTML, it indicates whether the frame should have a border or not. 
	- A value of **`0`** indicates that no border should be shown. 
	- A value of **`1`** indicates that a border should be shown.

**`seamless`**
- In HTML5, a new attribute called **`seamless`** can be applied to an **`iframe`** where scrollbars are not desired. The **`seamless`** attribute (like some other new HTML5 attributes) does not need a value, but you will often see authors give it a value of seamless. Older browsers do not support the seamless attribute.

---