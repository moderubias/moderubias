# Profile review

Public repository snapshot: **29 September 2026**. Recommendations below are proposals; account settings and other repositories have not been changed.

**Redesign note:** The first-pass presentation recorded below has since been revised. The README now features SeonCore and senkeidaisu and uses a compact SVG masthead with light/dark variants. The repository findings and metadata/pin recommendations remain applicable.

## Public evidence

The [account](https://github.com/moderubias) has five public repositories, including the profile. All four code repositories primarily use C++. There are no public Rust, Python, or LaTeX portfolio repositories in this account snapshot. Rust/Python and study direction in the profile come from the author's supplied context. In the first pass, the README contained no project links at the author's request.

At the initial inspection, the published profile contained the starter greeting and pinned senkaid and SeonCore. Its bio already mentioned AI research, mathematics, Rust/Python, and LaTeX. The replacement README explains the current direction and provides a direct contact for work.

| Repository / inspected revision | Last push | Evidence and limitations |
| --- | --- | --- |
| [SeonCore](https://github.com/moderubias/SeonCore/tree/95f326128eda006ca63d45f6ee478eff21cbbaf5) | 2026-02-01 | C++20 dense matrices, strided views, transposition, and multiplication. MIT. No README; the test executable has an empty `main`. Best first entry into the engineering work, with an experimental label. |
| [senkeidaisu](https://github.com/moderubias/senkeidaisu/tree/1a4ba5741d1fbbe8c10a965cd7c749728c9538f7) | 2025-03-18 | C++20 dense/sparse matrix implementations and linear regression code. MPL-2.0. Two-line README; tests are a placeholder. Useful mathematical programming evidence, without a correctness claim. |
| [senkaid](https://github.com/moderubias/senkaid/tree/39faf85074c1362e38ff1880fd3e3aeac2f3f31b) | 2025-08-05 | C++23 experiment with rotation routines and memory utilities. Apache-2.0. Of 387 files, 318 are empty. Tests contain no assertions. CMake references a missing `cmake/senkaidConfig.cmake.in`. Backend directories do not establish working GPU support. |
| [LINALG](https://github.com/moderubias/LINALG/tree/110593b3ced2d3fb3fb8c00280ee7d0cd28e1126) | 2024-10-15 | Early C++20 matrix and sparse-storage experiment. No license detected. Its documentation says it does not work; the example hardcodes a local log path and requires spdlog. |

None of these four repositories has a published GitHub release or a GitHub Actions workflow at the inspected revision. Recent profile/star metadata is not evidence of recent development. This was a source and metadata review; project builds and numerical correctness were not tested.

## Pins

**Recommend two pins now: SeonCore, then senkeidaisu.** There are only four public code repositories, and filling six slots would misrepresent the available work.

| Slot | Recommendation |
| --- | --- |
| 1 | SeonCore — clearest small engineering example. Add a build/run README and meaningful tests. |
| 2 | senkeidaisu — mathematical programming and the regression experiment. Document a reproducible example. |
| 3 | Leave empty until a substantial Rust project is public. |
| 4 | Leave empty until a useful Python tool or experiment is public. |
| 5 | Leave empty until a LaTeX portfolio has source and rendered examples. |
| 6 | Leave empty until mathematical notes or a distinct AI/math experiment can be inspected. |

Senkaid ranks third among the existing candidates, but its scaffolding and broken CMake reference make it a weaker entry point. Reconsider it after documenting implemented features and fixing the build. LINALG ranks fourth and should remain unpinned. The profile repository does not need a pin.

## Suggested descriptions and topics

| Repository | Description | Topics |
| --- | --- | --- |
| SeonCore | Experimental C++20 matrix library with dense storage, strided views, and matrix multiplication. | `cpp`, `cpp20`, `linear-algebra`, `matrix` |
| senkeidaisu | C++20 linear algebra experiments with dense and sparse matrices and linear regression. | `cpp`, `cpp20`, `linear-algebra`, `sparse-matrix`, `linear-regression` |
| senkaid | Experimental C++ linear algebra code with rotation routines and memory utilities; incomplete. | `cpp`, `cpp23`, `linear-algebra`, `numerical-computing` |
| LINALG | Early C++ matrix and sparse-storage experiment; incomplete. | `cpp`, `linear-algebra`, `sparse-matrix` |
| moderubias | Personal GitHub profile of Akayo Kiyoshima. | `profile`, `github-profile` |

An optional shorter bio: “Independent builder working toward AI research. Studying higher mathematics; working with Rust, Python and LaTeX.”

## Archive candidates

**LINALG is the strongest candidate for review:** old work, an explicit nonworking notice, and newer repositories covering related ground. Before archiving, decide whether any unique work should be preserved elsewhere and clarify its license if reuse is intended.

**Senkaid is conditional:** archive only if the experiment is finished and no maintenance is planned. Inactivity alone does not establish abandonment. Keep senkeidaisu available while it supplies distinct matrix/regression evidence. Neither MatrixDot nor XYONRAD appears in the public inventory.

Archiving, deleting, and changing account settings require a separate decision from the owner.

## LaTeX evidence to publish next

The public account currently offers no typesetting samples to inspect. The README presents availability without claiming a portfolio or proven service history.

A useful future `latex-typesetting` repository would contain one original mathematical document as `.tex` and PDF, an original before/after formatting example, and a reusable `.sty` or `.cls` with a working sample. Include the engine and exact build command. Publish it when those artifacts exist; avoid an empty portfolio repository or client material without permission.

## First-pass presentation and upkeep

The profile uses one text heading, short paragraphs, a secondary work section, and a collapsed personal note. Age, language levels, education plans, legal details, and secondary media are omitted. LinkedIn is omitted until its destination is verified. There is no empty project section or placeholder portfolio link.

Native Markdown inherits GitHub's light/dark colors and responsive typography. There are no fixed-width layouts, badges, widgets, external fonts, or generated statistics. A decorative SVG would duplicate selectable text, so no artwork is needed. The four pre-existing SVG files were empty and have been removed.

The root README meets GitHub's [profile README requirements](https://docs.github.com/en/account-and-profile/how-tos/profile-customization/managing-your-profile-readme). Its final disclosure uses GitHub's documented [collapsed-section syntax](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/organizing-information-with-collapsed-sections). Keep the blank lines around that content.

When adding projects, place them between the introduction and LaTeX section. Keep maturity labels honest and link directly to readable code or examples when a project's README is thin. No generator or scheduled workflow is needed for this content.
