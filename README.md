# Bird-Eye View to Street View: A Survey

This repository contains the supplementary materials for our survey paper titles _<a href="https://arxiv.org/abs/2405.08961" target="_blank">Bird-Eye View to Street-View : A Survey</a>_. In this paper, we review various methods in bird-eye view to street-view synthesis domain, we categorized each method based on applied techniques, and summarizing the keys advancement in the field. 

**Table of Contents:**
- Conditional GAN-based Models.
- Multi Generator and Discriminator Models.
- Image-to-Image Translation Frameworks.
- Representation-based Models.
- Geometric Correspondence Models.
- Siamese Network-based Models.
- MLP-based Models.
- Recent Advancements. 

**Citing this work**

If you find this repository helpful, please cite our survey.

<pre> @article{bajbaa2024bird,
  title={Bird's-Eye View to Street-View: A Survey},
  author={Bajbaa, Khawlah and Usman, Muhammad and Anwar, Saeed and Radwan, Ibrahim and Bais, Abdul},
  journal={arXiv preprint arXiv:2405.08961},
  year={2024}
} </pre>


# 1. Conditional GAN-based Models.

1. Cross-view image synthesis using conditional gans, _Regmi et. al_, **2018**, CVPR, [[Open Access](https://openaccess.thecvf.com/content_cvpr_2018/html/Regmi_Cross-View_Image_Synthesis_CVPR_2018_paper.html)]. (X-fork)

2. What is it like down there? generating dense
ground-level views and image features from
overhead imagery using conditional generative adversarial networks, _Deng et. al_, **2018**, 26th acm sigspatial international conference on advances in geographic information
systems, [[Open Access](https://dl.acm.org/doi/abs/10.1145/3274895.3274969)]. (cGANs)


2. Bridging the domain gap for ground-to-aerial image
matching, _Regmi et. al_, **2019**, ICCV, [[Open Access](https://openaccess.thecvf.com/content_ICCV_2019/html/Regmi_Bridging_the_Domain_Gap_for_Ground-to-Aerial_Image_Matching_ICCV_2019_paper.html)] (feature fusion)

3. Geometry-aware satellite-to-ground image synthesis
for urban areas, _Lu et. al_, **2020**, CVPR, [[Open Access](https://openaccess.thecvf.com/content_CVPR_2020/html/Lu_Geometry-Aware_Satellite-to-Ground_Image_Synthesis_for_Urban_Areas_CVPR_2020_paper.html)]. (GeoUrban)

4. Cross-view panorama image synthesis, _Wu et. al_, **2022**, IEEE Transactions on Multimedia, [[Open Access](https://ieeexplore.ieee.org/abstract/document/9743312)]. PanoGAN

# 2. Multi Generator and Discriminator Models.

1. Generative Adversarial Frontal View to Bird View Synthesis, _Zhu et. al_, **2018**, 2018 International Conference on 3D Vision (3DV), [[Open Access](https://ieeexplore.ieee.org/abstract/document/8490997)]. (BridgeGAN)

2. Multi-Channel Attention Selection GAN With Cascaded Semantic Guidance for Cross-View Image Translation, _Tang et. al_, **2019**, CVPR, [[Open Access](https://openaccess.thecvf.com/content_CVPR_2019/html/Tang_Multi-Channel_Attention_Selection_GAN_With_Cascaded_Semantic_Guidance_for_Cross-View_CVPR_2019_paper.html)]. SelectionGAN.

4. Local Class-Specific and Global Image-Level Generative Adversarial Networks for Semantic-Guided Scene Generation, _Tang et. al_, **2020**, CVPR [[Open Access](https://openaccess.thecvf.com/content_CVPR_2020/html/Tang_Local_Class-Specific_and_Global_Image-Level_Generative_Adversarial_Networks_for_Semantic-Guided_CVPR_2020_paper.html)]. LGGAN

3. Cross-view panorama image synthesis with progressive
attention gans, _Wu et. al_, **2022**, Pattern Recognition, [[Pattern Recognition (Elsevier)](https://www.sciencedirect.com/science/article/abs/pii/S003132032200365X?via%3Dihub)]. PAGAN


# 3. Image-to-Image Translation Frameworks.

1. Image-To-Image Translation With Conditional Adversarial Networks, _Isola et. al_, **2017**, CVPR, [[Open Access](https://openaccess.thecvf.com/content_cvpr_2017/html/Isola_Image-To-Image_Translation_With_CVPR_2017_paper.html)]. Pix2pix


# 4. Representation-based Models.

1. Wide-Area Image Geolocalization With Aerial Reference Imagery, _Workman et. al_, **2015**, ICCV, [[Open Access](https://openaccess.thecvf.com/content_iccv_2015/html/Workman_Wide-Area_Image_Geolocalization_ICCV_2015_paper.html)]. WAGL.

2. Predicting Ground-Level Scene Layout From Aerial Imagery, _Zhai et. al_, **2017**, CVPR, [[Open Access](https://openaccess.thecvf.com/content_cvpr_2017/html/Zhai_Predicting_Ground-Level_Scene_CVPR_2017_paper.html)]. PGSL

# 5. Geometric Correspondence Models

1. Localizing and orienting street views using overhead imagery, _Vo et. al_, **2016**,  Computer Vision – ECCV 2016, [[Open Access](https://link.springer.com/chapter/10.1007/978-3-319-46448-0_30)]. CrossViewGT


2. CVM-Net: Cross-View Matching Network for Image-Based Ground-to-Aerial Geo-Localization, _Hu et. al_, **2018**, CVPR, [[Open Access](https://openaccess.thecvf.com/content_cvpr_2018/html/Hu_CVM-Net_Cross-View_Matching_CVPR_2018_paper.html)]. CVM-Net

1. Lending Orientation to Neural Networks for Cross-View Geo-Localization, _Liu et. al_, **2019**,CVPR, [[Open Access](https://openaccess.thecvf.com/content_CVPR_2019/html/Liu_Lending_Orientation_to_Neural_Networks_for_Cross-View_Geo-Localization_CVPR_2019_paper.html)]. LONN


1. Where am i looking at? joint location and
orientation estimation by cross-view match-
ing, _Shi et. al_, **2020**, CVPR, [[Open Access](https://openaccess.thecvf.com/content_CVPR_2020/html/Shi_Where_Am_I_Looking_At_Joint_Location_and_Orientation_Estimation_CVPR_2020_paper.html)] JLO

1. Coming down to earth: Satellite-to-street view synthesis for geo-localization, _Toker et. al_, **2021**, CVPR, [[Open Access](https://openaccess.thecvf.com/content/CVPR2021/html/Toker_Coming_Down_to_Earth_Satellite-to-Street_View_Synthesis_for_Geo-Localization_CVPR_2021_paper.html)]. SSVS

2. Geometry-guided street-view panorama
synthesis from satellite imagery, _Shi et. al_, **2022**, IEEE Transactions on Pattern Analysis and Machine Intelligence, [[TPAMI](https://ieeexplore.ieee.org/abstract/document/9674229)]. SSVG


# 6. Siamese Network-based Models.

1. Learning Deep Representations for Ground-to-Aerial Geolocalization, _Lin et. al_, **2015**, CVPR, [[Open Access](https://www.cv-foundation.org/openaccess/content_cvpr_2015/html/Lin_Learning_Deep_Representations_2015_CVPR_paper.html)].

# 7. MLP-based Models.

1. Cascaded Cross MLP-Mixer GANs for Cross-View Image Translation, _Ren et. al_, **2021**, [[arXiv](https://arxiv.org/abs/2110.10183)]. CrossMLP

# 8. Recent Advancements. 
1. Street-View Image Generation From a Bird's-Eye View Layout, _Swerdlow et. al_, **2024**, [[LRA](https://ieeexplore.ieee.org/abstract/document/10443014)]. BevGen

2. Sat2Scene: 3D Urban Scene Generation from Satellite Images with Diffusion, _Li et. al_, **2024**, CVPR, [[Open Access](https://openaccess.thecvf.com/content/CVPR2024/html/Li_Sat2Scene_3D_Urban_Scene_Generation_from_Satellite_Images_with_Diffusion_CVPR_2024_paper.html)]. Sat2Scene

3. CrossViewDiff: A Cross-View Diffusion Model for Satellite-to-Street View Synthesis, _Li et. al_, **2024**, [[arXive](https://arxiv.org/abs/2408.14765)].



