# Typescript-React-Map
A map made using react, react-map-gl and typescript

## Example Map
```
<Map lat={-27} lng={153}/>
```

## Example Markes
```
const pins: Markers[] = [
    {
      lat: -27.4715,
      lng: 153.0260,
      marker: <Pin/>,
      draggable: true,
      click: () => setMapPos({lat: -27.4715, lng: 153.0260})
    },
    {
      lat: -27.4725,
      lng: 153.0260,
      marker: <Pin/>,
      click: () => setMapPos({lat: -27.4725, lng: 153.0260})
    }
  ];
```

## Example Buttons
```
const buttons: JSX.Element[] = [<button>1</button>, <button>2</button>];
```

## GeoJSON
When adding GeoJSON make sure the FeatureCollection type is infered
this type can be found in GeoJSONTypes.tsx
