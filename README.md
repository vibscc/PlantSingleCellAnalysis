# Plant Single Cell Analysis
Analysis pipeline for plant scRNA-seq data

## Citations

This github accompanies the book chapter "Development and application of scRNA-seq in Arabidopsis root using 10X-genomics based technology" (Methods. Mol. Biol., XXX?) and the processing pipeline was used in:
- Wendrich, J. R., Yang, B., Vandamme, N., Verstaen, K., Smet, W., Van De Velde, C., Minne, M., Wybouw, B., Mor, E., Arents, H. E., Nolf, J., Duyse, J. Van, Van Isterdael, G., Maere, S., Saeys, Y., & De Rybel, B. (2020). Vascular transcription factors guide plant epidermal responses to limiting phosphate conditions. Science, 370. https://doi.org/10.1126/science.aay4970
- Yang, B. J., Minne, M., Brunoni, F., Plačková, L., Petřík, I., Sun, Y., Nolf, J., Smet, W., Verstaen, K., Wendrich, J. R., Eekhout, T., Hoyerová, K., Van Isterdael, G., Haustraete, J., Bishopp, A., Farcot, E., Novák, O., Saeys, Y., & De Rybel, B. (2021). Non-cell autonomous and spatiotemporal signalling from a tissue organizer orchestrates root vascular development. Nature Plants 2021 7:11, 7(11), 1485–1494. https://doi.org/10.1038/s41477-021-01017-6

## Dependencies

R (>=3.6.0)
R packages: Seurat (>= 4.0), scater, dplyr, ggplot2


Here, we will show the analysis steps that we use to process a single-cell RNA-seq dataset, starting from a cellranger count matrix and ending with a Seurat object.

## Acknowledgements

The processing pipelines that are described here and the explanations were co-developed between the VIB Single Cell Core, VIB Bioinformatics Core, the Plant Single Cell Platform (VIB-UGent Center for Plant Systems Biology) and the group of Yvan Saeys (VIB-UGent Center for Inflammation Research).
