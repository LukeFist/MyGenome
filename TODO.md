# MyGenome Notebook — Outstanding TODOs

Every `<!-- INSERT ... -->` placeholder in `README.md` and the `*_commands.md` files maps to one entry below. Check the box once the placeholder is filled.

---

## Images / Screenshots

- [ ] **§6.4 IGV — gene predicted only by SNAP**: capture screenshot, record `contig:start-end`, save to `./Gene Prediction/igv/snap_only.png`
- [ ] **§6.4 IGV — gene predicted only by AUGUSTUS**: capture screenshot, record `contig:start-end`, save to `./Gene Prediction/igv/augustus_only.png`
- [ ] **§6.4 IGV — SNAP + AUGUSTUS same exon/intron structure**: capture screenshot, record `contig:start-end`, save to `./Gene Prediction/igv/snap_augustus_same.png`
- [ ] **§6.4 IGV — SNAP + AUGUSTUS different exon/intron structure**: capture screenshot, record `contig:start-end`, save to `./Gene Prediction/igv/snap_augustus_different.png`
- [ ] **§6.4 IGV — SNAP + AUGUSTUS + MAKER + external evidence**: capture screenshot, record `contig:start-end`, save to `./Gene Prediction/igv/snap_augustus_maker_evidence.png`
- [ ] **§7.4 IGV — largest B71 unique sequence block**: capture screenshot showing coordinate boundaries, save to `./Genome Interrogation using BLAST/igv/B71_unique_block.png`

## Numeric Results / Tables

- [ ] **§5 BUSCO**: paste `short_summary*.txt` excerpt into the `<details>` block in README §5 **and** into BUSCO commands § 3
- [ ] **§5 BUSCO**: paste sample `slurm-XXXXXXX.out` tail into the `<details>` block in BUSCO commands § 2
- [ ] **§6.1 SNAP**: number of predicted genes from `fathom -gene-stats` output → fill table in README §6.1 **and** paste output into Gene Prediction commands SNAP `<details>`
- [ ] **§6.2 AUGUSTUS**: number of predicted genes from GFF3 output → fill table in README §6.2 **and** paste count into Gene Prediction commands AUGUSTUS `<details>`
- [ ] **§6.3 MAKER**: gene count from `awk '$3 == "gene"' igvFiles/Eb314ss1-maker.gff3 | wc -l` → fill table in README §6.3 **and** paste into Gene Prediction commands MAKER gene-count `<details>`
- [ ] **§6.3 MAKER**: protein count from `grep -c "^>" Eb314ss1.all.maker.proteins.fasta` (must match gene count) → fill table in README §6.3 **and** paste into Gene Prediction commands MAKER protein-count `<details>`
- [ ] **§4 NCBI Post-Processing**: paste slurm output / `seqkit stats Eb314ss1_final.fasta` into the `<details>` block in Post-Processing commands § 1
- [ ] **§4 / §7.1 Mito BLAST**: paste `head -n 10 MoMitochondrion.Eb314ss1.BLAST` excerpt into Post-Processing commands § 2 `<details>`
- [ ] **§4 / §7.1 Mito CSV head**: paste `cat Eb314ss1_mitochondrion.csv` contents into Post-Processing commands § 2 `<details>`
- [ ] **§4 / §7.1 Short mito hits head**: paste `head -n 10 Eb314ss1_short_mitochondrial_hits.txt` excerpt into Post-Processing commands § 2 `<details>`

## Code Snippets / Commands

- [ ] **§2.1 Sequence Data commands**: exact `scp` command used to download raw reads from the course server (replace the `# TODO` placeholder in `Sequence Data, Quality Assessment and Trimming_commands.md` § 2.1)
- [ ] **§5 BUSCO commands**: paste contents of `BuscoSingularity.sh` (or link to a copy in the repo) into `Assess Genome Quality using BUSCO_commands.md` § 1

## Files to Upload / Link

- [ ] **§5 BUSCO**: upload `short_summary*.txt` to `./Assess Genome Quality using BUSCO/` and link from README §5 + commands file § 3
- [ ] **§7.1 Mitochondrial CSV**: upload `Eb314ss1_mitochondrion.csv` to `./Genome Post Processing for NCBI submission/` and link from README §7.1 + commands file § 2
- [ ] **§7.1 Short mito hits**: upload `Eb314ss1_short_mitochondrial_hits.txt` to `./Genome Post Processing for NCBI submission/` and link from README §7.1 + commands file § 2
- [ ] **§7.2 Contig list**: upload list of Eb314ss1 contigs lacking B71 matches (output of `grep -B 2 "0 hits found" ... | grep "Query"`) to `./Genome Interrogation using BLAST/` and link from README §7.2
- [ ] **§7.3 GFF3**: upload `B71_alignments.gff3` to `./Genome Interrogation using BLAST/` and link from README §7.3
