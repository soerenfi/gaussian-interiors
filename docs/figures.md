# Figure and rendering details

[Overview](../README.md) · [Results](results.md) · [Pipeline](pipeline.md)

The media are selected outputs from personal capture and reconstruction
experiments. Compact input previews are retained where needed for comparison;
full input images, raw capture videos, point clouds and model checkpoints are
not distributed.

| Asset | Interpretation |
|---|---|
| [Walkthrough](assets/reconstruction-walkthrough.mp4) | Actual C007 50k MCMC + PPISP render; 40 seconds, 1,200 frames, 810 × 1440 at 30 fps |
| [GIF preview](assets/reconstruction-walkthrough.gif) | Twelve-second excerpt, 270 × 480 at 8 fps |
| [Matched comparisons](assets/reconstruction-teaser.jpg) | Two reduced source RGB previews alongside actual renders at matched capture poses |
| [Depth alignment](assets/depth-alignment.png) | Compact RGB crop and saved Depth Pro predictions before/after fitting; not reference depth |
| [Geometry comparison](assets/geometry-comparison.png) | Sampled point-cloud inspection views with common bounds; underlying geometry stays private |
| [Pose comparison](assets/pose-refinement.png) | Difference between saved ARKit and aligned SfM camera centers; not ground-truth error |
| [C007 ablation](assets/c007-ablation.png) | Historical measurements from notes; original run evidence is incomplete |
| [Capture app](assets/iphone-app.svg) | Source-based schematic, not a device screenshot |
| [Pipeline](assets/pipeline.svg) | Overview of the implemented pipeline and experimental branches |

The walkthrough follows the main capture route with repeated scanning detours
removed and smooth position/orientation interpolation. No model retraining or
external image enhancement was used to produce it. Existing evaluation records
are reported separately; the tour itself is qualitative evidence.

The [asset manifest](results/asset-manifest.json) records hashes of exactly the
published files. It contains no original camera trajectories or machine-specific
paths. The model weights and full internal rendering provenance remain private.

See the [third-party notices](../THIRD_PARTY_NOTICES.md) for model attribution and
research-use restrictions.
