# Parte tecnica per lo sviluppo della documentazione

## Contribuire alla documentazione {docsify-ignore}

Se si desidera partecipare alla stesura della documentazione, conviene partire dall'installazione di `docsify-cli`:

```bash
npm i docsify-cli -g
```

Dopo aver lanciato `docsify serve` da terminale (all'interno della cartella), è possibile accedere alla documentazione all'indirizzo `http://localhost:3000`.

```bash
docsify serve
```

per maggiori info su `docsify-cli` consultare la documentazione di docsify [docsify-cli github](https://github.com/docsifyjs/docsify-cli) o qui [docsify-cli documentation](https://docsify.js.org/#/quickstart).

## Alberatura dei contenuti {docsify-ignore}

I contenuti sono strutturati nel seguente ordine:

* `index.html` è il file dove viene inizializzata la doc
* `README.md` è l'home page

Alla creazione di una nuova pagina della documentazione dovrà corrispondere l'aggiornamento della `_sidebar.md`! 