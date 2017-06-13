# Rider Workshop exercise

## Making your profile page

First you’re going to make your page using plain, semantic HTML.

1. Click on the big **S** icon in the Dock at the bottom of the screen to open the _Sublime Text_ editor window. Choose _New File_ from the _File_ menu, then press Command-S (or File > Save) to save it, and call it `index.html`, and save it to the Desktop.

2. The first thing you need to add is your **doctype**; this lets the browser know that your page is written in HTML5. It’s unusual in that it looks a bit different to other HTML tags. Write exactly this into your page:

```
<!DOCTYPE html>
```

3. Below this, you will need to add the main HTML tag for your page, like so:

```
<!DOCTYPE html>
<html>
</html>
```

4. Within this, there are two important sections: the **head** and the **body**. The _head_ is for the page to give the browser important details about itself, like what the page’s title is, _metadata_ description information and so on. The _body_ is where the _content_ of the page goes. So let’s add these, _inside_ the `<html>` tag you already added:

```
<!DOCTYPE html>
<html>
  <head>
  </head>
  <body>
  </body>
</html>
```

5. Since we already mentioned the page _title_, let’s add one of these to your page. This is what appears in the title bar of the window, as well as being used for things like bookmarks:

```
<!DOCTYPE html>
<html>
  <head>
    <title>My profile!</title>
  </head>
  <body>
  </body>
</html>
```

Next, you should try to add some more things to your page:

6. A main heading on the page with your name in it, e.g.:

```
<h1>Your Name Here</h1>
```

7. A photo of yourself (if you don’t have one to hand, your mentor can help you to take one using your Mac’s webcam), e.g.:

```
<img src="my-photo.jpg" alt="This is a photo of me">
```

8. A medium-length ‘about me’ description of yourself; talk about the kind of vehicle you use to deliver etc.

```
<p>Hi, my name is Ben. Here’s some interesting facts about me!</p>
```

9. A list of things related to you, such as:
    * Your favourite foods (maybe in order of preference?)
    * Zones you’ve delivered in
    * Links to your social media presence, Facebook page, Twitter profile etc.
    * Your hobbies
    * A link to your favourite sports team’s website
    * Any other interesting list of things you can think of

This should be either an _ordered_ (numbered) or _unordered_ (bulleted) list, e.g.:

```
<ul>
  <li>A list</li>
  <li>Of things</li>
  <li>Like this</li>
</ul>
```

## Making your profile page _look nicer!_

First of all, use the Web Inspector tools to change and play with your layout dynamically. Here are some ideas for things students might want to try playing with to improve how their profile page looks:

1. Change the typography, using the `font-family` property
2. Change the background and text colour, with `color` and `background-color`
3. Give the layout a maximum width so that it doesn’t occupy the whole width of the window at larger sizes
4. Make your “about me” text sit alongside your photo (using [`float`][floated-elements])

If you’re looking for inspiration for things you can do with, or add to your site, here are a few ideas. Ask your mentor if you want help with any of this:

1. Make things on your page change their appearance when you hover the mouse over them.
2. Add an animated GIF or two to your page!
3. Give your photo some [rounded corners][borders] (or even make it into a circle!)
4. Give your [text a nice drop-shadow effect][text-shadow]
5. Embed a widget, e.g. [your Strava profile][strava], [Soundcloud player][soundcloud], [Spotify playlist][spotify], [Twitter][twitter] timeline, a favourite YouTube video etc.
6. Here are a few example profile pages we’ve made that you can check out if you want some ideas!
    1. [Ben Darlow][ben-darlow]
    2. [Tommy Palmer][tommyp]

## Publishing your website

Once you’ve completed your website, we can publish it to make it live for anyone to view!

1. Visit [github.com][github] and create an account. Your username will form part of your website address, so choose it carefully — for example, if you choose `khaleesi2017` as your username, your website will be at `khaleesi2017.github.io`. Sign up using an email address you have access to right now.
2. You’ll be asked to verify your email address, so log into your email and follow the link in the email you receive from GitHub.
3. Launch _GitHub Desktop_ from the Dock, and log in using your new user account.
4. Once you’re logged in, click the “Create New Repository” button on the left side of the window. You will be prompted to enter the repository name. This should be your username that you used to sign up with, followed by `.github.io` — e.g. `khaleesi2017.github.io`
5. Click Create Repository to confirm these settings
6. From the Repository menu, choose Open in Finder to open up your new project folder in the Finder
7. On the Desktop, drag the `index.html` file you created earlier (plus any images you might have added) into the window for your new Repository
8. Switch back to _GitHub Desktop_ and you should see all the files you added in a list on the left side of the window, with a green checkmark alongside each one.
9. At the bottom left you will see a couple of text boxes. In ‘Summary’, write a short message — it’s not important what, something like “My first commit!” works fine
10. Click the button that says “Commit to master”
11. Once this is done, you should be able to visit `https://<username>.github.io/` and see your shiny new rider profile!

## Further reading

1. [Semantic markup][semantic-markup]: headings, images, paragraphs, links, lists
2. `<style>` tag vs `<link rel="stylesheet">`
3. `font-family`
4. `color` and `background-color`, and [how colour codes work][colors] (using hexadecimal and RGB)
5. container elements, `width` and `margin`
6. [`display: float;`][floated-elements]
7. [Media queries][media-queries]
8. [`:hover`][hover]
9. [`text-shadow`][text-shadow], [`border`, `border-radius`][borders], [`box-shadow`][box-shadow], [`text-transform`][text-transform]
10. [transitions][transitions], [transforms][transforms], [animations][animations], [opacity][opacity]
11. [Mobile viewport][mobile-viewport]

[github]: https://github.com/
[semantic-markup]: http://html.com/semantic-markup/
[media-queries]: https://rider-code-workshop.github.io/media-queries.html
[floated-elements]: https://rider-code-workshop.github.io/floated-elements.html
[hover]: https://rider-code-workshop.github.io/hover.html
[text-shadow]: https://rider-code-workshop.github.io/text-shadow.html
[borders]: https://rider-code-workshop.github.io/borders.html
[box-shadow]: https://rider-code-workshop.github.io/box-shadow.html
[text-transform]: https://rider-code-workshop.github.io/text-transform.html
[transitions]: https://developer.mozilla.org/en/docs/Web/CSS/transition
[transforms]: https://developer.mozilla.org/en-US/docs/Web/CSS/transform
[animations]: https://developer.mozilla.org/en/docs/Web/CSS/animation
[opacity]: https://developer.mozilla.org/en/docs/Web/CSS/opacity
[colors]: https://developer.mozilla.org/en/docs/Web/CSS/color_value
[mobile-viewport]: https://rider-code-workshop.github.io/mobile-viewport.html
[strava]: https://support.strava.com/hc/en-us/articles/216918527-Sharing-your-activities-with-a-Strava-Widget
[soundcloud]: https://soundcloud.com/pages/embed
[spotify]: https://developer.spotify.com/technologies/widgets/spotify-play-button/
[twitter]: https://dev.twitter.com/web/embedded-timelines
[ben-darlow]: https://rider-code-workshop.github.io/
[tommyp]: https://tommyp.github.io/
