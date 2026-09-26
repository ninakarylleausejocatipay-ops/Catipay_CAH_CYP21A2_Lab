# From Gene Mutation to Disease: Investigating How DNA Sequence Changes Affect Protein Products and Human Phenotypes

**Student:** Niña Karylle A. Catipay
**Subject:** Cell and Molecular Biology Laboratory  
**Disease:** Congenital Adrenal Hyperplasia (CAH)  
**Gene:** CYP21A2  

## 1. Introduction

Congenital Adrenal Hyperplasia (CAH) is a group of autosomal recessive disorders characterized by impaired adrenal steroidogenesis. The most common form, accounting for approximately 95% of CAH cases, is caused by 21-hydroxylase deficiency. This deficiency impairs the biosynthesis of cortisol and aldosterone, leading to compensatory adrenocorticotropic hormone (ACTH) hypersecretion and excessive adrenal androgen production.

The `CYP21A2` gene encodes the steroid 21-hydroxylase enzyme (a cytochrome P450 enzyme localizing to the endoplasmic reticulum), which catalyzes the 21-hydroxylation of progesterone and 17-hydroxyprogesterone. The purpose of this laboratory activity was to examine how a documented pathogenic `CYP21A2` mutation alters DNA and protein sequences and compare its molecular impact against an artificially created frameshift mutation.

## 2. Reference Sequence

The reference `CYP21A2` transcript used in this study was **NM_000500.9**, with reference protein **NP_000491.4**. The coding sequence (CDS) was retrieved from the NCBI RefSeq database.

The wild-type CDS is 1,488 bp long and produces a predicted protein of 495 amino acids. The start codon is ATG, the stop codon is TGA, and the reading frame is 1. The predicted protein sequence agreed with accepted reference records through MAFFT alignment. These baseline data serve as the standard reference for subsequent variant comparisons.

## 3. Documented Disease-Associated Mutation

The documented mutation analyzed was **NM_000500.9(CYP21A2):c.518T>A (p.Ile173Asn)**, commonly referred to as **I173N**. It is a single-nucleotide variant and missense substitution in which thymine (T) is replaced by adenine (A) at nucleotide position 518.

This variant is strongly associated with simple virilizing Congenital Adrenal Hyperplasia. The substitution of isoleucine with asparagine at position 173 reduces enzymatic activity to approximately 1%–2% of wild-type levels, disrupting normal glucocorticoid production without causing complete loss of mineralocorticoid synthesis.

## 4. Mutant Sequence and Translation

The original nucleotide at position c.518 was T, while the mutant nucleotide was A. The surrounding coding sequence changed from:

`TCCAATCAAATT`

to:

`TCCACCAAATT`

Only one nucleotide was substituted. The mutant CDS remained 1,488 bp in length, and the predicted mutant protein remained 495 amino acids long. The reading frame remained intact, and no premature stop codons were introduced.

The first amino-acid difference occurred at position 173, where isoleucine (I) was replaced by asparagine (N). No amino acids were inserted or deleted, and the downstream amino-acid sequence remained completely unchanged.

## 5. WT and I173N Protein Comparison

MAFFT alignment of the wild-type and I173N mutant proteins demonstrated that the sequences differed exclusively at amino-acid position 173. The only change was Ile → Asn at this locus.

Because the mutation is a single-nucleotide substitution, it did not alter the reading frame or overall protein length. The computational results directly support the classification of c.518T>A as a missense mutation rather than a frameshift, nonsense, or indel variant.

## 6. Molecular Consequence

The I173N substitution replaces a nonpolar, hydrophobic isoleucine with a polar, uncharged asparagine in a critical transmembrane/hydrophobic core region of the 21-hydroxylase enzyme. This alters local protein folding and stability, drastically reducing enzymatic turnover.

Impaired 21-hydroxylase activity reduces cortisol synthesis, driving excessive pituitary ACTH secretion. Accumulated precursor steroids (such as 17-hydroxyprogesterone) are shunted into the adrenal androgen pathway, causing prenatal virilization in female fetuses and progressive androgen excess postnatally.

## 7. Artificial Mutation

An artificial mutation was created by deleting one nucleotide (T) at position c.518 (del518). This reduced the total CDS length from 1,488 bp to 1,487 bp.

Because a single nucleotide was deleted, the reading frame was disrupted starting at codon 173. This frameshift altered all downstream amino acids and introduced premature stop codons, predicting a truncated, non-functional protein product.

## 8. Documented vs. Artificial Mutation

The wild-type CYP21A2 sequence produced a functional 495-amino-acid enzyme. The documented c.518T>A mutation retained the full CDS and protein length, changing only a single residue (p.Ile173Asn).

In contrast, the artificial del518 deletion disrupted the reading frame completely. It altered the entire C-terminal primary structure following position 172 and caused premature termination.

This comparison underscores how mutation class dictates molecular severity: single-nucleotide missense mutations can partially impair catalytic function while preserving overall protein architecture, whereas single-base deletions cause global frame disruptions and total loss of function.

## 9. Interpretation

The precise location and type of a mutation dictate its clinical phenotype. Missense substitutions like I173N maintain structural integrity while lowering catalytic rate, leading to moderate disease phenotypes (simple virilizing CAH).

Conversely, frameshift mutations completely ruin enzymatic structure, leading to classic salt-wasting CAH with severe aldosterone deficiency. Computational sequence alignments reliably reflect these genomic changes, though published functional assays are necessary to quantify actual enzymatic retention.

## 10. Limitations

This investigation relied on bioinformatic sequence prediction tools. The structural and downstream effects were modeled in silico rather than tested in vitro or in vivo.

While sequence alignment confirms that c.518T>A alters only one codon and del518 causes a frameshift, actual protein folding dynamics, membrane insertion, and enzymatic kinetics require experimental assay validation. Furthermore, the artificial del518 deletion was designed solely for comparative modeling.

## 11. Conclusion

This study illustrates how distinct mutation classes within CYP21A2 yield divergent sequence and structural outcomes. The documented c.518T>A (p.Ile173Asn) variant is a missense mutation that preserves the 495-amino-acid length while altering a critical residue required for full enzymatic efficiency.

In contrast, an artificial single-base deletion at position 518 causes a total frame shift and premature truncation. These findings explain the molecular basis of 21-hydroxylase deficiency and demonstrate the utility of bioinformatic workflows in evaluating clinical genetics.
