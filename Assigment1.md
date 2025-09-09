The Questions

1. Write a program using OpenCV to read an RGB image, convert it into grayscale,
visualise the individual colour channels (R, G, B), and compute as well as display
the histogram for each channel. (Marks:2)
2. Using OpenCV, read an RGB image, add Gaussian noise to it (e.g., mean = 0,
variance = 10–20). Then, on the noisy image:
1. Convert it to grayscale.
2. Visualise the individual colour channels (R, G, B) and the grayscale image.
3. Compute and display the histogram for each channel (R, G, B) and for the
grayscale image.
All plots must be clearly labelled. (Marks:3)

3. Apply three different filters of sizes 3 × 3, 5 × 5, and 7 × 7 on an image with and
without Gaussian noise. Perform edge detection using the following methods:
1. Sobel edge detector

2. Edge detection using the Sobel operator in both horizontal and vertical direc-
tions

3. Laplacian edge detector
Compare and describe the differences observed in edge detection results across the
filters, kernel sizes, and noise conditions. (Marks:5)
4. Implement the Canny edge detector from scratch by following these steps:
1. Apply Gaussian smoothing.
2. Compute gradient magnitude and orientation using Sobel filters.
3. Apply non-maximum suppression.
4. Apply hysteresis thresholding (use two thresholds).
Apply your implementation to both a clean image and a noisy image. Show how
noise affects the results. (Marks:5)
