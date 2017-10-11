# Demo 1, tehtävä 4 
(a) Käy  läpi  yksityiskohtaisesti vaihe  vaiheelta,  miten  kyseinen  taulukko  järjestetään käyttäen Lisäyslajittelualgoritmia (insertion sort)

Algoritmi toimii pitämällä taulukon alkuosan koko ajan järjestyksessä lisäämällä yksitellen jokaisen alkion käsittelemättömästä loppuosasta oikealle paikalleen alkuosaan. [Wikipedia](https://fi.wikipedia.org/wiki/Lis%C3%A4yslajittelu)

Järjestelty | Järjestelemättä
------------:|----------------
48 | 23 11 35 27 51 39 6 72 43
**23** 48 | 11 35 27 51 39 6 72 43
**11** 23 48 | 35 27 51 39 6 72 43
11 23 **35** 48 | 27 51 39 6 72 43
11 23 **27** 35 48 | 51 39 6 72 43
11 23 27 35 48 **51** | 39 6 72 43
11 23 27 35 **39** 48 51 | 6 72 43
**6** 11 23 27 35 39 48 51 | 72 43
6 11 23 27 35 39 48 51 **72** | 43
6 11 23 27 35 39 **43** 48 51 72 |