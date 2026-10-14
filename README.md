# Micro Medics: Body Systems Case Files

An interactive review game for **Georgia 7th Grade Life Science, S7L2** (cells, levels of organization, and body systems interacting), aligned to the **Gwinnett County 7th Grade Science AKS**.

Students shrink down to cell size and help four 7th-grade patients: Jordan (soccer tournament), Leo (lunch and PE), Ava (a cold), and Sofia (a science fair presentation). There are 77 questions, and every case covers all 7 systems named in S7L2.c: cardiovascular, excretory, digestive, respiratory, muscular, nervous, and immune.

© 2026 Dr. Rebecca Cooper

## Features
- **Study briefings** for each zone: flip cards, diagrams, "Did you know?" facts, and source links
- **Feedback:** celebration on correct answers, encouragement when close, and "Read this, then try again" notes when wrong, with a Try again button
- **Learn-more links** to Nemours KidsHealth and NIH pages, with Spanish versions where available
- **Lightning Round:** a 90-second timed review, solo or in teams
- **Auto-save** on each device, with an "Is this you?" check for shared devices
- **Copy my results:** students paste a summary into a Google Form, LMS, or email
- **Teacher answer key** (password-protected) and **vocabulary sheet**, both printable
- **Medical report** scored by standard and by body system (first tries only)

## Put it on GitHub Pages
1. Create a new repository on GitHub (for example, `micro-medics`). Set it to **Public**.
2. Upload `index.html`, `README.md`, and `.nojekyll` to the main branch. (On the upload page you can drag the files in. If `.nojekyll` is hidden on your computer, it's optional.)
3. Go to **Settings → Pages**. Under "Build and deployment," choose **Deploy from a branch**, pick **main** and **/ (root)**, then **Save**.
4. Wait a minute or two. Your link will be `https://YOUR-USERNAME.github.io/micro-medics/`.
5. Open the link in a private/incognito window on a student device to confirm it loads and isn't blocked by the district filter.

To update the game later, upload a new `index.html` over the old one.

## Teacher password
- The answer key asks for a teacher password. It stays unlocked until the browser tab is closed or you click **Lock**.
- **To change it:** unlock the answer key, open **Change the teacher password**, type a new one, and copy the line it gives you. In `index.html`, replace the line that starts with `const TEACHER_KEY_HASH` with your new line, then upload the file again.
- The password itself is never written in the file (only a scrambled version is), but this is a deterrent, not true security. The game needs the answers to check student work, so a tech-savvy student could still find them with browser developer tools.

## Good to know
- **One file.** Everything runs from `index.html`; no server or accounts needed.
- **Saving** uses the browser's local storage, so progress stays on that device and browser only. Clearing browser data or switching devices starts fresh.
- **Fonts** load from Google Fonts. If a network blocks them, the game uses standard fonts instead.
- **No student data leaves the device.** Results are only shared when a student copies and pastes them.

## Standards and sources
- Georgia Standards of Excellence, Grade 7 Science, S7L2 (GaDOE) and the GaDOE GSE Science FAQ & Clarifications (2021)
- Gwinnett County Public Schools, 7th Grade Science AKS (2025–26)
- Science content checked against OpenStax *Biology 2e* and *Anatomy & Physiology 2e* (openstax.org), NIH/NIDDK, and MedlinePlus
- Standards, AKS, and all links last checked September 2026. Re-check links each semester.
