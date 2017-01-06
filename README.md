# Leveraging anatomical information to improve transfer learning in brain–computer interfaces
Mark Wronkiewicz, Eric Larson and Adrian KC Lee (2015). _Journal of Neural
Engineering_ 12(4), 046027. http://stacks.iop.org/1741-2552/12/i=4/a=046027

This paper is aimed at improving the ability to calibrate BCI classifiers using data recycled from other subjects (i.e., transfer learning). Transfer learning is an important area in BCIs because it attempts to address the limitation that traditional BCI systems currently take 20-30 minutes to train before they are calibrated and ready to use -- a major problem for clinical applications. Here, we project EEG data to the surface of the brain, using a technique called source imaging, prior to transferring data for the training other subjects' BCI classifiers. A source-based approach is advantageous because it partially accounts for differences in head and brain shape as well as variance or errors in EEG electrode positioning. This is in contrast to standard sensor-based approaches where these sources of variability will impede the ability to learn something from one BCI user and apply it to another subject's system. Through both simulated and actual data, we found that a BCI classifier trained _solely_ with data from about 5-7 other subjects (and transferred through the source space) matched the accuracy of a traditional subject-specific BCI. Importantly, this approach requires _no training data_ from the subject under study, and therefore, is a step towards reducing the 20-30 minute calibration period that is still needed in traditional BCIs.
