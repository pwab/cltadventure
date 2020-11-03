# CLTadventure

Built with the [WorkAdventure](https://workadventu.re) Map [Starter Kit](https://github.com/thecodingmachine/workadventure-map-starter-kit).

## Let's play

Click here: https://play.workadventu.re/_/global/pwab.github.io/cltadventure/map.json

## Edit the map

### Prerequisites

In order to edit the map for CLTadventure, you need:

- the [Tiled editor](https://www.mapeditor.org/) software
- "tiles" (i.e. images) to create your map

### Workflow

Then the process to edit is as follows:

1. Fork this repository
1. Clone your fork
2. Load the map `map.json` into Tiled
3. Edit the map and save the changes
4. Commit and push
5. Create a PR for this repository
6. Wait for merge

### Hints

In order to design a map that will be readable by WorkAdventure, you will need to:

- set a start position for the players
- configure the "floor layer" (so that WorkAdventure can correctly display characters above the floor, but under the ceiling)
- eventually, you can place exits that link to other maps

More details can be found here:

- [Workadventure Map rules](https://workadventu.re/create-map.html#workadventure-maps-rules)

Some resources regarding Tiled:

- [Tiled documentation](https://doc.mapeditor.org/en/stable/manual/introduction/)
- [Tiled video tutorials](https://www.gamefromscratch.com/post/2015/10/14/Tiled-Map-Editor-Tutorial-Series.aspx)
