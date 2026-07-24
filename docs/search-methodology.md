# Search Methodology

Last searched: **2026-07-24**.

## Scope

The main list includes peer-reviewed papers from these venues, in this order:
CVPR, ICCV, ECCV, NeurIPS, ICLR, ICML, IJCV, and TPAMI. The request's “lcml”
was normalized to **ICML**.

A paper is included when a look-up table is a central model, representation,
operator, compression target, or inference mechanism. Papers that merely use a
table as a minor implementation detail are outside the scope.

The collection is topic-neutral and contains bibliographic and topical
metadata only.

## Sources Checked

| Venue | Primary source | Coverage checked |
|:---:|:---|:---|
| CVPR | [CVF Open Access](https://openaccess.thecvf.com/menu) | Complete available CVF proceedings, 2013–2026, plus the historical DBLP conference backfile from 1988; DOI cross-checks |
| ICCV | [CVF Open Access](https://openaccess.thecvf.com/menu) | Complete available CVF proceedings, 2013–2025, plus the historical DBLP conference backfile from 1987; DOI cross-checks |
| ECCV | [ECVA Papers](https://www.ecva.net/papers.php) | Full ECVA paper index; DBLP and Springer DOI cross-checks |
| NeurIPS | [NeurIPS Proceedings](https://proceedings.neurips.cc/) | Annual proceedings, 1987–2025 |
| ICLR | [OpenReview](https://openreview.net/group?id=ICLR.cc) | Conference records, 2013–2026; DBLP cross-check |
| ICML | [PMLR](https://proceedings.mlr.press/) | Conference records, 1988–2025; DBLP cross-check |
| IJCV | [Springer IJCV](https://link.springer.com/journal/11263) | DBLP-indexed volumes 1–134, through 2026; DOI cross-check |
| TPAMI | [IEEE TPAMI](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=34) | DBLP-indexed volumes 1–48, through 2026; DOI cross-check |

Search terms included `LUT`, `LUTs`, `lookup table`, `look-up table`,
`3D LUT`, and task-specific combinations for enhancement, restoration,
super-resolution, fusion, style transfer, quantization, and inference. Title
matches were verified against the official publication record. Scholarly APIs,
DBLP, Crossref/DOI metadata, arXiv metadata, and GitHub were used only for
cross-checking venue, year, and official code links.

## Exclusions

- arXiv-only work without a confirmed publication in one of the target venues;
- workshop papers and papers published only at other conferences or journals;
- papers where lookup tables appear only as an engineering detail;
- duplicate preprint and journal records (the final target-venue publication is
  retained; a substantially extended paper at another requested venue remains a
  separate entry).

Examples such as NLUT, NILUT, 4D LUT, FastLLVE, and other relevant preprints are
therefore not placed in the main list unless a target-venue publication can be
verified.
