# 100 Days Of Code - Log

### Day 0: January 6, 2019 

**Today's Progress**: Repeated Basic HTML and a little Basic CSS

**Thoughts:** I remember almost all of Basic HTML. Not bad.

*Mark:*
+ main - for SEO; 
+ required in input - user will not be able to submit form until user filled them out;
+ same radio button shoud have same name atribute;
+ use atribute for on label and same id in input;

### Day 1: January 8,2019

**Today's Progress:** Repeated Basic CSS. Applied Visual Design

**Thoughts:** I need more practice in variables and media query. I have learned a lot of new things from section Applied Visual Design. 

*Mark:*
+ [attr=value] to change style of elemen with specific atribute
+ em and rem - relative lenth units
+ !important to make style important
+ CSS variables 
+ media query
+ tag *strong, em, u, s*
+ *hr* to make horizontal line
+ opacity - from 1, which is fully opaque or a solid color, to 0, which is fully transparent or clear
+ *box-shadow*
+ *text-transform* to make uppercase, lowercase and other
+  *font-weight* sets how thick or thin characters are in a section of text
+ relative position doesn't remove element from the normal flow, other element round it still behave as if that item were in its default position
+ absolute position delete element from normal flow and lock it  in place relative to its parent container
+ fixed position locked element to the browser window
+ *float* remov element from the normal flow of a document and push it to either the left or right of their containing parent element. You can use it to make two column
+ *z-index* higher values covers 
+ *linear-gradient()* for *background* looks cool. Try to use it
+ *repeatin-linear-gradient()* too
+ you can use *transform: scale(..);* witj hover
+ you can skew element with *transform: skewX/skewY(..deg)*
+ i need practice with :before and :after
+ @keyframes - animation 
  + *cubic-bezier*
  
  ### Day 2: January 22, 2019 

**Today's Progress**: Applied Accessibility

**Thoughts:** It was easy. I think it must on page to make easier life for people with some disableties.

*Mark:*
+  use *main* to wrap central information on your page
+ *<div>* - groups content
+ *<section>* - groups related content
+ *<article>* - groups independent, self-contained content
+ *audio* tag including *controls* for play, pause and others and *source* with *src* and *type* 
+ tag *figure* and *figcaption*
+ *label* atribute *for* associate that *label* with the form control. *for* must be the same with *id*
+ *fieldset* and *legend* to surround radio buttons
+ *input* with type *date*
+ *time datetime*
+ with CSS you can make content visible only to a screen reader
+ contrast ratio between background color  and text color must be 6:1
+*accesskey* *tabindex*
  
  ### Day 3: January 23, 2019 

**Today's Progress**: Responsive Web Design. CSS Flexbox

**Thoughts:** More practice with responsive WD plz. More. Using Flexbox - cool. You can make beautiful web-page with it.

*Mark:*
+ media query
+ max-width: 100%; height: auto;
+ retina image. Width and height are only half of what the original file 
+ Viewport units are relative to the viewport dimensions (width or height) of a *device*, and percentages are relative to the size of the *parent container element*.
  +vw
  +vh
  +vmin
  +vmax
-------------------------
+ display: flex;
+ *flex-direction* row,column
+ https://www.w3.org/TR/css-flexbox-1/images/flex-direction-terms.svg
+ *justify-content* center, flex-start, flex-end, space-around, space-between. It's for main axis
+ *align-items* flex-start, flex-end, center, stretch, baseline
+ *flex-wrap* Next item move into a new row or column. The break point of  wrapping happens - the size of the items and the size of the container.
+ *flex-shrink* 
+ opposite to preveous *flex-grow*
+ *flex-basis* to set initial size of an item
+ *flex* flex-grow:  flex-shrink:  flex-basis: 
+ Use the *order* Property to Rearrange Items
+ *flex-self* to adjust each item's alignment individually

 ### Day 4: January 24, 2019 

**Today's Progress**: CSS Grid

**Thoughts:** Just practice more.

*Mark:*
+ to set element into a grid container, you need to setting *display* property to *grid*  
+ to make some columns use *grid-temolate-column: 50% 50%(for example)*
+ *grid-temolate-rows*
  + fr: sets the column or row to a fraction of the available space,
  + auto: sets the column or row to the width or height of its content automatically,
  + %: adjusts the column or row to the percent width of its container.
+ to make gap between columns use *grid-column-gap* (for rows *gris-row-gap*)
+ *grid-gap: [between rows] [between columns];*
+ *grid-column* and *grid-row*
+ *justify-self* the content of each item in grid is located in cell. It's align this item in this cell. **Horizontal**. *justify-items* for all items
+ *align-self* same but **vertical**. *align-items* for all
+ *grid-template-areas* ?????
+ grid-area: horizontal line to start at / vertical line to start at / horizontal line to end at / vertical line to end at;
+ *repaet()* to make some columns/rows with same size
+ grid-template-columns: repeat(3, **minmax**(90px,1fr)) ;
+ grid-template-columns:repeat(**auto-fill**, minmax(60px, 1fr));
+ grid-template-columns:repeat(**auto-fit**, minmax(60px, 1fr));
  + The only difference is that when the container's size exceeds the size of all the items combined, auto-fill keeps inserting empty rows or columns and pushes your items to the side, while auto-fit collapses those empty rows or columns and stretches your items to fit the size of the container.
+ grid within grid

### Day 5: January 25, 2019 

**Today's Progress**: Practice. Start intensiv and portfolio page. FCC's project Tribute page.

**Thoughts:** I don't remember all from lessons. So i need just try to use of it and read one more time discription of atributes and tags.

**Links**:
+ Tribute Page https://codepen.io/yongmink/full/mvVxER
+ Portfolio (header) https://codepen.io/yongmink/full/PVPveb

### Day 6: January 29, 2019 

**Today's Progress**: Practice. End (no) intensive course. Make survey form

**Thoughts:** It's going better. I make html files faster when early. But responsive for me is very difficult.
**Links**:
+ Survey Form https://codepen.io/yongmink/pen/aXmjrx
+ Portfolio (media query, project's cards, footer) https://codepen.io/yongmink/pen/PVPveb

### Day 7: January 30, 2019 

**Today's Progress**: Practice. Make landing page.

**Thoughts:** Wow! I think, i understand media query now. Anyway it's better. 
To make *media query* work don't forget to use in HTML *meta name="viewport" content="width=device-width"*

**Links**:
+ Landing page https://codepen.io/yongmink/pen/XONQrP

### Day 8: January 31, 2019 

**Today's Progress**: Practice. Make Techical Documentation Page.

**Thoughts:** The hardest part of this challenge was select topic of page. I tried to do dropdown menu with button for mobile version. But i don't understand how to realise it and how search information for it. *crying*

**Links**:
+ Techical Documentation Page https://codepen.io/yongmink/pen/WPRaQK

### Day 9: February 4, 2019 

**Today's Progress**: Practice. Make Personal Portfolio Page

**Thoughts:** The hardest part of this challenge - my fantasy. I'm done. I think now i need to understand when and how use float, flexbox and grid.

**Links**:
+ Personal Portfolio Page https://codepen.io/yongmink/pen/LqWpmr

### Day 10: February 5, 2019 

**Today's Progress**: Basic JavaScript

**Thoughts:** This is just an introduction to the syntax of the language.

### Day 11: February 6, 2019 

**Today's Progress**: Bootstrap

**Thoughts:** It's easy and useful.

**Marks:**
+ Add bootstrap: link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous"
+ nest all in div with class container-fluid
+ class *img-responsive* 
+ *text-center*
+ Bootstrap uses a responsive **12-column** grid system *col-md-4*

### Day 12: February 8, 2019 
**Today's Progress**: Practice. Bootstrap

**Thoughts:** Try to use Bootstrap on my first portfolio page. Now it's looking better on mobile devices. (only project's cards)
**Links:** https://yongmink.github.io/portfolio/

### Day 13: February 13, 2019
**Today's Progress:** Read some articles about adaptive page-proofs.

**Thoughts:** I think now i understand how works flexbox and grid (maybe).
when you CAN'T use Bootstrap:
+ big online store and new web-sites
+sites with complex components reusable in different places
+ sites with many types of pages that may require redesign
+ promo and landings
+ games 

### Day 14: February 18, 2019
**Today's Progress:** Basic JS.

**Thoughts:** Still easy, but i'm workinf very slow. And i ned to practice more, because simetimes it's difficult for me to write easy code on JS.

### Day 15: February 19, 2019
**Today's Progress:** CSS Grid Game. Qality of JS's code.

**Thoughts:** This topic isn't important now. I will come back to this later.  

### Day 16: February 20, 2019
**Today's Progress:** Data structure
+ Introduction to methods and properties
+ Numbers

**Thoughts:**  Rounding of numbers sometimes can makes some troubles. 

### Day 17: February 21, 2019
**Today's Progress:** Data structure
+ Objects as associative arrays
+ Objects: enumerating properties
+ Objects: pass by reference

**Thoughts:**  
+ The object is assigned and copied "by reference."
+ The primitive - copied by value
+ *var name = {};*

### Day 18: February 22, 2019
**Today's Progress:** Data structure
+ Arrays with numeric indices
+ Arrays: methods
+ Array: enumeration methods

**Thoughts:**  
+ *var name = [];*
+ pop, push, shift, unshift
+ array - object
+ method *split* - string to array
+ method *join* - array to string
+ delete arr[i] - make undefined
+ method *arr.splice(index\[, deleteCount, elem1, ..., elemN\])* -  from *index* *deleteCount* and paste on empty place(s) elem1,...,elemN. Return array of removed elements
+ *slice()*
+ *sort(fn)*
+ *reverse()*

### Day 19: February 24, 2019
**Today's Progress:** Work with html and css. Design for simulator.
**Thoughts:** It's difficult to work with code of someone else and change something that already using Bootstrap's styles, but stick a part of this styles
**Link:** https://yongmink.github.io/simulator-of-relational-algebra/

### Day 20: March 1-8, 2019
**Today's Progress:** Work with html and css. Design for simulator.
**Thoughts:** So, okay, now it looks better than first version. Sadly that scrollbar doesn't work like i want
**Link:** https://yongmink.github.io/simulator-of-relational-algebra/

### Day 21: March 29, 2019
**Today's Progress:** knowledge about DOM-elements
**Thoughts:** 
**Mark:** 
+ work in console
+ *for (var i = 0; i < 5; i++) {
      table.rows[i].cells[i].style.backgroundColor = 'red'
    }*
+ getElemetById(id) - only in *document*
+ getElementsByTagName(tag)  tag = 'div' - inside any element. tag = '\*' - get all elements. ** DON'T FORGET ABOUT S**
+ document.getElementsByName(name)
+ getElementsByClassName(className)
+ querySelectorAll(css)
  var elements = document.querySelectorAll('ul > li:last-child');
  return *all* elemets inside elem
  :hover, :active 
+ querySelector - return *only first* element
+ matches(css) - return *true* or *false*
    for (var i = 0; i < elems.length; i++) {
        if (elems[i].matches('a[href$="zip"]')) {
            alert( "Ссылка на архив: " + elems[i].href );
        }
    }
+ closest(css) - search closest element above the DOM hierarchy
+ **XPath**  
+ innerHTML - get HTML-content of element. can change
+ outerHTML - get all HTML-content of element. can't change
+ (nodeValue)/data 
+ textContent - return concatenation of all text nodes
  document.body.children[0].innerHTML = name;   Винни-пух
  document.body.children[1].textContent = name; <b>Винни-пух</b>
+ hidden = true/false
+ **polyfill** - library that adds to old browsers support of possibility, which in modern browsers is inline
+ how to check:
    \<input type="no-such-type"\>
    alert( document.body.children[1].type ); // text, не поддерживается


