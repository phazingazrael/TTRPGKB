---
Pronounced: "Federation of Pithudia"
Alias: "Federation of Pithudia"
NoteIcon: "Country"
Type: "Country"
Population: "134,620"
Theme: "Naval"
Kingdom: "Federation of Pithudia"
Terrain:
Defences: 
Rulers: 
Leaders: 
GovtType: "Federation (Republic)"
Religions:
Imports:
Exports:
creation_date: <%+ tp.file.creation_date("dddd Do MMMM YYYY HH:mm:ss") %> 
modification_date: <%+ tp.file.last_modified_date("dddd Do MMMM YYYY HH:mm:ss") %>
Rural: 110,127
Urban: 24,493
tags:
 - Location
 - Country
 - Pithudia
---

> [!infobox]+
> **Pronounced:**  "`=this.Pronounced`"
> ![[Federation of Pithudia.svg]]
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
> **City Name** | Allora | 🏰 | 
> **City Name** | Olori |  | 
> **City Name** | Kursk |  | 
> **City Name** | Lobyl |  | 
> **City Name** | Tororobo |  | 
> **City Name** | Bargos |  | 
> **City Name** | Testololye |  | 
> **City Name** | Pohogida |  | 
> **City Name** | Mezutsk |  | 
> **City Name** | Bratsk |  | 
> **City Name** | Orechevsk |  | 
> **City Name** | Rzhev |  | 
> **City Name** | Berechev |  | 
> **City Name** | Bererenets |  | 
> **City Name** | Mesch |  | 
> **City Name** | Rosla |  | 
> **City Name** | Smenicha |  | 
> **City Name** | Opylgogo |  | 
> **City Name** | Rechi |  | 
> 


## Districts


## History


## Notes
### Plot Hooks


### Hidden Details


### General Notes

