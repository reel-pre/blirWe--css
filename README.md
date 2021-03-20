# blirWe
![logo](https://github.com/reel-pre/blirWe--css/blob/main/images/logo.png)
### A library entirely based on styling CSS cards.

blirWe aims to provide a huge variety of CSS card components.

# Demo: <br/>
![Demo GIF](https://github.com/reel-pre/blirWe--css/blob/main/images/animatedCard.gif)

# Getting started
#### For usage example you can also refer the public folder which contains the html and css files.

Download and add **blirwe.main.css** to your project. After inserting the stylesheet to your html, you can start using the library by assigning the bliCard--X class to your repective div element. Here X is the specific card modifier that you want to use.

Ex: 
 ``` <div class="bliCard--warning">{...content1}  <br/><hr/> {... content2} </div> ```

Here the naming convention is "bliCard--X"
Here X can be replaced by: normal, dark, alert, warning, bliss.

Here is how the cards look with normal and dark modifiers:
![Example1](https://github.com/reel-pre/blirWe--css/blob/main/images/Example1.png)

Here is how the cards look with alert, warning and bliss modifiers:
![Example1](https://github.com/reel-pre/blirWe--css/blob/main/images/Example2.png)


## bliCardDual 

bliCardDual is the second set of cards in blirWe. It has two different section, which are the header(bliCardDual__header) and the content(bliCardDual__content).  
Both the section goes into the "bliCardDual--X" class. Here X is the modifier names.  
Right now 3 modifier names are supported for bliCardDual: normal, alert, warning.  
Ex:  
``` <div class="bliCardDual--alert">  ```</br>
```<div class="bliCardDual__header">{...header} </div>  ```</br>
```<div class="bliCardDual__content">{... content} </div> ```</br>
```</div>```  
Here is how the bliCardDual looks with different modifiers:  
</br>
![Example1](https://github.com/reel-pre/blirWe--css/blob/main/images/Example3.png)



## bliCardNote: <br/>
![Demo GIF](https://github.com/reel-pre/blirWe--css/blob/main/images/animatedCard.gif)

Html for using the above card:  
``` <div class="bliCardNote">  ```</br>
```<div class="bliCardNote__header">{...header} </div>  ```</br>
```<div class="bliCardNote__content">{... content} </div> ```</br>
```</div>```  
