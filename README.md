## Identifier Scheme Url Extension

### Description
A url to more with human-readable information about the scheme used in the identifier block

### Fields
- identifier.schemeURL: A url to more with human-readable information about the scheme used in the identifier block

### Example
```javascript
...
 "parties": [
          {
            "id": "06C00",
            "additionalIdentifiers": [
              {
                "scheme": "MX-CPA",
                "id": "06",
                "legalName": "Hacienda y Crédito Público",
                "schemeUrl": "http://www.transparenciapresupuestaria.gob.mx/work/models/PTP/DatosAbiertos/Metadatos/catalogos_presupuestarios.xlsx"
              }
            ],
            "name": "Comisión Nacional de Seguros y Fianzas",
            "contactPoint": {
              "name": "Luis Fernando Sanchez Fernandez"
            },
            "identifier": {
              "id": "06C00",
              "legalName": "Comisión Nacional de Seguros y Fianzas",
              "scheme": "MX-CPA",
              "schemeUrl": "http://www.transparenciapresupuestaria.gob.mx/work/models/PTP/DatosAbiertos/Metadatos/catalogos_presupuestarios.xlsx"
            },
            "roles": [
              "buyer"
            ]
          },
...
```