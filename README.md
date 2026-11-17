# Particle Strands (three.js)

4 asimetrične linije od izmešanih čestica (#106ACA i #14171A) koje se uvijaju jedna oko druge i teku nagore pod uglom, na beloj pozadini. Kada pređeš mišem (ili prstom), čestice se razlete na sve strane i zatim vrate u linije.

## Pokretanje
Otvori `index.html` u browseru (three.js se učitava sa CDN-a), ili lokalno:

```
npx serve .
```

- `index.html?t=9` prikazuje statičan kadar u 9. sekundi (za skice/screenshot).

## Podešavanja (`CONFIG` i `STRANDS` u `index.html`)
| Parametar | Opis |
|---|---|
| `tiltDeg` | nagib ose (vrh ulevo) |
| `flowSpeed` | brzina kretanja čestica nagore |
| `twistSpeed` | brzina uvijanja linija jedna oko druge |
| `particlesPerStrand` | gustina čestica po liniji |
| `thickness` | debljina linije |
| `coreHollow` | koliko je centar linije ređi |
| `blue`, `dark`, `blueShare` | dve boje, izmešane; udeo plave |
| `STRANDS[]` | oblik svake linije posebno (poluprečnik, gustina uvijanja, brzina, vijuganje, debljina) |
| `mouseRadius` | koliko daleko od kursora čestice beže |
| `mouseStrength` | koliko daleko odleću |
| `mouseRecover` | brzina vraćanja u liniju |
