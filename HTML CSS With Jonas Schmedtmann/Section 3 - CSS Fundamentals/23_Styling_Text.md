# 23. Styling Text

### 1. First Styling our main heading first 
```CSS
h1 {
  /* color: blue; */
  font-size: 26px;
  font-family: sans-serif;
  text-transform: uppercase;
  font-style: italic;
}
```
#### NOTE
* The **text transform** has attributes  
  1. **capitalize** - This **capitalizes all the first letters** in the word
  2. **UpperCase** - This **capitalizes all the letters** within the h1 tag  
* After you make all the necessary changes your webpage will look like this 
![Styling the H1](./images/23_Styling_The_H1.png)
* with the help of **font-style**, you can make the text to be **italic/bold..etc..**

### 2. Setting the **h2 tag** here 
```CSS
h2 {
  font-size: 40px;
  font-family: sans-serif;
}
```
#### NOTE
* It is not necessary that h2 tag should be smaller than h1(Semantically it might be the case but it is not necessary)

### 3. Styling the **p tag**
```CSS
p {
  font-size: 22px;
  font-family: sans-serif;
  line-height: 1.5;
}
```
#### NOTE
* Here i have set the line-height to 1.5 (which conveys that **line height = 1.5 * (font-size)**)

