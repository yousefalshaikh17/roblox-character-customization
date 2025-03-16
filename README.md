# Character Customization Systems

### Overview

I developed a character customization system for a client with a published title. This system enables players to create and customize their characters or OCs (Original Characters), allowing them to wear any item from the Roblox catalog. This approach is similar to the [Catalog Avatar Creator](https://www.roblox.com/games/7041939546/Catalog-Avatar-Creator), but tailored to our specific audience.

The system allows players to manage multiple characters with individual bios, name colors, and outfits. They can easily switch between characters and outfits, providing a dynamic and personalized experience. A significant amount of effort went into the exporting and importing processes to ensure efficient data compression, allowing users to store multiple characters and outfits. We currently support 50 characters with 50 outfits each, with plans to increase these limits to 1000 characters and 3000 outfits through datastore splitting.

### Development & Features

The project was developed on Roblox and their Luau programming language. Key milestones included:

- **Character Creation**: Players can create and customize characters, including setting names and bios, with full access to items from the Roblox catalog.
- **Outfit Management**: Characters can have multiple outfits, and players can switch between these outfits easily.
- **Data Compression**: Focused on data optimization to ensure users can store many characters and outfits without hitting datastore limits, resulting in a 80% reduction in outfit data size. Current limits are 50 characters with 50 outfits each, with plans to increase this further.
- **Avatar Compression System**: Avatars are compressed into avatar codes, which are short and efficient for storage in datastores, making it easier for players to share and use avatars.
- **Roblox Studio Plugin**: We introduced a plugin that allows players to import their custom creations directly into Roblox Studio.
- **Advanced Customization**: Recently added advanced customization options, including the ability for players to use custom textures for faces and manipulate various accessory options.
    - **Accessory Customization**: Players can modify position, rotation, scale, color, and texture of accessories. We’re also working on a new option to adjust accessory welds to other limbs.

### Real-World Applications

This project allowed me to explore efficient data compression techniques and develop a custom avatar system for a large-scale multiplayer game. The advanced customization features also provided insight into how to implement flexible and user-friendly UI systems and character customization workflows. We’re now working on open sourcing the avatar compression system to help other developers integrate it into their own games.

### Screenshots of the Character Customization
Screenshots will be shown at a later time once cleared with the client.
