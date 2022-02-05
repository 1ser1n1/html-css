## 스타일을 적용하는 방법

**1. `<style>` 태그**
````html
    <style>
     h1 { 
     color: green; 
     text-align: center; 
     } 
     
     p { 
     font-size: 18px; 
     } 
     </style> 

     <h1>Hello World!</h1>
     <p>hi, hi</p>
````
**2. style 속성**
````html
<h1 style="color: green; text-align: center;">Hello World!</h1>
<p style="font-size: 18px;">hi hi</p>
```` 

**3. 외부 CSS  파일 + `<link>` 태그**
- css/style.css
```css
h1 {
  color: green;
  text-align: center;
}

p {
  font-size: 18px;
}

```
- index.html
````html
<link href="css/styles.css" rel="stylesheet"> 
<h1>Hello World!</h1> 
<p>hi hi</p>
```` 
