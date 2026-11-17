# Particle Strands (three.js)

Plave linije od sitnih čestica koje se prepliću i teku nagore pod uglom, na beloj pozadini.

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
| `twistSpeed` | brzina uvijanja/preplitanja |
| `particlesPerStrand` | gustina čestica po liniji |
| `thickness` | debljina linije |
| `colors` | nijanse plave |
| `STRANDS[].r / w / ph / dx` | poluprečnik uvijanja, učestalost, faza, pomak svake linije |
