## &lt;einsteinium-periodic&gt;##

`einsteiniumperiodic`
is a Polymer web component that renders a periodic table. Using the components attributes, and nested components the periodic table can be rendered either as a static view, or as a fully dynamic mini-application.

Example:

```html
<einsteinium-periodic></einsteinium-periodic
```

### Styling

The following custom properties and mixins are available for styling:

| Custom property | Description | Default |
| --- | --- | --- |
| `--einsteinium-periodic-element-default-background-color` | Default background color for elements whose series does not have a specified color | 'transparent` | 
| `--einsteinium-periodic-element-alkali-metal-background-color` | Background color for elements in the alkali metal series | `Crimson` |
| `--einsteinium-periodic-element-alkaline-earth-metal-series-background-color` | Background color for elements in the alkali earth metal series | `SandyBrown` |
| `--einsteinium-periodic-element-lanthanide-series-background-color` | Background color for elements in the lanthanide series | `Violet` |
| `--einsteinium-periodic-element-actinide-series-background-color` | Background color for elements in the actinide series | `Orchid` |
| `--einsteinium-periodic-element-transition-metal-series-background-color` | Background color for elements in the transition metal series | `LightSalmon` | 
| `--einsteinium-periodic-element-post-transition-metal-series-background-color` | Background color for elements in the post transition metal series | `DarkGray` |
| `--einsteinium-periodic-element-metalloid-series-background-color` | Background color for elements in the metalloid series | `DarkKhaki` |
| `--einsteinium-periodic-element-polyatomic-nonmetal-series-background-color` | Background color for elements in the polyatomic nonmetal series | `MediumAquamarine` |
| `--einsteinium-periodic-element-diaatomic-nonmetal-series-background-color` | Background color for elements in the diatomic nonmetal series | `GreenYellow` |
| `--einsteinium-periodic-element-polyatomic-noble-gasses-series-background-color` | Background color for elements in the noble gasses series | `Aqua` |
| `--einsteinium-periodic-element-atomic-number-default-color` | Color for the atomic number for elements with an unknown state at 0 degrees centigrade and 1 atmosphere | `Grey` |
| `--einsteinium-periodic-element-atomic-number-liquid-color` | Color for the atomic number for elements with a liquid state at 0 degrees centigrade and 1 atmosphere | `Green` |
| `--einsteinium-periodic-element-atomic-number-solid-color` | Color for the atomic number for elements with a solid state at 0 degrees centigrade and 1 atmosphere | `Black` |
| `--einsteinium-periodic-element-atomic-number-gas-color` | Color for the atomic number for elements with a gaseous state at 0 degrees centigrade and 1 atmosphere | `Red` |
| `--einsteinium-periodic-element-name-default-color` | Color for the element name | `Black` |
| `--einsteinium-periodic-element-symbol-default-color` | Color for the element symbol | `Black` |
| `--einsteinium-periodic-element-primordial-border` | Border style for elements with primordial occurrence |  |
| `--einsteinium-periodic-element-synthetic-border` | Border style for elements with synthetic occurrence |  |
| `--einsteinium-periodic-element-from-decay-border` | Border style for elements with occurring as a result of decay |  |
|`--einsteinium-periodic-element-height` | The height of a single element | 10% of the container |
|`--einsteinium-periodic-element-width` | The width of a single element | 5% of the container |








