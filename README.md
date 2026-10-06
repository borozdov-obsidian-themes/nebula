# Borozdov Nebula

A theme from the Borozdov collection. Two faces — dark **Cosmos**, a starlit thinking
space, and light **Dawn**, the same space at first light. A violet-tinted void, lilac-white
text, rim-lit cards, medium-weight headlines and one lavender point of focus for what you
act on.

![Borozdov Nebula in dark mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/nebula/main/screenshots/dark.png)

![Borozdov Nebula in light mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/nebula/main/screenshots/light.png)

## Principles

- **A violet void.** The canvas is near-black with a violet undertone, never pure black;
  text is lilac-white, never pure white. Surfaces step up by lightness alone.
- **Rim light, not shadows.** Callouts, code, embeds and panels are lit by a faint inset
  glow along their edge; nothing casts a drop shadow.
- **One point of focus.** Lavender marks links, the caret, a checked task and a toggle;
  iris fills the main button. Nothing else is chromatic.
- **Medium, not bold.** Inter at 500 for the title and every heading, 600 for bold —
  nothing heavier. The system is calibrated to medium and regular.

## Features

- Dark and light modes, following Settings → Appearance → Base color scheme
- Tags and property values as badge pills with an iris rim and a faint violet glow
- Horizontal rules as aurora lines that fade in and out around a lavender centre
- Tables as midnight cards with a hairline frame
- Quiet editing: no focus ring around the note, its title or form fields while you type;
  property names read as labels, not boxed fields
- Text colours meet WCAG contrast on both faces
- The phone layout keeps the same colours and shapes
- No `!important`: every rule can be overridden with a CSS snippet

## Installation

**From the community directory, as a variant:** this theme ships inside **Borozdov
Console**. Install Borozdov Console under Settings → Appearance → Themes → Manage, then
the [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) plugin, and
choose **Nebula** under Style Settings → Borozdov Console → Variant. The variant brings
this theme's palette, type and corners; its own layout, and its embedded font if it has
one, come with the full theme below.

**The full theme, by hand:** download `manifest.json` and `theme.css` from the
[latest release](https://github.com/borozdov-obsidian-themes/nebula/releases/latest) into
`<vault>/.obsidian/themes/Borozdov Nebula/`, then choose Borozdov Nebula under
Settings → Appearance → Themes.

## Font

Inter (© 2016 The Inter Project Authors) is embedded in `theme.css` as base64 WOFF2 under
the SIL Open Font License 1.1 — see [`fonts/OFL.txt`](fonts/OFL.txt). A variable instance
spanning weights 400–600, Latin and Cyrillic.

## License

MIT — see [LICENSE](LICENSE).

---

**По-русски.** Тема из коллекции Borozdov. Два лика: тёмный «Космос» — звёздное
пространство для мыслей, и светлый «Рассвет» — то же пространство на первом свету.
Фиолетовая тьма вместо чёрной, сиренево-белый текст, карточки с подсветкой по краю,
заголовки среднего веса (Inter) и одна лавандовая точка фокуса для того, что вы делаете.
В каталоге тема живёт вариантом Borozdov Console: установите Borozdov Console и плагин Style Settings, затем выберите Nebula в Style Settings → Borozdov Console → Variant. Целиком, со своей вёрсткой, тема ставится вручную из последнего релиза репозитория.
