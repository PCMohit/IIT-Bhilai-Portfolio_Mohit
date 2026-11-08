# Mohit Choudhary — IIT Bhilai Internship Portfolio

A responsive static portfolio website documenting the internship period **08 June–08 August 2026**. Built with HTML, CSS and vanilla JavaScript; ready for GitHub Pages.

## Included

- Internship overview and work timeline
- Python fundamentals and lunar South Pole annotation using QuickMap (**15 TIFF datasets**, matching the latest report and résumé)
- Generalized 18-module CNN accelerator pipeline diagram
- Vivado missing `.bd` and `.dcp` troubleshooting screenshots
- HDMI / RGB565 estimate table with an engineering consistency note
- QGIS lunar South Pole annotated map and step-by-step procedure PDF
- Public research context for MANAS Lab and internship guide Dr. Nitin Khanna, with source links
- **Latest internship documentation Word file**
- **Latest résumé Word file**

## Files to download from the website

- `downloads/Mohit_Choudhary_IIT_Bhilai_Internship_Documentation.docx`
- `downloads/Mohit_Choudhary_Resume.docx`
- `downloads/qgis-annotation-steps.pdf`

## Publish on GitHub Pages

1. Create a GitHub repository (for example, `iit-bhilai-internship-portfolio`).
2. Extract this ZIP and upload **the contents of the `iit_bhilai_internship_site` folder** to the repository root. `index.html` must be at the root, not inside another nested folder.
3. Commit the files to the `main` branch.
4. Open **Settings → Pages** in the repository.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch `main` and folder `/ (root)`, then save.
7. GitHub Pages will publish the site; the URL will appear in the Pages settings.

## Customize

- Edit content in `index.html`.
- Update theme and responsive styling in `styles.css`.
- Mobile menu, scroll progress and image lightbox interactions are in `script.js`.
- Replace images in `assets/` while keeping filenames, or update references in `index.html`.
- Replace the Word files in `downloads/` when a future résumé or report revision is ready, keeping the same filenames if you do not also update the links.

## External image and fonts

The hero section uses a remotely hosted Wikimedia Commons photo of IIT Bhilai's Kumaragupta (Central Library and ITIS) building. It is **not** a photograph of MANAS Lab. The photo credit and CC BY-SA 4.0 license are included on the page. Google Fonts are also loaded remotely, with system font fallbacks.

## Accuracy notes

- This is an independent student portfolio, not an official IIT Bhilai or MANAS Lab website.
- The latest internship documentation and résumé both record **15 lunar South Pole TIFF/raster datasets**. The website count has been aligned to 15.
- The generalized 18-module block diagram documents the supplied architecture flow. The revised documentation identifies the FP16 multiplier source as `mul_half2ints2316.v`.
- Vivado screenshots show unavailable `real_detect.bd` and `real_detect_wrapper.dcp` references. The missing project artifacts prevented complete restoration of the original Vivado flow; gate-level mapping and synthesized resource counts are not claimed.
- The 6.67 FPS processing throughput is not interchangeable with the 74.25 MHz HDMI pixel timing clock. The page labels the rates as estimates and includes the consistency caveat from the updated report.

## Sources

- [IIT Bhilai official website](https://www.iitbhilai.ac.in/)
- [Dr. Nitin Khanna — IIT Bhilai faculty profile](https://www.iitbhilai.ac.in/index.php?pid=nitin)
- [MANAS Lab — Multimedia Analysis and Security](https://sites.google.com/view/nitinkhanna/home)
- [Wikimedia Commons campus image source](https://commons.wikimedia.org/wiki/File:Kumaragupta_(Library_and_ITIS).jpg)
- [Creative Commons Attribution-ShareAlike 4.0](https://creativecommons.org/licenses/by-sa/4.0/)
