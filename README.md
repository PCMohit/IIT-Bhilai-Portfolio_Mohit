# Mohit Choudhary — IIT Bhilai Internship Portfolio

A responsive, static portfolio website documenting the internship period **08 June–08 August 2026**. It is built with plain HTML, CSS and JavaScript and is suitable for GitHub Pages.

## Included

- Internship overview and work timeline
- Python fundamentals and QuickMap lunar annotation work
- Generalized 18-module CNN accelerator pipeline diagram
- Vivado missing `.bd` and `.dcp` troubleshooting screenshots
- HDMI / RGB565 estimate table with engineering caveat
- QGIS lunar South Pole annotated map and map-making workflow
- Public information about MANAS Lab and Dr. Nitin Khanna, with source links
- Downloadable Word internship report and QGIS procedure PDF

## Publish on GitHub Pages

1. Create a new GitHub repository (for example, `iit-bhilai-internship-portfolio`).
2. Extract this ZIP and upload **the contents of this folder** to the repository root. `index.html` must be at the root, not inside another nested folder.
3. Commit the files to the `main` branch.
4. Open **Settings → Pages** in the repository.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch `main` and folder `/ (root)`, then save.
7. Wait for GitHub Pages to publish the site. The published URL will appear in the Pages settings.

## Customize

- Edit the content in `index.html`.
- Adjust the theme, responsive layouts and typography in `styles.css`.
- Interactions (mobile menu, scroll progress, image preview) are in `script.js`.
- Replace images in `assets/` while keeping the filenames, or update their references in `index.html`.

## External image and fonts

The hero section uses a remotely hosted Wikimedia Commons photo of IIT Bhilai's Kumaragupta (Central Library and ITIS) building. It is **not** a photograph of MANAS Lab. The photo credit and CC BY-SA 4.0 license are included in the page. The website also loads Google Fonts and therefore uses those fonts when an internet connection is available; system sans-serif fallbacks are provided.

## Accuracy notes

- The website is an independent student portfolio and is not an official IIT Bhilai or MANAS Lab website.
- The 18-module pipeline is a generalized block diagram prepared from the supplied module flow.
- The exact multiplier RTL filename should be checked: the module list says `mul_half2ints.sv`, while the supplied register/bus analysis says `mul_half2ints2316.v`.
- The Vivado screenshots show missing `real_detect.bd` and `real_detect_wrapper.dcp` references. Gate-level mapping and synthesized resource counts are not claimed.
- The reported 6.67 FPS is a processing-throughput figure. It is not interchangeable with the 74.25 MHz pixel timing clock; the HDMI figures are estimates requiring validation against the actual resolution and video timing.

## Sources

- [IIT Bhilai official website](https://www.iitbhilai.ac.in/)
- [Dr. Nitin Khanna — IIT Bhilai faculty profile](https://www.iitbhilai.ac.in/index.php?pid=nitin)
- [MANAS Lab — Multimedia Analysis and Security](https://sites.google.com/view/nitinkhanna/home)
- [Wikimedia Commons campus image source](https://commons.wikimedia.org/wiki/File:Kumaragupta_(Library_and_ITIS).jpg)
- [Creative Commons Attribution-ShareAlike 4.0](https://creativecommons.org/licenses/by-sa/4.0/)
