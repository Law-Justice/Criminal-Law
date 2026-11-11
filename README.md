# Criminal Law: The Case File

A live, Pear Deck-style classroom game that combines the "Criminal Law" and "People Involved in
Criminal Law" decks. Students move a marker along the scale of proof, from a hunch to proof beyond a
reasonable doubt.

## What's inside (72 slides, six acts, 28 scored questions)
- Fewer but harder questions: long scenarios, three case-study sets (State v. Reyes, a trial transcript),
  six "select all that apply" questions with partial credit, two ordering slides, and four jury verdicts.
- Act I The Crime, Act II The Accused, Act III The Players, Act IV The Courtroom, Act V The Deal, Act VI The Verdict.

## Updating a site that is already live (keeps class progress)
1. In your GitHub repository, replace `index.html` with this file (same file name, same repository).
   The site address stays the same. Do not rename the file or change the repository.
2. Progress lives in the teacher's browser, so use the same browser and device that ran the class.
   Reload the page and choose **Resume my class**. The class code is the same.
3. Every student's earned XP is carried over, and the class is moved to the matching slide in the new deck.
   If the slide you were on was removed, it moves to the next slide that still exists.
4. Students can keep their link. They reload and enter the same class code.
5. From now on, XP is "banked" the moment you press Reveal answer, so later edits to questions never change
   points a student has already earned.

## Publish on GitHub Pages (first time)
1. Create a public repository and upload `index.html` to the top folder.
2. Settings > Pages > Source: **Deploy from a branch** > Branch: `main`, folder `/ (root)` > Save.

## Run a class
1. Open the page and choose **I'm the teacher**. You get a 4-letter class code.
2. Students open the same address (or use **Copy student link**), enter the code, and pick a call sign.
3. Use the arrow keys, Next/Prev, or the **Jump to...** menu. On question slides, press **Reveal answer**.
4. **Case Board** shows each student's marker on the scale of proof. Keep the teacher tab open.

## Editing the deck
Use the Case File Deck Editor to change questions and slides, then export a new `index.html`.
Exported files keep the carry-over data, so they also resume a class started on the previous version.

## If students on another network (Wi-Fi vs. wired) can't connect
Create a free account at https://www.metered.ca/tools/openrelay/ , make an app, and enter the app name and
API key in the editor's relay fields before exporting (or edit `TURN_RELAY` near the top of the script).

## Notes
- Carry-over assumes the live site is the previous 105-slide version of this game.
- Colorado details reflect state law as of late 2026. Check current statutes before relying on exact numbers.
- Answer keys are in the page source. Call signs and written responses are student-typed and not moderated.
