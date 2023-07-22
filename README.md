# ShadowRun campaign

This project holds materials and information related to a tabletop [ShadowRun RPG] campaign I shall be running.
You can read this content in a pleasant format on [the campaign website, at `https://shadowrun.toreadorvampire.co.uk`].

[ShadowRun RPG]: https://www.shadowruntabletop.com/
[the campaign website, at `https://shadowrun.toreadorvampire.co.uk`]: https://shadowrun.toreadorvampire.co.uk/

## Contributing & editing

The contents of these pages are _editable online_ with a GitHub login.
If you are one of my players, you may create a free login.
Ask me to grant you edit access (tell me your GitHub username), and I shall.
Alternatively, if you know how, you may clone the git repository and work on it offline.

For example, the [content of the home page] of the website is defined in `index.md`.

[content of the home page]: index.md

### Where to put stuff

The organisation of the site should become self-evident over time.
Also, if you put something in an incorrect location, it is very easy to move it to the right one.

There are a few important guidelines to follow though:

* Don't put spaces in filenames; they are _no bueno_ on the web
    * Use minus-dashes instead
* All files of text content have the extension `.md`
    * This site uses [a language called **Markdown**] for its content, you are welcome to learn it but it's strictly optional
* Blog entries (such as game-session logs) must go into the `_posts` directory.
    * There, the files must follow a specific naming convention: `YYYY-MM-DD-page-title.md`
    * Where `YYYY`, `MM` & `DD` correspond to the date on which the entry was first written
    * For example: `2023-07-21-session-one.md`
    * Following this format means that the articles will be correctly treated as blogs; for example they will automatically appear in the list of articles
* Unless you want to contribute to the design/layout of the site, you should ignore everything in the directories `_includes`, `_layouts`, `_sass` & `assets`

[a language called **Markdown**]: https://www.markdownguide.org/getting-started/
