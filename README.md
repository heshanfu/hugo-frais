# Hugo frais

**/!\ Please note that this is a Work In Progress theme**

A fresh (and french) theme for [Hugo](//gohugo.io/).

Recipe for a good theme:
- **light**: minimum viable dependencies
- **responsive**: mobile-first is not an option
- **accessible**: a11y is quality
- **SVG**: light + responsive + accessibility = Epic win
- **consistent**: if maintainability is king, BEM is queen
- **customizable**: make it yours
- ...

## How to install

Inside the folder of your Hugo site run:

```sh
$ cd themes
$ git clone https://github.com/the2ne/hugo-frais
```

Then update your _config.toml_ file:

```toml
theme = "hugo-frais"
```

For more information read the official [setup guide](//gohugo.io/overview/installing/) of Hugo.


## Configuration

You can define some social network bullshit like:
- [params] **author** *str* : the author's website name;
- [params] **pseudo** *str* : the author's online pseudonym;
- [params] **twitter** *str* : Twitter account;
- [params] **github** *str* : GitHub account;
- [params] **linkedin** *str* : LinkedIn account;

_./config.toml example:_
```toml
[params]
    author = "Olivier Fredon"
    pseudo = "the2ne"
    twitter = "the2ne"
    github = "the2ne"
    linkedin = "the2ne"
```


## Contributing

Did you found a bug or got an idea for a new feature? Feel free to use the [issue tracker](//github.com/the2ne/hugo-frais/issues) to let me know. Or make directly a [pull request](//github.com/the2ne/hugo-frais/pulls).


## License

This theme is released under the MIT license. For more information read the [License](//github.com/the2ne/hugo-frais/blob/master/LICENSE.md).


## Annotations

Thanks to:
- [Steve Francia](//github.com/spf13) for creating Hugo and the awesome community around the project.
