# Custom Sprites
Custom sprites for plantuml diagrams

[create_sprites.sh](create_sprites.sh) file copied from [PlantUML Repository](https://github.com/plantuml/plantuml)

## How to create sprite from PNG image

- find image and scale it down to 100x100 px (large icon) or smaller
- save image in the same filder as the [create_sprites.sh](create_sprites.sh) script
- use [create_sprites.sh](create_sprites.sh) to generate sprites
- reference sprites in your *plantuml* diagram like so:
`!include https://raw.githubusercontent.com/Piotr1215/sprites/master/rest-api.puml`
