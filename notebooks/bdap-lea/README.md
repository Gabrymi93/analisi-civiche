# bdap-lea

- **Tema**: spesa sanitaria e prevenzione collettiva nelle ASL italiane
- **Domanda**: quanto pesa la Prevenzione Collettiva e Sanita' Pubblica sul totale della spesa corrente delle ASL nel consuntivo 2024?
- **Fonte**: BDAP - Modello LEA 2024
- **Stato**: `draft`
- **Caveat principali**:
  - il consuntivo 2024 potrebbe avere dati non ancora consolidati per alcuni enti
  - la voce contabile "Prevenzione Collettiva" e' un aggregato — non include attivita' di prevenzione in altri capitoli
  - la soglia LEA del 5% e' un riferimento minimo, non un obiettivo vincolante
  - nessun aggiustamento pro-capite: un'ASL piccola puo' avere quota alta ma volume basso

## Prerequisiti

- mart `mart_spesa_enti_2024.parquet` generato dalla pipeline bdap-lea
- Path: `dataset-incubator/out/data/mart/bdap_lea/2024/mart_spesa_enti_2024.parquet`

## Contenuti

- notebook v0: incidenza % prevenzione per ASL, distribuzione, top/bottom 10
- grafico: distribuzione percentuale con soglia LEA 5% e mediana evidenziata
