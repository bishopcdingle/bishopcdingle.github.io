# Bishop Dingle books kit: links page, QR codes, and flyers

Built for Bishop Dr. Charles W. Dingle by Meraki is Love, LLC (Soulful Tech).

## What is in the kit

| Folder or file | What it is |
|---|---|
| `books/index.html` | The links page. Bilingual, works on phones, four title sections. |
| `books/covers/` | Web-sized covers and the social preview image (`shelf.jpg`). |
| `qr/` | Five QR codes as SVG (vector, for print) and PNG. |
| `flyers/tri-fold-brochure-11x8.5.pdf` | Letter tri-fold, two pages (outside, then inside). |
| `flyers/handout-half-sheet-5.5x8.5.pdf` | Half-sheet handout, one page. |
| `flyers/church-service-insert-5.5x8.5.pdf` | Generic service insert, one page, no church name or service times. |

## Where each QR code goes

| Code | Opens |
|---|---|
| `qr-all-books` | https://bishopcdingle.github.io/books/ |
| `qr-man-is-soul` | https://bishopcdingle.github.io/books/#man-is-soul |
| `qr-el-hombre-es-alma` | https://bishopcdingle.github.io/books/#el-hombre-es-alma |
| `qr-the-heart-intruder` | https://bishopcdingle.github.io/books/#heart-intruder |
| `qr-el-intruso-del-corazon` | https://bishopcdingle.github.io/books/#el-intruso-del-corazon |

The codes point to the page, not to a store. To change a link later, edit `books/index.html`. The printed flyers keep working.

## Put the page live

1. Copy the `books` folder into the root of the `bishopcdingle.github.io` repository, so the file sits at `books/index.html`.
2. Commit and push. GitHub Pages usually publishes within a couple of minutes.
3. Open https://bishopcdingle.github.io/books/ on a phone and confirm it loads.
4. Scan each QR code from the PDFs on screen and confirm each one lands on the right title.

The QR codes do nothing until step 2 is done.

## Check before printing

- Tap every store button from a US phone. Amazon and Walmart block automated checks, so the six Amazon links and the Walmart link have not been tested. The Spanish Kindle listing is priced in euros, so confirm it opens for a US visitor.
- Confirm whether the Books-A-Million listing for Man Is Soul is the hardcover or the paperback. The button currently says only "Books-A-Million."
- The Bishop approves the author bio on the brochure and handout. It uses only these facts: founder of True Standard Holy Church, Inc. and True Standard Christian Bible College and Seminary in Tarboro, North Carolina, and more than fifty-three years of ministry.
- Cover files came from retailer listings at 300 to 600 pixels tall and were sharpened with AI upscaling. Original cover files will print sharper. To swap them, replace the four files in `books/covers/` and rebuild the flyers.
- The Spanish Heart Intruder eBook cover reads "Corazon" without the accent, while the Strand print cover reads "Corazón." The flyers show the unaccented eBook cover.
- Cover designs differ by format. The Amazon hardcover of Man Is Soul and the Kindle edition of The Heart Intruder use different covers than the ones shown on the flyers and page.

## Printing

- Print at 100 percent on US Letter, with no "fit to page" scaling. Every design keeps a white margin, so an office printer can handle it. A print shop that needs bleed will need a bleed version.
- Tri-fold: print both pages on one sheet, double-sided. Make one test sheet first and check that the front cover sits directly behind the inside-left panel. Fold the narrow left panel of the outside page inward first, then fold the front cover over it.
- Handout and insert: print on Letter and cut in half for the 5.5 x 8.5 size, or print on 5.5 x 8.5 stock.
- Scan the printed proof with a phone before any full run.

## Checked so far

- All five QR codes decode to the addresses above, from the PNG files and from all three flyer PDFs at 150 and 200 dpi.
- The page was viewed at phone and desktop widths.
- Not checked: the live page (it is not published yet) and the store links listed above.
