# Signal-Analysis-Using-FFT
This code tries to implement signal denoising of financial data using Fast Fourier Transform (FFT)



As you may be knowing Fourite Transform is a way to mathematically represent any waves as a sum of sine waves of varying frequency, i.e, coverting a signal from time domain to frequency domain. 

The FFT algorithm discussed here in this project uses signal processing to detect the most significant frequencies and therefore removing noise from data.

   ![alt text](https://stemporium.blog/wp-content/uploads/2023/04/3311485_orig.gif)



Steps in Applying FFT to financial data:
1. Accquiring data: OHLCAV data was extracted for a stock and stored in a data file (in this case TCS).
2. Transform: Apply the FFT algorithm to convert the time-domain data into the frequency domain.
3. Analysis: Identify significant frequencies and their amplitudes to understand the periodic components.
4. Post-processing: Filter out unwanted frequencies and transform back to the time domain if needed, along with the overlay of processed signal and the original signal.

