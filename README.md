# KSBR – verkkosivuston klikattava prototyyppi

Klikattava HTML-prototyyppi KSBR:n uudistetusta verkkosivustosta. Pohjana ovat Design-kanvaasin "KSBR sivut" hi-fi-sivut. Prototyyppi ei vaadi build-vaihetta: avaa `index.html` selaimessa tai katso julkaistu versio GitHub Pagesissa.

Sivusto on julkaisupeili esittelyä varten. Se ei näy hakukoneissa (`noindex` ja `robots.txt`).

## Sivut

| Sivu | Tiedosto |
|---|---|
| Etusivu | `index.html` |
| Tuulivoima (energia) | `tuulivoima.html` |
| Teollisuus | `teollisuus.html` |
| Betonirakentaminen | `betonirakentaminen.html` |
| Referenssit | `referenssit.html` |
| Referenssi: Lestijärvi | `referenssi-lestijarvi.html` |
| Suunnitteluyhteistyö | `suunnitteluyhteistyo.html` |
| Toteutusmallit | `toteutusmallit.html` |
| Laatu ja turvallisuus | `laatu.html` |
| Meistä | `meista.html` |
| Ura | `ura.html` |
| Yhteystiedot | `yhteystiedot.html` |
| Yhteyshenkilöt | `yhteyshenkilot.html` |
| Tarjouspyyntö | `tarjouspyynto.html` |
| Tietopankki › Artikkeli: Talvibetonointi | `artikkeli-talvibetonointi.html` |

## Miten prototyyppi toimii

- Sivujen välillä liikutaan päävalikon, korttien, murupolkujen ja toimintakehotteiden kautta.
- Kaikki referenssikortit vievät samaan referenssisivupohjaan (Lestijärvi).
- Energia-linkit vievät Tuulivoima-sivulle ja Tietopankki-linkit artikkelipohjaan (Talvibetonointi).
- Jos sivua ei ole prototyypissä (esim. Infra, Datakeskukset tai uutiset), näytölle tulee ilmoitus "Tämä sivu ei ole mukana prototyypissä".
- Lomakkeita ei lähetetä.
- Vasemmassa alakulmassa olevasta "Prototyypin sivut" -valikosta pääsee suoraan mille tahansa sivulle.
- Mobiilissa toimii hampurilaisvalikko.
- Tekstien [Täydennä]-merkinnät ovat sisältöjä, jotka täydennetään copyvaiheessa.

## Rakenne

- `css/tokens.css` ja `css/bundle.css`: KSBR design systemin tokenit ja komponentit (b-*).
- Sivukohtaiset hi-fi-tyylit (hf-*) ovat kunkin sivun `<style>`-lohkossa.
- `img/`: kuvat on haettu ksbr.fi-sivustolta. Kuvaajien oikeudet tarkistetaan ennen tuotantoa.
