# Lifts

[Lifts](https://www.curseforge.com/minecraft/mc-mods/lifts) a technology mod that adds various lifts for better vertical traversal inside your world.

This integration allows you to control lift and moves it via CC computers. Any lift controller will provide such capabilities to you

> [!info]
> This integration only for 1.18, lifts not yet updated to 1.19

## Peripheral methods

| Function                    | Returns        | Description                                                       |
|-----------------------------|----------------|-------------------------------------------------------------------|
| floors()                    | table          | Returns list of floors with information about related controllers |
| getCurrentFloor()           | [Result](./../../turtlematic/api/introduction.md#result)[number] | Get current floor index                                           |
| getFloorName(floor: number) | string         | Get floor name, how it will be displayed on lift controller hud   |
| changeFloor(floor: number)  | [Result](./../../turtlematic/api/introduction.md#result) | Tries to send lift to selected floor                              |