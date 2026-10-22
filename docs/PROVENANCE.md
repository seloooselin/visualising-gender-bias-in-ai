# Recovery and preparation record

Prepared 22 October 2026. The original files and connected Drive sources were not edited. Final publication cleanup completed 22 October 2026. This is a local public-ready portfolio package; no repository has been created or published.

## Source inventory

- Notebook source: recovered `weatvisual.ipynb`, 1,488,571 bytes; SHA-256 `294594612c6fed09e6c97dba07ec11a6610264cf54c704a20f4407771d791350`. Four local copies were byte-identical.
- Final essay: public copy `reports/unveiling-bias-submitted-essay.pdf`. Original source was 10,517,860 bytes, SHA-256 `f0699c1b90acc640f659d48dadbeeca74ec44d52dbf35013c91ac25575bc8f37`. Three recovered source copies were byte-identical. The original remains outside this package and was not modified. The public copy changes only filename/document metadata; text, layout, and image content are preserved. Author metadata credits Selin Deniz İşken.
- Four selected chart PNGs and two collages match the final essay's embedded images pixel-for-pixel. See `asset-manifest.json` for source and public-copy hashes. Four chart files remain byte-identical; the two collages have metadata-only privacy edits with unchanged image pixels and compressed IDAT data. These are recovered screenshot assets, not vector exports or regenerated charts.
- Original planning material, assignment samples, rubric, external papers, unrelated coursework, and additional duplicate screenshots are excluded for compactness and attribution clarity.

## Notebook changes

All 23 original code cells remain in their original order. Only environment scaffolding, display compatibility, and execution artifacts changed:

1. Replaced Kaggle input-directory traversal and install boilerplate with the same NumPy/pandas imports and an attribution comment.
2. Replaced in-notebook download/unzip commands with a portable local data-path check. Both model-loading statements use that path.
3. Removed repeated install/download commands from the later domain-score cell.
4. Removed unused `mplsoccer` installation and `Radar` import; the original radar is drawn with Matplotlib.
5. Added `ax=plt.gca()` to the network colorbar to avoid implicit-axes compatibility failures. Graph computations, weights, layout, and colors are unchanged.
6. Cleared all outputs, execution counts, and irrelevant environment metadata. Added markdown explaining historical zero scores, score provenance, and exploratory limitations.

Word lists, cosine formulas, both score functions, PCA, clustering, graph construction, and plotting choices are otherwise preserved. Original titles containing “WEAT” remain for traceability, with corrected interpretation in adjacent markdown. The early same-set score experiment is deliberately retained rather than silently corrected.

## Reproducibility boundary

The recovered notebook defines eight professions. Original final heatmap/radar assets define fourteen. No expanded code version was located in the accessible files, VS Code history/backups, Jupyter checkpoints, IPython history, or connected project folder. This preparation does not reconstruct that missing source or generate replacement figure assets.

## Authorship boundary

The user identifies the project as individual coursework. Recovered materials support that description; no coauthor record was found. Standard Kaggle scaffolding and third-party pretrained data are external contributions. Exact line-by-line code provenance is not established. Planning documents contain assistant-style wording, so sole unaided authorship is not claimed. AI image outputs are credited separately.


## Public metadata cleanup

The essay now has a neutral public filename and descriptive Title/Subject metadata with author Selin Deniz İşken. All 14 pages were rendered before and after the change and compared pixel-for-pixel, and extracted page text was compared. Both were identical. The original identifying PDF is not retained inside the public package.

Both image collages contained Canva document/account/tracking identifiers in XMP. Those fields were removed without decoding/re-encoding image data; the generic Canva tool credit and corrected author attribution remain. All IDAT chunks and image pixels are unchanged. Notebook metadata contains only kernel/language information and the intended author name; code cells are unchanged. Private recovery Drive links were removed from this public provenance record. No original source file or Google Drive file was edited.
