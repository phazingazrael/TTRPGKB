---
Pronounced: "Topocan Kingdom"
Alias: "Topocan Kingdom"
NoteIcon: "Country"
Type: "Country"
Population: "368,266"
Theme: "Nomadic"
Kingdom: "Topocan Kingdom"
Terrain:
Defences: 
Rulers: 
Leaders: 
GovtType: "Kingdom (Monarchy)"
Religions:
- [[Minetesmo Deities]]
- [[Nagymamoszomian Cult]]
- [[Astellianism]]
Imports:
Exports:
creation_date: <%+ tp.file.creation_date("dddd Do MMMM YYYY HH:mm:ss") %> 
modification_date: <%+ tp.file.last_modified_date("dddd Do MMMM YYYY HH:mm:ss") %>
Rural: 305,318
Urban: 62,948
tags:
 - Location
 - Country
 - Topoco
---

> [!infobox]+
> **Pronounced:**  "`=this.Pronounced`"
> ![[Topocan Kingdom.svg]]
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
> **City Name** | Esmukkoria | 🏰 | 
> **City Name** | Piolttame |  | 
> **City Name** | Nildiski |  | 
> **City Name** | Porvo |  | 
> **City Name** | Lokia |  | 
> **City Name** | Elhobyloke |  | 
> **City Name** | Sakanta |  | 
> **City Name** | Tulpuren |  | 
> **City Name** | Sanhagoin |  | 
> **City Name** | Ridiro |  | 
> **City Name** | Ponho |  | 
> **City Name** | Funho |  | 
> **City Name** | Tavel |  | 
> **City Name** | Hahaiiolaki |  | 
> **City Name** | Arelpalcan |  | 
> **City Name** | Lahka |  | 
> **City Name** | Mepoy |  | 
> **City Name** | Merais |  | 
> **City Name** | Soulemaux |  | 
> **City Name** | Coully |  | 
> **City Name** | Vences |  | 
> **City Name** | Ropio |  | 
> **City Name** | Liepo |  | 
> **City Name** | Rotan |  | 
> **City Name** | Tuukka |  | 
> **City Name** | Alheiras |  | 
> **City Name** | Kilvakara |  | 
> **City Name** | Kasla |  | 
> **City Name** | Vildiski |  | 
> **City Name** | Eskog |  | 
> **City Name** | Rakkasenky |  | 
> **City Name** | Malma |  | 
> **City Name** | Yvaskogsund |  | 
> **City Name** | Puinay |  | 
> **City Name** | Vieilleroy |  | 
> **City Name** | Boigny |  | 
> **City Name** | Rakiviese |  | 
> **City Name** | Pupunta |  | 
> **City Name** | Tottalisuo |  | 
> **City Name** | Sila |  | 
> **City Name** | Jampaa |  | 
> **City Name** | Flecheima |  | 
> **City Name** | Turan |  | 
> **City Name** | Feins |  | 
> **City Name** | Kolvalanvaa |  | 
> **City Name** | Tuusjarja |  | 
> **City Name** | Pylahai |  | 
> **City Name** | Rezelamal |  | 
> **City Name** | Ylapirttala |  | 
> **City Name** | Ahjanie |  | 
> **City Name** | Valvaku |  | 
> **City Name** | Guille |  | 
> **City Name** | Liekka |  | 
> **City Name** | Kilmajo |  | 
> **City Name** | Anteau |  | 
> **City Name** | Kanasta |  | 
> **City Name** | Tiormu |  | 
> 


## Districts


## History


## Notes
### Plot Hooks


### Hidden Details


### General Notes

