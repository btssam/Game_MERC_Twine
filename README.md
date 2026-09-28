# Merc

A 29,800+ word interactive branching narrative game built with **Twine 2** using the **Harlowe 3.2.2** story format. 

*Merc* puts players in command of a mercenary company.

**Play in Browser:** [Merc on itch.io](https://btssam.itch.io/merc)

---

## Technical Architecture

- **Story Format:** Harlowe 3.2.2
- **Twine Version:** Twine 2.3.14+
- **Structure:** 
  - Dynamic state machine managing inventory, currency, companion approval, and moral alignment.
  - Custom Twine user styles (`twine-user-stylesheet`) optimizing text-box presentation, typography, and link color states.
  - Variable-based state tracking over 106 unique choice branches.

---

## How to Open and Edit

### Option 1: Play Directly in Browser
You can run the game locally without any software:
- Double-click `Merc_Folder/Merc.html` (or `Merc_pt2_7.html`) to open and play in any standard web browser.

### Option 2: Inspect or Edit in Twine
1. Download or launch [Twine 2](https://twinery.org/) (browser or desktop edition).
2. Click **Import From File**.
3. Select `Merc_Folder/Merc.html`.
4. Twine will reconstruct the full interactive story map showing all passage connections, variables, and macros.

---

## Credits

- **Story, Writing, & Game Design:** Ben Samara
- **Engine:** [Twine](https://twinery.org/) (Harlowe 3.2.2)

---

## License

- **Code & Logic:** Licensed under the [MIT License](LICENSE).
- **Narrative, Characters, & Writing:** Licensed under [Creative Commons Attribution-NonCommercial 4.0 (CC BY-NC 4.0)](LICENSE).
