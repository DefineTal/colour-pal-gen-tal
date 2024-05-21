# ColourAcademy - CSS Variable Generator Website

## Routes

- "/" : homepage
    - CSS generator available here
- "/cssvariables" - CSS generator page
    - CSS generator available here
- "generator/saved" - view list of saved themes
    - reads localstorage


## Contexts

- Localstorage manager for list of CSS themes
- Localstorate manager for current CSS theme
    - One Theme List
- List of CSS themes
    - Array of Theme lists
- Current CSS theme
    - One Theme List

## Data

### Colour Object

```JS
{
    hex: "#000000",
    strength: 100,
    rgba: [255, 255, 255, 255]
}
```
### Theme list
```JS
{
    name: "violet eggplant",
    colours: [
        Colour Objects go here ^_^
    ]
}

```