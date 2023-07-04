---
Pronounced: "United Provinces of Qajaria"
Alias: "United Provinces of Qajaria"
NoteIcon: "Country"
Type: "Country"
Population: "971,272"
Theme: "Naval"
Kingdom: "United Provinces of Qajaria"
Terrain:
Defences: 
Rulers: 
Leaders: 
GovtType: "United Provinces (Union)"
Religions:
- [[Nagymamoszomian Cult]] 
- [[Norse Ancestors]]
- [[Vengrian Forefathers]]
- [[Iconoclasm of the Disturbing Guardian]]
Imports:
Exports:
creation_date: <%+ tp.file.creation_date("dddd Do MMMM YYYY HH:mm:ss") %> 
modification_date: <%+ tp.file.last_modified_date("dddd Do MMMM YYYY HH:mm:ss") %>
Rural: 790,607
Urban: 180,665
tags:
 - Location
 - Country
 - Qajaria
---

> [!infobox]+
> **Pronounced:**  "`=this.Pronounced`"
> ![[United Provinces of Qajaria.svg]]
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

  |
---|---|---|
**City Name** | Kuopioki | 🏰 |
**City Name** | Tuukve |  | 
**City Name** | Nikkapirttu |  | 
**City Name** | Visis |  | 
**City Name** | Cherin |  | 
**City Name** | Thiviers |  | 
**City Name** | Sigran |  | 
**City Name** | Hyvina |  | 
**City Name** | Klauksa |  | 
**City Name** | Liekvemi |  | 
**City Name** | Bjorvi |  | 
**City Name** | Djufargar |  | 
**City Name** | Muurikmori |  | 
**City Name** | Neulonvilly |  | 
**City Name** | Ormshamber |  | 
**City Name** | Piekmotanki |  | 
**City Name** | Lokmokioi |  | 
**City Name** | Soulise |  | 
**City Name** | Chatilles |  | 
**City Name** | Lajarhokia |  | 
**City Name** | Onstad |  | 
**City Name** | Djugager |  | 
**City Name** | Briatelleurs |  | 
**City Name** | Sompaa |  | 
**City Name** | Rozoy |  | 
**City Name** | Rakka |  | 
**City Name** | Menevik |  | 
**City Name** | Kehja |  | 
**City Name** | Bentama |  | 
**City Name** | Huitti |  | 
**City Name** | Bauvy |  | 
**City Name** | Sundyrdur |  | 
**City Name** | Helmendoya |  | 
**City Name** | Vampssas |  | 
**City Name** | Huistouy |  | 
**City Name** | Uttavepaa |  | 
**City Name** | Kunisanepo |  | 
**City Name** | Parai |  | 
**City Name** | Dunsmoutham |  | 
**City Name** | Bonte |  | 
**City Name** | Penksey |  | 
**City Name** | Raupun |  | 
**City Name** | Paarai |  | 
**City Name** | Dalboliton |  | 
**City Name** | Jarceville |  | 
**City Name** | Kuhlaivies |  | 
**City Name** | Bevandillevoy |  | 
**City Name** | Orandre |  | 
**City Name** | Kaulasesima |  | 
**City Name** | Vilpsa |  | 
**City Name** | Valga |  | 
**City Name** | Nilvivijapa |  | 
**City Name** | Villiers |  | 
**City Name** | Litla |  | 
**City Name** | Latille |  | 
**City Name** | Pertti |  | 
**City Name** | Aucourtevil |  | 
**City Name** | Chevraimouy |  | 
**City Name** | Felvik |  | 
**City Name** | Laula |  | 
**City Name** | Ellisbak |  | 
**City Name** | Harvijarvi |  | 
**City Name** | Heikylapa |  | 
**City Name** | Reykseynes |  | 
**City Name** | Syrve |  | 
**City Name** | Charce |  | 
**City Name** | Laisa |  | 
**City Name** | Shifton |  | 
**City Name** | Burmouth |  | 
**City Name** | Kylosaajo |  | 
**City Name** | Eresseaux |  | 
**City Name** | Brotierreau |  | 
**City Name** | Rozotska |  | 
**City Name** | Yvasajola |  | 
**City Name** | Benkama |  | 
**City Name** | Klovspovii |  | 
**City Name** | Morgis |  | 
**City Name** | Junnesvog |  | 
**City Name** | Channes |  | 
**City Name** | Rouvrery |  | 
**City Name** | Grepoy |  | 
**City Name** | Hogarten |  | 
**City Name** | Puinouve |  | 
**City Name** | Vehtikyla |  | 
**City Name** | Pohti |  | 
**City Name** | Meungnes |  | 
**City Name** | Aasaredakka |  | 
**City Name** | Monthinete |  | 
**City Name** | Briarieuilles |  | 
**City Name** | Croteres |  | 
**City Name** | Brerevillevil |  | 
**City Name** | Turenjo |  | 
**City Name** | Lohtiio |  | 
**City Name** | Desherce |  | 
**City Name** | Ogstad |  | 
**City Name** | Jamsa |  | 
**City Name** | Rakimatti |  | 
**City Name** | Vienvilleaux |  | 
**City Name** | Oisonnetevil |  | 
**City Name** | Kasvaanijar |  | 
**City Name** | Solles |  | 
**City Name** | Humenmoen |  | 
**City Name** | Vrigny |  | 
**City Name** | Kaula |  | 
**City Name** | Jiori |  | 
**City Name** | Leaux |  | 
**City Name** | Montes |  | 
**City Name** | Kausu |  | 
**City Name** | Oittinijar |  | 
**City Name** | Siglain |  | 
**City Name** | Viohja |  | 
**City Name** | Hovira |  | 
**City Name** | Austrandra |  | 
**City Name** | Aschevoy |  | 
**City Name** | Jouernoicy |  | 
**City Name** | Leighton |  | 
**City Name** | Lemsa |  | 
**City Name** | Lautio |  | 
**City Name** | Greres |  | 
**City Name** | Kaski |  | 
**City Name** | Bosting |  | 
**City Name** | Falescoux |  | 
**City Name** | Cheres |  | 
**City Name** | Parvi |  | 
**City Name** | Fjellvikho |  | 
**City Name** | Ralankalala |  | 
**City Name** | Tuuskuepaa |  | 
**City Name** | Koksylota |  | 
**City Name** | Oittumaja |  | 
**City Name** | Joenpaari |  | 
**City Name** | Marde |  | 
**City Name** | Kinentavala |  | 
**City Name** | Mamoutardon |  | 
**City Name** | Aschevillevan |  | 
**City Name** | Grigy |  | 
**City Name** | Cournoinaynes |  | 
**City Name** | Kusumava |  | 
**City Name** | Nines |  | 
**City Name** | Harvimio |  | 
**City Name** | Berham |  | 
**City Name** | Brory |  | 
**City Name** | Tulpio |  | 
**City Name** | Stordi |  | 
**City Name** | Bacray |  | 
**City Name** | Sanneaulivet |  | 
**City Name** | Lohlai |  | 
> 


## Districts


## History


## Notes
### Plot Hooks


### Hidden Details


### General Notes

