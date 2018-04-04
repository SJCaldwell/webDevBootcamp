CSS Exercises

### Reminder:
A valid CSS tag looks like this:
```css
selector {
	property: value;
	property: value1 value2 value3;
}
```

You can select by tag name (`div`), by class name (`.form-group`), or by ID (`#mpgPlot`)

# Questions

1. Your boss comes in, having just read a clickbait article about "Millenial Pink". He is convinced that pink is in, and every data science product **must have a pink background, including your shiny app.** Your company's graphic designer Xiaotai, who has good taste but is powerless in the face of your boss's feverish cries for color, has made the best of a bad situation and recommended a specific pink shade to use: `#FFD6DC`. Of course, you are able to pick your own shade of pink (or even just use the color `pink`), but you have to *go pink or go home*.

* Make your shiny app have a pink background.


2. You change your background and are unsatisfied with how your graph looks now - just an ugly white box in a sea of pink. You see what the form box on the left looks like and you want something like that - with a white background and rounded corners.

* Put the graph and its header in a white (or off-white: `#f5f5f5`) box with rounded corners.
	
(Hint: I never told you how to do rounded corners in CSS. You gotta figure this out on your own, but it's not very difficult and can be done in one property.)

3. In what she will later explain to your company's HR department as a "heated designing moment", your web designer sent a number of very threatening emails to your boss over his use of the color pink. But things are still cool between you and her. However, she suggests that the font could use some revamping from Bootstrap's default font.

* She suggests first changing the font of the form labels to something else... maybe try a serif font, like Georgia.

4. Your phone buzzes. Your fellow data scientist Lydia, with whom you have spent an inordinate amount of time on this shiny app, just sent you some desperate messages on Slack. Apparently, the "show outliers" checkbox doesn't actually work, and there is no time to change the spaghetti code of your R app. Instead, you could try doing this in CSS.

* Hide the "Show Outliers" checkbox using CSS.


# More Fun

5. Both you and your web designer Xiaotai look at the font changes and are not satisfied. She suggests **grabbing a font from [Google Fonts](https://fonts.google.com) and using it instead of Georgia.**

6. Your boss, back after the Intentional Infliction of Emotional Distress lawsuit between him and your web designer was settled out of court for an undisclosed sum, has another brilliant idea to **spice up your shiny dashboard with some icons**.

(See the Bootstrap documentation on how to add icons in.)

# Really? You're done everything else? Okay, fine, here's some big brain CSS exercises.

1. After drinking a possibly unhealthy amount of mid-grade Panamanian coffee, your coworker Michael came up with the idea of adding in 

* Make the form on the left hand side zoom in with an animation.

2. Mike and you agree that this looks a bit garish. instead, how about having the form box fade in?

3. Seriously? Okay. Have it so that...

 * The sidebar is initially invisible and the main panel takes up the entire width of the screen...

 * Then, the main panel resizes to how big it is normally (66% width?)

 * *Then*, the form box fades in.