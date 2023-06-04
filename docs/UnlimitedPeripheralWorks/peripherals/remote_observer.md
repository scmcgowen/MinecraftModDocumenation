# Remote observer

??? info "Supported versions"
    **Forge**: 1.19.4
    **Fabric**: 1.19.4

Observer is a perfect tool for tracking remote changes. But this tools is vastly limited by position and redstone logic. Computer world shouldn't be limited with this! Remote observer allows you to observe block state changes from a small range. And it also works with up to 8 blocks (by default).

## How to configure

To configure remote observer, you can use [ultimate configurator](ultimate_configurator.md) or peripheral methods. 

## Peripheral methods

| Function                                             | Returns                          | Description                            |
|------------------------------------------------------|----------------------------------|----------------------------------------|
| addPosition([blockPos](introduction.md#blockpos))    | [Result](introduction.md#result) | Tries to add new position to track     |
| removePosition([blockPos](introduction.md#blockpos)) | [Result](introduction.md#result) | Tries to remove position from tracking |
| getPositions()                                       | table                            | Return list of all tracked positions   |


## Events

### block_change

Fires when any observer block changes it block state (take a note, that this happens also when block is destroyed or placed)

#### Values

1. `blockPos: table` relative position of block, that changed
2. `oldState: table` lua table with old block state
3. `newState: table` lua table with new block state
