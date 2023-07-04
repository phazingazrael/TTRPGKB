---
Pronounced: "Menut Most Serene Republic"
Alias: "Menut Most Serene Republic"
NoteIcon: "Country"
Type: "Country"
Population: "847,664"
Theme: "Naval"
Kingdom: "Menut Most Serene Republic"
Terrain:
Defences: 
Rulers: 
Leaders: 
GovtType: "Most Serene Republic (Republic)"
Religions:
- [[Minetesmo Deities]]
Imports:
Exports:
creation_date: <%+ tp.file.creation_date("dddd Do MMMM YYYY HH:mm:ss") %> 
modification_date: <%+ tp.file.last_modified_date("dddd Do MMMM YYYY HH:mm:ss") %>
Rural: 704,490
Urban: 143,174
tags:
 - Location
 - Country
 - Menut
---

> [!infobox]+
> **Pronounced:**  "`=this.Pronounced`"
> ![[Menut Most Serene Republic.svg]]
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
> **City Name** | Paguilmo | 🏰 | 
> **City Name** | Pigoscosa |  | 
> **City Name** | Nobla |  | 
> **City Name** | Sytos |  | 
> **City Name** | Saudeca |  | 
> **City Name** | Ainon |  | 
> **City Name** | Hijos |  | 
> **City Name** | Megana |  | 
> **City Name** | Hesmossos |  | 
> **City Name** | Manes |  | 
> **City Name** | Orizizi |  | 
> **City Name** | Aldeca |  | 
> **City Name** | Urgaz |  | 
> **City Name** | Nobraquegas |  | 
> **City Name** | Umatillos |  | 
> **City Name** | Molea |  | 
> **City Name** | Estable |  | 
> **City Name** | Esplena |  | 
> **City Name** | Valla |  | 
> **City Name** | Burtuejas |  | 
> **City Name** | Skylcis |  | 
> **City Name** | Pesos |  | 
> **City Name** | Cornapon |  | 
> **City Name** | Fontequeda |  | 
> **City Name** | Tierninches |  | 
> **City Name** | Casterastil |  | 
> **City Name** | Areta |  | 
> **City Name** | Olluranillo |  | 
> **City Name** | Riofrio |  | 
> **City Name** | Carrevojo |  | 
> **City Name** | Citasenanil |  | 
> **City Name** | Talote |  | 
> **City Name** | Pocetecada |  | 
> **City Name** | Ugeca |  | 
> **City Name** | Laomega |  | 
> **City Name** | Zardos |  | 
> **City Name** | Aldecillo |  | 
> **City Name** | Tiergos |  | 
> **City Name** | Piniescana |  | 
> **City Name** | Estriena |  | 
> **City Name** | Drieguman |  | 
> **City Name** | Viagantes |  | 
> **City Name** | Artue |  | 
> **City Name** | Vallana |  | 
> **City Name** | Fuentando |  | 
> **City Name** | Lavas |  | 
> **City Name** | Lilco |  | 
> **City Name** | Pramurzona |  | 
> **City Name** | Almadra |  | 
> **City Name** | Pebestilca |  | 
> **City Name** | Torcos |  | 
> **City Name** | Orinthon |  | 
> **City Name** | Muroniacos |  | 
> **City Name** | Crolymnos |  | 
> **City Name** | Rhitros |  | 
> **City Name** | Gourma |  | 
> **City Name** | Phais |  | 
> **City Name** | Soniara |  | 
> **City Name** | Soporinthi |  | 
> **City Name** | Ruena |  | 
> **City Name** | Hurontella |  | 
> **City Name** | Monala |  | 
> **City Name** | Horges |  | 
> **City Name** | Sopesera |  | 
> **City Name** | Numabueras |  | 
> **City Name** | Dikon |  | 
> **City Name** | Suron |  | 
> **City Name** | Rolis |  | 
> **City Name** | Melioseicos |  | 
> **City Name** | Histhekion |  | 
> **City Name** | Honta |  | 
> **City Name** | Seranarme |  | 
> **City Name** | Torban |  | 
> **City Name** | Lekros |  | 
> **City Name** | Omanes |  | 
> **City Name** | Robledabue |  | 
> **City Name** | Poranquerin |  | 
> **City Name** | Escatanca |  | 
> **City Name** | Ocenta |  | 
> **City Name** | Noblant |  | 
> **City Name** | Byblos |  | 
> **City Name** | Trita |  | 
> **City Name** | Eurondos |  | 
> **City Name** | Almeguzon |  | 
> **City Name** | Sejos |  | 
> **City Name** | Sanzajofrin |  | 
> **City Name** | Cosoralota |  | 
> **City Name** | Mados |  | 
> **City Name** | Santa |  | 
> **City Name** | Gallanes |  | 
> **City Name** | Alzamur |  | 
> **City Name** | Gyrian |  | 
> **City Name** | Pyrgos |  | 
> **City Name** | Medrola |  | 
> **City Name** | Hedanconta |  | 
> **City Name** | Fuenta |  | 
> **City Name** | Puebles |  | 
> **City Name** | Calla |  | 
> **City Name** | Ontatilpita |  | 
> **City Name** | Ondina |  | 
> **City Name** | Herronsase |  | 
> **City Name** | Nobraga |  | 
> **City Name** | Phacamos |  | 
> 


## Districts


## History


## Notes
### Plot Hooks


### Hidden Details


### General Notes

