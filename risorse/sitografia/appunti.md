Questa sitografia è raccolta con Zotero ed esportata in CSV da Zotero.

Per farne un elenco puntato come questo

  - DECRETO LEGISLATIVO 24 gennaio 2006, n. 36 - Attuazione della direttiva (UE) 2019/1024 relativa all'apertura dei dati e al riutilizzo dell'informazione del settore pubblico che ha abrogato la direttiva 2003/98/CE ([link](https://www.normattiva.it/uri-res/N2Ls?urn:nir:stato:decreto.legislativo:2006-01-24;36!vig))
  - DECRETO LEGISLATIVO 7 marzo 2005, n. 82 - Codice dell'Amministrazione Digitale ([link](https://www.normattiva.it/uri-res/N2Ls?urn:nir:stato:decreto.legislativo:2005-03-07;82!vig))
  - Defining Open in Open Data, Open Content and Open Knowledge ([link](https://opendefinition.org/od/2.0/it/))

si può usare Miller in questo modo

```bash
mlrgo --c2n cut -f Title,Url then sort -f Title then put '$out="  - ".$Title." [(link)](".$Url.")"' then cut -f out input.csv
```
