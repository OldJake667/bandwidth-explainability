# Bandwidth explainability

Explainability code, notebooks, validation images, saved numerical results,
figures, and reports for the original **Low / High bandwidth** classifiers.
The split is **176 training / 45 validation / no independent test set**.
This is separate from SUTD/RDN compact-response classification.

## Downloads

- [Code and notebooks](bandwidth-explainability-code.zip): all 37 Python files,
  19 notebooks, setup instructions, and source-integrity manifests.
- [Full collection, including all supporting data and results](https://github.com/OldJake667/bandwidth-explainability/releases/download/v1.0.0/bandwidth-explainability-full.zip):
  approximately 1.15 GB compressed / 1.38 GB extracted, containing 2,813 files.
- [Release page and SHA-256 checksum](https://github.com/OldJake667/bandwidth-explainability/releases/tag/v1.0.0)
- [Required model checkpoint names and checksums](supporting-resources.json)

The full collection contains the complete saved LIME, attention-rollout and
gradient-attention-rollout outputs; Grad-CAM code and results; the original
221-image input dataset; validation images; presentation PDFs; the expanded
structural atlas; image assets; and historical provenance/verification records.
The code download preserves the same relative folder layout. For analyses that
need data or saved results, extract the full collection and use that folder.

## Running the analyses

Start with the lab package's `START_HERE.md` inside either download. The model
weights and Python environment are excluded. Restore the exact checkpoint
files listed in `supporting-resources.json` before running model inference or
checkpoint-integrity checks. Their SHA-256 hashes remain in the original
integrity manifests. Third-party licenses are retained with the source.

All exported Python files and notebook code cells compile, and exported files
were checked for secret markers and accidental environment/model-weight files.
Historical reports describe their original runs. Full LIME and GPU execution
were not newly verified for this upload. The spatial explanations describe
model behavior and do not establish physical causality.
