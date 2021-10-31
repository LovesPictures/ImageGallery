##
# Project 5: Flex Panels Image Gallery
Made with vanilla JavaScript

Judith Ricketts, Artist, Lecturer and Software engineer - [Contact](https://lovespictures.com/)  
Commit Date: 31 st October 2021

## Guide

<!-- Javascript array methods are arrays forming a data structure containing list of elements which store multiple values in a single variable. The strength of JavaScript arrays lies in the array methods which are built-in functions we can apply to our arrays.  Each method has a unique function that performs a change or calculation to our array, saving having to write common functions from scratch. -->

![image](https://user-images.githubusercontent.com/25634451/139583986-0abf4818-03ae-43f5-b326-fb936e86b74d.png)
  
## Approach

![image](https://user-images.githubusercontent.com/25634451/139527566-d4ca18eb-0629-4cbf-91ec-254eb1f6bfab.png)
<!-- after stage 10 in the code  -->
Nested flexbox, work in progress 

### listening event 

![image](https://user-images.githubusercontent.com/25634451/139581859-7ef6532b-e778-4c65-a7a2-5c0c71a413bb.png)
<!-- after stage 18 in the code  -->
Listening for 'click' event to grow and end the animation 

<!-- elements -->
<!-- elements -->
 panels.forEach(panel => panel.addEventListener('click', toggleOpen));
   panels.forEach(panel => panel.addEventListener('transitionend', toggleActive));
<!-- elements -->

<!-- elements -->
### long version of the code 
    const ordered = inventors.sort(function(a,b){
        if(a.year > b.year) {
              return 1;
       } else {
        return -1;
       }
    });    
    console.table(ordered);
<!-- elements -->
<!-- elements -->
 
 
## Useful links
* [40 CSS & Javascript Image Gallery Examples](https://bashooka.com/coding/css-javascript-image-gallery-examples/) 
* [Creating an infinite gallery with vanilla JS](https://weareferal.com/blog/creating-an-infinite-gallery-with-vanilla-js) 
* [Responsive Gallery with Vanilla JavaScript ES6](https://itsgus.dev/2021/vanilla-javascript-gallery)
* [What is flexbox?](https://flexbox.io/)


<!-- A List of JavaScript Array Methods -->
<!-- guide  https://github.com/nitishdayal/JavaScript30 -->
<!-- formatting read.me https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax -->
