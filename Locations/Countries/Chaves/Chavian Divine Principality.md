---
Pronounced: Chavian Divine Principality
Alias: Chavian Divine Principality
NoteIcon: Country
Type: Country
Population: 833,883
Theme: Generic
Kingdom: Chavian Divine Principality
Terrain: null
Defences: null
Rulers: null
Leaders: null
GovtType: Divine Principality (Theocracy)
Religions:
  - "[Minetesmo Deities]"
Imports: null
Exports: null
creation_date: <%+ tp.file.creation_date("dddd Do MMMM YYYY HH:mm:ss") %>
modification_date: <%+ tp.file.last_modified_date("dddd Do MMMM YYYY HH:mm:ss") %>
Rural: 703,050
Urban: 130,833
tags:
  - Location
  - Country
  - Chaves
---

> [!infobox]+
> **Pronounced:**  "`=this.Pronounced`"
> ![[Chavian Divine Principality.svg]]
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
> **City Name** | Chadelazul | 🏰 | 
> **City Name** | Lagos |  | 
> **City Name** | Apinquerga |  | 
> **City Name** | Lourogavami |  | 
> **City Name** | Chares |  | 
> **City Name** | Maxias |  | 
> **City Name** | Cavavendaga |  | 
> **City Name** | Ponquerca |  | 
> **City Name** | Seixezamal |  | 
> **City Name** | Romarca |  | 
> **City Name** | Balhalhal |  | 
> **City Name** | Seigal |  | 
> **City Name** | Sagos |  | 
> **City Name** | Viala |  | 
> **City Name** | Douziarel |  | 
> **City Name** | Guirolis |  | 
> **City Name** | Campiradou |  | 
> **City Name** | Coimbrixopo |  | 
> **City Name** | Seimao |  | 
> **City Name** | Pedelo |  | 
> **City Name** | Pontenana |  | 
> **City Name** | Arviveitoli |  | 
> **City Name** | Alcoruchelo |  | 
> **City Name** | Chavo |  | 
> **City Name** | Pamporgabe |  | 
> **City Name** | Alveiranhal |  | 
> **City Name** | Casboa |  | 
> **City Name** | Retaguirao |  | 
> **City Name** | Conha |  | 
> **City Name** | Calegreta |  | 
> **City Name** | Aranquerti |  | 
> **City Name** | Sanholinde |  | 
> **City Name** | Sintralhand |  | 
> **City Name** | Raliro |  | 
> **City Name** | Vibeima |  | 
> **City Name** | Seinas |  | 
> **City Name** | Corilgueira |  | 
> **City Name** | Coentraburi |  | 
> **City Name** | Flosais |  | 
> **City Name** | Vacasboaran |  | 
> **City Name** | Douleixas |  | 
> **City Name** | Lompor |  | 
> **City Name** | Guibeigabu |  | 
> **City Name** | Vicao |  | 
> **City Name** | Carvelaxo |  | 
> **City Name** | Freira |  | 
> **City Name** | Fangaldoar |  | 
> **City Name** | Tranhaiace |  | 
> **City Name** | Leiras |  | 
> **City Name** | Peciveiros |  | 
> **City Name** | Ranilhao |  | 
> **City Name** | Formada |  | 
> **City Name** | Alheus |  | 
> **City Name** | Quarmalicei |  | 
> **City Name** | Gradoeirao |  | 
> **City Name** | Santalcanha |  | 
> **City Name** | Lirinha |  | 
> **City Name** | Telveiracol |  | 
> **City Name** | Silmivalha |  | 
> **City Name** | Avelo |  | 
> **City Name** | Sinco |  | 
> **City Name** | Felgurolis |  | 
> **City Name** | Lorvelacas |  | 
> **City Name** | Seixe |  | 
> **City Name** | Ficaodixoei |  | 
> **City Name** | Rimoso |  | 
> **City Name** | Sanhaoril |  | 
> **City Name** | Alelosoba |  | 
> **City Name** | Penichelo |  | 
> **City Name** | Macharetada |  | 
> **City Name** | Portado |  | 
> **City Name** | Baiaveixei |  | 
> **City Name** | Viagantei |  | 
> **City Name** | Fidel |  | 
> **City Name** | Grainhoei |  | 
> **City Name** | Olmiraorabe |  | 
> **City Name** | Santinxa |  | 
> **City Name** | Samintedin |  | 
> **City Name** | Quetacela |  | 
> **City Name** | Forta |  | 
> **City Name** | Cartadouei |  | 
> **City Name** | Leirastan |  | 
> **City Name** | Relas |  | 
> **City Name** | Carvebo |  | 
> **City Name** | Trolis |  | 
> **City Name** | Sobra |  | 
> **City Name** | Abrical |  | 
> **City Name** | Alhelasmo |  | 
> **City Name** | Coimbrabua |  | 
> **City Name** | Sagres |  | 
> **City Name** | Oqurinhadou |  | 
> **City Name** | Lombagoas |  | 
> 


## Districts


## History


## Notes
### Plot Hooks


### Hidden Details


### General Notes

