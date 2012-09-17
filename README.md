# Yulquen
### An HTML and CSS framework for prototyping interactions

Yulquen is a hack of [Skeleton](http://www.getskeleton.com), a responsive CSS framework, to fit some common ways that interaction designers and other sundry UX folk prototype websites and applications. It provides some functionality for annotations and forms, with all of the styling CSS removable for handoff or more custom tweaks.

## Presuppositions

- You have __passing fluency in writing HTML and CSS__. Yulquen deliberately doesn't contain JavaScript, so you can use whatever library you want.
- You are okay either with __Skeleton being your production framework__, or with rewriting the HTML and CSS later. Yulquen is meant to remove the pain of rewriting the same layout and behavior in code, so the latter seems a bit disingenuous.
- You are okay with the whole thing being a __static site__, with no templating functionality included. A Yulquen for [Jekyll](http://jekyllrb.com) is in the works.

## How to Use

Yulquen contains three CSS files:

- __wireframe.css__: All of your CSS should go here. If you want to preserve CSS in your handoff, make another stylesheet and put your CSS there instead.
- __base.css__: All of Skeleton’s styling, typography, and CSS reset. Provides a good start.
- __skeleton.css__: The responsive hoo-hah that makes your grid and provides reflow for mobile layouts.

### During handoff:

- Delete base.css and wireframe.css.
- Remove all instances of sup.annotation and div.annotations.
- Enjoy your new reality of barebones minimalism.

## In conclusion

This is ridiculously alpha, and comes with no support. You should probably know what you're doing when it comes to reading front end code. I have no idea what I am doing, so feel free to make a pull request and make this better.

Read more at [Yulquen's official site](http://nickd.org/yulquen/). [Share your uses of Yulquen](mailto:nickd@nickd.org) and I'll put together a gallery sometime.

## Future tweaks

- Jekyll integration
- Better looking forms
- Right-aligned, responsive side labels
- Site map page
- Data model page

## License

Yulquen is licensed under [WTFPL version 2](http://sam.zoy.org/wtfpl/).