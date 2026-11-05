# turtle_labels
Hope turtles are exclusively used for the delivery of humanitarian aid along non-violent and ecological principles.  To make this mission clear to those who come across our turtles both at sea and upon their coastal arrivals, we are developing a set of multi-lingual labeling and iconography that can be printed or laser engraved on the turtles.  

SVG source files for the printed labels that go on **Hope Turtles** — the bottle-based care packages sent out by [Hopeturtles.org](https://hopeturtles.org) 

This repository is the design source of truth for these labels: edit the files here, export flattened/print-ready versions, and send those to print.

## Repository structure

```
master/         Editable master SVGs — one file per label design (layers, guides, text as live text)
v1_exports/     Flattened exports derived from master/, ready for print layout/output
fonts/          Typefaces used by the labels, bundled for accurate rendering (see below)
*.pdf           Print proofs / press-ready PDF exports
```

### `master/`

| File | Label |
|---|---|
| `you-have-found-a-hope-turtle_EN.svg` | "You have found a Hope Turtle" — English |
| `you-have-found-a-hope-turtle-AR.svg` | Same label — Arabic |
| `you-have-found-a-hope-turtle-HE.svg` | Same label — Hebrew |
| `hopeturtles-org_master.svg` | hopeturtles.org branding label |
| `dear-fellow-human_master.svg` | "Dear fellow human, with love, this is for you" |
| `95-organic_master.svg` | "95% organic materials, all components reusable" |
| `craft-id-master.svg` | Craft/maker ID label (version + maker info) |
| `aid-master.svg` | "AID" label — English, Hebrew (סיוע), Arabic (إغاثات) |
| `virtue-icons-master.svg` | Virtue icon set used across labels |

### `v1_exports/`

Flattened, print-ready exports of a subset of the master designs (text converted to paths, layout composed for the printer), plus the combined print sheet (`V1_stickers to print.svg`) and its proof PDF (`v1_turtle-stickers-to-print.pdf`).

## Editing

Masters were created and should be edited in **Inkscape**. When adding a new label:

1. Duplicate the closest existing master as a starting point to keep consistent dimensions, guides, and styles.
2. Keep text as live text (not outlined) in `master/` so it stays editable and translatable.
3. Only outline text / flatten the file when exporting to `v1_exports/` for print.
4. Make sure any font you use is listed under [Fonts](#fonts) below — add it if it isn't.

## Fonts

The labels currently use these typefaces, all free/open and sourced from [Google Fonts](https://fonts.google.com):

| Font | Used in | Google Fonts |
|---|---|---|
| Mulish | body text, most labels | https://fonts.google.com/specimen/Mulish |
| Aleo | headings/body, most labels | https://fonts.google.com/specimen/Aleo |
| Oswald | `craft-id-master.svg` | https://fonts.google.com/specimen/Oswald |
| Arvo | `virtue-icons-master.svg` | https://fonts.google.com/specimen/Arvo |



## License

The label designs in this repository are licensed under [Creative Commons Attribution-ShareAlike 4.0 (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/). You're free to use and adapt these labels for your own ecobricking/Hope Turtle efforts, with attribution to Hopeturtles.org, and shared under the same license.

Fonts under `fonts/` are licensed separately under the [SIL Open Font License](https://openfontlicense.org/) by their respective authors — see the `OFL.txt` in each font's folder.
