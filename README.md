Burgerfy
========


##First Step: Installing Burgerfy


###CSS


In order to install the Burgerfy CSS you will need to paste the following link into the `<head>` section of your document:

```HTML
<link rel="stylesheet" href="css/burgerfy-style.css" type="style.css">
```

Make sure your own stylesheet is **underneath** the Burgerfy stylesheet. If you put your stylesheet first, some of the style in our stylesheet might override yours!

###JQuery

In order to install the JQuery aspect of Burgerfy, you will first need to link to JQuery. To do this, copy this link into your `<head>`:

```HTML 
<script src="http://ajax.googleapis.com/ajax/libs/jquery/2.1.1/jquery.min.js"></script>
```

The next step is to link to burgerfy.js. To do this, copy the following link into your `<head>`, **underneath** the JQuery link from above.

```HTML 
<script src="js/burgerfy.js"></script>
```

##Step Two: Burgerfying Your Menu

Firstly, we need a menu to Burgerfy! Your menu **needs** to be a ```<ul>``` with a series of ```<li>``` elements.

Next, your ```<ul>``` needs a class. This can be anything you want, but we would suggest something like *menu* or *nav*. Here's an example:

```HTML
<ul class="menu">
  <li>Home</li>
  <li>About</li>
  <li>Contact</li>
</ul>
```

We now need to Burgerfy this!

You can do this step in a Javascript file, or in your HTML between ```<script>``` tags.

All you need to do is put your menu's class (in our case *menu*) into the following script:

```javascript
$('.menu').burgerfy({

});
```

##Step Three: Options
