# 🧬 Agarwood-Associated Microbiome

**Project type:** Ongoing collaborative project  
**Approach:** Shotgun metagenomics  
**Focus:** Microbial communities associated with healthy, naturally infected, and artificially infected *Aquilaria* samples

## Research question

How does microbial taxonomic composition vary across different infection conditions associated with agarwood formation, and what functional hypotheses can be explored from microbial reference genomes?

## Computational workflow

```text
Shotgun paired-end reads
        |
        v
   MultiQC review
        |
        v
Host-read filtering (Bowtie2)
        |
        v
Taxonomic classification (Kraken2)
        |
        v
Abundance estimation (Bracken)
        |
        v
Taxonomic visualization (Krona)
        |
        v
Reference-fungal-genome CAZyme investigation
```

## Biological interpretation

Reference-genome CAZyme annotation can generate hypotheses about potential microbial capabilities related to plant cell-wall interaction. Such annotations **do not independently demonstrate** that particular enzymes were encoded, expressed, or active in the collected samples.

## Important limitations

- Results depend on read quality, reference databases, and host-read depletion.
- Infection-group comparisons require attention to replication and sample metadata.
- All project results are preliminary until scientifically checked and approved for dissemination.

## Reproducibility status

This is an overview of the computational approach, **not** a complete public pipeline or uploaded dataset. Validated scripts, figures, software versions, and permitted data references may be added later.

[← Back to profile](../README.md)
