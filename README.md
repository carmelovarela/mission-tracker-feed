# Mission Tracker feed

SpaceX launch data for the Mission Tracker iPhone app, rebuilt every 15 minutes.

**Feed:** https://carmelovarela.github.io/mission-tracker-feed/feed.json

Built from the public launch data on [spacex.com](https://www.spacex.com/launches/), with [Launch Library 2](https://thespacedevs.com/llapi) by The Space Devs filling what SpaceX doesn't publish (launch status, probability, weather, booster serials). Not affiliated with SpaceX. Launch times can change at short notice.

- `gh-pages`: the current `feed.json` (and the generator's cached source data in `state/`), replaced on each run.
- `main`: the workflow, and a weekly snapshot of the feed in `history/`.
