# A-GAM-Study-on-the-OneStop-L2-Corpus
we ask whether second-language (L2) readers are more sensitive to lexical surprisal than native (L1) readers. Using the OneStop Eye Movements} datasets Ordinary Reading for L1 OneStopL2 for L2 ,we compute word-by-word surprisal from Pythia-70M with streaming left-to-right inference and fit GAM for FFD,FRD,TFD, controlling length and log frequency.

Code and notebooks for analyzing whether full-context neural **surprisal** explains more reading-time variance for **L2** than **L1** readers using the **OneStop Eye-Movements – Ordinary Reading** corpus.  
Models: EleutherAI `pythia-70m` for surprisal; GAMs (`pygam`) for statistics.

- Compute full-context token surprisal with `pythia-70m`.
- Fit separate GAMs for L1 and L2 on **FFD**, **FRD**, **TFD** with controls (length, log frequency, position).
- Compare unique contributions (ΔR²) of **frequency vs. surprisal**.
- Key finding (fill with your numbers): Surprisal contributes ~X.X pp more ΔR² for L2 than L1 in FFD; no reliable group difference in TFD/FRD.
