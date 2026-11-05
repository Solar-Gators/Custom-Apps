# Custom-Apps
Self-contained HTML applications for Solar Gators.

## [GatorWire](https://solar-gators.github.io/Custom-Apps/gatorwire)
Turns a draw.io wiring diagram into a full wiring spec: every connector, conductor, and splice defined in one place.

### Work on Car 5 with the team
The Car 5 project lives in **[Solar-Gators/Gator-Wire](https://github.com/Solar-Gators/Gator-Wire)**, and everyone edits it at the same time.

1. **Make a token, once.** Follow the steps in the [Gator-Wire README](https://github.com/Solar-Gators/Gator-Wire#getting-started). It takes about five minutes.
2. **Connect.** Open GatorWire, click **In this browser · Share** at the top right, paste your token, and click **Connect**.
3. **Work.** Your edits save on their own, and teammates' changes show up within about half a minute. If two people change the same thing, the app asks which version to keep.

Without a token you can still connect and look at Car 5, but you can't save.

### Workflow
1. **Upload drawing:** bring in a `.drawio` wiring diagram. GatorWire finds every shape and asks which are components and which are just zones.
2. **Click anything on the diagram:** a wire, component, or connector opens the connection editor. Name pins and cavities, and lay conductors two clicks at a time.
3. **Add connectors and splices** anywhere along a run, then place them on the drawing when prompted. **Edit drawing** opens Draw.io in the page whenever the diagram itself needs changing.
4. **Export finalised:** one read-only `.html` of the finished diagram. It opens in any browser, still shows what every wire joins, and can't be edited.

### Working on your own
Skip the **Share** button and GatorWire works entirely offline, with no account and nothing uploaded. **Save file** writes one `.json` holding the data, the drawing, and its picture, and **Open file** picks it back up on any computer. This is useful for trying things out without touching the team's project.

## [CE Scope Map](https://solar-gators.github.io/Custom-Apps/responsibilitymap)
An editable four-way Venn diagram of Chief Engineer responsibilities and where their scopes overlap. A living document for future CEs.

## [Solar Evals](https://solar-gators.github.io/Custom-Apps/solarevals)
The semester review rubric. It holds the **master template** and a version for each CE division, and every saved version is kept, so the next CE sees what the last one used and why they changed it.

- **Look:** pick the master template or a CE division on the left. **Print / PDF** prints the two-page form.
- **Make your version:** open your division and click **Start from master** (or **Make a new version**). Click any text on the pages to change it, add or remove criterion rows, then **Save as new version** with your name and a note on what changed.
- **History** lists every version. **Compare** shows exactly what changed between any two (for example master vs. your division, or this semester vs. last).
- If the master template changes after you made your version, your division shows a note with a link to see what changed.

Versions are saved to `rubrics.json` in **[Solar-Gators/Solar-Evals](https://github.com/Solar-Gators/Solar-Evals)**. Saving needs a token, made the same way as for GatorWire but for the Solar-Evals repository; click the status at the top right to connect. Without a token you can still look at everything.
