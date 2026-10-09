# Repository archive — 2026-10-09

This branch retains Revision Outline, Revision Summary, the compiled manuscript, legacy Tex/ chapters and template reference files. It is for local records and is not the Overleaf upload branch.

main contains the active manuscript source, bibliography, 13 referenced figure PDFs, the document class, the active bibliography style, and Git ignore rules.

Git audit before cleanup: five official commits; approximately 890 MiB of loose objects and 233 MiB of packs; 758 objects not reachable from branch refs; no unreachable commits found by git fsck --unreachable --no-reflogs. Many unreferenced objects are repeated compiled PDFs. Existing official history is preserved; git gc removes unreferenced objects and repacks reachable history.

To access records: git switch codex/revision-records. Return to upload source: git switch main. The archive branch does not automatically follow future main changes.

Revision documents are retained only on this branch and are excluded from the upload package. Old Tex/ chapters are retained here because they are not input by the active sn-article.tex.
