# StarRailResStaticAPI

Serving [StarRailRes](https://github.com/Mar-7th/StarRailRes) static JSON files.

## Overview

Endpoints are broken down into 3 main components: base, language, and endpoint.

```
https://{base}/{language}/{endpoint}.json
```

### URL

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

## Example Endpoints

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

I'm thinking about it.

## Links

- StarRailRes: [Mar-7th/StarRailRes](https://github.com/Mar-7th/StarRailRes)
- Game data source: [Dimbreath/StarRailData](https://github.com/Dimbreath/StarRailData)