# Calculating the Limit of Stokesian Settling in Wastewater

## Summary
In wastewater treatment, clarifiers are critical to maintain clear effluent. **The limit of stokesian settling (LOSS) parameter measures the total suspended solids (TSS) concentration at which clarifier failures occur.** LOSS characterizes a wastewater transition from a faster settling or flocculent regime to a slower or hindered regime. A limitation in measurement of LOSS was visual subjectivity. 

In this project, three methods employing grayscale image data were introduced for measuring LOSS. They used simple linear regression, sigmoid fitting, noise (standard deviations in grayscale index) respectively and were tested for consistency in changing light exposure settings, settling time and sludge quality. Light exposure impacted the measurements at very bright settings, by decreasing the sensitivity of calculations, while longer settling times for taking measurements (> 50 s) also reduced the sensitivity. **Noise (light dispersion in the wastewater) calculations provided the least variability in LOSS from the methods, and was promising to use as a metric for LOSS.**

![](https://github.com/OlaOlagunju/LOSS_Project/blob/main/fig_14.jpg)
