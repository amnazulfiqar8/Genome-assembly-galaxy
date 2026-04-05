# Genome-assembly-galaxy
# Vertebrate Genome Assembly using HiFi and Hi-C Data (Galaxy)

## Step 1: Opening Galaxy Platform

The Galaxy platform was accessed through a web browser to perform genome assembly analysis. It provides an interactive environment for bioinformatics workflows.

## Step 2: Opening Upload Tool

The upload tool was opened by clicking the **Upload Data** button in Galaxy. This allows importing datasets into the workspace.

## Step 3: Importing HiFi Data using URLs

HiFi sequencing datasets were imported by pasting Zenodo URLs using the **Paste/Fetch Data** option. This avoids manual downloading.

## Step 4: Setting Datatype for HiFi Data

The datatype was set to **fasta** to ensure proper reading of HiFi sequences by Galaxy tools.

## Step 5: Uploading HiFi Data

The upload process was started, and datasets were fetched into Galaxy. Successful uploads are indicated by green status in the history panel.

## Step 6: Uploading Hi-C Data

Hi-C paired-end datasets were uploaded similarly. The datatype was set to **fastqsanger.gz**, which is required for correct processing.

## Step 7: Renaming Datasets

Datasets were renamed to meaningful names for easy identification during later steps.

## Step 8: Verifying Data in History

All uploaded datasets appeared in the history panel, confirming successful data import.

## Step 9: Selecting Assembly Tool

The genome assembly tool (hifiasm) was selected from the Galaxy tool panel.

## Step 10: Configuring Assembly Tool

HiFi datasets were selected as input, and default parameters were used for assembly.

## Step 11: Running Assembly

The tool was executed, and Galaxy processed the data to generate genome contigs.

## Step 12: Viewing Assembly Output

The output contigs were generated and displayed in the history panel.

## Step 13: Selecting Scaffolding Tool

A Hi-C scaffolding tool was selected to organize contigs into larger structures.

## Step 14: Configuring Scaffolding Inputs

Hi-C forward and reverse reads along with assembled contigs were selected as input.

## Step 15: Running Scaffolding

The scaffolding process was executed to arrange contigs using Hi-C interaction data.

## Step 16: Viewing Scaffolded Output

The output showed scaffolded genome sequences representing chromosome-level organization.

## Step 17: Running Quality Assessment

Quality assessment tools (such as QUAST or BUSCO) were used to evaluate assembly accuracy

## Step 18: Analyzing Quality Metrics

Important metrics such as N50, completeness, and genome size were analyzed to assess assembly quality.

## Step 19: Final Genome Assembly Output

The final assembled genome represents the complete workflow result, combining assembly and scaffolding steps.

## Conclusion

This workflow demonstrates genome assembly using HiFi sequencing and Hi-C data on the Galaxy platform. The process includes data upload, assembly, scaffolding, and quality assessment, resulting in a high-quality genome assembly.

---
