# 7AD Debate Games

Classroom-ready HTML tools for the Grade 7 debate class (7AD).

## Tools

| Tool | Use | Link |
| --- | --- | --- |
| Debate Scoreboard | Live squad points for the five debate skills, plus a 60/90-second speech timer | [scoreboard.html](scoreboard.html) |

## Debate Scoreboard

- Six squads, one card each, sized to read and click from the back of the room with a mouse.
- **+** and **−** buttons for each skill: Argument, Response, Persuasion, Delivery, WSDC Strategy.
- **Key** shows what earns and what loses points. Show it once at the start of the lesson.
- **Undo last point** takes back the most recent click.
- **Copy scores** copies one row per squad (date, total and five skill totals) to paste into a spreadsheet.
- **New debate: clear scores** needs a second click and keeps the squads.
- **Edit squads**: six lines, one per squad, written `Squad 1: name, name, name`.

Keyboard: **Space** starts or pauses the timer, **R** resets it, **K** opens the Key, **Z** undoes the last point.

### Where scores are saved

Squads, scores and the timer length are saved in the browser that opens the page (on that laptop, in that browser only). They stay after a refresh or restart. Another computer or browser starts with a blank board. Use **Copy scores** before you clear the board.

Student names are not stored in this repository. Enter them with **Edit squads** on the classroom laptop.

## Publish using GitHub Pages

In this GitHub repository:

1. Select **Settings**.
2. In the sidebar, open **Pages** (under Code and automation).
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select branch **main**, folder **/(root)**, then **Save**.

Once GitHub finishes publishing, the scoreboard should be available at:
https://richardmichael0000-cpu.github.io/7AD-Debate-Games/scoreboard.html

GitHub Pages may take a little time to publish a newly configured site.

## Structure

- `scoreboard.html`: the debate scoreboard (standalone HTML, CSS and JavaScript; it loads only its fonts from Google Fonts)
- `README.md`: this page
