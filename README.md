# Particle Strands (three.js)

4 asimetrične linije od izmešanih čestica (#106ACA i #14171A) koje se uvijaju jedna oko druge i teku nagore pod uglom, na beloj pozadini. Pojedine svetloplave čestice se pojavljuju 200–300px od linija i vrate nazad u tok. Kada pređeš mišem (ili prstom), čestice se razlete na sve strane i zatim vrate u linije.

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
| `speedVariety` | razlika u brzini između čestica |
| `orbitSpeed` | kruženje čestica unutar linije |
| `wander` | slobodno lutanje čestica |
| `pathDrift` | koliko se putanje linija menjaju u vremenu |
| `twistSpeed` | koliko se sam oblik okreće |
| `particlesPerStrand` | gustina čestica po liniji |
| `thickness` | debljina linije |
| `coreHollow` | koliko je centar linije ređi |
| `blue`, `dark`, `blueShare` | dve boje, izmešane; udeo plave |
| `STRANDS[]` | oblik svake linije posebno (poluprečnik, gustina uvijanja, brzina, vijuganje, debljina) |
| `strayPerStrand` | broj čestica koje se pojave pored linija i vrate u tok |
| `strayDistMin` / `strayDistMax` | udaljenost od linija gde se pojavljuju (px) |
| `strayColor` | boja tih čestica |
| `strayLifeMin` / `strayLifeMax` | trajanje jednog takvog ciklusa (s) |
| `mouseRadius` | koliko daleko od kursora čestice beže |
| `mouseStrength` | koliko daleko odleću |
| `mouseRecover` | brzina vraćanja u liniju |
