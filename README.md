# USED splits
These tsv files contain the information of the splits used in the USED paper. Each tsv file consists of 5 fields in the following order: mixture id, mixture path, extraction output path, reference speech path, speaker id. 

The paths are relative paths. The reference speech files are chosen randomly from the LibriSpeech samples of the same speaker. This randomness can change the performance. Hence, we provide these tsv files to ensure that future experiments can conduct a fair comparison. 

We also add the test split for the SparseLibriMix dataset. This tsv file contains 4 fields in the following order: mixture id, mixture path, reference speech path, speaker id. 

Again the choice of the reference speech is random, hence we provide this tsv file to ensure the reproducibility of our results for future experiments. Note that this file is only for overlap ratio 0. For the other overlap ratios, the same reference speech choice is used for the same mixture ids. Hence, you should modify the mixture path according to the overlap ratio to get the tsv files for the other overlap ratios.
