# zmk-corne-rdv
Real programmers dvorak layout on a 40% split keyboard (corne). 
- `Layer 0`: ✍️ Standard dvorak layout
- `Layer 1`: 💯 Numbers
- `Layer 2`: 🔣 Symbols
- `Layer 3`: 📡 Multimedia

<details>
  <summary>keymap</summary>

```
// +------------------------------------------------------------------------------------+
// |  TAB  | ; : | , < | . > |  P  |  Y  |         |  F  |  G  |  C  |  R  |  L  | BSPC |
// | LSHFT |  A  |  O  |  E  |  U  |  I  |         |  D  |  H  |  T  |  N  |  S  | DEL  |
// |  CTLR | ' " | q @ |  J  |  K  |  X  |         |  B  |  M  |  W  |  V  |  Z  | ESC  |
//                       | GUI | LOWER | SPC |  | ENT | RAISE | ALT |
// +------------------------------------------------------------------------------------+
  
// +------------------------------------------------------------------------------------+
// |   TAB |  1  |  2  |  3  |  4  |  5  |         |  6  |  7  |  8  |  9  |  0  | BKSP |
// | LSHFT |     |     |     |     |     |         | LEFT| DOWN|  UP | RHGT|     |      |
// |  CTLR |     |     |     |     |     |         |     |     |     |     |     |      |
//                         | GUI |     | SPC |  | ENT |MEDIA| ALT |
// +------------------------------------------------------------------------------------+

// +------------------------------------------------------------------------------------+
// |  TAB  |  !  |  @  |  #  |  $  |  %  |         |  ^  |  &  |  *  |  (  |  )  | BSPC |
// | LSHFT |  ~  |  -  |  [  |  (  |  /  |         |  \  |  )  |  ]  |  +  |  =  | ` ~  |
// |  CTLR |GLOBE|  _  |  ?  |  {  |  :  |         |  ;  |  }  |  "  |  |  |     |  ESC |
//                        | GUI |MEDIA| SPC |   | ENT |     | ALT |
// +------------------------------------------------------------------------------------+

// +------------------------------------------------------------------------------------+
// |   TAB |     |     |     |     |     |         |     |     |     |     |     | BKSP |
// |BT CLR | BT1 | BT2 | BT3 | BT4 | BT5 |         | PREV|> || | NEXT|     |     |      |
// |  CTLR |PW ON|PWOFF|     |     |     |         | MUTE| VOL-| VOL+|     |     |  ESC |
//                        | GUI |     | SPC |  | ENT |     | ALT |
// +------------------------------------------------------------------------------------+
```

</details>

# Inspiration and credits
[Dvorak layout](https://en.wikipedia.org/wiki/Dvorak_keyboard_layout).

This config is a modified implementation of [programmers dvorak](https://www.kaufmann.no/roland/dvorak/). This layout is close to [real programmers dvorak](https://github.com/ThePrimeagen/keyboards/blob/master/README.md).
Deviation from programmers dvorak is that I do not remap `numbers`, but do optimize brackets and some symbols.

Also see [my qmk config](https://github.com/timonviola/qmk_firmware) I use for my wired corne.

Special thanks for all zmk contributors and community members.
