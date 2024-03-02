---
layout: single
title: "sublime text 세팅"
categories: linux
tag: ubuntu
---

## sublime text Presferences-setting

## vi-mode "jj" key bindings

```
{
    "tree_animation_enabled": true,
    "fade_fold_buttons": false, 
    "line_padding_top": 1,
    "line_padding_bottom": 1,
    "font_size": 13,
    "always_show_minimap_viewport": true,
    "bold_folder_labels": true,
    "draw_minimap_border": true,
    "highlight_line": true,
    "vintage_start_in_command_mode": true,
    "ignored_packages":
    [
    ],
    "tab_size": 4,
            "translate_tabs_to_spaces": false,
    "word_wrap": true,
            "draw_white_space": "all",
    "font_face": "Hack Nerd Font Mono",
    "indent_guide_options":
    [
        "draw_normal","draw_active"
    ],
    "color_scheme": "Packages/Colorsublime - Themes/Dark-Dracula.tmTheme",
}


## 키바인딩

{
    "keys":["j", "k"],
    "command": "exit_insert_mode",
    "context":
    [
        { "key": "setting.command_mode", "operand":
            false },
        {
           "key": "setting.is_widget", "operand":
            false }
    ]
},

{ "keys": ["ctrl+e"],
  "command": "toggle_side_bar"},    
```

## sublime text 설치후 세팅과 키바인딩
