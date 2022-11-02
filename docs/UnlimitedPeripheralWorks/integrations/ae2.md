# Applied Energistics 2

Applied Energistics 2 is a mod for [Minecraft](https://www.minecraft.net/) which contains a large amount of new content, mostly centered around the concept of using Energy, and the Transformation of Energy in a unique way. 

This integration allows you to interact with AE2 network itself, transforming some blocks (CPU cores, energy modules) into peripheral, that would provide full-featured AE2 integration.

## Supported APIs

- [[storage|Storage]] API for all items, that stored inside system
- [fluid_storage](https://tweaked.cc/generic_peripheral/fluid_storage.html) API for all fluids, that stored inside system

## Additional peripheral methods

| Function                                                                         | Returns | Description                                                                                        |
| -------------------------------------------------------------------------------- | ------- | -------------------------------------------------------------------------------------------------- |
| getEnergy()                                                                      | number  | Returns amount of stored energy in AE2 system                                                      |
| getEnergyCapacity()                                                              | number  | Returns amount of max stored energy in AE2 system                                                  |
| getAverageEnergyDemand()                                                         | number  | Returns average energy demand of AE2 system                                                        |
| getAverageEnergyIncome()                                                         | number  | Returns average energy income for AE2 system                                                       |
| getChannelEnergyDemand()                                                         | number  | Returns amount of energy that spent for channels                                                   |
| getChannelInformation                                                            | table   | Returns information about maxium and actual amount of channels in AE2                              |
| getCraftingCPUs                                                                  | table   | Returns detailed information about crafting CPUS, including name, capacity, storage and occupation |
| getCraftableItems                                                                | table   | Returns list of craftable items inside AE2 system                                                  |
| getCraftableFluids                                                               | table   | Returns list of craftable fluids inside AE2 system                                                 |
| getPatternsFor("item", item_id: String)                                          | table   | Returns list of patterns, that exists for particual item inside AE2 system                         |
| getPatternsFor("fluid", fluid_id: String)                                        | table   | Returns list of patterns, that exists for particual fluid inside AE2 system                        |
| scheduleCrafting("item", item_id: String, amount?: number, targetCPU?: string)   | [Result](introduction.md#result)  | Try to schedule crafting for an item                                                               |
| scheduleCrafting("fluid", fluid_id: String, amount?: number, targetCPU?: string) | [Result](introduction.md#result)  | Try to schedule crafting for an fluid                                                              |
