# Verification record

## Completed during preparation

- Confirmed every code cell parses after removing shell/environment commands.
- Compared the cleaned code with the source: all 23 code cells remain; allowed differences are limited to the cleanup documented in `PROVENANCE.md`.
- Verified source hashes during preparation. During final cleanup, four charts and the score CSV remain byte-identical; the collages and essay have metadata-only public copies with identical pixels/page content. Updated file hashes are in `asset-manifest.json`.
- Independently evaluated the recovered cosine-difference computation using only required vectors streamed from the local `glove.6B.zip` archive. No data were downloaded, and no replacement charts were written.
- Confirmed all 49 words in the checked original and expanded word selections were present in the 100d vectors.
- Checked relative README links and image paths and performed a targeted privacy scan.

## Numerical result

| Domain | Independently checked difference |
|---|---:|
| Professions | 0.150554358959198 |
| Personality traits | 0.04576657712459564 |
| Activities | 0.13902893662452698 |

Small floating-point differences are expected across NumPy/Gensim versions. Agreement to approximately five decimal places is the intended comparison, not bitwise equality.

The historical same-attribute-list experiment returns zero by construction. The later distinct-list calculation yields the values above. The original final bar chart agrees with these latter values, while the essay narrative states approximately 0.14, 0.08, and 0.12 respectively. Neither record has been silently replaced.

## Not verified

The available bundled runtime lacks several plotting/scientific dependencies. A complete Jupyter run in the proposed pinned environment was not performed. The requirements are a documented compatibility target, not a verified historical lockfile. Original figure pixels were inspected and preserved; they were not regenerated. Exact reproduction of the expanded fourteen-profession figures remains impossible from the recovered notebook alone.


## Final publication cleanup check (22 October 2026)

All 23 code cells still parse and are byte-for-byte identical to the prepared code. Actual notebook function definitions and word lists were executed using NumPy and a minimal vector adapter backed by selected float32 vectors streamed from the existing local archive. The 18-by-8 cosine matrix is finite; all three domain scores match the table above within 1e-6; identical A/B sets yield zero. This exercises the numerical functions, not Gensim loading, plotting, PCA, clustering, or a full Jupyter kernel. No datasets or dependencies were downloaded; no charts were generated.

Every one of the 14 essay pages was rendered in memory at scale 1 before/after PDF metadata cleanup: all pixels and extracted page texts are identical. The two collages retain exactly the same compressed IDAT chunks and decoded pixels after XMP identifier removal. The four chart files and score CSV retain their prior SHA-256 values. All relative links were rechecked after the essay rename. Known identifiers are absent from public filenames, text, notebook/PDF metadata, and PNG textual metadata. The full environment execution limitation above is unchanged and is not a publication blocker.
