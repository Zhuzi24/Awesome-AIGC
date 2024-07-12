[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/Zhuzi24/Awesome-AIGC/graphs/commit-activity)
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/Zhuzi24/Awesome-AIGC)
<img alt="GitHub watchers" src="https://img.shields.io/github/watchers/Zhuzi24/Awesome-AIGC?style=social"> <img alt="GitHub stars" src="https://img.shields.io/github/stars/Zhuzi24/Awesome-AIGC?style=social"> <img alt="GitHub forks" src="https://img.shields.io/github/forks/Zhuzi24/Awesome-AIGC?style=social">

<div align="center">
<h1> Awesome-AIGC </h1> 
</div>

<!-- CVPR-8A2BE2 -->
<!-- WACV-6a5acd -->
<!-- NIPS-CD5C5C -->
<!-- ICML-FF7F50 -->
<!-- ICCV-00CED1 -->
<!-- ECCV-1e90ff -->
<!-- TPAMI-BC8F8F -->
<!-- IJCAI-228b22 -->
<!-- AAAI-c71585 -->
<!-- arXiv-b22222 -->
<!-- ACL-191970 -->
<!-- TPAMI-ffa07a -->


# 🎀 Introduction 
This is a collection of AIGC, including text-to-image, text-to-3D, graph-to-3D, etc. Welcome star, fork and PR !
  <!-- <p align="center">
  <img src="assets/intro1.png" width="75%">
</p> -->

---

 # 📘 Table of Contents
- [🎀 Introduction](#-introduction)
- [🚠 Datasets](#-datasets)
- [🍁 3D Synthesis](#-3D-Synthesis)
- [🍎 Image Generetion](#-Image-Generetion)
- [⭐️ Star History](#️-star-history)


---


# 🚠 Datasets
<p align="center">

| Dataset |  Modality  |   Obj. Class  | CAD. models | Rela. Class | Triplets | Model. Textures | 
|:--------:|:--------:|:--------:| :--------:|  :--------:|  :--------:|  :--------:|
| [3D Semantic Scene Graphs (3DSSG)](https://openaccess.thecvf.com/content_CVPR_2020/papers/Wald_Learning_3D_Semantic_Scene_Graphs_From_3D_Indoor_Reconstructions_CVPR_2020_paper.pdf) ![Paper](https://img.shields.io/badge/CVPR20-8A2BE2) | 3D | 160 | N/A | 26 | N/A | Rec. fromScan |
| [3D Furnished Rooms With layOuts and semaNTics (3D-FRONT) ![Paper](https://img.shields.io/badge/ICCV21-00CED1)](https://openaccess.thecvf.com/content/ICCV2021/papers/Fu_3D-FRONT_3D_Furnished_Rooms_With_layOuts_and_semaNTics_ICCV_2021_paper.pdf) | 3D | 23 | 13151 | N/A | N/A | Professional| 
| [SG-FRONT ![Paper](https://img.shields.io/badge/NeurIPS21-CD5C5C)](https://proceedings.neurips.cc/paper_files/paper/2023/file/5fba70900a84a8fb755c48ba99420c95-Paper-Conference.pdf) <img alt="GitHub stars" src="https://img.shields.io/github/stars/ymxlzgy/commonscenes?style=social"> <img alt="GitHub forks" src="https://img.shields.io/github/forks/ymxlzgy/commonscenes?style=social">  | 3D | 23 | 13151 | 15 | 45000 | Professional| 

</p>
Note: “N/A”=“not available”, “Rec. fromScan” is the result of reconstruction from raw RGB-D data.

---

# 🍁 3D Synthesis

## 🌿 Graph-to-3D
+ [**Graph-to-3D: End-to-End Generation and Manipulation of 3D Scenes Using Scene Graphs** ![Paper](https://img.shields.io/badge/ICCV21-00CED1)](https://openaccess.thecvf.com/content/ICCV2021/papers/Dhamo_Graph-to-3D_End-to-End_Generation_and_Manipulation_of_3D_Scenes_Using_Scene_ICCV_2021_paper.pdf) <img alt="GitHub stars" src="https://img.shields.io/github/stars/he-dhamo/graphto3d?style=social"> <img alt="GitHub forks" src="https://img.shields.io/github/forks/he-dhamo/graphto3d?style=social"> 


 + [**CommonScenes: Generating Commonsense 3D Indoor Scenes with Scene Graph Diffusion** ![Paper](https://img.shields.io/badge/NeurIPS23-CD5C5C)](https://proceedings.neurips.cc/paper_files/paper/2023/file/5fba70900a84a8fb755c48ba99420c95-Paper-Conference.pdf) <img alt="GitHub stars" src="https://img.shields.io/github/stars/ymxlzgy/commonscenes?style=social"> <img alt="GitHub forks" src="https://img.shields.io/github/forks/ymxlzgy/commonscenes?style=social">

+ [**Compositional 3D Scene Synthesis with Scene Graph Guided Layout-Shape Generation** ![Paper](https://img.shields.io/badge/arXiv24-b22222)](https://arxiv.org/pdf/2403.12848)

  <b>Note:</b> Graph-to-3D (Semi-generative), CommonScenes (Generative (baseline)), and Compositional 3D (Generative while focusing on the layout) can be understood together.

 + [**GraphDreamer: Compositional 3D Scene Synthesis from Scene Graphs** ![Paper](https://img.shields.io/badge/CVPR24-8A2BE2)](https://openaccess.thecvf.com/content/CVPR2024/papers/Gao_GraphDreamer_Compositional_3D_Scene_Synthesis_from_Scene_Graphs_CVPR_2024_paper.pdf) <img alt="GitHub stars" src="https://img.shields.io/github/stars/GGGHSL/GraphDreamer?style=social"> <img alt="GitHub forks" src="https://img.shields.io/github/forks/GGGHSL/GraphDreamer?style=social">

   <b>Note:</b> GraphDreamer do not need 3D bbox.

 + [**EchoScene: Indoor Scene Generation via Information Echo over Scene Graph Diffusion** ![Paper](https://img.shields.io/badge/ECCV24-1e90ff)](https://arxiv.org/pdf/2405.00915) <img alt="GitHub stars" src="https://img.shields.io/github/stars/ymxlzgy/echoscene?style=social"> <img alt="GitHub forks" src="https://img.shields.io/github/forks/ymxlzgy/echoscene?style=social">


## ☘️ Diffusion for 3D
 + [**DiffuScene: Denoising Diffusion Models for Generative Indoor Scene Synthesis** ![Paper](https://img.shields.io/badge/CVPR24-8A2BE2)](https://openaccess.thecvf.com/content/CVPR2024/papers/Tang_DiffuScene_Denoising_Diffusion_Models_for_Generative_Indoor_Scene_Synthesis_CVPR_2024_paper.pdf) <img alt="GitHub stars" src="https://img.shields.io/github/stars/tangjiapeng/DiffuScene?style=social"> <img alt="GitHub forks" src="https://img.shields.io/github/forks/tangjiapeng/DiffuScene?style=social">

## 🍃Text-to-3D

 + [**GVGEN:Text-to-3D Generation with Volumetric Representation** ![Paper](https://img.shields.io/badge/ECCV24-1e90ff)](https://arxiv.org/pdf/2403.12957) <img alt="GitHub stars" src="https://img.shields.io/github/stars/SOTAMak1r/GVGEN?style=social"> <img alt="GitHub forks" src="https://img.shields.io/github/forks/SOTAMak1r/GVGEN?style=social">

 + [**ScaleDreamer: Scalable Text-to-3D Synthesis with Asynchronous Score Distillation** ![Paper](https://img.shields.io/badge/ECCV24-1e90ff)]( https://arxiv.org/abs/2407.02040) <img alt="GitHub stars" src="https://img.shields.io/github/stars/theEricMa/ScaleDreamer?style=social"> <img alt="GitHub forks" src="https://img.shields.io/github/forks/theEricMa/ScaleDreamer?style=social">

 + [**VividDreamer: Invariant Score Distillation For Hyper-Realistic Text-to-3D Generation** ![Paper](https://img.shields.io/badge/ECCV24-1e90ff)]() <img alt="GitHub stars" src="https://img.shields.io/github/stars/SupstarZh/VividDreamer?style=social"> <img alt="GitHub forks" src="https://img.shields.io/github/forks/SupstarZh/VividDreamer?style=social">




## 🍀 LLM for 3D and Image

 + [**SceneX:Procedural Controllable Large-scale Scene Generation via Large-language Models** ![Paper](https://img.shields.io/badge/arXiv24-b22222)](https://arxiv.org/pdf/2403.15698) <img alt="GitHub stars" src="https://img.shields.io/github/stars/SceneX-LAB/SceneX-LAB?style=social"> <img alt="GitHub forks" src="https://img.shields.io/github/forks/SceneX-LAB/SceneX-LAB?style=social">

# 🍎 Image Generetion
## 🍊 Text-to-Image
 + [**Adversarial Text to Continuous Image Generation** ![Paper](https://img.shields.io/badge/CVPR24-8A2BE2)](https://openaccess.thecvf.com/content/CVPR2024/papers/Haydarov_Adversarial_Text_to_Continuous_Image_Generation_CVPR_2024_paper.pdf) <img alt="GitHub stars" src="https://img.shields.io/github/stars/Kilichbek/hypercgan?style=social"> <img alt="GitHub forks" src="https://img.shields.io/github/forks/Kilichbek/hypercgan?style=social">

 + [**Attention Calibration for Disentangled Text-to-Image Personalization** ![Paper](https://img.shields.io/badge/CVPR24-8A2BE2)](https://openaccess.thecvf.com/content/CVPR2024/papers/Zhang_Attention_Calibration_for_Disentangled_Text-to-Image_Personalization_CVPR_2024_paper.pdf) <img alt="GitHub stars" src="https://img.shields.io/github/stars/Monalissaa/DisenDiff?style=social"> <img alt="GitHub forks" src="https://img.shields.io/github/forks/Monalissaa/DisenDiff?style=social">


 + [**Text2Street: Controllable Text-to-image Generation for Street Views** ![Paper](https://img.shields.io/badge/arXiv24-b22222)](https://arxiv.org/pdf/2402.04504)

 + [**AnyControl: Create Your Artwork with Versatile Control on Text-to-Image Generation** ![Paper](https://img.shields.io/badge/ECCV24-1e90ff)](https://arxiv.org/abs/2406.18958) <img alt="GitHub stars" src="https://img.shields.io/github/stars/open-mmlab/AnyControl?style=social"> <img alt="GitHub forks" src="https://img.shields.io/github/forks/open-mmlab/AnyControl?style=social">

 + [**Getting it Right: Improving Spatial Consistency in Text-to-Image Models** ![Paper](https://img.shields.io/badge/ECCV24-1e90ff)](https://arxiv.org/abs/2404.01197) <img alt="GitHub stars" src="https://img.shields.io/github/stars/SPRIGHT-T2I/SPRIGHT?style=social"> <img alt="GitHub forks" src="https://img.shields.io/github/forks/SPRIGHT-T2I/SPRIGHT?style=social">

 + [**MasterWeaver: Taming Editability and Identity for Personalized Text-to-Image Generation** ![Paper](https://img.shields.io/badge/ECCV24-1e90ff)](https://arxiv.org/abs/2405.05806) <img alt="GitHub stars" src="https://img.shields.io/github/stars/csyxwei/MasterWeaver?style=social"> <img alt="GitHub forks" src="https://img.shields.io/github/forks/csyxwei/MasterWeaver?style=social">



# ⭐️ Star History

[![Star History Chart](https://api.star-history.com/svg?repos=Zhuzi24/Awesome-AIGC&type=Date)](https://star-history.com/#Zuzhi/Awesome-AIGCg&Date)

Thanks to template of [Awesome-Scene-Graph-for-CrossModal-Learning](https://github.com/ChocoWu/Awesome-Scene-Graph-for-CrossModal-Learning) <img alt="GitHub stars" src="https://img.shields.io/github/stars/ChocoWu/Awesome-Scene-Graph-for-CrossModal-Learning?style=social"> <img alt="GitHub forks" src="https://img.shields.io/github/forks/ChocoWu/Awesome-Scene-Graph-for-CrossModal-Learning?style=social"> and collections of [Awesome-CVPR2024-ECCV2024-AIGC](https://github.com/Kobaayyy/Awesome-CVPR2024-ECCV2024-AIGC) <img alt="GitHub stars" src="https://img.shields.io/github/stars/Kobaayyy/Awesome-CVPR2024-ECCV2024-AIGC?style=social"> <img alt="GitHub forks" src="https://img.shields.io/github/forks/Kobaayyy/Awesome-CVPR2024-ECCV2024-AIGC?style=social">.
