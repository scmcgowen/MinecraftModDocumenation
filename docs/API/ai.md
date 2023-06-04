# AI API

AI API responsible for controlling entities AI, toggling it and perform checks if it is enabled or disabled.

| Function                                                        | Returns                          | Description                                                                     |
|-----------------------------------------------------------------|----------------------------------|---------------------------------------------------------------------------------|
| toggleAI(direction?: [Direction](introduction.md#direction))    | [Result](introduction.md#result) | Tries to toggle AI of entity in specific direction                              |
| isAIEnabled(direction?: [Direction](introduction.md#direction)) | boolean?                         | Returns true if entity AI is enable, false if not and nil if there is no entity |
