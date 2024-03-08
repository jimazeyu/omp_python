# Finding Sparse Solutions via Orthogonal Matching Pursuit (OMP)

## Installation
```bash
conda create -n omp python=3.8
conda activate omp
pip install -r requirements.txt
```

## Usage
- Put the image data within "data" and the sound data within "sound_data".
- "sol_noiseless.ipynb" for noiseless case. 
- "sol_noise_a.ipynb"  for noisy case with known sparsity.
- "sol_noise_b.ipynb"  for noisy case with known norm.
- "sol_image" for the recovery of the images.
- "sol_sound" for the recovery of the sound.
- Project requirements and the report is within the folder "docs".