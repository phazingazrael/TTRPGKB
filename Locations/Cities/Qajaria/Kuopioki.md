---
Pronounced: "Kuopioki"
Alias: "Kuopioki"
NoteIcon: "City - Small Town"
Type: "City - Small Town"
Population: 479
Theme: Hunting
Kingdom: United Provinces of Qajaria
Terrain:
Defences: 
Rulers: 
Leaders: 
GovtType: "United Provinces (Union)"
Religions:
Imports:
Exports:
creation_date: <%+ tp.file.creation_date("dddd Do MMMM YYYY HH:mm:ss") %> 
modification_date: <%+ tp.file.last_modified_date("dddd Do MMMM YYYY HH:mm:ss") %>
Country: Qajaria
capitalCity: CapitalCity
Features:
 - Citadel
 - Plaza
 - Walls
tags:
 - Location
 - City - Small Town
 - Kuopioki
 - Capital
 - Citadel
 - Plaza
 - Walls
---

> [!infobox]+
> **Pronounced:**  "`=this.Pronounced`"
> ![[Kuopioki.svg]]
> ###### Info
>  |
> ---|---|
> **Alias** | `=this.alias` |
> **Type** | `=this.type` |
> **Population** | `=this.population` |
> **Theme** | `=this.theme` |
> **Kingdom** | `=link(this.Kingdom)` |
> **Terrain** | `=this.terrain` |
> ###### Politics
>  |
> ---|---|
> **Ruler(s)** | `=this.Rulers` |
> **Leaders** | `=this.Leaders` |
> **Govt Type** | `=this.GovtType` |
> **Defenses** | `=this.defences` |
> **Religion(s)** | `=link(this.religions)` |
> ###### Commerce
>  |
> ---|---|
> **Imports** | `=this.imports` |
> **Exports** | `=this.exports` |
> ###### Groups
>  |
> ---|
[[🔰 Group Database]]
> ```dataview 
table join(Type, ", ") AS Type
WHERE econtains(Location, this.file.name) AND contains(NoteIcon, "Group")
SORT Type ASC

> [!infobox|left]- 
> ![[Placeholderimage.png]]
> **Description:** 

# **`=this.file.name`**
> [!recite]- Introduction 
> Kuopioki, the capital city of [[United Provinces of Qajaria|Qajaria]], stands as a testament to the resilience and adaptability of the survivors in the post-apocalyptic world of Eatheria. Nestled within the hollowed-out ruins, sewers, and subway tunnels of a once bustling metropolis, Kuopioki has become a beacon of hope and community amidst the desolation.
> ### Location and Setting: 
> Located in the heart of Qajaria, Kuopioki benefits from its strategic positioning, offering both defensive advantages and access to vital resources. The city is surrounded by the remnants of a once-thriving urban landscape, with towering skyscrapers and crumbling infrastructure serving as a reminder of the pre-war era. The twisted remnants of highways and overpasses connect the various districts, providing a labyrinthine network that has become the lifeblood of the city.
> ### Population and Diversity: 
> Kuopioki is home to a diverse population comprising survivors from various backgrounds and races. Humans, dwarves, elves, orcs, and hybrid beings have come together, finding refuge within the city's fortified walls. The mixing of cultures, traditions, and beliefs has created a rich tapestry of diversity within the city, with different races contributing their unique perspectives and skills to the community.
> ### Community Structure and Governance: 
> Unlike traditional governance systems, Kuopioki operates under a unique model where the city is managed and run by a collective group known as the [[Iron Wardens]]. This decentralized leadership structure ensures that power is shared among the guards, who are chosen from the community and tasked with the responsibility of safeguarding the city and its inhabitants.
> ### Trade and Economy: 
> Kuopioki thrives on a bustling trade network, as it serves as a major hub for commerce and barter between the various factions and settlements in the region. The city's strategic location, combined with its access to trade routes and resources, has allowed it to flourish as a center of economic activity. Traders, merchants, and craftsmen ply their wares in the city's bustling marketplaces, exchanging goods and services to meet the diverse needs of the population.
> ### Infrastructure and Architecture: 
> The unique nature of Kuopioki's location within the ruins has shaped its infrastructure and architecture. The city utilizes the existing structures of the pre-war era, repurposing them to suit the needs of the inhabitants. Makeshift dwellings, built within the nooks and crannies of the ruins, coexist with refurbished buildings, creating a visually striking blend of old and new. The city's underground tunnels and sewers have been repurposed as vital passageways, connecting different districts and serving as hidden havens for the residents.
> ### Culture and Lifestyle: 
> The people of Kuopioki have developed a resilient and resourceful lifestyle in the face of adversity. They have adapted to the challenges of the post-apocalyptic world, embracing a culture of camaraderie, self-sufficiency, and innovation. Art, music, and storytelling thrive within the city, providing an outlet for creativity and a source of inspiration for its residents.
> ### Challenges and Threats: 
> Despite its resilience, Kuopioki faces numerous challenges and threats. The remnants of pre-war technology and the constant struggle for resources within the post-apocalyptic world can lead to conflicts and power struggles. The city's unique location also makes it a target for hostile factions seeking to exploit its resources or establish dominance. The [[Iron Wardens]]  plays a crucial role in defending Kuopioki against external threats and maintaining order within its walls.
> 
> Kuopioki stands as a symbol of hope and unity, a place where survivors have come together to rebuild and forge a new future. In this post-apocalyptic world, the city remains a beacon of civilization, offering safety, trade, and a sense of community to those who call it home.

> [!metadata|map]- Map
> ```leaflet
> id: TBD
> image: [[Eatheria_Map.svg]]
> height: 550px
> width: 550px
> lat: 50
> long: 50
> minZoom: 1
> maxZoom: 5
> defaultZoom: 1
> unit: meters
> scale: 1
> darkMode: false
> ```

> [!metadata|shops]- Shops
> [[💲 Shop & Service Database|📝Add New Shop/Service]]
> ```dataview
table join(Type, ", ") AS Type, join(link(AffiliatedGroup), ", ") AS "Group(s)"
WHERE Location = this.file.name AND contains(NoteIcon, "Shop")
SORT file.name ASC

> [!metadata|pois]- Points of Interest
> [[❓ POI Database|📝Add New Point of Interest]]
> ```dataview
table join(Type, ", ") AS Type, join(link(AffiliatedGroup), ", ") AS "Group(s)"
WHERE Location = this.file.name AND contains(NoteIcon, "POI")
SORT file.name ASC

> [!metadata|npcs]- NPCs
> [[👨‍👩‍👧‍👦 NPC Database| 📝Add New NPC]]
> ```dataview
table Pronouns, Party1Standing AS "Motley Few Standing", join(Occupation, ", ") AS "Occupation(s)", join(link(AssociatedGroup), ", ") AS "Group(s)", join(link(AssociatedReligion), ", ") AS "Religion(s)"
WHERE Location = this.file.name AND contains(NoteIcon, "NPC") AND !contains(Condition, "Dead")
SORT file.name ASC

## Districts


## History


## Notes
### Plot Hooks


### Hidden Details


### General Notes

