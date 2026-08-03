# Pintapojat – staattinen nettisivu

Tämä projekti toimii suoraan GitHub Pagesissa ilman käännösvaihetta.

## Käyttöönotto GitHubissa

1. Luo uusi GitHub-repositorio.
2. Lataa kaikki tämän kansion tiedostot repositorion juureen.
3. Avaa **Settings → Pages**.
4. Valitse **Deploy from a branch**.
5. Valitse branchiksi `main` ja kansioksi `/ (root)`.
6. Tallenna. Sivusto julkaistaan GitHub Pages -osoitteeseen.

## Tarjouspyyntölomake

Lomake lähettää tiedot FormSubmit-palvelun kautta osoitteeseen `pintapojat@gmail.com`.
Ensimmäisen lähetyksen yhteydessä sähköpostiin tulee vahvistusviesti. Vahvistamisen jälkeen lomake toimii normaalisti.

Sähköpostiosoitteen voi vaihtaa tiedostossa `index.html` kohdassa:

```html
<form action="https://formsubmit.co/pintapojat@gmail.com" method="POST">
```

## Tiedostot

- `index.html` – sivun sisältö
- `styles.css` – ulkoasu ja responsiivisuus
- `script.js` – pehmeä vieritys
- `assets/` – kuvat
