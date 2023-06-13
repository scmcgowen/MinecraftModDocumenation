# Suck API

Suck API exists for sucking surrounding items to peripheral owner inventory

| Function                                | Returns | Description                                                                                            |
|-----------------------------------------|---------|--------------------------------------------------------------------------------------------------------|
| suck(limit?: number, query?: [ItemQuery](introduction.md#itemquery)) | [Result](introduction.md#result)  | Tries to suck items around interaction radius. If query is provided, sucked item will be limited by it |
