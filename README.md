# Symbolization-of-Time-series-and-calculation-of-Entropy

### Workflow to Calculate Entropy of a list of Time Series after their symbolization

Normalised Corrected Shannon Entropy is calculated for different time series.
The following steps are performed on a Signal or time series  ' $T$ ' . 
> 1. Mean is calculated for $T$.
> 2. A **Threshold** value $\theta$ is chosen and $T$ is converted into a sequence of 0s and 1s based on threshold.
> 3. This binary sequence is converted into a word sequence based on a choice of **Wordlength** $w$. The data points are grouped into words based on a moving window having it's size equal to the word length.
> 4. The number of possible words are finite and are based on the chosen wordlength.
> 5. Entropy is calculated for these sequence of words. The quantity calculated here is a modified form of the Shannon Entropy called Normalised Corrected Shannon Entropy.

The details of the method can be obtained here [  Hussain, L., Aziz, W., Alowibdi, J.S. et al. ](https://jphysiolanthropol.biomedcentral.com/articles/10.1186/s40101-017-0136-8)
The method was performed on two datasets (EEG and ECG Signals) as part of a project to distinguish different type of signals using NCSE. A detailed report can be sent. Mail at nayantelrandhe150@gmail.com
