# Reactions

## convert

Returns the int value of the colourname so obs can use it

| Field  | Type  | Required  | Default  | Description  |
|---|---|---|---|---|
| colourName  | string  | :heavy_check_mark:  | none  | Name of the html colour to convert  |

```
module.exports = async (data, services) => {
  const int = await services.plugin('colour', 'convertToObs', 'colourName')
}
```

Returns the hexadecimal value of the colourname

| Field  | Type  | Required  | Default  | Description  |
|---|---|---|---|---|
| colourName  | string  | :heavy_check_mark:  | none  | Name of the html colour to convert  |

```
module.exports = async (data, services) => {
  const int = await services.plugin('colour', 'convertToHex', 'colourName')
}
```

Returns the RGB value of the colour name

| Field  | Type  | Required  | Default  | Description  |
|---|---|---|---|---|
| colourName  | string  | :heavy_check_mark:  | none  | Name of the html colour to convert  |

```
module.exports = async (data, services) => {
  const int = await services.plugin('colour', 'convertToRgb', 'colourName')
}
```

