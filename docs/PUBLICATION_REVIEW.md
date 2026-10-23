# Publication review — final local cleanup

Reviewed 22 October 2026. **Suitable for public portfolio publication within the documented scope; no material publication blocker identified.** The reviewed package is now published in this public GitHub repository. No repository-wide licence has been added.

## Privacy and file integrity

- The submitted essay is now `reports/unveiling-bias-submitted-essay.pdf`. Its identifying title was replaced, with author attribution to Selin Deniz İşken. The original identifying filename is absent from the public package. Original coursework outside this folder is unchanged.
- All 14 PDF pages have identical extracted text and identical rendered pixels before/after metadata cleanup. No attachments, forms, private links, email addresses, or student numbers were identified in the essay. Its research bibliography links are retained.
- Both AI-image collages were visually reviewed in full: only profession prompts, generated outputs, and cropped interface elements are visible; no account name, email, conversation URL, or unrelated private message was observed. Metadata contained Canva document/account/tracking identifiers; these were removed while retaining generic tool credit and attribution. Image pixels and compressed IDAT data are unchanged.
- All four chart files and the results CSV are unchanged. Notebook code is unchanged. Notebook metadata is restricted to kernel/language information and the intended author name.
- Public text, filenames, PDF metadata/text, and PNG textual metadata were scanned for known student/account identifiers, local paths, email addresses, and credential-like patterns. Private recovery Drive links were removed. All package-relative Markdown and notebook links resolve.

## Coursework guidance checked

Read the recovered 2024 assignment brief (Essay or StoryMap with Self Designed Visualisation), Course Structure, and assessment rubric. None contains an explicit publication prohibition. The brief permits an essay or StoryMap and discusses linking a published StoryMap. These course materials are not included in the public package.

Also checked the current official [UCIL Visualising Information unit page](https://www.ucil.manchester.ac.uk/unit-catalogue/visualising-information/) and the University's [Intellectual Property Policy](https://documents.manchester.ac.uk/display.aspx?DocID=24420), dated 1 January 2025, for this 2026 publication review. The policy generally assigns student-created IP to the student subject to listed exceptions (2.1) and encourages publication of scholarly materials (3.7); third-party content retains its owners' rights. No applicable funding, sponsorship, assignment of rights, confidentiality agreement, or explicit course publication ban was identified in the available project evidence. This is a bounded review, not an exhaustive search of private university systems or a claim about an unseen agreement. **The absence of an explicit prohibition is not treated as a restriction or a requirement to seek permission.**

## Attribution and rights

The user identifies this as individual coursework. Attribution to Selin Deniz İşken, Stanford GloVe, WEAT research, Kaggle scaffolding, scientific libraries, OpenAI DALL·E, Canva, and portfolio-preparation assistance is retained or clarified. See [third-party notices](THIRD_PARTY_NOTICES.md). No unverified licence terms have been assigned to the analysis or the mixed-origin package. A complete historical record of line-by-line code authorship is unavailable, but no specific uncredited copied implementation or missing applicable notice was identified in this review.

The retained generated images are clearly disclosed as AI output. The archived December 2024 OpenAI terms and current sharing/publication policy were checked and linked in the notices. No specific publication restriction was identified for these retained examples. No exclusive copyright claim is made over AI imagery.

## Technical checks and continuing limitations

A lightweight check executed the actual notebook's cosine/matrix/score functions against selected vectors read from the existing local GloVe archive, through a NumPy-backed adapter. The 18-by-8 matrix is finite, three recovered domain scores agree, and the historical same-set example is zero. All 23 code cells parse. Nothing was downloaded or installed and no charts were regenerated.

A full Jupyter run with the pinned Gensim/plotting environment remains unverified because the available bundled runtime lacks several dependencies. This is an explicitly disclosed execution limitation, not a publication blocker. The eight-versus-fourteen-profession source gap, reported-versus-calculated scores, qualitative image scope, and other methodological limitations remain unchanged. The historical essay is not a corrected report or a fully audited bibliography.

## Release conclusion

The straightforward privacy, attribution, path, and publication-readiness issues identified in the prepared package have been addressed. No material unresolved publication blocker was found. This does not grant a blanket reuse licence or claim complete computational reproducibility. The package has since been published within the reviewed scope.
