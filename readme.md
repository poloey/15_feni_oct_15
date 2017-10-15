# [:house: Feni Batch Home Page](http://poloey.github.io/feni)
# Class 15 - Bootstrap  [official website](http://getbootstrap.com/)

## Home work  
After every class, I am making documentation what you have learned from class, plus some appropriate resource link to accelerate your learning. Which took me about 1.5 hours after every class. My objectives is make you good @ web development, make you fluent @ web technology, make you fluent @ technology. Therefore this amount of hour expending after every class its not adding value to my carrier, Or Lict people didn't asked me for that. Therefore I am doing it, so that you  can use it as your life time reference. You know its totally impossible to explain everything in this class gist documentation. But I am focusing on core things. But you have to learn beyond this gist from different source, official website. Do hard work for next 3 months, it definitely will help  you, in your whole life. 
**Make a ecommerce website template. or ticketing system template or school management template** Its official assignment. You have to submit it as your html css course

### Introduction
Here I have describe basic bootstrap which i describe in class 15. But you should always follow bootstrap [official link](http://getbootstrap.com/)      
Bootstrap is most popular front-end component library. It has 2 file one css file and one js file. Js file depend on `Jquery` and `popper js` file. So before adding bootstrap in your html, you have to add `jquery` and `popper js` in your html document. You can use cdn(content delivery network) which is give this [link](https://getbootstrap.com/docs/4.0/getting-started/introduction/), instead of downloading. Since its quicker. But It won't be good idea if you don't have internet. So if you don't have internet you should download bootstrap html and css file and add to your html page.    

### 5 size
You can easily make your webpage responsive using bootstrap. They have 5 size in BS4(bootstrap 4)
* xs (extra small) : col
* sm (small) : col-sm 
* sm (medium) : col-md 
* sm (large) : col-lg 
* sm (extra large) : col-xl


### 8 color:
Bootstrap has 8 color.
* primary
* secondary
* success
* danger
* warning
* info
* light
* dark

### direction full word
* top 
* right
* bottom 
* left

### direction short word
* t 
* r
* b 
* l
* x = l, r
* y = t, b

### display property
* inline
* inline-block
* none
* block
* flex

### text transform
* uppercase
* lowercase
* capitalize

### Grid system
Bootstrap divided 100% width into 12 column. So if we need 4 column grid we can take 3 `col-4`, or `col-sm-4`, or `col-md-4`, or `col-lg-4`, or `col-xl-4`. column must be encapsulate by `row` 

~~~html
<div class="row">
  <div class="col-sm-4">
    <p>col one</p>
  </div>
  <div class="col-sm-4">
    <p>col two</p>
  </div>
  <div class="col-sm-4">
    <p>col three</p>
  </div>
</div>
~~~

### `container`
To make a container and placed horizontally center  bootstrap use `container` class.  Today's example we placed our whole website and navbar inside `container` class to make it center

### component practice today
* navbar
* jumbotron `jumbotron`
* carousel 
* card - `card` `card-img-top` `card-body` `card-text` you can use bootstrap different background color using `bg-<color>`
* btn - `btn` `btn-<color>` `btn-<size>` `btn-outline-<color>` `btn-block`, `btn-toolbar` `btn-group` 
* alert - `alert` `alert-<color>`, `alert-dismissible`
* form - `form` `form-inline` `form-group` `form-control` `input-group` `input-group-addon`(when we use search box)
* list-group - `list-group` `list-group-item`
* background-color: `bg-<color>`
* text: `text-<color>` `text-justify` `text-center` `text-right`, `text-<text transform>` `font-weight-bold` `font-weight-normal` `font-italic`
* position: `fixed-top` `fixed-bottom` `sticky-top`
* modal: you can keep modal content anywhere you want inside html. You will give a id and give the `data-target="#YourId"`in a button
* pagination: `pagination` `page-item` `page-link` `pagination-<size>`
* progress: `progress` `progress-bar`
* spacing: `m` `p` , `<dirction-short-word>` - `0`, `1`,`2`,`3`,`4`,`5`. e.g `mt-4`
* border: `border` `border-<color>` `border-0` `border-<direction-full-word>-0` `rounded`, `rounded-0`, `rounded-<direction-full-word>`, `rounded-circle` 
* display: `display-<display-property>`

  












