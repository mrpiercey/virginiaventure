# The Virginia Venture

A decision game about the first years of Jamestown, 1607 to 1612, for 5th grade social studies.

Students lead the colony through ten decisions. After each one they see what their choice did, what they gave up (the opportunity cost), and what the real settlers did. At the end they get a report they can copy into a doc.

- **Check the Charter.** Every decision has a Check the Charter button. It opens the real passage from the King's charter (April 1606) or the Virginia Company's instructions (November 1606) that speaks to that decision, with the key words highlighted and a plain-words version underneath.
- **Real evidence.** After each decision, students can open the primary sources behind it in a pop-up: the real words, a plain-words version, a question to think about, and a link to the full source. There are 16 sources in all, including John Smith's map and the 1616 portrait of Pocahontas.
- **You and the real Jamestown.** The final report puts each of the student's choices beside what the real settlers did, and charts how many of their people lived next to the real numbers.

## How to play

Open `index.html` in any web browser. There is nothing to install and no login.

- A full game takes about 15 to 20 minutes.
- The same choices always give the same result, so students can compare and talk about why.
- To print a report, use the browser's own print command (Ctrl+P or Command+P) on the last screen.

## What students practice

- **Standards:** 5.H.CO.1 (conflict and collaboration), 5.E.IC.1 (incentives and opportunity costs), 5.G.GR.1 (maps), 5.I.UE.1 (evidence and claims)
- **Words:** incentive, opportunity cost, collaboration, conflict, adapt
- **Each round also has** a box called "The other side of the river," which tells what the same moment looked like to the Powhatan.

## How true is it?

The places, dates, numbers, and events are real. The advisors' words were written for the game, based on what those people said or did. The player is a made-up leader. The real colony had several leaders, and their choices are described after each decision.

The scene pictures are original drawings made in code for this game. No art, text, or code was copied from any other game.

Every quotation in the pop-ups was copied from the page it links to. The three historical images in the `sources` folder (John Smith's map of Virginia, the 1616 engraving of Pocahontas, and John Smith's map of New England) are public domain scans from Wikimedia Commons.

Some sources use old spellings and unfair words for Powhatan people. Henry Spelman's full account describes violence. Preview the full sources before sending students to them.

## Look and feel

The game follows the Edutopia brand guidelines and shares its design system with Class Jobs Maker and Authentic or AI?: cream background, flat corner circles, slab headlines in Pacific Blue, pill buttons, white cards with soft shadows, and the palette ribbon under the top bar.

- **Fonts.** Poppins stands in for Gotham and is used for all interface text. Zilla Slab stands in for Museo Slab in headlines.
- **Colors.** The page and every picture are built only from the Edutopia palette and soft tints of it. The palette is listed as CSS variables at the top of `index.html`.
- **Electric Orange (#FF4C00)** is used sparingly: one word in the title and one main button per screen.
- **Logo.** The Edutopia "edu" bug is not included. Add it only if Edutopia is publishing the game.

## Put it online with GitHub Desktop

1. Open GitHub Desktop.
2. Choose **File**, then **Add Local Repository**, and pick this `virginiaventure` folder.
3. GitHub Desktop will say the folder is not a repository yet. Click **create a repository**, then **Create Repository**.
4. Click **Publish repository**. Uncheck **Keep this code private**, then click **Publish Repository**.
5. On github.com, open the new repository. Go to **Settings**, then **Pages**. Under **Branch**, choose **main** and **/ (root)**, then click **Save**.
6. Wait about a minute. The game will be live at `https://YOUR-USERNAME.github.io/virginiaventure/`.

To update it later: replace `index.html` (and keep the `sources` folder beside it), then in GitHub Desktop click **Commit to main** and **Push origin**.
