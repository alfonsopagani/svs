# Codici

Script MATLAB e notebook Wolfram Mathematica per esempi numerici e analisi di problemi di dinamica strutturale, stabilità e meccanismi spaziali.

I modelli includono sistemi discreti a più gradi di libertà, modelli strutturali semplificati e formulazioni non lineari.

## [vibroacoustics.m](vibroacoustics.m)

Capitolo 2, [slides/svs_02_dinamica_1gdl.pdf](../slides/svs_02_dinamica_1gdl.pdf).

Modello a singolo grado di libertà di una piastra con massa fittizia soggetta a carichi acustici. Assegnato il livello di pressione sonora (SPL) del lanciatore, calcola:
- densità spettrale di potenza della pressione;
- funzione di trasferimento;
- PSD dell'accelerazione della massa fittizia;
- PSD dello spostamento;
- valori RMS.

## [launcher.m](launcher.m)

Capitolo 3, [slides/svs_03_dinamica_mgdl.pdf](../slides/svs_03_dinamica_mgdl.pdf).

Per un sistema payload-lanciatore a 4 gradi di libertà, calcola:
- forme modali e frequenze naturali;
- risposta dinamica;
- masse modali efficaci e fattori di partecipazione modale;
- contributo di ciascun modo alla risposta.

## [guyan.m](guyan.m)

Capitolo 4, [slides/svs_04_dinamica_substructuring.pdf](../slides/svs_04_dinamica_substructuring.pdf).

Per un sistema payload-lanciatore a 10 gradi di libertà, calcola:
- forme modali e frequenze naturali;
- matrici generalizzate di massa e rigidezza;
- condensazione statica (riduzione di Guyan);
- matrici ridotte di massa e rigidezza;
- MAC e COC.

## [effmasses.m](effmasses.m)*

Esempio aggiuntivo del Capitolo 4, crediti: [@PieroChiaia](https://github.com/PieroChiaia).

Per lo stesso modello a 10 gradi di libertà dell'esempio precedente, calcola:
- animazioni delle forme modali;
- matrici generalizzate di massa e rigidezza;
- fattori di partecipazione;
- masse modali efficaci.

\*Per eseguire lo script è necessaria la funzione [animate.m](animate.m).

## [buckling.m](buckling.m)

Capitoli 10-12, [slides/](../slides/) & Sezioni 13.1.2 e 13.1.3 di [book/svsbook.pdf](../book/svsbook.pdf)

Per una colonna soggetta a compressione, calcola:
- i primi tre carichi critici di instabilità;
- le prime tre forme modali di buckling.

## [postbuckling.m](postbuckling.m)

Per lo stesso problema precedente, calcola:
- la curva di equilibrio in campo post-critico;
- il confronto con la soluzione linearizzata.

## [elastica.nb](elastica.nb)

Notebook Wolfram Mathematica. Ripropone lo stesso esercizio di [postbuckling.m](postbuckling.m).

## [pendulum.nb](pendulum.nb)

Appendice C di [book/svsbook.pdf](../book/svsbook.pdf).

Notebook Wolfram Mathematica relativo al pendolo non lineare e alla sua analogia con la soluzione dell'elastica.

## [solararray.m](solararray.m)

Capitolo 12, [slides/svs_12_esempi_nonlineari.pdf](../slides/svs_12_esempi_nonlineari.pdf).

Analisi cinematica di un sistema multibody rappresentativo di un pannello solare dispiegabile. Fornisce:
- animazione delle configurazioni durante il dispiegamento;
- cinematica e meccanica di attuazione.

## [tapedeploy.nb](tapedeploy.nb)

Capitolo 12, [slides/svs_12_esempi_nonlineari.pdf](../slides/svs_12_esempi_nonlineari.pdf) & Sezione 13.3 di [book/svsbook.pdf](../book/svsbook.pdf).

Notebook Wolfram Mathematica per l'analisi del dispiegamento a singolo grado di libertà di una tape spring. Fornisce
- formulazione completa del modello di anello circolare in espansione non vincolato;
- effetti della dissipazione e della gravità;
- velocità e dinamica di dispiegamento;
- confronto con risultati sperimentali.
