# Search Methodology

Last searched: **2026-07-24**.

## Scope

The list covers peer-reviewed papers and arXiv preprints in computer vision and
machine learning for which a look-up table is a central model, representation,
operator, compression target, or inference mechanism. This includes modern
learned LUTs and classical image-processing LUT methods from TIP.

Papers are displayed together in descending publication-year order rather than
grouped by venue. When a preprint has a confirmed formal publication, only the
formal venue record is retained. A substantially extended journal version can
remain alongside its conference predecessor.

The collection contains bibliographic and topical metadata only.

## Sources Checked

The original venue set was checked exhaustively and then expanded:

| Source group | Coverage checked |
|:---|:---|
| CVPR / ICCV | Complete available [CVF Open Access](https://openaccess.thecvf.com/menu) proceedings, plus historical DBLP conference backfiles |
| ECCV | Full [ECVA paper index](https://www.ecva.net/papers.php), including confirmed 2026 papers |
| NeurIPS | [Annual proceedings](https://proceedings.neurips.cc/), 1987–2025 |
| ICLR / ICML | OpenReview and PMLR records, with DBLP cross-checks |
| IJCV / TPAMI | Full DBLP-indexed journal backfiles through 2026, with DOI cross-checks |
| TIP | Full DBLP-indexed journal backfile through 2026; all central LUT-title matches were reviewed |
| Other publications | AAAI, ACM MM, TMM, TCSVT, IJCAI, ICASSP, HPCA, FCCM, ICME, ICFPT, CVMP, JMLR, Pattern Recognition, Neurocomputing, Computer Graphics Forum, and ACM Computing Surveys |
| Preprints | arXiv title and metadata searches through 2026-07-24 |

Search terms included `LUT`, `LUTs`, `lookup table`, `look-up table`, `3D LUT`,
`4D LUT`, and task-specific combinations for enhancement, restoration,
super-resolution, fusion, style transfer, video coding, quantization, and neural
inference. Titles and publication status were cross-checked through official
proceedings, DBLP, Crossref/DOI metadata, arXiv metadata, and official GitHub
repositories where available.

## Inclusion and Exclusion Rules

Included:

- learned or optimized LUTs used as the paper's main representation or model;
- LUT-based image/video processing, neural inference, quantization, or
  acceleration methods;
- classical TIP papers specifically centered on image-processing LUT design;
- arXiv preprints without a verified formal version.

Excluded:

- papers where a lookup table is only a minor implementation detail;
- ordinary FPGA logic-cell mapping papers that use “LUT” only to mean a hardware
  primitive;
- domain-specific control, circuit calibration, signal acquisition, database,
  and cryptographic lookup-table work outside the vision/ML scope;
- duplicate arXiv records when a formal publication is available.
