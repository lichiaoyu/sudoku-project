# Sudoku Mock Website – README Writeup

**Link to website on Github Page:** [https://lichiaoyu.github.io/sudoku-project/](https://lichiaoyu.github.io/sudoku-project/)  
**Collaborators:** Chiao-Yu Li, Xinyi Zhang, Tianlu Xu  
**GithubRepo:** [https://github.com/lichiaoyu/sudoku-project](https://github.com/lichiaoyu/sudoku-project)  
**Link to video:** [https://youtu.be/V_ptH7AUttk](https://youtu.be/V_ptH7AUttk)

---

### 1. What was the most challenging piece of this assignment? Did you find it easy or challenging to work with HTML and CSS? How long did this assignment take?

One of the challenging parts of this assignment was building a consistent layout across all pages while maintaining a professional and clean design. Since this project only allowed HTML and CSS, we needed to carefully structure our HTML and rely on CSS layout techniques like Flexbox and Grid to control spacing and alignment.

We found HTML relatively straightforward because it is mainly used for structuring content. However, CSS was more challenging, especially when trying to position elements correctly and make the website responsive. Understanding how Flexbox works and managing spacing between components required practice and experimentation.

Another tricky part was using pseudo-selectors (nth-child) to create the Sudoku sub-grids. We had to calculate the exact cell numbers to place thick borders in the right spots. Especially when we had to make sure the borders didn't look messy when the board shrunk for mobile screens.

Overall, this assignment took us approximately 20-30 hours to complete.

### 2. What decisions did you make when you made your site mobile friendly?

To make the website mobile friendly, we used responsive layout techniques such as Flexbox and Grid. These allowed elements to automatically adjust their size and position depending on the screen width.

We also used media queries to adjust font sizes, spacing, and layout for smaller screens. For example, navigation items and game selection cards become easier to read and interact with on mobile devices. We moved the navbar from the top to the bottom on mobile devices, making it more accessible for thumb navigation. We also changed the feature cards from a 3-column grid to a single column layout, and ensured all buttons and inputs were large enough for touch interaction. The Sudoku boards scale proportionally to fit smaller screens while remaining playable.

### 3. What did you take into account when you developed the design of your website? What are you particularly proud of?

We separated page-specific CSS into individual files while keeping shared styles in global.css. This helped us keep a consistent look across the site, and it also made it easier to debug or tweak one page without accidentally affecting others. We’re also happy we used CSS variables for colors and spacing, because once the theme was set, we could update the whole site quickly and consistently.

For the design, we chose a nature-inspired green palette because one of our teammates mentioned she can get really immersed in Sudoku and her eyes sometimes feel strained afterward. We wanted a calmer UI with lower contrast, so the site feels less “harsh” during longer play sessions. To find a good direction, we first browsed green, soothing poster templates on Canva, picked one that felt calming, and extracted the main colors from it as our theme. We then applied those colors across the UI (navbar, cards, borders, and buttons) and used the “DynaPuff” font from Google Fonts to keep the vibe friendly instead of overly formal.

Finally, we made a conscious choice to keep the navbar concise by using a single “Play” entry point, and letting users switch between Selection/Easy/Hard inside the gameplay flow. This made navigation simpler and reduced clutter, especially on mobile.

We’re most proud of how consistent the site feels across pages, especially the navbar and the overall spacing/typography. We also spent a lot of time tuning the Sudoku board borders (thicker subgrid lines) so the 9×9 and 6×6 boards look clean instead of “messy,” even when the screen gets smaller. On mobile, we’re proud that the layout still reads well and the navbar moves to the bottom without covering content. Lastly, having our own theme image on the home page made the project feel more complete and branded instead of looking like a plain class demo.

### 4. Given more time or resources, what additional features would you add?

If JavaScript is allowed in later parts, we would add real Sudoku behavior such as input validation (only allow 1–9 or 1–6) and conflict highlighting for rows/columns/subgrids. We would also implement a real timer and a “finish game” flow that records completion time. Lastly, we’d add small usability enhancements like a reset button, pencil marks/notes, and accessibility improvements for keyboard navigation.

### 5. How many hours did you spend on this assignment?

As a team, we spent approximately 20–30 hours on this assignment. This time was divided between the initial design phase, structuring the HTML for all pages, implementing complex CSS layouts and refining the responsive elements to ensure everything worked smoothly on mobile devices.

### 6. If you used code or design from somewhere online, please mention it here. Furthermore, if you imported a file to use a Fonts or Icons library, please indicate that here as well.

* **Font:** DynaPuff (Google Fonts). Imported via CSS @import in assets/css/global.css.
* **Design reference:** We referenced a Canva green-themed infographic template for color palette and calming style direction (used as visual inspiration only; we did not copy Canva graphic assets directly).
* **Canva template link:** [https://www.canva.com/es_es/plantillas/EAGIU_26sEE-infografia-datos-sobre-medio-ambiente-organico-ilustrado-verde/](https://www.canva.com/es_es/plantillas/EAGIU_26sEE-infografia-datos-sobre-medio-ambiente-organico-ilustrado-verde/)
* **Images:** The home page hero image was AI-generated based on our chosen color palette and Sudoku theme.
