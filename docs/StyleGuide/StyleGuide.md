# Eleven Fifty Style Guide

### Colors

```scss
$red: #D9514E;
$charcoal: #53565A;
$orange: #f79569;
$cyan: #86BAD3;
$teal: #9AD0D5;
$green: #8acfba;
$yellow: #F6D57A;
$purple: #A992BC;
$brown: #725b4d;
```

### Font
Belleza

### For Gitbook
- `#` on all pages for title of page
- `###` for subheadings
- Include filenames and Component names in backticks
- Keep EFA Logo on Front Page
- Directions exceeding 2 steps should be numbered/bulleted….
- Make sure all code is in a code block (three backticks and the language - see markdown docs) 
- Resources/Works Cited at end
- Have all assets locally and in git





# Paul's Feedback
Kathryn & Christian,

Good start on the CSS project. I am looking this over on a plane and am about to land, so I am going to just be as direct as possible.


Here are my thoughts here:

# Sync Often
Just as a good practice, make sure to keep the master up to date as often as possible. I usually update master every time I push a bunch of working commits into develop. 

# Explain the code more
This is probably highest priority. More explanation of the code is needed. You might need to chunk the code a little more and scaffold it out step by step. This might require creating more files and making the project longer. That is fine. 

On chunking the code, there are two pretty good ways to do it: scaffolding and annotating. Let's say I'm teaching beginners how to write the following function:

```js
function add(x,y){
    let total = x + y;
    return total;
}
```

While this function is simple to us, it requires more breakdown for them. There's two ways that we are trying to approach this now:

#### Scaffold Approach
Scaffold the method in chunks and explain as you go:

1. Add the following code:
```js
function add(){

}
```
Here we declare our function....and some explanation.

2. Add to the function:
```js
function add(x, y){

}
```
Here we add parameters.....and some explanation

3. Let's add a total variable:
```js
function add(x, y){
    let total = x + y;
}
```
Here we add a `total` variable.....and some explanation

You get the idea....

This approach is good for showing how to build complex things in a step by step way, as we would if we were coding it out. 

### Annotated
You can also do it with annotations:
```js 
        //1   /2
function add(x, y){
    let total = x + y; //3
    return total; //4
}
```
Let's analyze the code:
1. Here we declare a function that adds two numbers. 
2. Here we have two parameters. These parameters will....
3. We create a variable called `total` that will allow us....
4. Here is the `return` for .....

This method takes up less space, but it can be overwhelming.

# Clarity
I think we need to be clear and focused in each module. If we are introducing multiple topics in one module(one file), then it's probably going to be confusing. For instance, I was confused by the first paragraph:

```
Flexbox is a method used to layout a website. Grids are a method used to layout a website. You may be asking yourself, "Does one replace the other?" No. Although similar, grids and flexboxes are different. It is best to think about them as complementary methods to structure the layout of a web site. Sort of like peanut butter and jelly.
```

What is the focus of this module, Flexbox or Grids? I am lost right away here.

Can we cut any fluff or confusion and get to the point sooner? 

Are we talking about Flexbox or Grid? Can we define what Flexbox is?

I guess I'm just saying to look for laser focus.

# Clean up the project
There is a good amount of code clean up to do in this project for future developers.Things I'm seeing that I started making TODOs for:
1. There are numerous blank files that aren't being used. Trash them if you're not using them. 
2. Assets should be moved into each chapter and have a starting number that matches the module that the image is in. See what I did for 1.0_FB_center.PNG in the assets folder. 
3. For all heading don't do this:

```
* [Part 1: Flexbox and Grids](0.1_flexbox_grids/0.1_flexbox_grids.md)
    *[1.0: Intro](0.1_flexbox_grids/1.0.Intro.md)
    *[1.1: Parents with Many Children](0.1_flexbox_grids/1.1.Parents_w_Children.md)
```

Leave markdown files out of chapter heading titles.

```
* [Part 1: Flexbox and Grids]()
    *[1.0: Intro](0.1_flexbox_grids/1.0.Intro.md)
    *[1.1: Parents with Many Children](0.1_flexbox_grids/1.1.Parents_w_Children.md)
```

That's all I have for now.



