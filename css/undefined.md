# 블록요소를 가로정렬

1. float : left
2. display : inline-block

display  속성   
 ; block : 크기o, 자동으로 아래로 떨어짐  
 ; inline : 크기x, 옆으로 나열   
 ; inline-block : 크기o , 옆으로 나열 



```markup
<ul class="float">
  <li></li>
  <li></li>
  <li></li>
</ul>

 <ul class="inlineblock">
  <li>
    <div>test</div>
  </li>
  <li></li>
  <li></li>
</ul>
```

```css
// 리셋 CSS
*{
    padding: 0; 
    margin: 0;
}
    
ul { 
    width: 600px; 
    list-style: none;
}

.float { 
    padding: 20px; 
    height: 100px; 
}

.float li { 
    height: 100px; 
    float: left; 
    width: 33.333%; 
    background-color: #fa0; 
    border: 1px solid #000; 
    box-sizing : border-box; 
}

.inlineblock { 
    padding: 20px; 
    width: 600px; 
    font-size: 0; 
}

.inlineblock li { 
    display: inline-block; 
    height: 100px; 
    width: 33.333333%; 
    background-color: #fa0; 
    border: 1px solid #000; 
    box-sizing : border-box; 
    vertical-align: top; 
    font-size: 16px; 
}
```

