

##CSS Animation

####Pseudo
```
:hover
:focus
:active
```
####Transformation

Transform is a property that takes functions as values

**Translation**

```css
	Transform: TranslateX(1px)
	Transform: TranslateY(1px)
	Transform: Translate(1px,1px)
```

**Scale**

We can use positive or negative number to change the direction

```css
	Transform: ScaleX(2)
	Transform: ScaleY(2)
	Transform: Scale(2,2)
```


**Transform-origin**

Allows you to redefine the origin (by default at the center of the element). 

```css
transform-origin : 0,0
transform-origin : left bottom
Transform-origin : right top
```

**Rotation**

Rotation is done with the center of the element as origin
We can apply transform-origin to change the center of the rotation

```css
transform:rotate(45deg)

```

**Side Note about browser prefixes :**
```
-moz-
-webkit-
-o-
-ms-
autoprefixer.github.io
Also an interesting article on MDN
```

**Transition-duration**


**Transition-property**


**Transition-timing-function**

Reference : 
 
 * www.easings.net
 * https://matthewlein.com/tools/ceaser

**Transition-delay**


**All transitions on 1 line**

transition : property duration timing-function delay
transition: background 2s ease-in 1s
transition: background 2s ease-in 1s, transform 5s linear 2s

**Questions**

What can be transitioned?
>Most properties can be transitioned however there is an impact on performance

What should be transitioned? (performs best)

* Transform:translate()
* Transform: Scale()
* Transform: Rotate()
* opacity

Article : html5rocks 