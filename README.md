# pstGiustiziaItSchemas
generazione classi java da schema  ufficiali del Processo Civile Telematico https://pst.giustizia.it/PST/it/pst_27.wp

Per generare le classi:

$mvn clean install generate-sources

il plug-in maven-jaxb2-plugin genera le classi nella cartella target/generated-sources
 