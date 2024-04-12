# StarRailResStaticAPI

Serving [StarRailRes](https://github.com/Mar-7th/StarRailRes) static JSON files.

## Overview

Endpoints are broken down into 3 main components: base, language, and endpoint.

```
https://{base_url}/{language}/{endpoint}.json
```

### Base URL

Start with the base URL:

```
vizualabstract.github.io/StarRailResStaticAPI/db/
```

### Language

Append the language code to the base URL. For example, if you want to use English, add en:

- Chinese: `cn`
- Chinese (Traditional): `cht`
- German: `de`
- English: `en`
- Spanish: `es`
- French: `fr`
- Japanese: `jp`
- Korean: `kr`
- Portuguese: `pt`
- Russian: `ru`
- Taiwanese: `th`
- Vietnamese: `vi`

### Endpoint

After selecting the language, add the specific endpoint you want to access. Here are the available English endpoints:

- Achievements: `achievements`
- Avatars: `avatars`
- Character Promotions: `character_promotions`
- Character Ranks: `character_ranks`
- Character Skill Trees: `character_skill_trees`
- Character Skills: `character_skills`
- Characters: `characters`
- Descriptions: `descriptions`
- Elements: `elements`
- Items: `items`
- Light Cone Promotions: `light_cone_promotions`
- Light Cone Ranks: `light_cone_ranks`
- Light Cones: `light_cones`
- Nickname: `nickname`
- Paths: `paths`
- Properties: `properties`
- Relic Main Affixes: `relic_main_affixes`
- Relic Sets: `relic_sets`
- Relic Sub Affixes: `relic_sub_affixes`
- Relics: `relics`
- Simulated Blessings: `simulated_blessings`
- Simulated Blocks: `simulated_blocks`
- Simulated Curios: `simulated_curios`
- Simulated Events: `simulated_events`

### Full URL

This pattern will allow you to get your desired resource in the desired language.

```
https://vizualabstract.github.io/StarRailResStaticAPI/db/en/achievements.json
```

### Example Endpoints

- [en/avatars.json](https://vizualabstract.github.io/StarRailResStaticAPI/db/en/avatars.json)
- [en/character_promotions.json](https://vizualabstract.github.io/StarRailResStaticAPI/db/en/character_promotions.json)
- [en/character_ranks.json](https://vizualabstract.github.io/StarRailResStaticAPI/db/en/character_ranks.json)
- [en/character_skill_trees.json](https://vizualabstract.github.io/StarRailResStaticAPI/db/en/character_skill_trees.json)
- [en/character_skills.json](https://vizualabstract.github.io/StarRailResStaticAPI/db/en/character_skills.json) 
- [en/characters.json](https://vizualabstract.github.io/StarRailResStaticAPI/db/en/characters.json) 
- [en/descriptions.json](https://vizualabstract.github.io/StarRailResStaticAPI/db/en/descriptions.json) 
- [en/elements.json](https://vizualabstract.github.io/StarRailResStaticAPI/db/en/elements.json) 
- [en/items.json](https://vizualabstract.github.io/StarRailResStaticAPI/db/en/items.json) 
- [en/light_cone_promotions.json](https://vizualabstract.github.io/StarRailResStaticAPI/db/en/light_cone_promotions.json) 
- [en/light_cone_ranks.json](https://vizualabstract.github.io/StarRailResStaticAPI/db/en/light_cone_ranks.json) 
- [en/light_cones.json](https://vizualabstract.github.io/StarRailResStaticAPI/db/en/light_cones.json) 
- [en/nickname.json](https://vizualabstract.github.io/StarRailResStaticAPI/db/en/nickname.json) 
- [en/paths.json](https://vizualabstract.github.io/StarRailResStaticAPI/db/en/paths.json) 
- [en/properties.json](https://vizualabstract.github.io/StarRailResStaticAPI/db/en/properties.json) 
- [en/relic_main_affixes.json](https://vizualabstract.github.io/StarRailResStaticAPI/db/en/relic_main_affixes.json) 
- [en/relic_sets.json](https://vizualabstract.github.io/StarRailResStaticAPI/db/en/relic_sets.json) 
- [en/relic_sub_affixes.json](https://vizualabstract.github.io/StarRailResStaticAPI/db/en/relic_sub_affixes.json) 
- [en/relics.json](https://vizualabstract.github.io/StarRailResStaticAPI/db/en/relics.json) 
- [en/simulated_blessings.json](https://vizualabstract.github.io/StarRailResStaticAPI/db/en/simulated_blessings.json) 
- [en/simulated_blocks.json](https://vizualabstract.github.io/StarRailResStaticAPI/db/en/simulated_blocks.json) 
- [en/simulated_curios.json](https://vizualabstract.github.io/StarRailResStaticAPI/db/en/simulated_curios.json) 
- [en/simulated_events.json](https://vizualabstract.github.io/StarRailResStaticAPI/db/en/simulated_events.json)

## Images

Many of the resources with endpoints have references to images and icons. This project's sole focus is to serve files as they are from their source repos.

Because of this, I've limited myself to only moving folders into directories I feel will make consumption of the API easier to understand.

This means zero file editing.

```
https://{base_image_url}/{asset_path}
```


So while the data may provide an image URL, it's only a path. For example, March 7th:

```
"1001": {
    "id": "1001",
    "name": "March 7th",
    "tag": "mar7th",
    "rarity": 4,
    "path": "Knight",
    "element": "Ice",
    "icon": "icon/character/1001.png",
    "preview": "image/character_preview/1001.png",
    "portrait": "image/character_portrait/1001.png"
}
```

Here, there are 3 asset files associated with her: an icon and two images.

To access their images, you'll need to prefix each URL with the base path to the asset directory, then append these paths to get the full image URL.

### Base Image URL

This path will allow you to access both icons and images

```
vizualabstract.github.io/StarRailResStaticAPI/assets
```

### Asset Path

As long as you use the path directly provided by the endpoint, you shouldn't have any issues accessing the image file. Each one already comes prefixed with either `icon` and `image`, matching the directory structure of the assets folder.

- Icon: `icon/character/1001.png`
- Image: `image/character_portrait/1001.png`

Extension already included.

### Full URL

```
https://vizualabstract.github.io/StarRailResStaticAPI/assets/image/character_portrait/1001.png
```

### Example Images

- [icon/character/1001.png](https://vizualabstract.github.io/StarRailResStaticAPI/assets/icon/character/1001.png)
- [image/character_preview/1001.png](https://vizualabstract.github.io/StarRailResStaticAPI/assets/image/character_preview/1001.png)
- [image/character_portrait/1001.png](https://vizualabstract.github.io/StarRailResStaticAPI/assets/image/character_portrait/1001.png)

![](https://vizualabstract.github.io/StarRailResStaticAPI/assets/image/character_portrait/1001.png)

## Links

- StarRailRes: [Mar-7th/StarRailRes](https://github.com/Mar-7th/StarRailRes)
- Game data source: [Dimbreath/StarRailData](https://github.com/Dimbreath/StarRailData)
