---
Pronounced: "Duchy of Garland"
Alias: "Duchy of Garland"
NoteIcon: "Country"
Type: "Country"
Population: "301,572"
Theme: "Naval"
Kingdom: "Duchy of Garland"
Terrain:
Defences: 
Rulers: 
Leaders: 
GovtType: "Duchy (Monarchy)"
Religions:
- [[Minetesmo Deities]]
- [[Iurorumian Circle]]
Imports:
Exports:
creation_date: <%+ tp.file.creation_date("dddd Do MMMM YYYY HH:mm:ss") %> 
modification_date: <%+ tp.file.last_modified_date("dddd Do MMMM YYYY HH:mm:ss") %>
Rural: 224,058
Urban: 77,514
tags:
 - Location
 - Country
 - Garland
---

> [!infobox]+
> **Pronounced:**  "`=this.Pronounced`"
> ![[Duchy of Garland.svg]]
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
> **City Name** | Lubkinobor | 🏰 | 
> **City Name** | Ostmyzhs |  | 
> **City Name** | Kopolch |  | 
> **City Name** | Korod |  | 
> **City Name** | Gorochukin |  | 
> **City Name** | Pemevan |  | 
> **City Name** | Voiversk |  | 
> **City Name** | Mstis |  | 
> **City Name** | Zhinyvan |  | 
> **City Name** | Vystonich |  | 
> **City Name** | Oryesk |  | 
> **City Name** | Beyanov |  | 
> **City Name** | Mstishin |  | 
> **City Name** | Orogodisch |  | 
> **City Name** | Yaraysk |  | 
> **City Name** | Dmitniasil |  | 
> **City Name** | Romny |  | 
> **City Name** | Glins |  | 
> **City Name** | Sneverech |  | 
> **City Name** | Luyatin |  | 
> **City Name** | Mstishere |  | 
> **City Name** | Lulatsk |  | 
> **City Name** | Luzborsk |  | 
> **City Name** | Chereniki |  | 
> **City Name** | Mglin |  | 
> **City Name** | Gokovgorod |  | 
> **City Name** | Luchin |  | 
> **City Name** | Trubc |  | 
> **City Name** | Kogorodno |  | 
> **City Name** | Ruteshvost |  | 
> **City Name** | Terezetsk |  | 
> **City Name** | Leretsk |  | 
> **City Name** | Votel |  | 
> **City Name** | Zizhok |  | 
> **City Name** | Merensk |  | 
> **City Name** | Midychelo |  | 
> **City Name** | Chelai |  | 
> **City Name** | Rshavin |  | 
> **City Name** | Duravets |  | 
> **City Name** | Bozhesk |  | 
> **City Name** | Temosh |  | 
> **City Name** | Lutsk |  | 
> **City Name** | Gomiy |  | 
> **City Name** | Mukilev |  | 
> **City Name** | Shilov |  | 
> **City Name** | Vilev |  | 
> **City Name** | Teskoedev |  | 
> **City Name** | Loshon |  | 
> **City Name** | Pronslavl |  | 
> **City Name** | Hotmyzhs |  | 
> **City Name** | Berevemil |  | 
> **City Name** | Rotel |  | 
> **City Name** | Trigovopos |  | 
> 


## Districts


## History


## Notes
### Plot Hooks


### Hidden Details


### General Notes

