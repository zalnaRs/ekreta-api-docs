# EKRÉTA api dokumentáció

[TheBlueLines](https://github.com/TheBlueLines) által készitett dokumentáció frissitése.

### API linkek lekérése

Hasznos ha megvátoztatjak (eddig még soha nem csinálták), akkor nem kell frisiteni az alkalmazást!

(*[thegergo02](https://github.com/thegergo02)*)

**Válasz**
```json
{
  "GlobalMobileApiUrlDEV": "https://kretaglobalmobileapidev.ekreta.hu/",
  "GlobalMobileApiUrlTEST": "https://kretaglobalmobileapitest.ekreta.hu",
  "GlobalMobileApiUrlUAT": "https://kretaglobalmobileapiuat.ekreta.hu",
  "GlobalMobileApiUrlPROD": "https://kretaglobalmobileapi2.ekreta.hu"
}
```

## Iskolák lekérése

1. opció:

`"https://kretaglobalmobileapi2.ekreta.hu/api/v3/Institute"
headers: "apiKey: 7856d350-1fda-45f5-822d-e1a2f3f1acf0"`

2. opció (új):

`https://kretaglobalapi.e-kreta.hu/intezmenyek/kreta/publikus`

**Válasz**
```json
[
    {
        "instituteId": 0000,
        "instituteCode": "xxxxxxxxxxx",
        "name": "Xxxxx Xxxx Xxxxxx",
        "city": "Xxxxxx",
        "url": "https://xxxxxxxxxxx.e-kreta.hu",
        "advertisingUrl": "",
        "informationImageUrl": "https://kretamobile.blob.core.windows.net/advertisement/nati_app.gif",
        "informationUrl": "",
        "featureToggleSet": {}
    },
    ...
]
```
