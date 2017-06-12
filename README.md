# Rider Workshop exercise

## Creating your website

1. Visit github.com and create an account. Your username will form part of your website address, so choose it carefully — for example, if you choose `khaleesi2017` as your username, your website will be at `khaleesi2017.github.io`. Sign up using an email address you have access to right now.
2. You’ll be asked to verify your email address, so log into your email and follow the link in the email you receive from GitHub.
3. Launch _GitHub Desktop_ from the Dock, and log in using your new user account.
4. Once you’re logged in, click the “Create New Repository” button on the left side of the window. You will be prompted to enter:
    1. The repository name. This should be your username that you used to sign up with, followed by `.github.io` — e.g. `khaleesi2017.github.io`
    2. The local path. This is the location on your computer where your source code will be placed — choose a location you’re happy with
5. Click Create Repository to confirm these settings
6. From the Repository menu, choose Open in Finder to open up your new project folder in the Finder
7. Drag this folder (it should be called something like `khaleesi2017.github.io`) from the Finder to the _Sublime Text_ icon on your Dock to open it in the _Sublime Text_ editor
8. In the _Sublime Text_ editor window, right-click the folder on the left hand side, and choose New File, then press Command-S (or File > Save) to save it, and call it `index.html`
9. Time to get started with the exercise!

## Making your profile page

First you’re going to make your page using plain HTML without any CSS. It won’t look very pretty, but that’s okay! You should try to have each of these things in your page:

1. A main heading on the page with your name in it, e.g.:

```
<h1>Your Name Here</h1>
```

2. A photo of yourself (if you don’t have one to hand, your mentor can help you to take one using your Mac’s webcam), e.g.:

```
<img src="my-photo.jpg" alt="This is a photo of me">
```

3. A medium-length ‘about me’ description of yourself; talk about the kind of vehicle you use to deliver etc.

```
<p>Hi, my name is Ben. Here’s some interesting facts about me!</p>
```

4. A list of things related to you, such as:
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

5. (For advanced students) maybe embed a widget, e.g. your Strava profile, Soundcloud player, Spotify playlist, Twitter timeline, a favourite YouTube video etc.

## Making your profile page _look nicer!_

First of all, use the Web Inspector tools to change and play with your layout dynamically. Some ideas for things students might want to try playing with to improve how their profile page looks:

1. Change the typography, using the `font-family` property
2. Change the background and text colour, with `color` and `background-color`
3. Give the layout a maximum width so that it doesn’t occupy the whole width of the window at larger sizes
4. Make your “about me” text sit alongside your photo (`float` plus `clear` —  see [advanced topics](#advanced-topics).)
5. GO NUTS!

## Concepts to learn about

1. [Semantic markup][semantic-markup]: headings, images, paragraphs, links, lists
2. `<style>` tag vs `<link rel="stylesheet">`
3. `font-family`
4. `color` and `background-color`, and [how colour codes work][colors] (using hexadecimal and RGB)
5. container elements, `width` and `margin`
6. [`display: float;`][floated-elements]

## Advanced topics

1. [Media queries][media-queries]
2. [`:hover`][hover]
3. [`text-shadow`][text-shadow], [`border`, `border-radius`][borders], [`box-shadow`][box-shadow], [`text-transform`][text-transform]
4. [transitions][transitions], [transforms][transforms], [animations][animations], [opacity][opacity]
5. [Mobile viewport][mobile-viewport]

## Publishing your website

Once you’ve completed your website and are ready to publish it, you can do this with GitHub Desktop, so switch back to it.

1. On the left hand side of the window you should see a list of all the files you’ve created as part of your exercise, including one called index.html. If you called your page something else, you’ll want to go back and change it to this right now, otherwise your website won’t work!
2. Everything you’ve created and want to be published needs to have a checkmark beside it.
3. At the bottom left you will see a couple of text boxes. In ‘Summary’, write a short message — it’s not important what, something like “My first commit!” works fine
4. Click the button that says “Commit to master”
5. Once this is done, you should be able to visit `https://<username>.github.io/` and see your shiny new rider profile!

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
