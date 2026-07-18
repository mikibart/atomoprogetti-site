# Studio Atomoprogetti — prima pagina statica

Prima pagina statica per `atomoprogetti.it`, pensata per sostituire la pagina WordPress di esempio.

## File

- `index.html` — one-page in italiano con SEO base e JSON-LD.
- `styles.css` — stile carta/blueprint: navy, terracotta, misura, niente template.
- `robots.txt` / `sitemap.xml` — pronti per la pubblicazione.

## Regola DNS

Non toccare `MX`/posta. Per il sito si modificano solo record web (`A`/`AAAA`/`CNAME`) dopo snapshot DNS.

## Pubblicazione consigliata

1. Backup/export WordPress e snapshot DNS.
2. Deploy di questa cartella in anteprima (Vercel o hosting statico).
3. Verifica contenuti e approvazione Architetto.
4. Puntamento DNS web.
5. Solo dopo: spegnere WordPress.

## Da verificare prima della pubblicazione

- Email definitiva da mostrare (attuale: `michelangelo@atomoprogetti.it`).
- Telefono e indirizzo.
- Eventuale P.IVA / dati legali da footer.
- Testi finali e foto/progetti reali da inserire nella sezione Progetti.
