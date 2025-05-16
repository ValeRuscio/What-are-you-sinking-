# Statistical Significance Analysis

This report shows which differences between layers are statistically significant.

## Interpretation

- p-value < 0.05: The difference is statistically significant
- p-value ≥ 0.05: The difference could be due to random variation

## Significant Differences Between Layers

Found 10 statistically significant differences:

| Comparison | Metric | Layer 1 Mean | Layer 2 Mean | p-value |
|------------|--------|--------------|--------------|--------|
| Layer 0 vs 14 | Dim0 Persistence | 0.0574 | 0.0880 | 0.0000 |
| Layer 0 vs 21 | Dim0 Persistence | 0.0574 | 0.0317 | 0.0000 |
| Layer 0 vs 27 | Dim0 Persistence | 0.0574 | 0.1620 | 0.0000 |
| Layer 0 vs 7 | Dim0 Persistence | 0.0574 | 0.0444 | 0.0000 |
| Layer 14 vs 21 | Dim0 Persistence | 0.0880 | 0.0317 | 0.0000 |
| Layer 14 vs 27 | Dim0 Persistence | 0.0880 | 0.1620 | 0.0000 |
| Layer 21 vs 27 | Dim0 Persistence | 0.0317 | 0.1620 | 0.0000 |
| Layer 7 vs 14 | Dim0 Persistence | 0.0444 | 0.0880 | 0.0000 |
| Layer 7 vs 21 | Dim0 Persistence | 0.0444 | 0.0317 | 0.0000 |
| Layer 7 vs 27 | Dim0 Persistence | 0.0444 | 0.1620 | 0.0000 |

## All Test Results

For completeness, here are all statistical test results, significant or not:

| Comparison | Metric | Layer 1 Mean | Layer 2 Mean | p-value | Significant? |
|------------|--------|--------------|--------------|---------|-------------|
| Layer 0 vs 14 | Betti₀ (Components) | 26.4060 | 26.4060 | 1.0000 | No |
| Layer 0 vs 14 | Betti₁ (Loops) | 0.0000 | 0.0000 | nan | No |
| Layer 0 vs 14 | Max Attention | 1.0000 | 1.0000 | nan | No |
| Layer 0 vs 14 | Mean Attention | 0.0351 | 0.0351 | 1.0000 | No |
| Layer 0 vs 14 | Dim0 Persistence | 0.0574 | 0.0880 | 0.0000 | Yes |
| Layer 0 vs 21 | Betti₀ (Components) | 26.4060 | 26.4060 | 1.0000 | No |
| Layer 0 vs 21 | Betti₁ (Loops) | 0.0000 | 0.0000 | nan | No |
| Layer 0 vs 21 | Max Attention | 1.0000 | 1.0000 | nan | No |
| Layer 0 vs 21 | Mean Attention | 0.0351 | 0.0351 | 1.0000 | No |
| Layer 0 vs 21 | Dim0 Persistence | 0.0574 | 0.0317 | 0.0000 | Yes |
| Layer 0 vs 27 | Betti₀ (Components) | 26.4060 | 26.4060 | 1.0000 | No |
| Layer 0 vs 27 | Betti₁ (Loops) | 0.0000 | 0.0000 | nan | No |
| Layer 0 vs 27 | Max Attention | 1.0000 | 1.0000 | nan | No |
| Layer 0 vs 27 | Mean Attention | 0.0351 | 0.0351 | 1.0000 | No |
| Layer 0 vs 27 | Dim0 Persistence | 0.0574 | 0.1620 | 0.0000 | Yes |
| Layer 0 vs 7 | Betti₀ (Components) | 26.4060 | 26.4060 | 1.0000 | No |
| Layer 0 vs 7 | Betti₁ (Loops) | 0.0000 | 0.0000 | nan | No |
| Layer 0 vs 7 | Max Attention | 1.0000 | 1.0000 | nan | No |
| Layer 0 vs 7 | Mean Attention | 0.0351 | 0.0351 | 1.0000 | No |
| Layer 0 vs 7 | Dim0 Persistence | 0.0574 | 0.0444 | 0.0000 | Yes |
| Layer 14 vs 21 | Betti₀ (Components) | 26.4060 | 26.4060 | 1.0000 | No |
| Layer 14 vs 21 | Betti₁ (Loops) | 0.0000 | 0.0000 | nan | No |
| Layer 14 vs 21 | Max Attention | 1.0000 | 1.0000 | nan | No |
| Layer 14 vs 21 | Mean Attention | 0.0351 | 0.0351 | 1.0000 | No |
| Layer 14 vs 21 | Dim0 Persistence | 0.0880 | 0.0317 | 0.0000 | Yes |
| Layer 14 vs 27 | Betti₀ (Components) | 26.4060 | 26.4060 | 1.0000 | No |
| Layer 14 vs 27 | Betti₁ (Loops) | 0.0000 | 0.0000 | nan | No |
| Layer 14 vs 27 | Max Attention | 1.0000 | 1.0000 | nan | No |
| Layer 14 vs 27 | Mean Attention | 0.0351 | 0.0351 | 1.0000 | No |
| Layer 14 vs 27 | Dim0 Persistence | 0.0880 | 0.1620 | 0.0000 | Yes |
| Layer 21 vs 27 | Betti₀ (Components) | 26.4060 | 26.4060 | 1.0000 | No |
| Layer 21 vs 27 | Betti₁ (Loops) | 0.0000 | 0.0000 | nan | No |
| Layer 21 vs 27 | Max Attention | 1.0000 | 1.0000 | nan | No |
| Layer 21 vs 27 | Mean Attention | 0.0351 | 0.0351 | 1.0000 | No |
| Layer 21 vs 27 | Dim0 Persistence | 0.0317 | 0.1620 | 0.0000 | Yes |
| Layer 7 vs 14 | Betti₀ (Components) | 26.4060 | 26.4060 | 1.0000 | No |
| Layer 7 vs 14 | Betti₁ (Loops) | 0.0000 | 0.0000 | nan | No |
| Layer 7 vs 14 | Max Attention | 1.0000 | 1.0000 | nan | No |
| Layer 7 vs 14 | Mean Attention | 0.0351 | 0.0351 | 1.0000 | No |
| Layer 7 vs 14 | Dim0 Persistence | 0.0444 | 0.0880 | 0.0000 | Yes |
| Layer 7 vs 21 | Betti₀ (Components) | 26.4060 | 26.4060 | 1.0000 | No |
| Layer 7 vs 21 | Betti₁ (Loops) | 0.0000 | 0.0000 | nan | No |
| Layer 7 vs 21 | Max Attention | 1.0000 | 1.0000 | nan | No |
| Layer 7 vs 21 | Mean Attention | 0.0351 | 0.0351 | 1.0000 | No |
| Layer 7 vs 21 | Dim0 Persistence | 0.0444 | 0.0317 | 0.0000 | Yes |
| Layer 7 vs 27 | Betti₀ (Components) | 26.4060 | 26.4060 | 1.0000 | No |
| Layer 7 vs 27 | Betti₁ (Loops) | 0.0000 | 0.0000 | nan | No |
| Layer 7 vs 27 | Max Attention | 1.0000 | 1.0000 | nan | No |
| Layer 7 vs 27 | Mean Attention | 0.0351 | 0.0351 | 1.0000 | No |
| Layer 7 vs 27 | Dim0 Persistence | 0.0444 | 0.1620 | 0.0000 | Yes |
