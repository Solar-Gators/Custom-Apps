# Custom-Apps
Self-contained HTML applications for Solar Gators.

**[GatorWire](https://solar-gators.github.io/Custom-Apps/gatorwire)** — Turns a draw.io wiring diagram into a full wiring spec: define every connector, conductor, and splice in one place.
**Workflow**

1. **Upload drawing** — bring in a `.drawio` wiring diagram. GatorWire finds every shape and asks which are components and which are just zones.
2. **Click anything on the diagram** — a wire, component or connector opens the connection editor. Name pins and cavities, and lay conductors two clicks at a time.
3. **Add connectors and splices** anywhere along a run, then place them on the drawing when prompted. **Edit drawing** opens Draw.io in the page whenever the diagram itself needs changing.
4. **Save file** — one `.json` holding the data, the drawing and its picture. **Open file** picks it back up on any computer. Nothing is uploaded; there is no account and no server.
5. **Export finalised** — one read-only `.html` of the finished diagram. It opens in any browser, still shows what every wire joins, and cannot be edited.

**[CE Scope Map](https://solar-gators.github.io/Custom-Apps/responsibilitymap)** — An editable four-way Venn diagram of Chief Engineer responsibilities and where their scopes overlap. A living document for future CEs.
