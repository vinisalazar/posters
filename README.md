# posters

My academic posters. Each one is deposited on the University of Melbourne figshare
repository and has its own DOI.

| Poster | Venue | Date | DOI |
|---|---|---|---|
| [nf-core/funcprofiler: standardised functional profiling of metagenomes at any scale](posters/ISME20_2026.pdf) | ISME20, 20th International Symposium on Microbial Ecology, NZICC, Auckland, New Zealand | August 2026 | [![DOI](https://img.shields.io/badge/DOI-10.26188%2F33423955-blue)](https://doi.org/10.26188/33423955) |
| [Global picoplankton biogeography revealed by metagenomic and climatic data integration](posters/ISME19_2024.pdf) | ISME19, 19th International Symposium on Microbial Ecology, Cape Town, South Africa | August 2024 | [![DOI](https://img.shields.io/badge/DOI-10.26188%2F33422692-blue)](https://doi.org/10.26188/33422692) |
| [Metaphor: facilitating the large-scale recovery of genomes from metagenomes](posters/AusME2022.pdf) | AusME 2022, Australian Microbial Ecology conference, Melbourne Connect, The University of Melbourne | November 2022 | [![DOI](https://img.shields.io/badge/DOI-10.26188%2F33422689-blue)](https://doi.org/10.26188/33422689) |
| [Knowledge Management in Genomics: The Role of Data Provenance](posters/XMeeting2019.pdf) | X-meeting 2019, 15th International Conference of the AB3C, Campos do Jordão, SP, Brazil | October 2019 | [![DOI](https://img.shields.io/badge/DOI-10.26188%2F33423958-blue)](https://doi.org/10.26188/33423958) |

## nf-core/funcprofiler: standardised functional profiling of metagenomes at any scale

[![DOI](https://img.shields.io/badge/DOI-10.26188%2F33423955-blue)](https://doi.org/10.26188/33423955)

Vinícius W. Salazar, Nicholas R. Waters, Mirae Baichoo, Yixuan Yang, Kim-Anh Lê Cao,
Julian Simmons, Gayle Philip, Bernard Pope

A community workflow for functional profiling of metagenomes: seven profilers (HUMAnN,
MetaPhlAn, eggNOG-mapper, RGI, mi-faser, FMH FunProfiler, DIAMOND) driven from a single
samplesheet, keeping native outputs rather than forcing harmonisation. Assembly-free, so
compute stays flat with sample size. Source: [nf-core/funcprofiler](https://github.com/nf-core/funcprofiler),
docs at [nf-co.re/funcprofiler](https://nf-co.re/funcprofiler). Licensed CC BY-SA 4.0.

## Global picoplankton biogeography revealed by metagenomic and climatic data integration

[![DOI](https://img.shields.io/badge/DOI-10.26188%2F33422692-blue)](https://doi.org/10.26188/33422692)

Vinícius W. Salazar, Vanessa R. Marcelino, Heroen Verbruggen, Kim-Anh Lê Cao

A model of picoplankton biogeography built by integrating 1454 metagenomes from the NCBI SRA,
15,551 reference genomes (OceanDNA, GTDB), and 10 environmental variables from Bio-ORACLE 3.
Provinces are defined from k-mer level pairwise metagenomic distances and projected across the
oceans with a random forest classifier, then characterised through taxonomic and functional
feature selection with mixOmics.

## Metaphor: facilitating the large-scale recovery of genomes from metagenomes

[![DOI](https://img.shields.io/badge/DOI-10.26188%2F33422689-blue)](https://doi.org/10.26188/33422689)

Vinícius W. Salazar, Babak Shaban, Maria Quiroga, Robert Turnbull, Edoardo Tescari,
Vanessa Rossetto Marcelino, Heroen Verbruggen, Kim-Anh Lê Cao

A general-purpose Snakemake workflow for the assembly and binning of metagenomes, combining
multiple binning programs with a refinement step and optional sample grouping for coassembly and
cobinning. Source: [vinisalazar/metaphor](https://github.com/vinisalazar/metaphor).

## Knowledge Management in Genomics: The Role of Data Provenance

[![DOI](https://img.shields.io/badge/DOI-10.26188%2F33423958-blue)](https://doi.org/10.26188/33423958)

Vinícius W. Salazar, Kary Ocaña, Fabiano L. Thompson, Marta Mattoso

Framing knowledge management in genomics through data provenance, pairing prospective provenance
(dataflow modelled as a DAG) with retrospective provenance captured at runtime in W3C PROV format.
The case study puts 167 assembled *Synechococcus* genomes through annotation and comparison with
the [Abacat](https://github.com/vinisalazar/abacat) library, leaving a queryable provenance database.

## Licence

Posters are released under [CC BY 4.0](LICENSE), except the ISME20 poster, which is CC BY-SA 4.0
as printed on the poster itself.
