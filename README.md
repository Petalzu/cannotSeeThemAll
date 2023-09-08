# cannotSeeThemAll
[![](https://img.shields.io/badge/%E4%B8%BB%E9%A1%B5-Petalzu%2FcannotSeeThemAll-orange)](https://github.com/Petalzu/cannotSeeThemAll)

You won't see the three of them walking together.
你不能见到他们同行。

This repository contains:

For pages built based on HTML, CSS and js, you can see a sample on [CannotSeeThemAll](https://csa.petalzu.top/).

The webpage can adapt to the window and support changing into different roles, which is easy to use. If you want to create such a web page for your favorite IP characters, it is a good choice.

## Table of Contents

- [cannotSeeThemAll](#cannotseethemall)
  - [Table of Contents](#table-of-contents)
  - [Background](#background)
  - [Install](#install)
  - [Usage](#usage)
  - [Related Efforts](#related-efforts)
  - [Maintainers](#maintainers)
  - [Contributing](#contributing)
  - [License](#license)

## Background

The characters Roland, Algalia and Angelica in the game [Libraryofruina](https://library-of-ruina.fandom.com/wiki/Library_Of_Ruina_Wiki) developed by [Project Moon](https://projectmoon.fandom.com/wiki/ProjectMoon_Wiki) have complex character relationships and plots. Because of the video [you can't always see them together...](https://www.bilibili.com/video/BV1vu4117746/?share_source=copy_web&vd_source=1ce0f3ddea2d717a3f13c29e58966e75) Inspiration,I created a web page with similar functions to those in the video.

> Note: This second creation may not be applicable to anyone. If you find that you can't control your emotions during use and have a strong emotional fluctuation due to resonance with the character story, please seek the help of a psychologist in time.

> Remember: This is just a derivative work.


## Install

This project uses [git](https://git-scm.com/). Go check them out if you don't have them locally installed.

```sh
$ git clone git@github.com:Petalzu/cannotSeeThemAll.git
```
Or Github CLI.
```sh
$ gh repo clone Petalzu/cannotSeeThemAll
```
Or download the. zip package directly.


## Usage

If you want to use it personally, you can deploy it on Github Page. Fork it directly to your own warehouse. After modifying its content, you can directly use GitHub Page for deployment and use your own domain name resolution.

For example:
```sh
<div class="switch-box" >
  <input id="switchButton" type="checkbox" class="switch" onclick="check()"/>
  <label for="switchButton"></label>
  <p style="position:relative;top:-40px;right:-60px;">罗兰</p>
  <img src="roland.png" alt="roland" style="position:relative;top:-120px;right: -80px ;height:120px">
</div>
```
You can modify the content of the label and the picture of the character to achieve the effect of changing the character.The position of the picture may not be in the right position.  You need to adjust its $top: -120px; Right: -80px; Height: 120px$.

By the way, footer can also be changed into your own information. If you think it is redundant, you can delete it directly.

<!--

### Generator

To use the generator, look at [generator-standard-readme](https://github.com/RichardLitt/generator-standard-readme). There is a global executable to run the generator in that package, aliased as `standard-readme`.

## Badge

If your README is compliant with Standard-Readme and you're on GitHub, it would be great if you could add the badge. This allows people to link back to this Spec, and helps adoption of the README. The badge is **not required**.

[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)

To add in Markdown format, use this code:

```
[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)
```

## Example Readmes

To see how the specification has been applied, see the [example-readmes](example-readmes/).

-->


## Related Efforts
None at present.

## Maintainers

[@Petalzu](https://github.com/Petalzu).

## Contributing

Feel free to dive in! [Open an issue]() or submit PRs.
<!--
### Contributors

This project exists thanks to all the people who contribute. 

<a href="https://github.com/RichardLitt/standard-readme/graphs/contributors"><img src="https://opencollective.com/standard-readme/contributors.svg?width=890&button=false" /></a>
-->

## License

[MIT](LICENSE) © Petalzu