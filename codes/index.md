---
layout: default
title: Codici
---

# Codici

Script MATLAB e notebook Wolfram Mathematica per esempi numerici e analisi di problemi di dinamica strutturale, stabilità e meccanismi spaziali.

I modelli includono sistemi discreti a più gradi di libertà, modelli strutturali semplificati e formulazioni non lineari.

## <a href="vibroacoustics.m" target="_blank" rel="noopener">vibroacoustics.m</a>

Capitolo 2, <a href="../slides/svs_02_dinamica_1gdl.pdf" target="_blank" rel="noopener">slide sulla dinamica a 1 GDL</a>.

Modello a singolo grado di libertà di una piastra con massa fittizia soggetta a carichi acustici. Assegnato il livello di pressione sonora (SPL) del lanciatore, calcola:

- densità spettrale di potenza della pressione;
- funzione di trasferimento;
- PSD dell'accelerazione della massa fittizia;
- PSD dello spostamento;
- valori RMS.

## <a href="launcher.m" target="_blank" rel="noopener">launcher.m</a>

Capitolo 3, <a href="../slides/svs_03_dinamica_mgdl.pdf" target="_blank" rel="noopener">slide sulla dinamica a più GDL</a>.

Per un sistema payload-lanciatore a 4 gradi di libertà, calcola:

- forme modali e frequenze naturali;
- risposta dinamica;
- masse modali efficaci e fattori di partecipazione modale;
- contributo di ciascun modo alla risposta.

## <a href="guyan.m" target="_blank" rel="noopener">guyan.m</a>

Capitolo 4, <a href="../slides/svs_04_dinamica_substructuring.pdf" target="_blank" rel="noopener">slide sul substructuring dinamico</a>.

Per un sistema payload-lanciatore a 10 gradi di libertà, calcola:

- forme modali e frequenze naturali;
- matrici generalizzate di massa e rigidezza;
- condensazione statica (riduzione di Guyan);
- matrici ridotte di massa e rigidezza;
- MAC e COC.

## <a href="effmasses.m" target="_blank" rel="noopener">effmasses.m</a>*

Esempio aggiuntivo del Capitolo 4, crediti: <a href="https://github.com/PieroChiaia" target="_blank" rel="noopener">@PieroChiaia</a>.

Per lo stesso modello a 10 gradi di libertà dell'esempio precedente, calcola:

- animazioni delle forme modali;
- matrici generalizzate di massa e rigidezza;
- fattori di partecipazione;
- masse modali efficaci.

\*Per eseguire lo script è necessaria la funzione <a href="animate.m" target="_blank" rel="noopener">animate.m</a>.

## <a href="buckling.m" target="_blank" rel="noopener">buckling.m</a>

Capitoli 10-12, <a href="../slides/" target="_blank" rel="noopener">slide del corso</a>, e Sezioni 13.1.2 e 13.1.3 degli <a href="../book/svsbook.pdf" target="_blank" rel="noopener">appunti del corso</a>.

Per una colonna soggetta a compressione, calcola:

- i primi tre carichi critici di instabilità;
- le prime tre forme modali di buckling.

## <a href="postbuckling.m" target="_blank" rel="noopener">postbuckling.m</a>

Per lo stesso problema precedente, calcola:

- la curva di equilibrio in campo post-critico;
- il confronto con la soluzione linearizzata.

## <a href="elastica.nb" target="_blank" rel="noopener">elastica.nb</a>

Notebook Wolfram Mathematica. Ripropone lo stesso esercizio di <a href="postbuckling.m" target="_blank" rel="noopener">postbuckling.m</a>.

## <a href="pendulum.nb" target="_blank" rel="noopener">pendulum.nb</a>

Appendice C degli <a href="../book/svsbook.pdf" target="_blank" rel="noopener">appunti del corso</a>.

Notebook Wolfram Mathematica relativo al pendolo non lineare e alla sua analogia con la soluzione dell'elastica.

## <a href="solararray.m" target="_blank" rel="noopener">solararray.m</a>

Capitolo 12, <a href="../slides/svs_12_esempi_nonlineari.pdf" target="_blank" rel="noopener">slide sugli esempi non lineari</a>.

Analisi cinematica di un sistema multibody rappresentativo di un pannello solare dispiegabile. Fornisce:

- animazione delle configurazioni durante il dispiegamento;
- cinematica e meccanica di attuazione.

## <a href="tapedeploy.nb" target="_blank" rel="noopener">tapedeploy.nb</a>

Capitolo 12, <a href="../slides/svs_12_esempi_nonlineari.pdf" target="_blank" rel="noopener">slide sugli esempi non lineari</a>, e Sezione 13.3 degli <a href="../book/svsbook.pdf" target="_blank" rel="noopener">appunti del corso</a>.

Notebook Wolfram Mathematica per l'analisi del dispiegamento a singolo grado di libertà di una tape spring. Fornisce:

- formulazione completa del modello di anello circolare in espansione non vincolato;
- effetti della dissipazione e della gravità;
- velocità e dinamica di dispiegamento;
- confronto con risultati sperimentali.

---

[← Torna alla pagina principale](../)
