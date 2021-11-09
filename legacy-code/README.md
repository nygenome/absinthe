# absinthe

`A`ssembly-`B`a`S`ed `IN`ser`T`ion calling from s`H`ort r`E`ad data.

* Version: 0.1-pre

## Requirements

* In `$PATH`:
  * `./scripts/`
  * Python 2.7+
  * Perl 5
  * BWA v0.7.12+
  * SAMtools v1.7+
  * BEDTools v2.25.0+
  * Cutadapt v1.16+
  * liftOver
  * GEM pre-release 3
  * AGE (`age_align` binary, more specifically)
  * ABySS v2.0.2

* UCSC references indexed for BWA-MEM:
  * hg38
  * hg38 (just the chromosomes)
  * gorGor5
  * panPan2
  * panTro6
  * ponAbe3

* List of all non-chromosome sequences of hg38 in BED format

* Reference indexed for GEM-mapper:
  * hg38 with only chromosomes 1-22,X,Y and hard-masked PAR on chromosome Y.

* UCSC chain files:
  * gorGor5ToHg38.over.chain
  * panPan2ToHg38.over.chain
  * panTro6ToHg38.over.chain
  * ponAbe3ToHg38.over.chain

* phiX index for GEM-mapper (provided in `./resources/`)
