# Variant Pathogenecity Evaluation

## Definitions

<dl>
<dt>Mutation</dt>
<dd>Any permatent change in nucleotide sequence</dd>
<dt>Polymorphism</dt>
<dd>Variant with Frequency above 1%</dd>
</dl>

Not recommended by ACMG, use **Variant** including one of following modifiers:

1. pathogenic
2. likely pathogenic
3. uncertain significance
4. likely benign
5. benign

## Criteria

Numbering does not convery any order inside an evidence level.

### Pathogenic Variants

| | Evidence | Criteria | Caveats | 
| - | - | - | - |
| PVS1 | very strong | LOF known MOD | exon-skipping, extreme 3', multiple transcripts |
| PS1 | strong |  same AA change as previously described PV | splicing changes |
| PS2 | strong | confirmed de novo | maternity/paternity need to be confirmed |
| PS3 | strong | functional studies | |
| PS4 | strong | significant prevalence in affected (RR/OR > 5.0, 95% CI > 1.0) | |
| PM1 | moderate | location in mutation hotspot/functional domain without benign variants | |
| PM2 | moderate | absent in controls | poor calling of indels in NGS |
| PM3 | moderate | recessive in trans | requires parents to determine phase |
| PM4 | moderate | in-frame protein length changes in non-repeat region incl stop-loss | |
| PM5 | moderate | novel AA change, with previous PV with different AA | splicing changes |
| PM6 | moderate | unconfirmed de-novo | |
| PP1 | supporting | co-segregation in known disease gene | |
| PP2 | supporting | Missense in low-rate missense gene and as common MOD | |
| PP3 | supporting | computational evidence | can only be used once |
| PP4 | supporting | highly specific phenotype | |
| PP5 | supporting | reported pathogenic without laboratory evaluation | |

### Benign Variants



### Combination of Scoring rules

```
pathogenic =
    1. (1 PVS && (1 PS || 2 PM || (1 PM && 1 PP) || 2 PP))
    2. 2 PS
    3. 1 PS && (3 PM || 2 PM && 2 PP || 1 PM && 4 PP)
likely pathogenic =
    1. 1 PVS && 1 PM
    2. 1 PS && 1-2 PM
    3. 1 PS && 2 PP
    4. 3 PM
    5. 2 PM && 2 PP
    6. 1 PM && 4 PP
benign =
    1. 1 BA1
    2. 2 BS
likely benign =

```

## Literature

[ACGS Best Practice Guidelines 2020](https://www.acgs.uk.com/media/11631/uk-practice-guidelines-for-variant-classification-v4-01-2020.pdf)

- Recommendation on Variant Interpration by ACGS in UK

[Standards and Guidelines for the Interpretation of Sequence Variants](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4544753/)

- Results from a workgroup on variant classification by ACMG, AMP and CAP from 2015.