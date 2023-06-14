# CSS
## inline CSS : Single Element Target 
>
> the style must be declared inside the tag
>
> < h1 style="color: blue;">Style Me in Blue! </ h1 >

## Internal CSS : single Web Page Target
>
>  the style is mentioned under a tag < style > < / style >
>
>   < style>  h1{color: red;} </ style >

## External CSS: For Entire Website 
>
>   <link rel="stylesheet" href="./style.css" />

# Selectors
>
> **class Selectors**: requires a symbol "." followed by the class mentioned 
>
> .red-text{color: red} ||  < h2 class="red-text">Hello< /h2>
>
> **id Selector**: used for one elememt only 
>
> symbol used "#"
>
> #main {color: green} || < h2 id="main"> 123 <>
>
> **attribute selector**: html elemet + attribute needs to be defined in css
>
> p[draggable]{ color: red} || < p draggable=true> drag </ p>
>
> **universal Selector**: applies the styling to all the elements
> Symbol used: * 
>
> *{color: red} 