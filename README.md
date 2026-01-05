# CNN_Datai_Oppimistehtava_Fruits365

## CNN-pohjainen hedelmien ja vihannesten kuvantunnistus

Tässä projektissa toteutetaan konvoluutioneuroverkkoon (CNN) perustuva malli, jonka avulla tunnistetaan hedelmiä ja vihanneksia kuvista. Projekti on tehty osana Data-AI-kurssin oppimistehtävää 2.

## Projektin yleiskuvaus

Projektin tavoitteena oli tutkia CNN-mallien toimivuutta kuvantunnistustehtävissä. Työ aloitettiin yksinkertaisella kahden luokan luokittelulla (banaani vs. kurkku), minkä jälkeen mallia laajennettiin useampiin hedelmä- ja vihannesluokkiin.

## Käytetyt teknologiat

- Python  
- TensorFlow / Keras  
- Konvoluutioneuroverkot (CNN)  
- ImageDataGenerator  
- Matplotlib  
- Scikit-learn  

## Datasetti

Projektissa käytetään Kagglesta saatavaa Fruits-360-datasettiä:
- Noin 120 000 kuvaa  
- 176 eri luokkaa  
- Kuvien resoluutio 100×100 pikseliä  
- Valkoinen tausta ja hallittu valaistus  

## Tulokset

- Banaanin ja kurkun luokittelu saavutti lähes täydellisen tarkkuuden.
- Usean luokan luokittelussa suorituskyky heikkeni datan epätasapainon vuoksi.
- Parhaat tulokset saavutettiin kuvilla, joissa tausta oli valkoinen ja varjoton.

## Rajoitteet ja jatkokehitys

- Luokkien voimakas epätasapaino vaikutti mallin ennusteisiin.
- Todelliset käyttökuvat heikensivät tunnistustarkkuutta.
- Mahdollisia jatkokehityskohteita ovat datan augmentointi, datan tasapainotus ja siirto-oppiminen.
