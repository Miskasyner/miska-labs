# miska-labs

Miskan kokeilut, pelit ja prototyypit yhdessä paikassa. Julkaistaan Cloudflare Pagesiin osoitteeseen
`https://miska-labs.pages.dev/`.

## Rakenne

Jokainen kokeilu on oma kansionsa, ja kansion nimi on sen osoite:

```
miska-labs/
├── index.html        ← etusivu, listaa kokeilut
├── jes-peli/
│   └── index.html    ← https://miska-labs.pages.dev/jes-peli/
└── README.md
```

## Uuden kokeilun lisääminen

1. Tee uusi kansio, esim. `palaute-demo/`, ja sinne `index.html`.
2. Lisää rivi etusivun listaan (`index.html`).
3. Tallenna muutos (commit) ja vie GitHubiin (push).
4. Cloudflare julkaisee automaattisesti noin minuutissa.

## Pysyvät osoitteet

Kun kokeilun QR-koodi on tulostettu, **älä nimeä sen kansiota uudelleen**. Kansion nimi on osa osoitetta,
ja nimenvaihto rikkoo tulostetut koodit.

## Cloudflare-asetukset

- Projekti: Workers & Pages → `miska-labs`, yhdistetty tähän repoon
- Tuotantohaara: `main`
- Build command: *(tyhjä)*
- Build output directory: `/`
