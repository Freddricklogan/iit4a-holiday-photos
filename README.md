# IIT-4A Holiday Photos

A single-page call for holiday photographs and short videos from the students, alumni,
friends and families of the African American Alumni Association of Illinois Tech, for
**Newsletter Issue III** (published January 31, 2027).

Any holiday from **Thanksgiving through Dr. Martin Luther King Jr. Day** counts, anywhere
in the world. **Submissions close January 30, 2027 at midnight.**

## What this is

`index.html` is self-contained — one file, no build step, no dependencies. It carries the
IIT-4A mark on Illinois Tech red over a bright winter palette, and a canvas weather layer
the visitor sets themselves (snowfall, flurries, blowing snow, sleet, clear and cold,
winter sun) or leaves on **Auto**, which turns the weather over on its own every nineteen
seconds. It honours `prefers-reduced-motion`.

Submissions arrive by email: the visitor fills in their name, the holiday and a caption,
ticks the permission box, and the button opens a pre-filled message to
`iit4a.records@gmail.com` for them to attach their files to.

## Publishing it

Settings → Pages → Build and deployment → **Deploy from a branch** → `main` / `/ (root)`.
The page is then served at `https://freddricklogan.github.io/<repo>/`.

## Editing the copy

Everything a person reads is in the markup near the top of `index.html`: the masthead, the
lede, the deadline, the holiday chips, the "Not sure what to send?" examples, the note for
anyone marking a loss this season, the form labels, the permission wording and the footer.
The weather engine is the last block in the file and needs no attention.

To change the editor's address, replace every instance of `iit4a.records@gmail.com`.

---

Maintained by Dr. Freddrick Logan, Recording Secretary & Editor, IIT-4A.
