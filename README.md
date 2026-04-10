# astr302_pulsating_star
This repository contains the raw data and the data processing pipeline (reduction and aperture photometry)

Workflow described by Dr. Green:
1) Bias subtraction & flatfielding of raw data
2) Use existing cosmic ray removal routine or create custom (should not affect data)
3) Use imdat to identify our stars, either solve for or take for granted best-fit SNR of star position and extent
4) Send her HJD time versus normalized star brightnesses from processed files so she can interpolate the timesteps for FFT
5) Receive files back from her and do FFT
