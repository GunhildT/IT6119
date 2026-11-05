# IT6119
Final project - Risikoklassifisering ved intracerebral blødning
Inneholder mitt avsluttende prosjekt for emnet IT6119 Helsedata/KI ved NTNU. 

Følgende problemstilling: Kan en enkel logistisk regresjonsfmodell basert på alder, Glasgow Coma Scale (GCS), hematomvolum og intraventrikulær blødning (IVH) brukes til å klassifisere risiko for mortalitet under sykehusoppholdet hos pasienter med intracerebral blødning (ICH)?

Informasjon om det brukte datasettet: 
Prosjektet bruker et offentlig tilgjengelig og anonymisert datasett for pasienter med intracerebral blødning. 
Originaldatasettet er tilgjengelig på Zenedo, med lenke: https://doi.org/10.5281/zenodo.15368710

Datasettet er ikke lagt inn direkte her. Det kan leses fra lenken. Datasettet bestod opprinnelig av 680 pasienter. Etter ekskludering av pasienter som ikke fylte valgte inkiusjonskriterier, endte datasettet opp med 601 pasienter. Av disse døde 178 under sykehusoppholdet. 

Analysen bruker Excel-filen: 
ICH AVCH 17-23u - final - anonymized - unif + imagistic.xlsx
,og arket:
ICH 17-23

Variabler - modellen bruker fire valgte inputvariabler: alder, GCS, hematomvolum, IVH
Alder og GCS var registrert ved innleggelse, mens hematomvolum og IVH ble hentet fra CT-undersøkelsen. variablene var dermed tilgjengelige tidlig i pasientforløpet og før utfallet mortalitet under sykehusoppholdet. Av de 601 pasientene hadde 349 komplette data for alle variablene som ble brukt i modellen. 
