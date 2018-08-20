## Grid Calc Sass

Standard SASS grid layout framework that allows you define the number of grid columns you require. It also allows you to specify your gutter width as a pixel value.

See demo <a href="https://codepen.io/Rueb/pen/qyeVWZ">here</a>.

### Usage

For the template to function correctly the column class numbers must be factors of the ``` $cols ```  variable and and their sum must match it's total. The default is 12, examples below.

``` html
<div class="row">
    <div class="cl-5"></div>
    <div class="cl-5"></div>
    <div class="cl-2"></div>
</div>

<div class="row">
    <div class="cl-4"></div>
    <div class="cl-3"></div>
    <div class="cl-2"></div>
    <div class="cl-2"></div>
    <div class="cl-1"></div>
</div>

```
Set the gutter width and total columns based on your needs.

``` scss
$cols: 12;
$gutter: 20px;
```

### Mobile

Mobile classes can be added to modify the layout on smaller screens. In the example below a single row of 4 elements will change to two rows of two elements when the screen width drops below the value specified in the media query.

``` html

<div class="row">
    <div class="cl-3 cl-sm-6"></div>
    <div class="cl-3 cl-sm-6"></div>
    <div class="cl-3 cl-sm-6"></div>
    <div class="cl-3 cl-sm-6"></div>
</div>

```

Computer magick.

```

   |\          .(' *) ' .
   | \        ' .*) .'*
   |(*\      .*(// .*) .
   |___\       // (. '*
   ((("'\     // '  * .
   ((c'7')   /\)
   ((((^))  /  \
 .-')))(((-'   /
    (((()) __/'
     )))( |
      (()
       ))

```
