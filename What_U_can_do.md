#What U Can and Probably Shouldn't do in EPUB
_Talk by Derrick Shultz, NYTimes, formerly of Atavist

##Use SASS
  1. use variables for styling
    * colors, font sizes, etc.
  2. Nesting
  3. Mixins

_ems vs rems_: rems look to the top of sheet for sizing and multiply off of the base elements. 

##Device detection
  1. Don't do it
  2. Use SASS mixins
    * essentially makes CSS modular
   	* mixins can have arguments

 _one __CAN__ make font-sizes scale down to prevent word-breaks

 @media screen and (min-width:5em) and (max-width:10rem) {font-size:.25rem;}


 [Color Contrast Checker](http://snook.ca/technical/colour_contrast/colour.html#fg=33FF33,bg=333333)
 [Scalabe and Modular Architecture for CSS](https://smacss.com/)
 Background-size: Contain?
 GIT for humans


##CSS Animations

* You can do it in iBooks

(Idea: Vanishing text in poetry. Wallace Stevens. Someone has walked across the snow)

