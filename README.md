WGS processing pipeline for Phylogenomics and Population Genomics

Precedures:

    　　raw_reads_cleaning
    　　　　　↓
    　　　　mapping
    　　　　　↓
    　bam_nsort_dedup_csort　>　mpileup_call_joint
    　　　　　↓
    　　　bam_consensus
    　　　　　↓
    extract_regions_coordinates　<　get_coordinates_blast
     




                                      

