# Data
Datasættet viser lovlige parkeringspladser i dagtimerne (7-18) på gadeplan (på offentlige og private fælles veje), parkeringspladser i offentligt ejede parkeringsanlæg samt parkeringspladser uden parkeringsordning. Parkeringsmuligheder for elbiler, delebiler, taxi og handicapbilister fremgår. Indeholder også parkeringspladser reserveret til ambassader og konsulater.

https://data.kk.dk/dataset/parkeringspladser

donlowder filen til computeren
https://data.kk.dk/dataset/parkeringspladser/resource/b1d84794-8262-4fd9-9346-db7bedcc0c8f

data set
http://wfs-kbhkort.kk.dk/k101/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=k101:p_pladser&outputFormat=csv&SRSNAME=EPSG:4326

header 

FID,vejkode,vejnavn,antal_pladser,restriktion,vejstatus,vejside,bydel,p_ordning,p_type,rettelsedato,oprettelsesdato,bemaerkning,id,
taelle_id,startdato_midlertidigt_nedlagt,slutdato_midlertidigt_nedlagt,wkb_geometry


1 find all p-pladers i Indre By

2 hvor mange Privat p-pladers er der i alt 

3 hvilken p-plads har flest p-plader

4 find all p-pladers der har oprettelsesdato 2015 10 -29 eller sener 

5 hvad er forskellen melem den by-del der flest Privat p-pladser og den der mindst

6 plot hvilken by-del er der flest privat p-pladser 

7 plot alle p-pladser, der er nedlagt

8 plot vejstatus som komunevej og hvor mange der har rettedato 2016-03-29 og bemarkinger  
