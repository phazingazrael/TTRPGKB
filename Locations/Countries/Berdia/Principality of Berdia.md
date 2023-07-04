---
Pronounced: "Principality of Berdia"
Alias: "Principality of Berdia"
NoteIcon: "Country"
Type: "Country"
Population: "496,191"
Theme: "Generic"
Kingdom: "Principality of Berdia"
Terrain:
Defences: 
Rulers: 
Leaders: 
GovtType: "Principality (Monarchy)"
Religions:
- [[Minetesmo Deities]]
Imports:
Exports:
creation_date: <%+ tp.file.creation_date("dddd Do MMMM YYYY HH:mm:ss") %> 
modification_date: <%+ tp.file.last_modified_date("dddd Do MMMM YYYY HH:mm:ss") %>
Rural: 386,019
Urban: 110,172
tags:
 - Location
 - Country
 - Berdia
---

> [!infobox]+
> **Pronounced:**  "`=this.Pronounced`"
> ![[Principality of Berdia.svg]]
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
> 
> **City Name** | Bopeia | 🏰 | 
> 
> **City Name** | Pithe |  | 
> 
> **City Name** | Thyros |  | 
> 
> **City Name** | Ampomiscu |  | 
> 
> **City Name** | Sicargiphid |  | 
> 
> **City Name** | Vatrea |  | 
> 
> **City Name** | Opozotipo |  | 
> 
> **City Name** | Goles |  | 
> 
> **City Name** | Braupaktos |  | 
> 
> **City Name** | Kyrelea |  | 
> 
> **City Name** | Eniagidamai |  | 
> 
> **City Name** | Gorgan |  | 
> 
> **City Name** | Histrea |  | 
> 
> **City Name** | Akleleamai |  | 
> 
> **City Name** | Delphaguri |  | 
> 
> **City Name** | Tholis |  | 
> 
> **City Name** | Rhamna |  | 
> 
> **City Name** | Smyrcyrekus |  | 
> 
> **City Name** | Enamos |  | 
> 
> **City Name** | Lintion |  | 
> 
> **City Name** | Zaraion |  | 
> 
> **City Name** | Hubla |  | 
> 
> **City Name** | Tyreumpo |  | 
> 
> **City Name** | Ablos |  | 
> 
> **City Name** | Stympha |  | 
> 
> **City Name** | Papha |  | 
> 
> **City Name** | Aicearat |  | 
> 
> **City Name** | Orina |  | 
> 
> **City Name** | Bhryrelea |  | 
> 
> **City Name** | Hyeleos |  | 
> 
> **City Name** | Onale |  | 
> 
> **City Name** | Rhithumna |  | 
> 
> **City Name** | Trolixt |  | 
> 
> **City Name** | Ninia |  | 
> 
> **City Name** | Pepoidea |  | 
> 
> **City Name** | Euroskan |  | 
> 
> **City Name** | Amphidna |  | 
> 
> **City Name** | Parnenena |  | 
> 
> **City Name** | Amphinontos |  | 
> 
> **City Name** | Kydontos |  | 
> 
> **City Name** | Zakroicea |  | 
> 
> **City Name** | Haris |  | 
> 
> **City Name** | Theolyme |  | 
> 
> **City Name** | Helion |  | 
> 
> **City Name** | Akroicos |  | 
> 
> **City Name** | Byreumnos |  | 
> 
> **City Name** | Chales |  | 
> 
> **City Name** | Phaponialia |  | 
> 
> **City Name** | Pyrma |  | 
> 
> **City Name** | Rhamnos |  | 
> 
> **City Name** | Orchopos |  | 
> 
> **City Name** | Gourgipsa |  | 
> 
> **City Name** | Aberl |  | 
> 
> **City Name** | Chios |  | 
> 
> **City Name** | Micyon |  | 
> 
> **City Name** | Pydria |  | 
> 
> **City Name** | Oncheleossa |  | 
> 
> **City Name** | Nymphidna |  | 
> 
> **City Name** | Naupha |  | 
> 
> **City Name** | Aphyrenes |  | 
> 
> **City Name** | Hyelos |  | 
> 
> **City Name** | Vathos |  | 
> 
> **City Name** | Siniamea |  | 
> 
> **City Name** | Pyrgamissos |  | 
> 
> **City Name** | Iolalaion |  | 
> 
> **City Name** | Lekroidea |  | 
> 
> **City Name** | Zakrorion |  | 
> 
> **City Name** | Myrtyndos |  | 
> 
> **City Name** | Amplios |  | 
> 
> **City Name** | Laopos |  | 
> 
> **City Name** | Mormenaida |  | 
> 
> **City Name** | Nileapo |  | 
> 


## Districts


## History


## Notes
### Plot Hooks


### Hidden Details


### General Notes

