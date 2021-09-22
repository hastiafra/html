# HTML Comprehension Questions

## Q1 - For each of the following HTML documents, is the HTML valid?


a) [False] `<div><span>hello</div></span>`

  <div><span>hello</span></div>


b) [False]

```html
<ul>
<li>one</li>
</ol>
```
<ol> 
<li> one </li>
</ol>


c) [false] `<ul></ul><img/><ol><li>one</li></ol>`

<ul>
<li>img</li>
</ul>

<ol>
<li>one</li>
</ol>

## Q2 - What is a screenreader and why should we care about them?
providing more information about the specific part of our website to a visually impaired person  for example the alt text we write in img tag to describe the img 

a) You want to create a webpage with the photos from your latest vacation
<img> <link> <map> <title> <a>

b) You want to create a website that lists all the art gallery websites in your city and links to their website.
<img> <map> <button> <iframe> <link> <a> <p>

c) You want to sell designer hats. You need to receive orders from the user.

<img> <ul> <a> <button> <span> 

## Q4 - Can a `button` be a child of a `button`? Explain your reasoning

no, because button is clickable and when we have 2 button inside each other it cause UI confusion 

## Q5 - What is the most generic tag you can use?
div

## Q6 - What do the following achronyms stand for?

a) `a` ancher tag

b) `ol` ordered list 

c) `ul` unordered list 

d) `li` list items

e) `tr` table row 

f) `th` table header

g) `td`  table cell 

## Q7 - Usually, `td` elements are children of what kind of elements?

tr, 

## Q8 - What is the difference between td and th?
th is located in the 1st row of the table indicate the header of the table
td is the cell in the table which is the child of tr


## Q9 - Which tag makes the text appear bigger: h1 or h3?

h1

## Q10 - In which situation can you use self closing tags?
when element doesn't have any child

## Q11 - What is autofilling and why is it important?

allows the browser to predict and complete the value, it is convenient because we don't need to type te whole thing 

## Q12 - Which attributes are always present in an img element?
alt, src

## Q13 - Which attribute is always present for an anchor tag?
herf
