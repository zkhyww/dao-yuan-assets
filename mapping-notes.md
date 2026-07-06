# Mapping Notes

The output names are based on visual/content purpose rather than the original numeric prefixes when the two disagree.

## Notes

- `hero-bg-main.png.png` -> `01-home-dao-yuan.webp`: Mapped from dedicated main hero asset, not from original 01 naming image.
- `24-hero-face-reading-background.png` -> `11-face-reading-background.webp`: Uses the newer formal face-reading hero image. The older 11 reference image is kept as legacy/reference.
- `01-hero-naming-bazi-background.png` -> `17-naming-main-background.webp`: Original file was numbered 01 but content is naming/BaZi; remapped to naming main.
- `17-advanced-methods-hub-background.png` -> `27-advanced-methods-hub-background.webp`: Extra page not present in the user's 01-26 example list; assigned 27 after required mappings.
- `11-reference-face-reading-beta-background.png` -> `11-face-reading-beta-reference.webp`: Kept for comparison only; formal faceReading manifest key points to 24-hero-face-reading-background.png.
- `cloud-01.png.png` -> `cloud-01.png`: Alpha check showed no transparent channel; kept as PNG reference but excluded from transparent overlay recommendations.
- `cloud-02.png.png` -> `cloud-02.png`: Alpha check showed no transparent channel; kept as PNG reference but excluded from transparent overlay recommendations.
- `cloud-03.png` -> `cloud-03.png`: Alpha check showed no transparent channel; kept as PNG reference but excluded from transparent overlay recommendations.
- `cloud-04.png` -> `cloud-04.png`: Alpha check showed no transparent channel; kept as PNG reference but excluded from transparent overlay recommendations.
- `cloud-05.png` -> `cloud-05.png`: Alpha check showed no transparent channel; kept as PNG reference but excluded from transparent overlay recommendations.
- `24-hero-face-reading-background.png` is used for the official `faceReading` manifest key.
- `11-reference-face-reading-beta-background.png` is retained as `faceReadingReferenceBeta` for comparison/reference only.
- `17-advanced-methods-hub-background.png` is retained as an extra advanced hub background because the user example list reserves output slot 17 for naming main.
- `cloud-01` through `cloud-05` are valid PNGs but do not contain transparency; they are listed as opaque cloud references instead of transparent overlays.
- `cloud-06` contains a normal alpha channel and remains the only recommended transparent cloud overlay in this input batch.
