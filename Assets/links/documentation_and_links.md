## Colours

[colours](https://colorhunt.co/)


## Fonts

1px     -   1/96 inch

1pt     -   1/72 inch

1em     -   100% of parent (eg : body)

1rem    -   100% of root (eg : html)


### font weight 

#### keywords

normal

bold

#### relative to parent

lighter 

bolder

#### number

100 - 900


### font family 

~~~css
    h1 {

        font-family : "name part1 part2", generic
    }

~~~

[fonts](https://fonts.google.com/)


### text align

~~~css

    h1 {

        text-align : center
    }
~~~


## CSS inspection

<kbd>ctrl </kbd> + <kbd>shift </kbd>+ <kbd>I</kbd>


## The box model

<ul>
    <li> each element is a box
    <li> height width top bottom
</ul>

~~~css
    h1 {
        border : 10px solid black ;
        border-top : 0px ;
        border-width : 0px(1) 10px(2) 20px(3) 30px(4);
        border-width : 0px(1&3) 10px(2&4)
    }
~~~


## Combining css selectors

### group rule 

~~~css
    selector, selector {
        color: red
    }
~~~

### child -> apply to direct child of left side

applicable only one level inside of parent and child selectors
~~~css
    selector (parent) > selector (child) {
        color: red
    }
~~~

### descendant -> Apply to a decendat of left side 

to change all selectors inside the first selector
~~~css
    selector (parent)  selector (child) {
        color: red
    }
~~~

### chaining

apply where all selectors are free. no spaces btween the selectors. targets the spcifc selector combo

eg : h1#id.class.cass2 (all values)
~~~css
    selectorselector {
        color: red
    }
~~~

### combining combiners

~~~css
    selector(parent) selectorselector {
        color: red
    }
~~~