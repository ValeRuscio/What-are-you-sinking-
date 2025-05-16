# Statistical Significance Analysis

This report shows which differences between layers are statistically significant.

## Interpretation

- p-value < 0.05: The difference is statistically significant
- p-value ≥ 0.05: The difference could be due to random variation

## Significant Differences Between Layers

Found 36 statistically significant differences:

| Comparison | Metric | Layer 1 Mean | Layer 2 Mean | p-value |
|------------|--------|--------------|--------------|--------|
| Layer 0 vs 12 | Betti₀ (Components) | 22.6900 | 1.0140 | 0.0000 |
| Layer 0 vs 12 | Betti₁ (Loops) | 20.9280 | 8.5240 | 0.0000 |
| Layer 0 vs 12 | Max Attention | 0.1732 | 0.8139 | 0.0000 |
| Layer 0 vs 12 | Dim0 Persistence | 0.0518 | 0.0025 | 0.0000 |
| Layer 0 vs 18 | Betti₀ (Components) | 22.6900 | 1.0000 | 0.0000 |
| Layer 0 vs 18 | Betti₁ (Loops) | 20.9280 | 0.0000 | 0.0000 |
| Layer 0 vs 18 | Max Attention | 0.1732 | 0.6609 | 0.0000 |
| Layer 0 vs 23 | Betti₀ (Components) | 22.6900 | 1.6980 | 0.0000 |
| Layer 0 vs 23 | Betti₁ (Loops) | 20.9280 | 3.1920 | 0.0000 |
| Layer 0 vs 23 | Max Attention | 0.1732 | 0.3552 | 0.0000 |
| Layer 0 vs 23 | Dim0 Persistence | 0.0518 | 0.0155 | 0.0000 |
| Layer 0 vs 6 | Betti₀ (Components) | 22.6900 | 2.2880 | 0.0000 |
| Layer 0 vs 6 | Betti₁ (Loops) | 20.9280 | 5.5400 | 0.0000 |
| Layer 0 vs 6 | Max Attention | 0.1732 | 0.7441 | 0.0000 |
| Layer 0 vs 6 | Dim0 Persistence | 0.0518 | 0.0545 | 0.0187 |
| Layer 12 vs 18 | Betti₀ (Components) | 1.0140 | 1.0000 | 0.0080 |
| Layer 12 vs 18 | Betti₁ (Loops) | 8.5240 | 0.0000 | 0.0000 |
| Layer 12 vs 18 | Max Attention | 0.8139 | 0.6609 | 0.0000 |
| Layer 12 vs 23 | Betti₀ (Components) | 1.0140 | 1.6980 | 0.0000 |
| Layer 12 vs 23 | Betti₁ (Loops) | 8.5240 | 3.1920 | 0.0000 |
| Layer 12 vs 23 | Max Attention | 0.8139 | 0.3552 | 0.0000 |
| Layer 12 vs 23 | Dim0 Persistence | 0.0025 | 0.0155 | 0.0003 |
| Layer 18 vs 23 | Betti₀ (Components) | 1.0000 | 1.6980 | 0.0000 |
| Layer 18 vs 23 | Betti₁ (Loops) | 0.0000 | 3.1920 | 0.0000 |
| Layer 18 vs 23 | Max Attention | 0.6609 | 0.3552 | 0.0000 |
| Layer 6 vs 12 | Betti₀ (Components) | 2.2880 | 1.0140 | 0.0000 |
| Layer 6 vs 12 | Betti₁ (Loops) | 5.5400 | 8.5240 | 0.0000 |
| Layer 6 vs 12 | Max Attention | 0.7441 | 0.8139 | 0.0000 |
| Layer 6 vs 12 | Dim0 Persistence | 0.0545 | 0.0025 | 0.0000 |
| Layer 6 vs 18 | Betti₀ (Components) | 2.2880 | 1.0000 | 0.0000 |
| Layer 6 vs 18 | Betti₁ (Loops) | 5.5400 | 0.0000 | 0.0000 |
| Layer 6 vs 18 | Max Attention | 0.7441 | 0.6609 | 0.0000 |
| Layer 6 vs 23 | Betti₀ (Components) | 2.2880 | 1.6980 | 0.0000 |
| Layer 6 vs 23 | Betti₁ (Loops) | 5.5400 | 3.1920 | 0.0000 |
| Layer 6 vs 23 | Max Attention | 0.7441 | 0.3552 | 0.0000 |
| Layer 6 vs 23 | Dim0 Persistence | 0.0545 | 0.0155 | 0.0000 |

## All Test Results

For completeness, here are all statistical test results, significant or not:

| Comparison | Metric | Layer 1 Mean | Layer 2 Mean | p-value | Significant? |
|------------|--------|--------------|--------------|---------|-------------|
| Layer 0 vs 12 | Betti₀ (Components) | 22.6900 | 1.0140 | 0.0000 | Yes |
| Layer 0 vs 12 | Betti₁ (Loops) | 20.9280 | 8.5240 | 0.0000 | Yes |
| Layer 0 vs 12 | Max Attention | 0.1732 | 0.8139 | 0.0000 | Yes |
| Layer 0 vs 12 | Mean Attention | 0.0299 | 0.0299 | 1.0000 | No |
| Layer 0 vs 12 | Dim0 Persistence | 0.0518 | 0.0025 | 0.0000 | Yes |
| Layer 0 vs 18 | Betti₀ (Components) | 22.6900 | 1.0000 | 0.0000 | Yes |
| Layer 0 vs 18 | Betti₁ (Loops) | 20.9280 | 0.0000 | 0.0000 | Yes |
| Layer 0 vs 18 | Max Attention | 0.1732 | 0.6609 | 0.0000 | Yes |
| Layer 0 vs 18 | Mean Attention | 0.0299 | 0.0299 | 1.0000 | No |
| Layer 0 vs 23 | Betti₀ (Components) | 22.6900 | 1.6980 | 0.0000 | Yes |
| Layer 0 vs 23 | Betti₁ (Loops) | 20.9280 | 3.1920 | 0.0000 | Yes |
| Layer 0 vs 23 | Max Attention | 0.1732 | 0.3552 | 0.0000 | Yes |
| Layer 0 vs 23 | Mean Attention | 0.0299 | 0.0299 | 1.0000 | No |
| Layer 0 vs 23 | Dim0 Persistence | 0.0518 | 0.0155 | 0.0000 | Yes |
| Layer 0 vs 6 | Betti₀ (Components) | 22.6900 | 2.2880 | 0.0000 | Yes |
| Layer 0 vs 6 | Betti₁ (Loops) | 20.9280 | 5.5400 | 0.0000 | Yes |
| Layer 0 vs 6 | Max Attention | 0.1732 | 0.7441 | 0.0000 | Yes |
| Layer 0 vs 6 | Mean Attention | 0.0299 | 0.0299 | 1.0000 | No |
| Layer 0 vs 6 | Dim0 Persistence | 0.0518 | 0.0545 | 0.0187 | Yes |
| Layer 12 vs 18 | Betti₀ (Components) | 1.0140 | 1.0000 | 0.0080 | Yes |
| Layer 12 vs 18 | Betti₁ (Loops) | 8.5240 | 0.0000 | 0.0000 | Yes |
| Layer 12 vs 18 | Max Attention | 0.8139 | 0.6609 | 0.0000 | Yes |
| Layer 12 vs 18 | Mean Attention | 0.0299 | 0.0299 | 1.0000 | No |
| Layer 12 vs 23 | Betti₀ (Components) | 1.0140 | 1.6980 | 0.0000 | Yes |
| Layer 12 vs 23 | Betti₁ (Loops) | 8.5240 | 3.1920 | 0.0000 | Yes |
| Layer 12 vs 23 | Max Attention | 0.8139 | 0.3552 | 0.0000 | Yes |
| Layer 12 vs 23 | Mean Attention | 0.0299 | 0.0299 | 1.0000 | No |
| Layer 12 vs 23 | Dim0 Persistence | 0.0025 | 0.0155 | 0.0003 | Yes |
| Layer 18 vs 23 | Betti₀ (Components) | 1.0000 | 1.6980 | 0.0000 | Yes |
| Layer 18 vs 23 | Betti₁ (Loops) | 0.0000 | 3.1920 | 0.0000 | Yes |
| Layer 18 vs 23 | Max Attention | 0.6609 | 0.3552 | 0.0000 | Yes |
| Layer 18 vs 23 | Mean Attention | 0.0299 | 0.0299 | 1.0000 | No |
| Layer 6 vs 12 | Betti₀ (Components) | 2.2880 | 1.0140 | 0.0000 | Yes |
| Layer 6 vs 12 | Betti₁ (Loops) | 5.5400 | 8.5240 | 0.0000 | Yes |
| Layer 6 vs 12 | Max Attention | 0.7441 | 0.8139 | 0.0000 | Yes |
| Layer 6 vs 12 | Mean Attention | 0.0299 | 0.0299 | 1.0000 | No |
| Layer 6 vs 12 | Dim0 Persistence | 0.0545 | 0.0025 | 0.0000 | Yes |
| Layer 6 vs 18 | Betti₀ (Components) | 2.2880 | 1.0000 | 0.0000 | Yes |
| Layer 6 vs 18 | Betti₁ (Loops) | 5.5400 | 0.0000 | 0.0000 | Yes |
| Layer 6 vs 18 | Max Attention | 0.7441 | 0.6609 | 0.0000 | Yes |
| Layer 6 vs 18 | Mean Attention | 0.0299 | 0.0299 | 1.0000 | No |
| Layer 6 vs 23 | Betti₀ (Components) | 2.2880 | 1.6980 | 0.0000 | Yes |
| Layer 6 vs 23 | Betti₁ (Loops) | 5.5400 | 3.1920 | 0.0000 | Yes |
| Layer 6 vs 23 | Max Attention | 0.7441 | 0.3552 | 0.0000 | Yes |
| Layer 6 vs 23 | Mean Attention | 0.0299 | 0.0299 | 1.0000 | No |
| Layer 6 vs 23 | Dim0 Persistence | 0.0545 | 0.0155 | 0.0000 | Yes |
