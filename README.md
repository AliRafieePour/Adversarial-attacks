# Adversarial-attacks
In this project, I have proposed and compared many variations of fuzzers and GA algorithms to generate adversarial examples.
## Fuzzers include:
* Random fuzzer
* Random fuzzer with normal distribution
* Random fuzzer with laplace distribution
* Random fuzzer with gumbel distribution
* Random fuzzer + SSIM similarity index
* Random fuzzer with normal distribution + SSIM similarity index
* Random fuzzer with laplace distribution + SSIM similarity index
* Random fuzzer with gumbel distribution + SSIM similarity index
* Random fuzzer + ISSM similarity index
* Random fuzzer with normal distribution + ISSM similarity index
* Random fuzzer with laplace distribution + ISSM similarity index
* Random fuzzer with gumbel distribution + ISSM similarity index
## GA algorithms include:
* GA algorithm with simple random function
* GA algorithm with gumbel random function and with SSIM similarity index considerd
## Approach
All proposed algorithms are tested on MNIST and CIFAR10 dataset with two ANN, and CNN trained models.
## Results
Most comparisons are done in the notebooks, but in general considering similarity index of images with the parent has shown great importance and significant differences.
