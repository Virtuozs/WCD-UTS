This is repository for Exercise 3 Web Client Development(WCD) 

This repository is intended to explore how HTML and CSS work. I included some overlapping CSS rules to refine and customize the project according to the provided UI design.

### Project Structure

```
├── images/
│   └── balls.svg
|   └── logo.svg
|   └── whatsapp-icon.svg
|   └── woman.svg
├── index.html
├── css/
├── README.md
└── style.css

```

### What I changed

To better understand how HTML and CSS work, I reviewed and corrected the original code. In the HTML file, I fixed several incorrect image asset paths that were preventing images from loading properly. In the CSS, I made adjustments based tips on the comments provided, refining layout, and customizing certain elements to better match the intended UI design.

#### Changes made to the `nav` Element
**Before**
```css
/* Check margin */
nav {
  font-family: 'Mulish', sans-serif;
  color: #000;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
```

**After**
```css
nav {
  font-family: 'Mulish', sans-serif;
  color: #000;
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 45px;
}
```

#### Changes made to the `nav ul` Element
**Before**
```css
/* Check list styling */
nav ul {
  display: flex;
  gap: 48px;
}
```

**After**
```css
nav ul {
  display: flex;
  gap: 48px;
  list-style: none;
}
```

#### Changes made to the `nav ul li a` and `nav ul li a:hover` Element
**Before**
```css
/* Check list link style */
nav ul li a {

}

/* Make text bold on hover */
nav ul li a:hover {
  
}
```

**After**
```css
nav ul li a {
  color: #1F1534;
  text-decoration: none;
  opacity: 0.5;
  font-weight: 400;
  font-size: 18px;
  line-height: 100%;
  letter-spacing: 0;
}

nav ul li a:hover {
  font-weight: 700;
  opacity: 1;
} 
```

#### Changes made to the `.text h1` and `.text h1 span`
**Before**
```css
/* Check margin and font styling */
.text h1 {
  font-family: 'Mulish', sans-serif;
}

/* Check font styling */
.text h1 span {
}
```

**After**
```css
.text h1 {
  font-family: 'Mulish', sans-serif;
  font-weight: 400;
  font-size: 48px;
  line-height: 150%;
  letter-spacing: 0%;
  margin-bottom: 16px;
}

.text h1 span {
  font-weight: 700;
  color: #89C5CC;
}
```


#### Changes made to the `.text p` Element
**Before**
```css
/* Check font styling */
.text p {
  font-family: 'Open Sans', sans-serif; 
}
```

**After**
```css
.text p {
  font-family: 'Open Sans', sans-serif;
  color: #7D7987;
  font-weight: 400;
  font-size: 16px;
  line-height: 160%;
  letter-spacing: 0%;
  margin-bottom: 48px;
  animation-delay: 0.4s;
}
```


#### Changes made to the `.text button` and `.text button:hover` Element
**Before**
```css
/* Check font styling and make sure the button is rounded */
.text button {
  font-family: 'Open Sans', sans-serif;
  display: flex;
  gap: 8px;
}

/* Handle when user hover on the button */
.text button:hover {
}
```

**After**
```css
.text button {
  font-family: 'DM Sans', sans-serif;
  background-color: #69B99D;
  color: #F9F9F9;
  display: flex;
  padding: 14px 32px 15px 32px;
  align-items: center;
  justify-content: center;
  font-weight: 500;
  font-size: 16px;
  border-radius: 4px;
  border: none;
  cursor: pointer;
  gap: 8px;
  width: fit-content;
  text-align: center;
  animation-delay: 0.6s;
}

.text button:hover {
  background-color: #4A9F70;
  text-decoration: underline;
}
```

#### Changes made to the `footer` and `footer a` Element
**Before**
```css
footer {
  font-family: 'Open Sans', sans-serif; 
}

/* Check the text styling */
footer a {
  color: #000;
  text-decoration: none;
  font-weight: 700;
}
```

**After**
```css
footer {
  font-family: 'Open Sans', sans-serif;
  color: #000;
  font-weight: 400;
  font-size: 14px;
  line-height: 160%;
  letter-spacing: 0%;
  text-align: center;
}

footer a {
  color: #000;
  text-decoration: none;
  font-weight: 700;
}

footer a:hover{
  text-decoration: underline;
}
```
