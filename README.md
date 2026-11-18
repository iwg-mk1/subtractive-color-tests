# subtractive-color-tests

## Pigment library

Edit [`pigments.json`](./pigments.json) to add pigments to the picker. Add entries to the `pigments` array with a display `name` and a six-digit hex color:

```json
{
  "pigments": [
    { "name": "Ultramarine Blue", "hex": "#415D9B" }
  ]
}
```

Serve the project over HTTP so the page can load `pigments.json` (for example, with VS Code Live Server). Search the pigment name or hex in a row to choose a library pigment, or use that row's custom color picker/hex value.

