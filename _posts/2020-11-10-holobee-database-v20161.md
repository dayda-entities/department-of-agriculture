---
title: HoloBee Database v2016.1
created: '2020-11-10T16:26:50.484498'
modified: '2020-11-10T16:26:50.484505'
state: active
type: dataset
tags:
  - Apis Andreniformis
  - Apis Cerana
  - Apis Dorsata
  - Apis Florea
  - Apis Koschevnikovi
  - Apis Laboriosa
  - Apis Nigrocincta
  - Bacteria
  - Data Collection
  - Fungi
  - Genome Sequences
  - Invasive Species
  - Metagenomics
  - Microbiota
  - Mitochondrial Dna
  - National Center For Biotechnology Information
  - Np305
  - Parasites
  - Pathogens
  - Protozoa
  - Quality Control
  - Ribosomal Rna
  - Transcriptome
  - Viruses
groups: []
csv_url: 'https://data.nal.usda.gov/system/files/Data_Dictionary_HoloBee_v2016.1.csv'
json_url: ''
layout: post

---
<p>Organisms living in honey bees and honey bee colonies form large associative holobiont communities that are integral to bee biology.  High-throughput sequencing approaches to characterize these holobiont communities from honey bees in various states of health and disease are now commonplace, producing large amounts of nucleotide sequence data that must be accurately and consistently analyzed in order to produce reliable and comparable reports.  In addition, new species designations and revisions are actively being made from honey bee holobiont communities, complicating nomenclature in larger databases where taxonomic descriptions associated with archived sequences can quickly become outdated and misleading.</p>
<p>To improve the accuracy and consistency of honey bee holobiont research, we have developed HoloBee: a curated database of publicly accessioned nucleotide sequences from the honey bee holobiont community.  Except in rare and noted exceptions made by curators, sequences used in HoloBee were obtained from, or in association with, <em>Apis mellifera</em> (Western honey bee) as well as other honey bee species where available (e.g. <em>Apis cerana</em>, <em>Apis dorsata</em>, <em>Apis laboriosa</em>, <em>Apis koschevnikovi</em>, <em>Apis florea</em>, <em>Apis andreniformis</em> and <em>Apis nigrocincta</em>).  Sources include:  within or on the surface of honey bees (adult, pupae, larvae, egg), corbicular pollen, bee bread, royal jelly, honey, comb, hive surfaces (e.g. bottom board debris, frames, landing platforms), and isolates of microbes, parasites and pathogens from honey bees.  HoloBee contains two non-overlapping sets of sequence data, HoloBee-Barcode and HoloBee-Mop, each of which have distinct intended uses.</p>
<p><strong>HoloBee-Barcode</strong> is a non-redundant database of taxonomically informative barcoding loci for all viruses, bacteria, fungi, protozoans and metazoans associated with honey bees (<em>Apis</em> spp.).  It was created from an exhaustive master sequence archive of all valid holobiont sequences.  Redundancy was removed from this master archive using a clustering algorithm that grouped sequences with ≥ 99% identity and retained the longest sequence from each cluster as the representative accession for that sequence type (“centroid”).  These centroid sequences were concatenated into a fasta formatted file to create the HoloBee-Barcode database.  Associated taxonomy for each centroid, including Superkingdom through Species and Strain/Isolate, was individually reviewed and corrected when necessary by a curator.  Cross reference tables (separated according to 5 major taxonomic groups) provide a user-friendly outline of information for each centroid accession within HoloBee-Barcode including taxonomy, gene/product name, sequence length, the unaltered NCBI definition line, the number and identity of redundant sequences clustered within each centroid, and any additional information provided by the curator.  HoloBee-Barcode centroid counts are: Viruses = 86; Bacteria = 496; Fungi = 41; Protozoa = 4; Metazoa = 60.</p>
<p>HoloBee-Barcode is intended to improve and standardize quantitative and qualitative metagenomic descriptions of holobiont communities associated with honey bees by providing a curated set of barcode sequences.  The goal of genetic barcoding is to associate a nucleotide sequence sample to a taxonomically valid species.  Genomic regions targeted for such barcoding purposes varied by taxonomic group.  The small subunit (SSU) ribosomal RNA, or 16S rRNA, is the most commonly used barcode for bacteria and is used in HB-Barcode.  These 16S rRNA sequences will support the analysis of data generated with the widely used approach of amplicon-based 16S rRNA deep sequencing to study microbiota communities.  Although barcode markers for fungi are less definitive than bacteria, HB-Barcode defaults to the ribosomal RNA internal transcribed spacer region (ITS), which typically includes ITS-1, 5.8S, and ITS-2.  For some clades that cannot be resolved by this region, other barcode markers were selected.  The majority of barcodes for metazoan taxa are the mitochondrial locus cytochrome c oxidase subunit I (COI).  Complete mitochondrial DNA (mtDNA) sequence for <em>Apis cerana</em> (Asian honey bee) and <em>Galleria mellonella</em> (Greater wax moth) are included as barcodes for these species.  We note that <em>A. cerana</em> mtDNA is included because it is considered a potentially invasive honey bee species and monitoring for its occurrence is in practice regionally, including in Australia, New Zealand and the USA.  Protozoan barcodes include cytochrome b oxidase (Cytb), SSU, or ITS while entire genomes are used for viral barcoding.</p>
<p><strong>HoloBee-Mop</strong> is a database comprised mostly of chromosomal, mitochondrial and plasmid genome assemblies in order to aggregate as much honey bee holobiont genomic sequence information as possible.  For a few organisms without genome assembly data, transcriptome data are included (e.g. <em>Aethina tumida</em>, small hive beetle).  Unlike HoloBee-Barcode, redundancy removal was not performed on the HoloBee-Mop database and thus this resource provides an archive of nucleotide sequence assemblies from honey bee holobionts.  However, since full viral genomes are used in HoloBee-Barcode, only redundant viral sequences occur in HoloBee-Mop.  All accessions within each of these assemblies were concatenated into a single fasta formatted file to create the HoloBee-Mop database.  The intended purpose of HoloBee-Mop is to improve honey bee genome and transcriptome assemblies by “mopping-up” as much viral, bacterial, fungal, protozoan and non-honey bee metazoan sequence data as possible.  Therefore, sequence data remaining after processing reads through both HoloBee-Barcode and HoloBee-Mop that do not map to the honey bee genome may contain unique data from taxonomic variants or novel species.  Details for each sequence assembly within HoloBee-Mop are tabulated in cross reference tables according to each major taxonomic group.  HoloBee-Mop assembly counts are: Viruses = 2; Bacteria = 55; Fungi = 5; Protozoa = 1; Metazoa = 6.</p>
<p>Follow the HoloBee database on Twitter at: <a href="https://twitter.com/HoloBee_db">https://twitter.com/HoloBee_db</a></p>

