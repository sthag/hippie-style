# HIPPIE styles

Collection of CSS styles, mainly for the use with HIPPIE, written in SASS language.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine.

### Prerequisites

All styles in this project are written in the [Sass](https://sass-lang.com/) language. So a preprocessor may be needed to form Cascading Style Sheets (CSS).

Please choose a implementation suitable for your needs from the [Install Sass document](https://sass-lang.com/install).

For example in a Node.js environment you can install Sass with the Node package manager:

```bash
npm install -g sass
```

### Installing

Clone the repository `https://github.com/sthag/hippie-styles.git` to a folder to get all source files.

To include HIPPIE styles to a Sass workflow, just import the main file at the appropriate position. Usually this would be at the beginning of your stylesheet:

```scss
@import "hippie/hippie";
```

It is also possible to link to the resulting CSS file. First the file needs to be compiled:

```
sass hippie/_hippie.scss stylesheets/hippie.css
```

Now the stylesheet can be included into the HTML document:

```
<link rel="stylesheet" type="text/css" href="stylesheets/hippie.css"/>
```

## Versioning

This project uses [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/hippie-styles/tags).

## Authors

* **Stephan Hagedorn** - *Initial work* - [Interaktionsweise](https://interaktionsweise.de)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
