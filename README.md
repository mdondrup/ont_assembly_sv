# ont_assembly_sv

Workflow used for assembly and structural variant calling of ONT data.

Uses Flye for assembly, pilon for polishing with Illumina reads and RagTag for scaffolding.
In additon, runs Quast and Busco for QC of assemblies.

Structural variants are called with CombiSV based on all recommended variant callers. 
Dependencies are installed via conda environments.
