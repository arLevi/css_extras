# Buttons 

# Chunky 3D buttons
Coming from CodePen: https://codepen.io/Andrew-Fisher-the-decoder/pen/raMZQNe

Usage:
```
// Create a button
create_section("Button Palette");
Object.keys(COLORS).forEach((color) => create_btn({ c: color,  l: color, i: "palette" }));

create_section("Square Icons");
Object.keys(COLORS).forEach((color) => create_btn({ c: color, i: "fingerprint", sq: true }));

create_section("Sizing & Layouts");
create_btn({ c: "blue", l: "Tiny", h: 30, i: "bolt" });
create_btn({ c: "teal", l: "Standard", h: 44, i: "rocket_launch" });
create_btn({ c: "pink", l: "Large & Long Label", h: 60, i: "celebration" });
create_btn({ c: "orange", l: "Full Width Button", h: 44, i: "width_full", class: "w-full block mt-4"});
```

[![Images|Demo](https://github.com/arLevi/css_helpers/raw/main/images/chunky_3d_image.png)](https://github.com/arLevi/css_helpers)
