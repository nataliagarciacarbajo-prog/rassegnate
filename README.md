# Rassegnate

Dati della rassegna quotidiana Big Tech & Finanza di Natàlia, aggiornati ogni mattina dopo le 6:48 (ora italiana).

- `rassegna.json`: la rassegna di oggi, letta dal riquadro in home su nataliagarciacarbajo.com
  (URL: https://raw.githubusercontent.com/nataliagarciacarbajo-prog/rassegnate/main/rassegna.json)
- `archivio/AAAA-MM-GG.json`: le rassegne dei giorni precedenti, stesso formato

## Formato

```
data, data_estesa, aggiornato_il, titolo
notizie[]: posizione, titolo, riassunto, il_senso, fonti[] { nome, url }
approfondimenti[]: titolo, testata, url, perche_e_importante, la_mia_lettura
da_tenere_d_occhio
```
