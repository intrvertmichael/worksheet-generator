# worksheet-generator

Printable worksheets for the classroom. Everything is in one file, `index.html`, so there is nothing to install or build.

## Math tab
- Addition, subtraction, multiplication or division, with numbers within 5, 10, 15, 20, 50 or 100 (0 is included)
- Within 5, 10 or 15, addition and subtraction can be shown as emojis, as a number line, or as numbers only
- Within 20, 50 or 100, and for multiplication and division, problems are always numbers only. Both numbers go up to the limit, and division answers are whole numbers
- 10 problems per sheet, with a name and date line
- **Save ink** option: no problem borders, small dots instead of emojis, and a lighter font for the numbers

## ELA tab
- Choose how many letters each word has (1 to 6) for random words, or choose **Custom** and type your own comma separated list (up to 8 letters per word)
- **Copy** or **Trace**: copy each word into writing spaces, or trace the word printed in gray
- 8 words per sheet (5 bigger ones when every word has 1 or 2 letters), each with two writing spaces
- Letters line up with the writing lines: tall letters touch the top line and small letters reach the dashed line

Both tabs have a **Refresh** button, a **Print** button (prints just the sheet on US Letter) and a **Download PDF** button.

## Run it
Open `index.html` in a browser. It loads fonts from Google Fonts and jsPDF from cdnjs, so it needs an internet connection.

## Put it online with GitHub Pages
1. Open the repo on GitHub, then **Settings > Pages**.
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
3. Choose the **main** branch and the **/ (root)** folder, then **Save**.
4. After a minute the site is live at `https://intrvertmichael.github.io/worksheet-generator/`.
