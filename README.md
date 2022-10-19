## Ноутбуки

1. [Подготовка файлов](https://colab.research.google.com/drive/1b1U4_8BizBDIXszYqOS-CiDywTZlqGqC?usp=sharing)
2. [Основная часть](https://colab.research.google.com/drive/1_onBKGVA-vxr_bVNPMbhCpEaduEElR18?usp=sharing)
3. [Бонусная часть](https://colab.research.google.com/drive/1HTyMjCHr9lB9RnQ2vH89pRGvbMRNnWWY?usp=sharing)

## Результаты

* Всего предсказано геномов: 3569
* Из них удалось аннотировать 3280 с помощью сравнения с бактерией MIL-1
* С помощью БД SwissProt: 53
* Итого осталось без аннотации: 236

#### Процент сходства между рибосомальными рнк
```
# BLASTN 2.6.0+
# Query: TOL_0319 16S ribosomal RNA
# Database: User specified sequence set (Input: scaffolds.fasta)
# Fields: query acc.ver, subject acc.ver, % identity, alignment length, mismatches, gap opens, q. start, q. end, s. start, s. end, evalue, bit score
# 2 hits found
TOL_0319	scaffold31_len1399_cov590_single	100.000	1399	0	0	134	1532	1399	1	0.0	2584
TOL_0319	scaffold2_len3831086_cov231	100.000	64	0	0	1	64	2173101	2173038	7.15e-27	119
# BLASTN 2.6.0+
# Query: TOL_0322 23S ribosomal RNA
# Database: User specified sequence set (Input: scaffolds.fasta)
# Fields: query acc.ver, subject acc.ver, % identity, alignment length, mismatches, gap opens, q. start, q. end, s. start, s. end, evalue, bit score
# 3 hits found
TOL_0322	scaffold34_len1815_cov590_single	100.000	1535	0	0	1353	2887	1815	281	0.0	2835
TOL_0322	scaffold38_len1051_cov598_single	100.000	1051	0	0	215	1265	1051	1	0.0	1941
TOL_0322	scaffold49_len223_cov624_single	100.000	127	0	0	1	127	127	1	1.28e-61	235
# BLASTN 2.6.0+
# Query: TOL_0323 5S ribosomal RNA
# Database: User specified sequence set (Input: scaffolds.fasta)
# Fields: query acc.ver, subject acc.ver, % identity, alignment length, mismatches, gap opens, q. start, q. end, s. start, s. end, evalue, bit score
# 4 hits found
TOL_0323	scaffold34_len1815_cov590_single	100.000	99	0	0	1	99	99	1	1.58e-47	183
TOL_0323	scaffold2_len3831086_cov231	100.000	60	0	0	57	116	2172930	2172871	7.58e-26	111
TOL_0323	scaffold2_len3831086_cov231	100.000	34	0	0	83	116	1328980	1328947	2.15e-11	63.9
TOL_0323	scaffold2_len3831086_cov231	100.000	34	0	0	83	116	2991451	2991484	2.15e-11	63.9
# BLASTN 2.6.0+
# Query: TOL_2453 5S ribosomal RNA
# Database: User specified sequence set (Input: scaffolds.fasta)
# Fields: query acc.ver, subject acc.ver, % identity, alignment length, mismatches, gap opens, q. start, q. end, s. start, s. end, evalue, bit score
# 2 hits found
TOL_2453	scaffold34_len1815_cov590_single	98.990	99	1	0	1	99	99	1	7.36e-46	178
TOL_2453	scaffold2_len3831086_cov231	96.667	60	2	0	57	116	2172930	2172871	1.64e-22	100
# BLASTN 2.6.0+
# Query: TOL_2454 23S ribosomal RNA
# Database: User specified sequence set (Input: scaffolds.fasta)
# Fields: query acc.ver, subject acc.ver, % identity, alignment length, mismatches, gap opens, q. start, q. end, s. start, s. end, evalue, bit score
# 3 hits found
TOL_2454	scaffold34_len1815_cov590_single	100.000	1535	0	0	1353	2887	1815	281	0.0	2835
TOL_2454	scaffold38_len1051_cov598_single	100.000	1051	0	0	215	1265	1051	1	0.0	1941
TOL_2454	scaffold49_len223_cov624_single	100.000	127	0	0	1	127	127	1	1.28e-61	235
# BLASTN 2.6.0+
# Query: TOL_2455 16S ribosomal RNA
# Database: User specified sequence set (Input: scaffolds.fasta)
# Fields: query acc.ver, subject acc.ver, % identity, alignment length, mismatches, gap opens, q. start, q. end, s. start, s. end, evalue, bit score
# 2 hits found
TOL_2455	scaffold31_len1399_cov590_single	99.929	1399	1	0	134	1532	1399	1	0.0	2579
TOL_2455	scaffold2_len3831086_cov231	100.000	64	0	0	1	64	2173101	2173038	7.15e-27	119
# BLASTN 2.6.0+
# Query: TOL_3250 5S ribosomal RNA
# Database: User specified sequence set (Input: scaffolds.fasta)
# Fields: query acc.ver, subject acc.ver, % identity, alignment length, mismatches, gap opens, q. start, q. end, s. start, s. end, evalue, bit score
# 4 hits found
TOL_3250	scaffold34_len1815_cov590_single	100.000	99	0	0	1	99	99	1	1.58e-47	183
TOL_3250	scaffold2_len3831086_cov231	100.000	60	0	0	57	116	2172930	2172871	7.58e-26	111
TOL_3250	scaffold2_len3831086_cov231	100.000	34	0	0	83	116	1328980	1328947	2.15e-11	63.9
TOL_3250	scaffold2_len3831086_cov231	100.000	34	0	0	83	116	2991451	2991484	2.15e-11	63.9
# BLASTN 2.6.0+
# Query: TOL_3251 23S ribosomal RNA
# Database: User specified sequence set (Input: scaffolds.fasta)
# Fields: query acc.ver, subject acc.ver, % identity, alignment length, mismatches, gap opens, q. start, q. end, s. start, s. end, evalue, bit score
# 3 hits found
TOL_3251	scaffold34_len1815_cov590_single	100.000	1535	0	0	1353	2887	1815	281	0.0	2835
TOL_3251	scaffold38_len1051_cov598_single	100.000	1051	0	0	215	1265	1051	1	0.0	1941
TOL_3251	scaffold49_len223_cov624_single	100.000	127	0	0	1	127	127	1	1.28e-61	235
# BLASTN 2.6.0+
# Query: TOL_3252 16S ribosomal RNA
# Database: User specified sequence set (Input: scaffolds.fasta)
# Fields: query acc.ver, subject acc.ver, % identity, alignment length, mismatches, gap opens, q. start, q. end, s. start, s. end, evalue, bit score
# 2 hits found
TOL_3252	scaffold31_len1399_cov590_single	99.929	1399	1	0	134	1532	1399	1	0.0	2579
TOL_3252	scaffold2_len3831086_cov231	100.000	64	0	0	1	64	2173101	2173038	7.15e-27	119
# BLASTN 2.6.0+
# Query: TOL_3253 5S ribosomal RNA
# Database: User specified sequence set (Input: scaffolds.fasta)
# Fields: query acc.ver, subject acc.ver, % identity, alignment length, mismatches, gap opens, q. start, q. end, s. start, s. end, evalue, bit score
# 4 hits found
TOL_3253	scaffold34_len1815_cov590_single	100.000	99	0	0	1	99	99	1	1.58e-47	183
TOL_3253	scaffold2_len3831086_cov231	100.000	60	0	0	57	116	2172930	2172871	7.58e-26	111
TOL_3253	scaffold2_len3831086_cov231	100.000	34	0	0	83	116	1328980	1328947	2.15e-11	63.9
TOL_3253	scaffold2_len3831086_cov231	100.000	34	0	0	83	116	2991451	2991484	2.15e-11	63.9
# BLASTN 2.6.0+
# Query: TOL_3254 23S ribosomal RNA
# Database: User specified sequence set (Input: scaffolds.fasta)
# Fields: query acc.ver, subject acc.ver, % identity, alignment length, mismatches, gap opens, q. start, q. end, s. start, s. end, evalue, bit score
# 3 hits found
TOL_3254	scaffold34_len1815_cov590_single	100.000	1535	0	0	1353	2887	1815	281	0.0	2835
TOL_3254	scaffold38_len1051_cov598_single	100.000	1051	0	0	215	1265	1051	1	0.0	1941
TOL_3254	scaffold49_len223_cov624_single	100.000	127	0	0	1	127	127	1	1.28e-61	235
# BLASTN 2.6.0+
# Query: TOL_3255 16S ribosomal RNA
# Database: User specified sequence set (Input: scaffolds.fasta)
# Fields: query acc.ver, subject acc.ver, % identity, alignment length, mismatches, gap opens, q. start, q. end, s. start, s. end, evalue, bit score
# 2 hits found
TOL_3255	scaffold31_len1399_cov590_single	99.929	1399	1	0	134	1532	1399	1	0.0	2579
TOL_3255	scaffold2_len3831086_cov231	100.000	64	0	0	1	64	2173101	2173038	7.15e-27	119
# BLAST processed 12 queries
```
