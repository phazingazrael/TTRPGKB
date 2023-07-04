---
Pronounced: "Kovam Principality"
Alias: "Kovam Principality"
NoteIcon: "Country"
Type: "Country"
Population: "472,951"
Theme: "Naval"
Kingdom: "Kovam Principality"
Terrain:
Defences: 
Rulers: 
Leaders: 
GovtType: "Principality (Monarchy)"
Religions:
- [[Minetesmo Deities]]
- [[Turchian Deities]]
- [[Schism of the Three]]
Imports:
Exports:
creation_date: <%+ tp.file.creation_date("dddd Do MMMM YYYY HH:mm:ss") %> 
modification_date: <%+ tp.file.last_modified_date("dddd Do MMMM YYYY HH:mm:ss") %>
Rural: 383,869
Urban: 89,082
tags:
 - Location
 - Country
 - Kovamstan
---

> [!infobox]+
> **Pronounced:**  "`=this.Pronounced`"
> ![[Kovam Principality.svg]]
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
> **City Name** | Thessanama | 🏰 | 
> **City Name** | Vyatrov |  | 
> **City Name** | Theramos |  | 
> **City Name** | Taion |  | 
> **City Name** | Cythos |  | 
> **City Name** | Amphos |  | 
> **City Name** | Peraclea |  | 
> **City Name** | Ampha |  | 
> **City Name** | Akros |  | 
> **City Name** | Nexandros |  | 
> **City Name** | Nararatros |  | 
> **City Name** | Kysatis |  | 
> **City Name** | Teracrakou |  | 
> **City Name** | Scidnaion |  | 
> **City Name** | Myraiontira |  | 
> **City Name** | Ronia |  | 
> **City Name** | Byretospon |  | 
> **City Name** | Pithos |  | 
> **City Name** | Petapa |  | 
> **City Name** | Ricea |  | 
> **City Name** | Bydontinia |  | 
> **City Name** | Troniara |  | 
> **City Name** | Imbros |  | 
> **City Name** | Egeala |  | 
> **City Name** | Vemil |  | 
> **City Name** | Lutesk |  | 
> **City Name** | Chalesant |  | 
> **City Name** | Sypebai |  | 
> **City Name** | Vruch |  | 
> **City Name** | Harathumnos |  | 
> **City Name** | Thaphidna |  | 
> **City Name** | Pizizepha |  | 
> **City Name** | Magra |  | 
> **City Name** | Braukeracra |  | 
> **City Name** | Leinona |  | 
> **City Name** | Cronapolcis |  | 
> **City Name** | Pylalia |  | 
> **City Name** | Zakha |  | 
> **City Name** | Straion |  | 
> **City Name** | Rhamera |  | 
> **City Name** | Thastias |  | 
> **City Name** | Trida |  | 
> **City Name** | Sparmaselo |  | 
> **City Name** | Euros |  | 
> **City Name** | Nympsos |  | 
> **City Name** | Athon |  | 
> **City Name** | Pylaca |  | 
> **City Name** | Psychmolis |  | 
> **City Name** | Arnegaloti |  | 
> **City Name** | Hyera |  | 
> **City Name** | Paphara |  | 
> **City Name** | Muroreos |  | 
> **City Name** | Nelailo |  | 
> **City Name** | Athre |  | 
> **City Name** | Orchoreos |  | 
> **City Name** | Segidolis |  | 
> **City Name** | Methotipat |  | 
> **City Name** | Lektas |  | 
> **City Name** | Cysos |  | 
> **City Name** | Opemaion |  | 
> **City Name** | Euron |  | 
> **City Name** | Rhyzantido |  | 
> **City Name** | Nymphi |  | 
> **City Name** | Haion |  | 
> **City Name** | Orcholis |  | 
> **City Name** | Magnegica |  | 
> **City Name** | Pemeamos |  | 
> **City Name** | Kyrorintho |  | 
> **City Name** | Omebemeatos |  | 
> **City Name** | Zalydon |  | 
> **City Name** | Pytion |  | 
> 


## Districts


## History


## Notes
### Plot Hooks


### Hidden Details


### General Notes

