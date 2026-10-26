# Prompt Breakdown and Layout Specification

## Example prompt

"Top-down comparison of a lush rainforest canopy with vibrant green density versus a barren desert featuring sparse, isolated vegetation. Annotate key features for easy comparison."

## Requirements extracted

| Prompt phrase | Requirement | Implementation decision | Validation |
|---|---|---|---|
| Top-down | Overhead viewpoint | Select overhead/aerial images for both panels | Canopy/ground seen from above; avoid oblique landscape shots |
| Comparison | Clear side-by-side contrast | Equal-width panels and a central divider | Both panels have equal dimensions |
| Lush rainforest canopy | Dense, overlapping vegetation | Image with extensive connected green canopy | Source/context supports rainforest identification |
| Barren desert | Arid terrain and exposed ground | Image with large visible areas of bare ground | Avoid dry grassland falsely labelled as desert |
| Sparse, isolated vegetation | Plants are widely spaced | Choose scene with clearly separated shrubs/trees | Vegetation gaps remain visible after crop |
| Annotate key features | Clear labels or legend | Use short callouts and a small legend | Labels point to the correct visual evidence |
| Easy comparison | Low clutter and readable hierarchy | Simple title, balanced margins, high contrast | Legible at presentation size |

## Composition specification

- **Canvas:** 16:9 landscape; recommended working size 1920 × 1080 px.
- **Margins:** consistent outer margins and panel gutters.
- **Panels:** 50/50 split, with matching crop scale as far as source material permits.
- **Heading:** "Vegetation Cover: Rainforest vs. Arid Desert".
- **Left label:** "Dense canopy"; supporting callout: "Overlapping vegetation limits ground visibility."
- **Right label:** "Sparse vegetation"; supporting callout: "Exposed ground and separated plants are prominent."
- **Legend:** "Illustrative visual comparison — conditions vary by location."
- **Typography:** one clean sans-serif family, clear hierarchy, no small text.
- **Annotations:** use a small number of fine leader lines; do not cover the key evidence.
- **Color:** use neutral labels and sufficient contrast; avoid color alone as the only way to distinguish categories.

## Asset selection checklist

For each candidate image, confirm:
1. The image is genuinely top-down or close to overhead.
2. The depicted land cover matches the intended label.
3. The crop preserves enough context to support the comparison.
4. Resolution is sufficient for the final canvas.
5. The original page and creator can be identified.
6. The license or terms permit the intended use, including portfolio display.
7. Any required attribution is retained.
8. No unsupported location, species, or environmental claim is added.

## File naming convention

Use lowercase, descriptive names with version numbers:
- `rainforest_canopy_source01.jpg`
- `arid_desert_source01.jpg`
- `rainforest_desert_comparison_v01.png`
- `rainforest_desert_comparison_v01.xcf` (GIMP) or the native project format
- `asset_sources.csv`

Keep original downloads separate from edited exports. Never overwrite source files.
