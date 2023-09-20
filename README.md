# Video: Variables and Data Types

<iframe src="https://player.vimeo.com/video/546130814?title=0&byline=0&portrait=0" width="640" height="360" allowfullscreen="allowfullscreen" allow="autoplay; fullscreen; picture-in-picture"></iframe>

## Resources

- [JavaScript data types and data structures](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures)
kelvin@kelvin-HP-EliteBook-840-G5:~/Development/Code/1/phase-1-lecture-videos-variables-and-data-types$ node
Welcome to Node.js v12.22.9.
Type ".help" for more information.
> let munene = 'great'
undefined
> munene
'great'
> typeof 1
'number'
> typeof 'yes'
'string'
> typeof 'juice'
'string'
> typeof false
'boolean'
> typeof true
'boolean'
> typeof undefined
'undefined'
> let juke = 'Nissan'
undefined
> juke
'Nissan'
> const munene = 'great'
Uncaught SyntaxError: Identifier 'munene' has already been declared
> const apple = 'fruit'
undefined
> fruit
Uncaught ReferenceError: fruit is not defined
> apple
'fruit'
> let apple = 'juice'
Uncaught SyntaxError: Identifier 'apple' has already been declared
> 
(To exit, press ^C again or ^D or type .exit)