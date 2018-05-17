# css-sexangle-draw
css绘画六边形
##### .wrapper{
    margin: 100px;
    height: 200px;
    width: 346.3px;
    background-color: red;
    position: relative;
}   
.wrapper:before{    
    content: '';    
    display: block; 
    position: absolute; 
    top: -100px;    
    border-left:173.2px solid transparent;  
    border-right:173.2px solid transparent; 
    border-bottom: 100px solid red; 
}    
.wrapper:after{ 
    content: '';    
    display: block; 
    position: absolute; 
    bottom: -100px; 
    border-left:173.2px solid transparent;  
    border-right:173.2px solid transparent; 
    border-top: 100px solid red;    
}   
