# pstGiustiziaItSchemas
generazione classi java da schema  ufficiali del Processo Civile Telematico https://pst.giustizia.it/PST/it/pst_27.wp

Per generare le classi:

```bash
$mvn -Pjaxb clean install generate-sources
```

Per generare classi + hibernate annotations

```bash
$mvn -Phyperjaxb clean install generate-sources
```
le classi vengono generate nella cartella target/generated-sources

progetto hyperjaxb:http://confluence.highsource.org/display/HJ3/Home
