---
Pronounced: "Grand Duchy of Tarda"
Alias: "Grand Duchy of Tarda"
NoteIcon: "Country"
Type: "Country"
Population: "239,985"
Theme: "River"
Kingdom: "Grand Duchy of Tarda"
Terrain:
Defences: 
Rulers: 
Leaders: 
GovtType: "Grand Duchy (Monarchy)"
Religions:
- [[Minetesmo Deities]]
Imports:
Exports:
creation_date: <%+ tp.file.creation_date("dddd Do MMMM YYYY HH:mm:ss") %> 
modification_date: <%+ tp.file.last_modified_date("dddd Do MMMM YYYY HH:mm:ss") %>
Rural: 199,953
Urban: 40,032
tags:
 - Location
 - Country
 - Tarda
---

> [!infobox]+
> **Pronounced:**  "`=this.Pronounced`"
> ![[Grand Duchy of Tarda.svg]]
> ###### Info
>  |
> ---|---|
> **Alias** | `=this.alias` |
> **Type** | `=this.type` |
> **Population** | `=this.population` |
> **Population: Rural** | `=this.Rural` |
> **Population: Urban** | `=this.Urban` |
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
TBD

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
WHERE Location = this.file.name AND contains(NoteIcon, "Character") AND !contains(Condition, "Dead")
SORT file.name ASC

## Cities

>  |
> ---|---|---|
> **City Name** | Shuryevya | 🏰 | 
> **City Name** | Ikubech |  | 
> **City Name** | Veteya |  | 
> **City Name** | Alsaz |  | 
> **City Name** | Orodnilov |  | 
> **City Name** | Sterzhyemi |  | 
> **City Name** | Vyslarorec |  | 
> **City Name** | Mezetsk |  | 
> **City Name** | Goposla |  | 
> **City Name** | Roblanona |  | 
> **City Name** | Promiyvan |  | 
> **City Name** | Gorochu |  | 
> **City Name** | Yaropolch |  | 
> **City Name** | Zverelecha |  | 
> **City Name** | Valmendral |  | 
> **City Name** | Yurov |  | 
> **City Name** | Rylsk |  | 
> **City Name** | Sernik |  | 
> **City Name** | Kavin |  | 
> **City Name** | Idychenets |  | 
> **City Name** | Svilov |  | 
> **City Name** | Mstishino |  | 
> **City Name** | Galforriola |  | 
> **City Name** | Glebolorod |  | 
> **City Name** | Bulatsk |  | 
> **City Name** | Vokov |  | 
> **City Name** | Desovgo |  | 
> **City Name** | Vruche |  | 
> **City Name** | Gororovsk |  | 
> **City Name** | Vereresk |  | 
> **City Name** | Drozelsk |  | 
> 


## Districts


## History


## Notes
### Plot Hooks


### Hidden Details


### General Notes

