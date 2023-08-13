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
