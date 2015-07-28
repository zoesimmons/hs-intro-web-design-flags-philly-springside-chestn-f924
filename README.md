# Flag Maker

<img src="https://s3.amazonaws.com/after-school-assets/flags.png" width="300" align="right" hspace="10">

What makes CSS so powerful is not just it's ability to change the font color and font style of our website, but also how we can use it to create designs. Let's get funky with some flags! 

## Let's Get Started

### Step 1:

Open this lab in Nitrous

### Step 2: 

Take a look at `index.html` and `css/style.css`. We've built out Ukraine for you. Let's take a look at the code in `css/style.css`:

```css
#ukraine div {
  height: 175px;
  width: 800px;
}

#box1 {
  background-color: blue;
}

#box2 {
  background-color: yellow;
}
```

It's important to note the selector `#ukraine div`. This descendant selector is selecting all the divs inside the div with the id `ukraine`. Basically, the two nested divs are stlyed to be 175px tall and 800px wide. From there, we selected each div individually to change the background color. You'll want to mimic this pattern for the rest of the flags.

### Step 3: 

Code your solution in both `index.html` and `css/style.css` to create flags from countries around the world!

### Step 4:

Remember you can preview your work by entering in terminal `python -m SimpleHTTPServer 3000` and then selecting `Preview < Port 3000` at the top of the page