# opus-2020-09-26.zip

* dataset: opus
* model: transformer
* source language(s): aze_Arab bak chg_Arab chg_Latn chv crh crh_Latn eng gag kaa_Latn kaz_Cyrl kaz_Latn kir_Cyrl kjh krc kum mon nog ota_Arab ota_Latn sah tat tat_Arab tat_Latn tuk tuk_Cyrl tuk_Latn tur tyv uig_Arab uig_Cyrl uig_Latn uzb_Cyrl uzb_Latn xal xal_Latn
* target language(s): aze_Arab bak chg_Arab chg_Latn chv crh crh_Latn eng gag kaa_Latn kaz_Cyrl kaz_Latn kir_Cyrl kjh krc kum mon nog ota_Arab ota_Latn sah tat tat_Arab tat_Latn tuk tuk_Cyrl tuk_Latn tur tyv uig_Arab uig_Cyrl uig_Latn uzb_Cyrl uzb_Latn xal xal_Latn
* model: transformer
* pre-processing: normalization + SentencePiece (spm32k,spm32k)
* a sentence initial language token is required in the form of `>>id<<` (id = valid target language ID)
* download: [opus-2020-09-26.zip](https://object.pouta.csc.fi/Tatoeba-MT-models/tut-tut/opus-2020-09-26.zip)
* test set translations: [opus-2020-09-26.test.txt](https://object.pouta.csc.fi/Tatoeba-MT-models/tut-tut/opus-2020-09-26.test.txt)
* test set scores: [opus-2020-09-26.eval.txt](https://object.pouta.csc.fi/Tatoeba-MT-models/tut-tut/opus-2020-09-26.eval.txt)

## Benchmarks

| testset               | BLEU  | chr-F |
|-----------------------|-------|-------|
| newsdev2016-entr-engtur.eng.tur 	| 6.9 	| 0.365 |
| newsdev2016-entr-tureng.tur.eng 	| 11.0 	| 0.359 |
| newstest2016-entr-engtur.eng.tur 	| 6.5 	| 0.345 |
| newstest2016-entr-tureng.tur.eng 	| 10.3 	| 0.355 |
| newstest2017-entr-engtur.eng.tur 	| 6.5 	| 0.341 |
| newstest2017-entr-tureng.tur.eng 	| 10.5 	| 0.351 |
| newstest2018-entr-engtur.eng.tur 	| 6.9 	| 0.344 |
| newstest2018-entr-tureng.tur.eng 	| 10.4 	| 0.352 |
| Tatoeba-test.aze-eng.aze.eng 	| 9.6 	| 0.270 |
| Tatoeba-test.aze-tur.aze.tur 	| 8.0 	| 0.294 |
| Tatoeba-test.bak-eng.bak.eng 	| 14.1 	| 0.361 |
| Tatoeba-test.bak-kaz.bak.kaz 	| 42.7 	| 0.782 |
| Tatoeba-test.bak-tat.bak.tat 	| 6.2 	| 0.433 |
| Tatoeba-test.bak-tur.bak.tur 	| 8.8 	| 0.344 |
| Tatoeba-test.bak-uzb.bak.uzb 	| 12.7 	| 0.152 |
| Tatoeba-test.chg-tur.chg.tur 	| 1.0 	| 0.135 |
| Tatoeba-test.chv-eng.chv.eng 	| 14.3 	| 0.325 |
| Tatoeba-test.chv-tat.chv.tat 	| 10.7 	| 0.127 |
| Tatoeba-test.chv-tur.chv.tur 	| 8.4 	| 0.337 |
| Tatoeba-test.crh-eng.crh.eng 	| 31.2 	| 0.442 |
| Tatoeba-test.crh-tat.crh.tat 	| 4.2 	| 0.095 |
| Tatoeba-test.crh-tur.crh.tur 	| 20.9 	| 0.461 |
| Tatoeba-test.eng-aze.eng.aze 	| 1.1 	| 0.218 |
| Tatoeba-test.eng-bak.eng.bak 	| 5.1 	| 0.301 |
| Tatoeba-test.eng-chv.eng.chv 	| 7.2 	| 0.336 |
| Tatoeba-test.eng-crh.eng.crh 	| 5.5 	| 0.301 |
| Tatoeba-test.eng-kaz.eng.kaz 	| 12.2 	| 0.353 |
| Tatoeba-test.eng-kir.eng.kir 	| 21.2 	| 0.444 |
| Tatoeba-test.eng-kjh.eng.kjh 	| 1.8 	| 0.014 |
| Tatoeba-test.eng-kum.eng.kum 	| 2.7 	| 0.008 |
| Tatoeba-test.eng-mon.eng.mon 	| 7.4 	| 0.292 |
| Tatoeba-test.eng-nog.eng.nog 	| 0.4 	| 0.013 |
| Tatoeba-test.eng-ota.eng.ota 	| 1.0 	| 0.111 |
| Tatoeba-test.eng-sah.eng.sah 	| 0.7 	| 0.008 |
| Tatoeba-test.eng-tat.eng.tat 	| 8.2 	| 0.289 |
| Tatoeba-test.eng-tuk.eng.tuk 	| 8.2 	| 0.352 |
| Tatoeba-test.eng-tur.eng.tur 	| 27.0 	| 0.548 |
| Tatoeba-test.eng-tyv.eng.tyv 	| 6.0 	| 0.220 |
| Tatoeba-test.eng-uig.eng.uig 	| 0.2 	| 0.167 |
| Tatoeba-test.eng-uzb.eng.uzb 	| 2.5 	| 0.277 |
| Tatoeba-test.eng-xal.eng.xal 	| 0.1 	| 0.008 |
| Tatoeba-test.gag-tur.gag.tur 	| 14.0 	| 0.292 |
| Tatoeba-test.kaa-tur.kaa.tur 	| 0.0 	| 0.250 |
| Tatoeba-test.kaz-bak.kaz.bak 	| 30.2 	| 0.532 |
| Tatoeba-test.kaz-eng.kaz.eng 	| 20.8 	| 0.398 |
| Tatoeba-test.kaz-tat.kaz.tat 	| 9.7 	| 0.396 |
| Tatoeba-test.kaz-tur.kaz.tur 	| 8.6 	| 0.264 |
| Tatoeba-test.kaz-uzb.kaz.uzb 	| 100.0 	| 1.000 |
| Tatoeba-test.kir-eng.kir.eng 	| 34.1 	| 0.497 |
| Tatoeba-test.kir-tur.kir.tur 	| 26.9 	| 0.524 |
| Tatoeba-test.kjh-eng.kjh.eng 	| 2.3 	| 0.119 |
| Tatoeba-test.kjh-tur.kjh.tur 	| 21.4 	| 0.089 |
| Tatoeba-test.krc-tur.krc.tur 	| 19.0 	| 0.213 |
| Tatoeba-test.kum-eng.kum.eng 	| 38.9 	| 0.458 |
| Tatoeba-test.kum-tur.kum.tur 	| 24.4 	| 0.330 |
| Tatoeba-test.mon-eng.mon.eng 	| 12.8 	| 0.326 |
| Tatoeba-test.multi.multi 	| 18.5 	| 0.393 |
| Tatoeba-test.nog-eng.nog.eng 	| 20.4 	| 0.335 |
| Tatoeba-test.nog-tur.nog.tur 	| 10.7 	| 0.195 |
| Tatoeba-test.ota-eng.ota.eng 	| 2.9 	| 0.169 |
| Tatoeba-test.ota-tur.ota.tur 	| 2.0 	| 0.173 |
| Tatoeba-test.sah-eng.sah.eng 	| 0.9 	| 0.152 |
| Tatoeba-test.sah-tur.sah.tur 	| 6.0 	| 0.092 |
| Tatoeba-test.tat-bak.tat.bak 	| 3.9 	| 0.405 |
| Tatoeba-test.tat-chv.tat.chv 	| 21.4 	| 0.782 |
| Tatoeba-test.tat-crh.tat.crh 	| 16.0 	| 0.082 |
| Tatoeba-test.tat-eng.tat.eng 	| 14.5 	| 0.324 |
| Tatoeba-test.tat-kaz.tat.kaz 	| 28.8 	| 0.409 |
| Tatoeba-test.tat-tuk.tat.tuk 	| 14.3 	| 0.446 |
| Tatoeba-test.tat-tur.tat.tur 	| 14.0 	| 0.384 |
| Tatoeba-test.tat-uzb.tat.uzb 	| 19.2 	| 0.417 |
| Tatoeba-test.tuk-eng.tuk.eng 	| 19.4 	| 0.402 |
| Tatoeba-test.tuk-tat.tuk.tat 	| 4.9 	| 0.389 |
| Tatoeba-test.tuk-tur.tuk.tur 	| 14.3 	| 0.453 |
| Tatoeba-test.tur-aze.tur.aze 	| 2.0 	| 0.247 |
| Tatoeba-test.tur-bak.tur.bak 	| 7.8 	| 0.319 |
| Tatoeba-test.tur-chg.tur.chg 	| 1.1 	| 0.062 |
| Tatoeba-test.tur-chv.tur.chv 	| 7.2 	| 0.349 |
| Tatoeba-test.tur-crh.tur.crh 	| 8.1 	| 0.366 |
| Tatoeba-test.tur-eng.tur.eng 	| 36.0 	| 0.544 |
| Tatoeba-test.tur-gag.tur.gag 	| 6.1 	| 0.331 |
| Tatoeba-test.tur-kaa.tur.kaa 	| 16.0 	| 0.215 |
| Tatoeba-test.tur-kaz.tur.kaz 	| 10.2 	| 0.198 |
| Tatoeba-test.tur-kir.tur.kir 	| 13.6 	| 0.509 |
| Tatoeba-test.tur-kjh.tur.kjh 	| 10.7 	| 0.013 |
| Tatoeba-test.tur-krc.tur.krc 	| 16.0 	| 0.013 |
| Tatoeba-test.tur-kum.tur.kum 	| 9.5 	| 0.011 |
| Tatoeba-test.tur-nog.tur.nog 	| 4.6 	| 0.010 |
| Tatoeba-test.tur-ota.tur.ota 	| 1.1 	| 0.125 |
| Tatoeba-test.tur-sah.tur.sah 	| 7.3 	| 0.010 |
| Tatoeba-test.tur-tat.tur.tat 	| 10.4 	| 0.344 |
| Tatoeba-test.tur-tuk.tur.tuk 	| 21.2 	| 0.568 |
| Tatoeba-test.tur-tyv.tur.tyv 	| 13.1 	| 0.288 |
| Tatoeba-test.tur-uig.tur.uig 	| 0.2 	| 0.164 |
| Tatoeba-test.tur-uzb.tur.uzb 	| 6.1 	| 0.346 |
| Tatoeba-test.tyv-eng.tyv.eng 	| 45.3 	| 0.603 |
| Tatoeba-test.tyv-tur.tyv.tur 	| 32.5 	| 0.402 |
| Tatoeba-test.uig-eng.uig.eng 	| 8.3 	| 0.245 |
| Tatoeba-test.uig-tur.uig.tur 	| 5.9 	| 0.261 |
| Tatoeba-test.uig-uzb.uig.uzb 	| 16.0 	| 0.193 |
| Tatoeba-test.uzb-bak.uzb.bak 	| 0.0 	| 0.022 |
| Tatoeba-test.uzb-eng.uzb.eng 	| 20.6 	| 0.357 |
| Tatoeba-test.uzb-kaz.uzb.kaz 	| 12.4 	| 0.184 |
| Tatoeba-test.uzb-tat.uzb.tat 	| 19.5 	| 0.298 |
| Tatoeba-test.uzb-tur.uzb.tur 	| 19.2 	| 0.414 |
| Tatoeba-test.uzb-uig.uzb.uig 	| 12.7 	| 0.264 |
| Tatoeba-test.xal-eng.xal.eng 	| 2.3 	| 0.147 |
