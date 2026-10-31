# Cashplannr: juridische documenten

Publieke, geversioneerde teksten van de contractdocumenten van Cashplannr BV
(Zeitje 5, 9681 Maarkedal, KBO 0741.779.289):

| Document | Map | Op de website |
| :- | :- | :- |
| Algemene voorwaarden (SaaS en implementatie) | `terms/` | [cashplannr.com/voorwaarden](https://cashplannr.com/voorwaarden) |
| Verwerkersovereenkomst (artikel 28 AVG) | `dpa/` | [cashplannr.com/verwerkersovereenkomst](https://cashplannr.com/verwerkersovereenkomst) |

## Structuur

Eén bestand per document, taal en versie:

```
<document>/<taal>/<YYYY-MM-DD>.md
```

- De datum in de bestandsnaam is de versie. De nieuwste datum is de geldende versie.
- Een gepubliceerde versie wordt nooit meer gewijzigd. Een nieuwe tekst krijgt een nieuw bestand met een nieuwe datum, zodat elke ondertekende versie terug te vinden blijft. Gebruik de git-historiek of een diff tussen twee bestanden om te zien wat er veranderde.
- Elke versie heeft een tag `<document>-<YYYY-MM-DD>`, bijvoorbeeld `terms-2026-10-30`.
- `nl` is de bindende tekst. `fr` en `en` zijn vertalingen; bij verschil heeft de Nederlandse tekst voorrang.
- Elke versie staat ook op de website, op `<pagina>/<YYYY-MM-DD>`, bijvoorbeeld [cashplannr.com/voorwaarden/2026-10-30](https://cashplannr.com/voorwaarden/2026-10-30).

## English

Public, versioned texts of Cashplannr's general terms and conditions (`terms/`) and data processing agreement (`dpa/`). One file per document, language and version (`<document>/<language>/<YYYY-MM-DD>.md`); published versions are never edited. The Dutch text (`nl`) is binding; `fr` and `en` are translations.

## Français

Textes publics et versionnés des conditions générales (`terms/`) et de l'accord de sous-traitance (`dpa/`) de Cashplannr. Un fichier par document, langue et version (`<document>/<langue>/<AAAA-MM-JJ>.md`) ; une version publiée n'est jamais modifiée. Le texte néerlandais (`nl`) fait foi ; `fr` et `en` sont des traductions.

## Contact

Vragen over deze documenten: hello@cashplannr.com.
