# awesome-site-effects
Repository containing information about batch effects in neuroimaging

- [Review papers](#Review papers)
- [ComBat papers](#ComBat papers)



### Review papers

Hu, F., Chen, A. A., Horng, H., Bashyam, V., Davatzikos, C., Alexander-Bloch, A., Li, M., Shou, H., Satterthwaite, T. D., Yu, M., & Shinohara, R. T. (2023). Image harmonization: A review of statistical and deep learning methods for removing batch effects and evaluation metrics for effective harmonization. NeuroImage, 274, 120125. [Link](https://www.sciencedirect.com/science/article/pii/S1053811923002719)

Bayer, J. M. M., Thompson, P. M., Ching, C. R. K., Liu, M., Chen, A., Panzenhagen, A. C., Jahanshad, N., Marquand, A., Schmaal, L., & Sämann, P. G. (2022). Site effects how-to and when: An overview of retrospective techniques to accommodate site effects in multi-site neuroimaging analyses. Frontiers in Neurology, 13, 923988.

Da-Ano, R., Visvikis, D., & Hatt, M. (2020). Harmonization strategies for multicenter radiomics investigations. Physics in Medicine and Biology, 65(24), 24TR02.

Ibrahim, A., Primakov, S., Beuque, M., Woodruff, H. C., Halilaj, I., Wu, G., Refaee, T., Granzier, R., Widaatalla, Y., Hustinx, R., Mottaghy, F. M., & Lambin, P. (2021). Radiomics for precision medicine: Current challenges, future prospects, and the proposal of a new framework. Methods (San Diego, Calif.), 188, 20–29.

Mali, S. A., Ibrahim, A., Woodruff, H. C., Andrearczyk, V., Müller, H., Primakov, S., Salahuddin, Z., Chatterjee, A., & Lambin, P. (2021). Making radiomics more reproducible across scanner and imaging protocol variations: A review of harmonization methods. Journal of Personalized Medicine, 11(9), 842.

Pinto, M. S., Paolella, R., Billiet, T., Van Dyck, P., Guns, P.-J., Jeurissen, B., Ribbens, A., den Dekker, A. J., & Sijbers, J. (2020). Harmonization of Brain Diffusion MRI: Concepts and Methods. Frontiers in Neuroscience, 14, 396.

Stamoulou, E., Spanakis, C., Manikis, G. C., Karanasiou, G., Grigoriadis, G., Foukakis, T., Tsiknakis, M., Fotiadis, D. I., & Marias, K. (2022). Harmonization Strategies in Multicenter MRI-Based Radiomics. The Journal of Imaging Science and Technology / IS&T, the Society for Imaging Science and Technology, 8(11). https://doi.org/10.3390/jimaging8110303

### ComBat Papers


### Extension of ComBat papers

#### ComBat Gam 
Pomponio, R., Erus, G., Habes, M., Doshi, J., Srinivasan, D., Mamourian, E., Bashyam, V., Nasrallah, I. M., Satterthwaite, T. D., Fan, Y., Launer, L. J., Masters, C. L., Maruff, P., Zhuo, C., Völzke, H., Johnson, S. C., Fripp, J., Koutsouleris, N., Wolf, D. H., … Davatzikos, C. (2020). Harmonization of large MRI datasets for the analysis of brain imaging patterns throughout the lifespan. NeuroImage, 208, 116450. [Link](https://www.sciencedirect.com/science/article/pii/S1053811919310419)

###### Paper summary:
-  Combat with a Gam model for non-linear modelling of covariates (covariates in the papers are age, sex and intercranial volume (ICF)
-  tested on a 18 number of data sets (n > 10000) covering full age range
-  implementation in Python
[Link to repository](https://github.com/rpomponio/neuroHarmonize)

#### Covbat 

##### Paper summary
- tests for site effects not only in mean and variance, but also in covariance
- Link to repository
  
### Papers that show the downsides of Combat

Price, E. M., & Robinson, W. P. (2018). Adjusting for batch effects in DNA methylation microarray data, a lesson learned. Frontiers in Genetics, 9, 83.
[Link](https://pubmed.ncbi.nlm.nih.gov/29616078/)

Zindler, T., Frieling, H., Neyazi, A., Bleich, S., & Friedel, E. (2020). Simulating ComBat: How batch correction can lead to the systematic introduction of false positive results in DNA methylation microarray studies. BMC Bioinformatics, 21(1), 1–15. [Link](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-020-03559-6)

Nygaard, V., Rødland, E. A., & Hovig, E. (2016). Methods that remove batch effects while retaining group differences may lead to exaggerated confidence in downstream analyses. Biostatistics , 17(1), 29–39. [Link](https://pubmed.ncbi.nlm.nih.gov/26272994/)

### GANs for site efffect correction

### Normative modelling for site effect correction

