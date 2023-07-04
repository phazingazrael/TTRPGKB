---

database-plugin: basic

---

```yaml:dbfolder
name: new database
description: new description
columns:
  __file__:
    key: __file__
    id: __file__
    input: markdown
    label: File
    accessorKey: __file__
    isMetadata: true
    skipPersist: false
    isDragDisabled: false
    csvCandidate: true
    accessor: __file__
    position: 1
    isHidden: false
    sortIndex: -1
    width: 219
    isSorted: false
    isSortedDesc: false
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: true
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      source_data: current_folder
  __created__:
    key: __created__
    id: __created__
    input: calendar_time
    label: Created
    accessorKey: __created__
    isMetadata: true
    isDragDisabled: false
    skipPersist: false
    csvCandidate: true
    accessor: __created__
    position: 17
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      source_data: current_folder
  __modified__:
    key: __modified__
    id: __modified__
    input: calendar_time
    label: Modified
    accessorKey: __modified__
    isMetadata: true
    isDragDisabled: false
    skipPersist: false
    csvCandidate: true
    accessor: __modified__
    position: 18
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      source_data: current_folder
  NoteIcon:
    input: select
    accessor: NoteIcon
    key: NoteIcon
    label: NoteIcon
    position: 4
    skipPersist: false
    accessorKey: NoteIcon
    isHidden: false
    sortIndex: -1
    width: 168
    isSorted: false
    isSortedDesc: false
    options:
      - { label: "POI", value: "POI", color: "undefined"}
      - { label: "Shop", value: "Shop", color: "undefined"}
      - { label: "City - Small Town", value: "City - Small Town", color: "hsl(155, 95%, 90%)"}
      - { label: "City - Large Town", value: "City - Large Town", color: "hsl(82, 95%, 90%)"}
      - { label: "Country", value: "Country", color: "hsl(257, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      source_data: current_folder
      option_source: manual
  Alias:
    input: text
    accessor: Alias
    key: Alias
    label: Alias
    position: 3
    skipPersist: false
    accessorKey: Alias
    isHidden: false
    sortIndex: -1
    width: 173
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      source_data: current_folder
  Type:
    input: select
    accessor: Type
    key: Type
    label: Type
    position: 5
    skipPersist: false
    accessorKey: Type
    isHidden: false
    sortIndex: -1
    width: 266
    options:
      - { label: "Thorp", value: "Thorp", color: "hsl(259, 95%, 90%)"}
      - { label: "Hamlet", value: "Hamlet", color: "hsl(168, 95%, 90%)"}
      - { label: "Village", value: "Village", color: "hsl(207, 95%, 90%)"}
      - { label: "Small Town", value: "Small Town", color: "hsl(301, 95%, 90%)"}
      - { label: "Large Town", value: "Large Town", color: "hsl(306, 95%, 90%)"}
      - { label: "Small City", value: "Small City", color: "hsl(324, 95%, 90%)"}
      - { label: "Large City", value: "Large City", color: "hsl(162, 95%, 90%)"}
      - { label: "Metropolis", value: "Metropolis", color: "hsl(344, 95%, 90%)"}
      - { label: "City - Small Town", value: "City - Small Town", color: "hsl(61, 95%, 90%)"}
      - { label: "City - Large Town", value: "City - Large Town", color: "hsl(212, 95%, 90%)"}
      - { label: "Country", value: "Country", color: "hsl(190, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      source_data: current_folder
  Defences:
    input: select
    accessor: Defences
    key: Defences
    label: Defences
    position: 10
    skipPersist: false
    accessorKey: Defences
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Formidable", value: "Formidable", color: "hsl(239, 95%, 90%)"}
      - { label: "Strong", value: "Strong", color: "hsl(293, 95%, 90%)"}
      - { label: "Average", value: "Average", color: "hsl(161, 95%, 90%)"}
      - { label: "Weak", value: "Weak", color: "hsl(274, 95%, 90%)"}
      - { label: "Patheric", value: "Patheric", color: "hsl(342, 95%, 90%)"}
      - { label: "None", value: "None", color: "hsl(217, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      source_data: current_folder
  GovtType:
    input: select
    accessor: GovtType
    key: GovtType
    label: GovtType
    position: 13
    skipPersist: false
    accessorKey: GovtType
    isHidden: false
    sortIndex: -1
    width: 193
    options:
      - { label: "United Provinces (Union)", value: "United Provinces (Union)", color: "hsl(40, 95%, 90%)"}
      - { label: "Tsardom (Monarchy)", value: "Tsardom (Monarchy)", color: "hsl(359, 95%, 90%)"}
      - { label: "Principality (Monarchy)", value: "Principality (Monarchy)", color: "hsl(43, 95%, 90%)"}
      - { label: "Grand Duchy (Monarchy)", value: "Grand Duchy (Monarchy)", color: "hsl(2, 95%, 90%)"}
      - { label: "Divine Principality (Theocracy)", value: "Divine Principality (Theocracy)", color: "hsl(166, 95%, 90%)"}
      - { label: "Kingdom (Monarchy)", value: "Kingdom (Monarchy)", color: "hsl(72, 95%, 90%)"}
      - { label: "Most Serene Republic (Republic)", value: "Most Serene Republic (Republic)", color: "hsl(135, 95%, 90%)"}
      - { label: "Federation (Republic)", value: "Federation (Republic)", color: "hsl(88, 95%, 90%)"}
      - { label: "Duchy (Monarchy)", value: "Duchy (Monarchy)", color: "hsl(78, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      source_data: current_folder
  Pronounced:
    input: text
    accessor: Pronounced
    key: Pronounced
    label: Pronounced
    position: 2
    skipPersist: false
    accessorKey: Pronounced
    isHidden: false
    sortIndex: -1
    width: 141
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      source_data: current_folder
  Religions:
    input: tags
    accessorKey: Religions
    key: Religions
    id: Religions
    label: Religions
    position: 14
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 462
    options:
      - { label: "Minetesmo Deities", value: "Minetesmo Deities", color: "hsl(159, 95%, 90%)"}
      - { label: "Iurorumian Circle", value: "Iurorumian Circle", color: "hsl(91, 95%, 90%)"}
      - { label: "Turchian Deities", value: "Turchian Deities", color: "hsl(37, 95%, 90%)"}
      - { label: "Nagymamoszomian Cult", value: "Nagymamoszomian Cult", color: "hsl(304, 95%, 90%)"}
      - { label: "Norse Ancestors", value: "Norse Ancestors", color: "hsl(165, 95%, 90%)"}
      - { label: "[Minetesmo Deities]", value: "[Minetesmo Deities]", color: "hsl(297, 95%, 90%)"}
      - { label: "[Iurorumian Circle]", value: "[Iurorumian Circle]", color: "hsl(227, 95%, 90%)"}
      - { label: "[Turchian Deities]", value: "[Turchian Deities]", color: "hsl(58, 95%, 90%)"}
      - { label: "[Schism of the Three]", value: "[Schism of the Three]", color: "hsl(213, 95%, 90%)"}
      - { label: "[Nagymamoszomian Cult]", value: "[Nagymamoszomian Cult]", color: "hsl(302, 95%, 90%)"}
      - { label: "[Astellianism]", value: "[Astellianism]", color: "hsl(332, 95%, 90%)"}
      - { label: "[Norse Ancestors]", value: "[Norse Ancestors]", color: "hsl(256, 95%, 90%)"}
      - { label: "[Vengrian Forefathers]", value: "[Vengrian Forefathers]", color: "hsl(270, 95%, 90%)"}
      - { label: "[Iconoclasm of the Disturbing Guardian]", value: "[Iconoclasm of the Disturbing Guardian]", color: "hsl(146, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      option_source: manual
      wrap_content: true
  Population:
    input: text
    accessorKey: Population
    key: Population
    id: Population
    label: Population
    position: 6
    skipPersist: false
    isHidden: false
    sortIndex: -1
    isSorted: false
    isSortedDesc: true
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Imports:
    input: tags
    accessorKey: Imports
    key: Imports
    id: Imports
    label: Imports
    position: 15
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Lumber", value: "Lumber", color: "hsl(164, 95%, 90%)"}
      - { label: "Grain", value: "Grain", color: "hsl(96, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Exports:
    input: tags
    accessorKey: Exports
    key: Exports
    id: Exports
    label: Exports
    position: 16
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Lumber", value: "Lumber", color: "hsl(112, 95%, 90%)"}
      - { label: "Grain", value: "Grain", color: "hsl(78, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Theme:
    input: tags
    accessorKey: Theme
    key: Theme
    id: Theme
    label: Theme
    position: 7
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Gothic", value: "Gothic", color: "hsl(186, 95%, 90%)"}
      - { label: "Victorian", value: "Victorian", color: "hsl(218, 95%, 90%)"}
      - { label: "Medieval", value: "Medieval", color: "hsl(319, 95%, 90%)"}
      - { label: "Generic", value: "Generic", color: "hsl(200, 95%, 90%)"}
      - { label: "Naval", value: "Naval", color: "hsl(148, 95%, 90%)"}
      - { label: "Hunting", value: "Hunting", color: "hsl(324, 95%, 90%)"}
      - { label: "Nomadic", value: "Nomadic", color: "hsl(111, 95%, 90%)"}
      - { label: "River", value: "River", color: "hsl(340, 95%, 90%)"}
      - { label: "Highland", value: "Highland", color: "hsl(194, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Rulers:
    input: text
    accessorKey: Rulers
    key: Rulers
    id: Rulers
    label: Rulers
    position: 11
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 129
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Leaders:
    input: text
    accessorKey: Leaders
    key: Leaders
    id: Leaders
    label: Leaders
    position: 12
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 140
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Kingdom:
    input: select
    accessor: Region
    key: Kingdom
    label: Kingdom
    position: 8
    skipPersist: false
    accessorKey: Kingdom
    isHidden: false
    sortIndex: -1
    width: 319
    isSorted: false
    isSortedDesc: false
    options:
      - { label: "asdf", value: "asdf", color: "hsl(207, 95%, 90%)"}
      - { label: "Principality of Berdia", value: "Principality of Berdia", color: "hsl(114, 95%, 90%)"}
      - { label: "Gandean Tsardom", value: "Gandean Tsardom", color: "hsl(56, 95%, 90%)"}
      - { label: "Chavian Divine Principality", value: "Chavian Divine Principality", color: "hsl(8, 95%, 90%)"}
      - { label: "United Provinces of Qajaria", value: "United Provinces of Qajaria", color: "hsl(53, 95%, 90%)"}
      - { label: "Topocan Kingdom", value: "Topocan Kingdom", color: "hsl(329, 95%, 90%)"}
      - { label: "Federation of Pithudia", value: "Federation of Pithudia", color: "hsl(162, 95%, 90%)"}
      - { label: "Grand Duchy of Tarda", value: "Grand Duchy of Tarda", color: "hsl(108, 95%, 90%)"}
      - { label: "Duchy of Garland", value: "Duchy of Garland", color: "hsl(356, 95%, 90%)"}
      - { label: "Kovam Principality", value: "Kovam Principality", color: "hsl(297, 95%, 90%)"}
      - { label: "Menut Most Serene Republic", value: "Menut Most Serene Republic", color: "hsl(243, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      source_data: current_folder
      option_source: manual
  Terrain:
    input: tags
    accessorKey: Terrain
    key: Terrain
    id: Terrain
    label: Terrain
    position: 9
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Hills", value: "Hills", color: "hsl(14, 95%, 90%)"}
      - { label: "Grassland", value: "Grassland", color: "hsl(296, 95%, 90%)"}
      - { label: "Marsh", value: "Marsh", color: "hsl(348, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      option_source: manual
  tags:
    input: tags
    accessorKey: tags
    key: tags
    id: tags
    label: Tags
    position: 100
    skipPersist: false
    isHidden: false
    sortIndex: 1
    isSorted: true
    isSortedDesc: true
    options:
      - { label: "Location", value: "Location", color: "hsl(264, 95%, 90%)"}
      - { label: "City - Small Town", value: "City - Small Town", color: "hsl(324, 95%, 90%)"}
      - { label: "Turenjo", value: "Turenjo", color: "hsl(111, 95%, 90%)"}
      - { label: "-", value: "-", color: "hsl(178, 95%, 90%)"}
      - { label: "Citadel", value: "Citadel", color: "hsl(61, 95%, 90%)"}
      - { label: "Walls", value: "Walls", color: "hsl(352, 95%, 90%)"}
      - { label: "Voiversk", value: "Voiversk", color: "hsl(1, 95%, 90%)"}
      - { label: "Port", value: "Port", color: "hsl(65, 95%, 90%)"}
      - { label: "Humenmoen", value: "Humenmoen", color: "hsl(22, 95%, 90%)"}
      - { label: "Fuentando", value: "Fuentando", color: "hsl(255, 95%, 90%)"}
      - { label: "Mamoutardon", value: "Mamoutardon", color: "hsl(209, 95%, 90%)"}
      - { label: "Plaza", value: "Plaza", color: "hsl(352, 95%, 90%)"}
      - { label: "Valmendral", value: "Valmendral", color: "hsl(132, 95%, 90%)"}
      - { label: "Pyrma", value: "Pyrma", color: "hsl(123, 95%, 90%)"}
      - { label: "Bjorvi", value: "Bjorvi", color: "hsl(115, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Features:
    input: tags
    accessorKey: Features
    key: Features
    id: Features
    label: Features
    position: 100
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Citadel", value: "Citadel", color: "hsl(81, 95%, 90%)"}
      - { label: "Walls", value: "Walls", color: "hsl(74, 95%, 90%)"}
      - { label: "Port", value: "Port", color: "hsl(244, 95%, 90%)"}
      - { label: "Plaza", value: "Plaza", color: "hsl(348, 95%, 90%)"}
      - { label: "Shanty Town", value: "Shanty Town", color: "hsl(118, 95%, 90%)"}
      - { label: "Temple", value: "Temple", color: "hsl(139, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
config:
  enable_show_state: false
  group_folder_column: 
  remove_field_when_delete_column: true
  cell_size: compact
  sticky_first_column: true
  show_metadata_created: true
  show_metadata_modified: true
  source_data: current_folder
  source_form_result: root
  show_metadata_tasks: false
  frontmatter_quote_wrap: false
  row_templates_folder: /
  current_row_template: __templates/ProStashio/Template - Settlement.md
  pagination_size: 10
  source_destination_path: /
  remove_empty_folders: false
  automatically_group_files: false
  hoist_files_with_empty_attributes: true
  show_metadata_inlinks: false
  show_metadata_outlinks: false
  enable_js_formulas: false
  formula_folder_path: /
  inline_default: false
  inline_new_position: top
  date_format: yyyy-MM-dd
  datetime_format: "yyyy-MM-dd HH:mm:ss"
  font_size: 16
  metadata_date_format: "yyyy-MM-dd HH:mm:ss"
  enable_footer: false
  implementation: default
  show_metadata_tags: false
filters:
  enabled: false
  conditions:
```