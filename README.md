# Music_Genre_Classification
From the birth of AI algorithms, there were few -
successful or less - attempts to project a full-working ML model
for music classification. In particular, one of the most challenging
tasks has been genre recognition. Among the best results obtained
in this field, it is worth mentioning the work made by Tzanetakis
et al.: first of all, it provided the GTZAN dataset, which
has become the main and most complete source for the abovementioned assignment; moreover, it granted a baseline, based
on simple ML structures, for future developements. Here, the
models exploited three different set of frequency-based features
that were directly extracted from audio signals.

This paper firstly reproduces the described approach, and
then takes the task to the state of the art by exploiting the
power of CRNNs, an established deep framework that succeeds
in understanding temporal structure in audio spectrograms,
following the approach described by Nasrullah et al.


The best performing model achieved an average F1 score
of 0.8920 from three independent trials, with a micro-precision
equal to 1.0 for 5 out of 10 genres it has been trained with. The
results obtained strongly outperform both the results obtained
with SVM and previous CRNN based attempts.
