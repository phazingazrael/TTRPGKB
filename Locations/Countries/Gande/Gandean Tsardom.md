---
Pronounced: "Gandean Tsardom"
Alias: "Gandean Tsardom"
NoteIcon: "Country"
Type: "Country"
Population: "1,076,086"
Theme: "Nomadic"
Kingdom: "Gandean Tsardom"
Terrain:
Defences: 
Rulers: 
Leaders: 
GovtType: "Tsardom (Monarchy)"
Religions:
- [[Minetesmo Deities]] 
- [[Turchian Deities]]
Imports:
Exports:
creation_date: <%+ tp.file.creation_date("dddd Do MMMM YYYY HH:mm:ss") %> 
modification_date: <%+ tp.file.last_modified_date("dddd Do MMMM YYYY HH:mm:ss") %>
Rural: 943,238
Urban: 132,848
tags:
 - Location
 - Country
 - Gande
---

> [!infobox]+
> **Pronounced:**  "`=this.Pronounced`"
> ![[Gandean Tsardom.svg]]
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
> **City Name** | Lurov | 🏰 | 
> **City Name** | Llan |  | 
> **City Name** | Gorovsk |  | 
> **City Name** | Themidea |  | 
> **City Name** | Dichi |  | 
> **City Name** | Lochilorha |  | 
> **City Name** | Svisvya |  | 
> **City Name** | Pomel |  | 
> **City Name** | Lolechevsk |  | 
> **City Name** | Avonning |  | 
> **City Name** | Aberlerefen |  | 
> **City Name** | Inve |  | 
> **City Name** | Inverkuaislo |  | 
> **City Name** | Modubkigov |  | 
> **City Name** | Abergeallan |  | 
> **City Name** | Rzhis |  | 
> **City Name** | Tuzasil |  | 
> **City Name** | Gozyr |  | 
> **City Name** | Smebovlnik |  | 
> **City Name** | Doresk |  | 
> **City Name** | Minsk |  | 
> **City Name** | Empianena |  | 
> **City Name** | Vemyshlno |  | 
> **City Name** | Mescht |  | 
> **City Name** | Zizmapech |  | 
> **City Name** | Deben |  | 
> **City Name** | Prolorodni |  | 
> **City Name** | Kursk |  | 
> **City Name** | Rodbesk |  | 
> **City Name** | Nerov |  | 
> **City Name** | Kurskiv |  | 
> **City Name** | Chernase |  | 
> **City Name** | Cherdedin |  | 
> **City Name** | Slorod |  | 
> **City Name** | Avonvegyn |  | 
> **City Name** | Beiganthing |  | 
> **City Name** | Sendiryart |  | 
> **City Name** | Insere |  | 
> **City Name** | Dvererez |  | 
> **City Name** | Cherni |  | 
> **City Name** | Teshesk |  | 
> **City Name** | Staroditin |  | 
> **City Name** | Plesk |  | 
> **City Name** | Golec |  | 
> **City Name** | Nabelta |  | 
> **City Name** | Infarthin |  | 
> **City Name** | Trimerlen |  | 
> **City Name** | Gosalsk |  | 
> **City Name** | Alaw |  | 
> **City Name** | Fhlai |  | 
> **City Name** | Moschersk |  | 
> **City Name** | Veremyshl |  | 
> **City Name** | Shiloshek |  | 
> **City Name** | Torzhok |  | 
> **City Name** | Goboresk |  | 
> **City Name** | Abergow |  | 
> **City Name** | Aber |  | 
> **City Name** | Durie |  | 
> **City Name** | Druts |  | 
> **City Name** | Golotsk |  | 
> **City Name** | Sizidamega |  | 
> **City Name** | Tedev |  | 
> **City Name** | Sitin |  | 
> **City Name** | Kirk |  | 
> **City Name** | Abertaber |  | 
> **City Name** | Aberkeita |  | 
> **City Name** | Aber |  | 
> **City Name** | Pinsk |  | 
> **City Name** | Kornitvert |  | 
> **City Name** | Bogodub |  | 
> **City Name** | Torzhets |  | 
> **City Name** | Chernobesk |  | 
> **City Name** | Vruchilosk |  | 
> **City Name** | Naber |  | 
> **City Name** | Invewedhek |  | 
> **City Name** | Voreloga |  | 
> **City Name** | Opolec |  | 
> **City Name** | Sinia |  | 
> **City Name** | Asktos |  | 
> **City Name** | Nicha |  | 
> **City Name** | Gogilologa |  | 
> **City Name** | Lubkin |  | 
> **City Name** | Snovshev |  | 
> **City Name** | Dmitlitsk |  | 
> **City Name** | Eurionti |  | 
> **City Name** | Kukoml |  | 
> **City Name** | Prokodok |  | 
> **City Name** | Dubech |  | 
> **City Name** | Novensk |  | 
> **City Name** | Dutivl |  | 
> **City Name** | Betebovlgo |  | 
> **City Name** | Minonok |  | 
> **City Name** | Migozyrval |  | 
> **City Name** | Aberviewed |  | 
> **City Name** | Boslynhafraw |  | 
> **City Name** | Izborsk |  | 
> **City Name** | Dveres |  | 
> 


## Districts


## History


## Notes
### Plot Hooks


### Hidden Details


### General Notes

