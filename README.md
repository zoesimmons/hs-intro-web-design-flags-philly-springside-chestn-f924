# Flag Maker

<img src="https://s3.amazonaws.com/after-school-assets/flags.png" width="300" align="right" hspace="10">

What makes CSS so powerful is not just its ability to change the font color and font style of our website, but also how we can use it to create designs. Let's get funky with some flags! 

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

It's important to note the selector `#ukraine div`. This descendant selector in `style.css` is selecting all the divs inside the div with the id `ukraine` in `index.html`. Basically, the two nested divs in `index.html` are styled in the CSS to be 175px tall and 800px wide. From there, we selected each div individually to change the background color. You'll want to mimic this pattern for the rest of the flags.

### Step 3: 

Code your solution in both `index.html` and `css/style.css` to create flags from countries around the world! Make sure you Google the flags if you aren't positive what their colors are!

Reminder, ID's should be unique in your HTML. We used `box1` and `box2` for Ukraine, so you'll need to use `box3`, etc. for your other flags.

If you get stuck at any point, try Googling the problem. The best thing about programming for the web, is using the web as your resource. For instance, if you're having problems controlling the size of a `div`, trying googling `how to set a divs height in css and html`. The width doesn't need to be specific height or width, you can make your best guess!

### Step 4:

Remember you can preview your work by entering in terminal `python -m SimpleHTTPServer 3000` and then selecting `Preview < Port 3000` at the top of the page.

If it doesn't seem like your changes are showing up in the browser, check to make sure you've saved your changes to your files in the Nitrous text editor.

### Step 3:

To mark this lab as done (and store your work on GitHub!) in Nitrous, in terminal, enter `learn submit`.
<p data-visibility='hidden'>View <a href='https://learn.co/lessons/hs-intro-web-design-flags' title='Flag Maker'>Flag Maker</a> on Learn.co and start learning to code for free.</p>
