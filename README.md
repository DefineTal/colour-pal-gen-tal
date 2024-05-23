# ColourAcademy - CSS Variable Generator Website

## Routes

- "/" : homepage
    - CSS generator available here
- "/cssvariables" - CSS generator page
    - CSS generator available here
- "generator/saved" - view list of saved themes
    - reads localstorage


## Contexts



- Current CSS theme
    - one theme list
    - local storate
- List of CSS themes
    - array of theme list
    - local storage
- Base colour
    - hex colour of new theme
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