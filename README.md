#Stylus-Mixins

Various [Stylus](http://learnboost.github.com/stylus/) mixins (CSS).

### pos
    
    pos absolute 10px 0 25px 12px
    --->
    position: absolute;
    top: 10px;
    right: 0;
    bottom: 25px;
    left: 12px;
    
    pos fixed 5px
    --->
    position: fixed;
    top: 5px;
    right: 5px;
    bottom: 5px;
    left: 5px;
    
    pos absolute 0 12px
    --->
    position: absolute;
    top: 0;
    right: 12px;
    bottom: 0;
    left: 12px;
    
    
### min-size

    min-size 10px
    --->
    min-width: 10px;
    min-height: 10px;
    
    min-size 2px 10px
    --->
    min-width: 2px;
    min-height: 10px;
    
### borders

    borders #00f
    --->
    border: 1px #00f solid;

    borders left 3px
    --->
    border-left: 3px #000 solid;
    
    borders top right #f00
    --->
    border-top: 1px #f00 solid;
    border-right: 1px #f00 solid;
    
    borders left bottom 3px #0f0 dashed right #000 top 4px
    --->
    border-left: 3px #0f0 dashed;
    border-bottom: 3px #0f0 dashed;
    border-right: 1px #000 solid;
    border-top: 4px #000 solid;
    
### size

    size 100%
    --->
    width: 100%;
    height: 100%;
    
    size 10px 100px
    --->
    width: 10px;
    heigth: 100px;
    
### [inline-]block 

    block 50px
    --->
    display: block;
    width: 50px;
    height: 50px;
    
    inline-block 10px 100px
    --->
    display: inline-block;
    width: 10px;
    height: 100px;
    
### type

    type #f00 14px center
    --->
    color: #f00;
    font-size: 14px;
    text-align: center;
    
### reset

    reset()
    --->
    padding: 0;
    margin: 0;
    border: 0;