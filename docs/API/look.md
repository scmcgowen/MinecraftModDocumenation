# Look API

Look API are mostly just improved `inspect` from ComputerCraft Turtle API. It is not pretty useful by itself, but it helps to understand who will be targeted of another APIs, like [Interaction API](interaction.md) or [Capture API](capture.md).

| Function                                           | Returns | Description                                                                                                                                                                                                                          |
|----------------------------------------------------|---------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| look(mode: [InteractionMode](introduction.md#interaction-mode), direction?: [Direction](introduction.md#direction)) | table   | Returns detailed information about first target in line of sight.  |

??? tip "Look output examples"
    ??? tip "Entity"
        ```json
        {
            "type": "Cow",
            "name": "Cow",
            "category": "CREATURE",
            "id": 1269,
            "tags": {},
            "uuid": "0737fd25-a1b6-4a1a-9cdd-3081e0155bb6"
        }
        ```
    ??? tip "Block"
        ```json
        ```
