# Presentation for Collaborations Workshop 2024


## Rendering the slides locally
These slides are produced using [Quarto](https://quarto.org).

In order to render them locally, you will need to install Quarto from <https://quarto.org/docs/get-started/>.

Quarto documents can be rendered in either:
* VSCode
* RStudio (> 2022.07.1+554)
* Jupyter
* Terminal

Full instructions can be found at the link above, however in brief:
* In RStudio, open `index.qmd`, above the document click `Render`
* In the terminal, run `quarto render` to build the files, or `quarto preview` to spin up the preview server.

## Enabling GitHub actions and GitHub Pages

In your repository settings, enable GitHub Actions (if they aren't already) and Pages.

Under the **Actions** page in your repo's settings, under **Workflow permissions** enable "Read and Write Permissions".

Once the actions have run once and created the `gh-pages` branch, you can select it as your pages source under the **Pages** page.

## What's included?

* Everything [quarto](https://quarto.org/) can do!
* Emojis are supported :smile: by using the `markdown+emoji` template.
* A couple of extensions I commonly use:
	* [`jmbuhr/qrcode`](https://github.com/jmbuhr/quarto-qrcode) - create QR codes in the source code with `{{< qrcode https://linktoathing.com width=350 height=350 >}}`
	* [`quarto-ext/fontawesome`](https://github.com/quarto-ext/fontawesome) - include nice fontawesome symbols, e.g. `https://github.com/quarto-ext/fontawesome`

## Contributing
Contributions and improvements are very welcome! Please fork this repo and make a pull request against the `main` branch.
Please ensure that your document compiles successfully with the instructions above.
