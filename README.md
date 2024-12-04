### About This Project
The contents of this project were written in Visual Studio Code.

_This version of the project was last updated: December 16th, 2022._

You can view the page at https://seanloesch.github.io/gomes-interactive-resume/.

# MY CONTRIBUTIONS

**All content in this project was written and curated by me**. You can find the
original version, which includes database functionality (though the file
structure and appearance are a bit unpolished), at the following link:
https://github.com/LaidlawJW/Interactive_Resume_CS268_Fall2022/.

In that version of the project, I did not write the SQL or PHP code. However,
most of the PHP is simply my HTML copied over.

# Overview/Backstory
This project was developed as the final project for my Web Systems course. When
the final project was introduced, we were tasked with creating a website for a
client and presenting our plan in a preliminary presentation. My partner and I
initially proposed a theoretical professor as our client, offering to create a
personal website for the theoretical professor. However, after our presentation,
Dr. Gomes, the course instructor, volunteered to serve as our actual client.
The rest is history.

Evidence of Dr. Gomes' involvement is available in `gomescv.pdf` in both my
version and the original and in his review of the project within the
Contribution section of `report.html`, located at the bottom of the file:
https://github.com/LaidlawJW/Interactive_Resume_CS268_Fall2022/blob/main/report.html.

# Interactive Features
Key features of the website include:

1. Fully-fledged animations and transitions for smooth viewing and navigation.
2. Sitewide multi-stage reactive sizing.
3. A back-to-top button that appears after scrolling a certain distance.
Please note that the only page currently long enough at standard magnification
for it to activate is the "Students" page. (_Also — Scroll distance checks
are throttled to every 50ms to minimize memory usage._)

## Weaknesses
- The reactive sizing does not accomodate mobile widths (~320-420px) on the
Research, Posts, and Students pages.
- There's a display issue on the About Me page that occurs between a width of
920-1360px where the main content box overflows to the right outside of the
page's intended border.
- My version does not include database compatbility — it is entirely front-end.
