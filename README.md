# Dalhousie-Beamer-Theme

My Dalhousie University-themed slide template for the LaTeX Beamer class.

Previously, this was a part of [`slides-posters`](https://github.com/KyleBryenton/slides-posters). I decided to create a separate repository after noticing interest from others. The `.tex` file has been updated to include interesting showcases and useful examples.

## Table of Contents

1. [Introduction](#introduction)
2. [Usage](#usage)
    - [Using Overleaf](#using-overleaf)
    - [Using a Local LaTeX Editor](#using-a-local-latex-editor)
3. [Contributing](#contributing)
4. [License](#license)

## Introduction

My hope is two-fold:
1. The showcases here will be interesting for experienced LaTeX users.
2. The examples will be pedagogically useful for newer LaTeX users and will help kick-start their first few presentations.

Also included is my personal colour-blind friendly swatches I use for my graphics. See: [`ColourBlindSwatches.txt`](https://github.com/KyleBryenton/Dalhousie-Beamer-Theme/blob/main/ColourBlindSwatches.txt)

_I intend to clean up my Dalhousie Poster Template and add it here at a later date. If interested, please contact me for a pre-release version._

## Usage

To use these templates, follow these steps:

### Using Overleaf

Overleaf is an online LaTeX editor that allows you to compile LaTeX documents in your browser.

1. Go to [`Dalhousie-Beamer-Theme`](https://github.com/KyleBryenton/Dalhousie-Beamer-Theme).

2. Click the green `<> Code` button, and then `Download ZIP`.

3. Sign-in to [Overleaf](https://www.overleaf.com/project)
  
4. Click `New Project`, then `Upload Project`, and select `Dalhousie-Beamer-Theme-main.zip` from your Downloads folder.

5. Click `DalBeamerTheme_Showcase.tex`, then compile.

### Using a Local LaTeX Editor

Instead of Overleaf (or if you need extended compile times) you may use a local editor. My personal preference has always been for [TeXMaker](https://www.xm1math.net/texmaker/download.html).

1. Clone the repository:
    ```bash
    git clone https://github.com/KyleBryenton/Dalhousie-Beamer-Theme.git
    ```

2. Ensure `beamerthemeDal_16x9.sty`, `beamercolorthemeDal.sty`, and `Dal_Background_16x9.pdf` are in the same directory as your `.tex` file.

3. Open the `DalBeamerTheme_Showcase.tex` file with your preferred LaTeX editor. 

4. Compile with `pdflatex`.

## Contributing

I welcome anybody to contribute, share, or modify this template or the `.sty` files to suit their needs. Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## License

This project is licensed under the GNU General Public License Version 3. See the [`LICENSE`](https://github.com/KyleBryenton/Dalhousie-Beamer-Theme/blob/main/LICENSE) file for details.
