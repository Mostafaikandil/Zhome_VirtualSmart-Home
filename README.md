# Zhome Experience · Virtual Dubai Villa

An interactive, three-room showroom. Explore how a home can respond to time and occupancy, and compare those automatic responses with manual controls.

## Open or upload

Open `index.html` in a browser. To update your repository, put `index.html` and `README.md` at its root. All images, styles, and scripts are embedded. The demo runs offline and has no build step.

## Try the villa

- **Family living** — use the four scenes or the Touch Pure Display Tree demo. After a time or occupancy change, the room selects Away while vacant, Good Night during night hours while occupied, or Welcome Home at other occupied times.
- **Bedroom** — choose 23:00, then switch the room to occupied. The curtains close at night and the low path light follows presence. The two bedroom controls can be used manually. The burglary test shows a main entrance alert on the bedroom phone.
- **Kitchen** — move to evening or night and set the room to occupied to see task lighting come on. Test smoke or an under-sink leak to see it on the kitchen phone. Each test adds a timestamped alert to the Loxone-styled phone preview. Smoke drifts above the cooktop, and a leak spreads and ripples across the floor by the island. Select the same test again to clear its visual effect and alert. The demo sends no push notifications.
- **Guided tour** — the spotlight points to each step. Tapping the highlight advances the guide. The room controls resume after the tour.

Time is shared across the villa. Occupancy is tracked per room. Time changes reapply all room rules. Occupancy changes reapply the rule in the selected room. Manual choices hold until the next relevant simulation input.

## Simulation and assets

The experience uses generated room imagery and Zhome-supplied product references and logo. The preview uses the supplied Loxone notification graphic and app mark. It runs entirely in the browser, with no tracking or live device connection. Alert tests are illustrative, and all readings are simulated. Room humidity is shown alongside the Smoke & Presence Detector readings as a separate simulated input. See [Loxone Smoke & Presence Detector](https://www.loxone.com/int/products/security/smoke-presence-detector/) and [Water Sensor Air datasheet](https://updatefiles.loxone.com/KnowledgeBase/Online/Common/Documents/Datasheet_WatersensorAir_100211.pdf).
