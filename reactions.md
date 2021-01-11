# Reactions

## convert

Returns an object containing all the details of the board

| Field  | Type  | Required  | Default  | Description  |
|---|---|---|---|---|
| colourName  | string  | :heavy_check_mark:  | none  | Name of the html colour to convert  |

```
module.exports = async (data, services) => {
  const int = await services.plugin('colour', 'convert', 'colourName')
}
```
