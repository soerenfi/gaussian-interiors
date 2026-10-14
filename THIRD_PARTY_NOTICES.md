# Attribution and publication scope

This repository is a portfolio of selected documentation and results. It does
not distribute the capture app, preprocessing/training implementation, model
weights, native libraries or a software package. No general reuse license has
been granted for the original text, footage or figures. Third-party names are
used to identify the methods and tools used in the experiments.

## Reconstruction and tooling

- [3DGRUT](https://github.com/nv-tlabs/3dgrut) — NVIDIA's Gaussian reconstruction/rendering implementation, Apache-2.0. Selected modifications are in the separate [public fork](https://github.com/soerenfi/3dgrut), which retains its own license and notices.
- [PPISP](https://github.com/nv-tlabs/ppisp) — learned appearance correction, Apache-2.0.
- [COLMAP](https://github.com/colmap/colmap) — structure from motion and camera refinement, BSD-3-Clause.
- [Open3D](https://github.com/isl-org/Open3D) — geometry processing and TSDF fusion, MIT.
- [PyTorch](https://github.com/pytorch/pytorch) — model optimization, BSD-style license.
- [plyfile](https://github.com/dranjan/python-plyfile) — geometry file processing, GPL-3.0-or-later. No copy of this library or packaged application is distributed here.
- [Matplotlib](https://matplotlib.org/) and [Pillow](https://python-pillow.github.io/) — figure export, under their respective licenses.
- [FFmpeg](https://ffmpeg.org/legal.html) with libx264 — video encoding. Encoded media are included; encoder binaries are not.

These credits do not replace license obligations for anyone obtaining or
redistributing those implementations. The private development repository keeps
the detailed dependency and native-component audit.

## Research models

**Depth Pro.** The depth-alignment figure contains saved predictions from Apple's
Depth Pro, identified as such in its caption. The project investigated these
predictions as additional geometry constraints. Apple's source-code terms and
model terms differ. The [original model license](https://huggingface.co/apple/DepthPro/blob/main/LICENSE)
limits use and model derivatives to non-commercial scientific research. The
[Transformers checkpoint](https://huggingface.co/apple/DepthPro-hf) is labeled
`apple-amlr` in metadata but also contains a conflicting source-license label in
its card. Its exact conversion provenance and applicable terms remain an item
for clarification before broader reuse. No weights are distributed here.

**DSINE.** Surface-normal estimation was investigated using
[DSINE](https://github.com/baegwangbin/DSINE). Its [Imperial College London license](https://github.com/baegwangbin/DSINE/blob/main/LICENSE)
limits use to non-commercial internal/academic research and includes publication
and redistribution conditions. No DSINE source, weights or normal-map outputs
are distributed in this showcase.

This presentation records engineering experiments. It makes no claim that the
complete underlying pipeline is cleared for unrestricted commercial reuse.
