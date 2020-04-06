# display

display  속성   
 ; block : 크기o, 자동으로 아래로 떨어짐  
 ; inline : 크기x, 옆으로 나열   
 ; inline-block : 크기o , 옆으로 나열  
 ; flex : 본인은 block , 자식은 inline , 크기o  



```css
/* 인라인블록 방식 */
.inlineblock { 
    padding: 20px; 
    width: 600px; 
    font-size: 0; /*블럭과 블럭 우 간격 없에기 */
    line-height : 0; /* 블럭과 블럭 하 간격 없에기 */
}

.inlineblock li { 
    display: inline-block; 
    height: 100px; 
    width: 33.333333%; 
    background-color: #fa0; 
    border: 1px solid #000; 
    box-sizing : border-box; 
    vertical-align: top;  /* 위로정 */
    font-size: 16px; /* 폰크사이즈 원래데로 돌리 */
    line-height : 1.5; /* 행간 원래데로 돌리 */
}
```

