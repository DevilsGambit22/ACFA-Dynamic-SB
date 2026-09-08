# ACFA GitHub Dashboard

Routine maintenance is done in **one file only**:

`data/acfa.json`

## Home dashboard
The home dashboard automatically handles:
- animated ACFA logo hero
- local clock
- time-based greeting
- Chess.com newest members
- Chess.com titled members
- vertical club-rules marquee

Only club events and rules need to be maintained in JSON.

## Tournament dashboard
Edit the current season inside `tournament`.

For winners, enter only:

```json
{
  "season": "Fall",
  "year": 2026,
  "username": "ChessUsername"
}
```

The dashboard automatically loads the player's current Chess.com:
- avatar
- title
- profile link
- rating

The three most recent winners are rendered as a podium. The latest champion is raised in the center, with the previous two on the sides. All winners also appear in the archive.

## Upload to GitHub
Upload the contents of this folder to the repository root and enable GitHub Pages.


## New-member mascot asset
`assets/lady-justice-new-members.png` is the compact transparent Lady Justice wave asset used inside the Newest Members board. It is positioned decoratively in the lower-right corner and does not block clicks or API content.
