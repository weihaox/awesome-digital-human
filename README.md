# Awesome Digital Human [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) 
<!-- # <p align=center>`awesome digital human`</p> -->
<!-- [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity)
[![PR's Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](http://makeapullrequest.com) 
![visitors](https://visitor-badge.glitch.me/badge?style=flat-square&page_id=weihaox/awesome-clothed-human)  -->

> A curated collection of resources on clothed people: full body recontruction, head reconstruction, digital human related projects, etc.  

## Contributing

Feedback and contributions are welcome! If you think I have missed out on something (or) have any suggestions (papers, implementations and other resources), feel free to [pull a request](https://github.com/weihaox/awesome-digital-human/pulls). You could manually edit items or use the [script](https://github.com/weihaox/arxiv_daily_tools) to produce them in the markdown format provided below.

```Markdown
**Here is the Paper Name.**<br>
*[Author 1](homepage), Author 2, and Author 3.*<br>
Conference or Journal Year. [[PDF](link)] [[Project](link)] [[Code](link)] [[Data](link)]
```

<details><summary>Table of Contents</summary><p>
	
- [Industry Demo or Product](#industry-demo-or-product)
- [3D Human Avatar Generation and Animation](#3d-human-avatar-generation-and-animation)
- [3D Head Animatable Avatar (from 2D Image Collections)](#3d-head-animatable-avatar--from-2d-image-collections-)
- [(Clothed) Human Motion Generation](#-clothed--human-motion-generation)
- [Clothed Human Digitalization](#clothed-human-digitalization)
- [Cloth Modelling, Draping, Simulation, and Dressing](#cloth-modelling--draping--simulation--and-dressing)
- [Human Image and Video Generation](#human-image-and-video-generation)
- [Image-Based Virtual Try-On](#image-based-virtual-try-on)
- [Human Body Reshaping](#human-body-reshaping)
- [Garment Design](#garment-design)
- [Fashion Style Influences](#fashion-style-influences)
- [Team and People](#team-and-people)
- [Dataset](#dataset)
- [Applications](#applications)

</p></details><p></p>

## Industry Demo or Product

Highavenue: Turn yourself into a 3D model.

## 3D/4D Human Avatar Generation and Animation

**Generative Human Geometry Distribution.**<br>
*Xiangjun Tang, Biao Zhang, Peter Wonka.*<br>
arxiv 2025.  [[PDF](https://arxiv.org/abs/2503.01448] 

**AniGS: Animatable Gaussian Avatar from a Single Image with Inconsistent Gaussian Reconstruction**<br>
*Lingteng Qiu, Shenhao Zhu, Qi Zuo, Xiaodong Gu, Yuan Dong, Junfei Zhang, Chao Xu, Zhe Li, Weihao Yuan, Liefeng Bo, Guanying Chen, Zilong Dong.*<br>
CVPR2025. [[Project page](https://lingtengqiu.github.io/2024/AniGS/)] [[Paper](https://arxiv.org/pdf/2412.02684)]

**PSHuman: Photorealistic Single-image 3D Human Reconstruction using Cross-Scale Multiview Diffusion**<br>
*Peng Li, Wangguandong Zheng, Yuan Liu, Tao Yu, Yangguang Li, Siyu Xia, Yan-Pei Cao, Yike Guo.*<br>
CVPR2025. [[Project Page](https://penghtyx.github.io/PSHuman/)]  [[Paper](https://arxiv.org/pdf/2409.10141)] [[Code](https://github.com/pengHTYX/PSHuman/)] [[Demo](https://huggingface.co/spaces/RipleysNest/PSHuman)]

**Pippo : High-Resolution Multi-View Humans from a Single Image**<br>
*Yash Kant, Ethan Weber, Jin Kyu Kim, Rawal Khirodkar, Su Zhaoen, Julieta Martinez, Igor Gilitschenski, Shunsuke Saito, Timur Bagautdinov*<br>
CVPR2025. [[Project page](https://yashkant.github.io/pippo/)] [[Paper](https://yashkant.github.io/pippo/pippo.pdf)] [[Code](https://github.com/facebookresearch/pippo)]

**DeClotH: Decomposable 3D Cloth and Human Body Reconstruction from a Single Image**<br>
*Hyeongjin Nam, Donghwan Kim, Jeongtaek Oh, Kyoung Mu Lee*</br>
CVPR2025. [[Page](https://hygenie1228.github.io/DeClotH/)] [[Paper](https://hygenie1228.github.io/DeClotH/static/DeClotH_CVPR2025.pdf)]

**FreeCloth: Free-form Generation Enhances Challenging Clothed Human Modeling**<br>
*Hang Ye, Xiaoxuan Ma, Hai Ci, Wentao Zhu, Yizhou Wang*<br>
CVPR2025. [[Page](https://alvinyh.github.io/FreeCloth/)] [[Paper](https://arxiv.org/abs/2411.19942)] [[Code](https://github.com/AlvinYH/FreeCloth)]

**Real-time High-fidelity Gaussian Human Avatars with Position-based Interpolation of Spatially Distributed MLPs**<br>
*Youyi Zhan, Tianjia Shao, Yin Yang, Kun Zhou*<br>
CVPR2025. [[Page](https://gapszju.github.io/mmlphuman/)] [[Paper](https://gapszju.github.io/mmlphuman/static/paper/zhan2025realtime.pdf)] [[Code](https://github.com/1231234zhan/mmlphuman)]

**SimAvatar: Simulation-Ready Clothed Gaussian Avatars from Text.**<br>
*Xueting Li, Ye Yuan, Shalini De Mello, Miles Macklin, Jonathan Leaf, Gilles Daviet, Jan Kautz, Umar Iqbal.*<br>
CVPR 2025.  [[PDF](https://nvlabs.github.io/SimAvatar/static/paper.pdf)] [[Project](https://nvlabs.github.io/SimAvatar)]

**Disco4D: Disentangled 4D Human Generation and Animation from a Single Image.**<br>
*Hui En Pang, Shuai Liu, Zhongang Cai, Lei Yang, Tianwei Zhang, Ziwei Liu.*<br>
CVPR 2025.  [[PDF](https://arxiv.org/abs/2409.17280)] [[Project](https://disco-4d.github.io)]

**AvatarArtist: Open-Domain 4D Avatarization.**<br>
*Hongyu Liu, Xuan Wang, Ziyu Wan, Yue Ma, Jingye Chen, Yanbo Fan, Yujun Shen, Yibing Song, Qifeng Chen.*<br>
CVPR 2025.  [[PDF](https://arxiv.org/abs/2503.19906)] [[Project](https://kumapowerliu.github.io/AvatarArtist)] [[Code](https://github.com/ant-research/AvatarArtist)]

**GaussianIP: Identity-Preserving Realistic 3D Human Generation via Human-Centric Diffusion Prior.**<br>
*Zichen Tang, Yuan Yao, Miaomiao Cui, Liefeng Bo, Hongyu Yang.*<br>
CVPR 2025.  [[PDF](https://arxiv.org/abs/2503.11143)] [[Project](https://silence-tang.github.io/gaussian-ip)] [[Code](https://github.com/silence-tang/GaussianIP)]

**DressRecon: Freeform 4D Human Reconstruction from Monocular Video.**<br>
*Jeff Tan, Donglai Xiang, Shubham Tulsiani, Deva Ramanan, Gengshan Yang.*<br>
3DV 2025.  [[PDF](https://arxiv.org/abs/2409.20563)] [[Project](https://jefftan969.github.io/dressrecon)] [[Code](https://github.com/jefftan969/dressrecon)]

**Drivable 3D Gaussian Avatars.**<br>
*Wojciech Zielonka, Timur Bagautdinov, Shunsuke Saito, Michael Zollhöfer, Justus Thies, Javier Romero.*<br> 
3DV 2025. [[PDF](https://arxiv.org/abs/2311.08581)] [[Project](https://zielon.github.io/d3ga)]

**RodinHD: High-Fidelity 3D Avatar Generation with Diffusion Models.**<br>
*Bowen Zhang, Yiji Cheng, Chunyu Wang, Ting Zhang, Jiaolong Yang, Yansong Tang, Feng Zhao, Dong Chen, Baining Guo.*<br>
ECCV 2024. [[PDF](https://arxiv.org/abs/2407.06938)] [[Project](https://rodinhd.github.io)] [[Code](https://github.com/RodinHD/RodinHD)]

**Animatable Gaussians: Learning Pose-dependent Gaussian Maps for High-fidelity Human Avatar Modeling.**<br>
*Zhe Li, Zerong Zheng, Lizhen Wang, Yebin Liu..*<br> 
CVPR 2024. [[PDF](http://arxiv.org/abs/2311.16096)] [[Project](https://animatable-gaussians.github.io)] [[Code](https://github.com/lizhe00/AnimatableGaussians)]

**HumanNorm: Learning Normal Diffusion Model for High-quality and Realistic 3D Human Generation.**<br>
*Xin Huang, Ruizhi Shao, Qi Zhang, Hongwen Zhang, Ying Feng, Yebin Liu, Qing Wang..*<br> 
CVPR 2024. [[PDF](https://arxiv.org/abs/2310.01406)] [[Project](https://humannorm.github.io)] [[Code](https://github.com/xhuangcv/humannorm)]

**RAM-Avatar: Real-time Photo-Realistic Avatar from Monocular Videos with Full-body Control.**<br>
*Xiang Deng, Zerong Zheng, Yuxiang Zhang, Jingxiang Sun, Chao Xu, XiaoDong Yang, Lizhen Wang, Yebin Liu.*<br> 
CVPR 2024. [[PDF](https://cloud.tsinghua.edu.cn/f/6b7a88c3b4ac43b0b506/?dl=1)] [[Project](https://github.com/Xiang-Deng00/RAM-Avatar)] [[Code](https://github.com/Xiang-Deng00/RAM-Avatar)]

**TexVocab:Texture Vocabulary-conditioned Human Avatars.**<br>
*Yuxiao Liu, Zhe Li, Yebin Liu, Haoqian Wang.*<br> 
CVPR 2024. [[PDF](https://arxiv.org/abs/2404.00524)] [[Project](https://texvocab.github.io)]

**HumanGaussian: Text-Driven 3D Human Generation with Gaussian Splatting.**<br>
*Xian Liu, Xiaohang Zhan, Jiaxiang Tang, Ying Shan, Gang Zeng, Dahua Lin, Xihui Liu, Ziwei Liu.*<br> 
CVPR 2024. [[PDF](http://arxiv.org/abs/2311.17061)] [[Project](https://alvinliu0.github.io/projects/HumanGaussian)]

**DreamAvatar: Text-and-Shape Guided 3D Human Avatar Generation via Diffusion Models.**<br>
*[Yukang Cao](https://yukangcao.github.io), [Yan-Pei Cao](https://yanpei.me), [Kai Han](https://www.kaihan.org), [Ying Shan](https://scholar.google.com/citations?user=4oXBp9UAAAAJ&hl=zh-CN), [Kwan-Yee K. Wong](https://i.cs.hku.hk/~kykwong).*<br>
CVPR 2024. [[PDF](https://arxiv.org/abs/2304.00916)] [[Project](https://yukangcao.github.io/DreamAvatar)] [[Code](https://yukangcao.github.io/DreamAvatar)]

**SCULPT: Shape-Conditioned Unpaired Learning of Pose-dependent Clothed and Textured Human Meshes.**<br>
*Soubhik Sanyal, Partha Ghosh, Jinlong Yang, Michael J. Black, Justus Thies, Timo Bolkart.*<br>
CVPR 2024. [[PDF](https://arxiv.org/abs/2308.10638)] [[Project](https://huangyangyi.github.io/tech)]

**3DGS-Avatar: Animatable Avatars via Deformable 3D Gaussian Splatting.**<br>
*Zhiyin Qian, Shaofei Wang, Marko Mihajlovic, Andreas Geiger, Siyu Tang.*<br> 
CVPR 2024. [[PDF](https://arxiv.org/abs/2312.09228)] [[Project](https://neuralbodies.github.io/3DGS-Avatar)]

**Emotional Speech-driven 3D Body Animation Via Disentangled Latent Diffusion.**<br>
*Kiran Chhatre, Radek Daněček, Nikos Athanasiou, Giorgio Becherini, Christopher Peters, Michael J. Black, Timo Bolkart.*<br> 
CVPR 2024. [[PDF](http://arxiv.org/abs/2312.04466)]

**GauHuman: Articulated Gaussian Splatting from Monocular Human Videos.**<br>
*Shoukang Hu, Ziwei Liu.*<br> 
CVPR 2024. [[PDF](http://arxiv.org/abs/2312.02973v1)] [[Project](https://skhu101.github.io/GauHuman)] [[Code](https://github.com/skhu101/GauHuman)]

**FlashAvatar: High-Fidelity Digital Avatar Rendering at 300FPS.**<br>
*Jun Xiang, Xuan Gao, Yudong Guo, Juyong Zhang.*<br> 
CVPR 2024. [[PDF](http://arxiv.org/abs/2312.02214v1)] [[Project](https://ustc3dv.github.io/FlashAvatar)]

**PEGASUS: Personalized Generative 3D Avatars with Composable Attributes.**<br>
*[Hyunsoo Cha](https://research.hyunsoocha.com), [Byungjun Kim](https://bjkim95.github.io), [Hanbyul Joo](https://jhugestar.github.io).*<br>
CVPR 2024. [[PDF](https://arxiv.org/pdf/2402.10636)] [[Project](https://snuvclab.github.io/pegasus)] [[Code](https://github.com/snuvclab/pegasus)]

**TADA! Text to Animatable Digital Avatars.**<br>
*[Tingting Liao](https://github.com/TingtingLiao), [Hongwei Yi](https://xyyhw.top), [Yuliang Xiu](http://xiuyuliang.cn), [Jiaxiang Tang](https://me.kiui.moe), [Yangyi Huang](https://github.com/huangyangyi), [Justus Thies](https://justusthies.github.io), [Michael J. Black](https://ps.is.tuebingen.mpg.de/person/black).*<br>
3DV 2024. [[PDF](https://arxiv.org)] [[Project](https://tada.is.tue.mpg.de)] [[Code](https://github.com/TingtingLiao/TADA)]

**Efficient 3D Articulated Human Generation with Layered Surface Volumes.**<br>
*Yinghao Xu, Wang Yifan, Alexander W. Bergman, Menglei Chai, Bolei Zhou, Gordon Wetzstein.*<br> 
3DV 2024. [[PDF](https://arxiv.org/abs/2307.05462)] [[Project](https://www.computationalimaging.org/publications/lsv)]

**TECA: Text-Guided Generation and Editing of Compositional 3D Avatars.**<br>
*[Hao Zhang](https://haozhang990127.github.io), [Yao Feng](https://scholar.google.com/citations?user=wNQQhSIAAAAJ&hl=en&oi=ao), [Peter Kulits](https://kulits.github.io), [Yandong Wen](https://is.mpg.de/person/ydwen), [Justus Thies](https://justusthies.github.io), [Michael J. Black](https://ps.is.mpg.de/person/black).*<br> 
3DV 2024. [[PDF](https://arxiv.org/abs/2309.07125)] [[Project](https://yfeng95.github.io/teca)]

**FLARE: Fast Learning of Animatable and Relightable Mesh Avatars.**<br>
*Shrisha Bharadwaj, Yufeng Zheng, Otmar Hilliges, Michael J. Black, Victoria Fernandez-Abrevaya.*<br>
SIGGRAPH Asia 2023. [[PDF](https://arxiv.org/abs/2310.17519)]

**Single-Shot Implicit Morphable Faces with Consistent Texture Parameterization.**<br>
*Connor Z. Lin, Koki Nagano, Jan Kautz, Eric R. Chan, Umar Iqbal, Leonidas Guibas, Gordon Wetzstein, Sameh Khamis.*<br>
SIGGRAPH 2023. [[PDF](https://arxiv.org/abs/2305.03043)] [[Project](https://research.nvidia.com/labs/toronto-ai/ssif)]

**DELIFFAS: Deformable Light Fields for Fast Avatar Synthesis.**<br>
*Youngjoong Kwon, Lingjie Liu, Henry Fuchs, Marc Habermann, Christian Theobalt.*<br> 
NeurIPS 2023. [[PDF](http://arxiv.org/abs/2310.11449)]

**PrimDiffusion: Volumetric Primitives Diffusion for 3D Human Generation.**<br>
*Zhaoxi Chen, Fangzhou Hong, Haiyi Mei, Guangcong Wang, Lei Yang, Ziwei Liu.*<br> 
NeurIPS 2023. [[PDF](http://arxiv.org/abs/2312.04559)] [[Project](https://frozenburning.github.io/projects/primdiffusion)] [[Code](https://github.com/FrozenBurning/PrimDiffusion)]

**XAGen: 3D Expressive Human Avatars Generation.**<br>
*Zhongcong Xu, Jianfeng Zhang, Jun Hao Liew, Jiashi Feng, Mike Zheng Shou.*<br>
NeurIPS 2023. [[PDF](https://arxiv.org/abs/2311.13574)] [[Project](https://showlab.github.io/xagen)] [[Code](https://github.com/magic-research/xagen)]

**DreamHuman: Animatable 3D Avatars from Text.**<br>
*[Nikos Kolotouros](https://www.nikoskolot.com), [Thiemo Alldieck](https://research.google/people/107250), [Andrei Zanfir](https://scholar.google.com/citations?user=8lmzWycAAAAJ&hl=en&oi=ao), [Eduard Gabriel Bazavan](https://research.google/people/107659), [Mihai Fieraru](https://mihaifieraru.github.io), [Cristian Sminchisescu](https://research.google/people/CristianSminchisescu).*<br> 
NeurIPS 2023. [[PDF](https://arxiv.org/abs/2306.09329)] [[Project](https://dream-human.github.io)] [[Avatar Gallery](https://dream-human.github.io/avatar_gallery.html)]

**DINAR: Diffusion Inpainting of Neural Textures for One-Shot Human Avatars.**<br>
*David Svitov, Dmitrii Gudkov, Renat Bashirov, Victor Lempitsky.*<br> 
ICCV 2023. [[PDF](https://arxiv.org/abs/2303.09375)] [[Code](https://github.com/SamsungLabs/DINAR)]

**AvatarCraft: Transforming Text into Neural Human Avatars with Parameterized Shape and Pose Control.**<br>
*[Ruixiang Jiang](https://j-rx.com), [Can Wang](https://cassiepython.github.io), [Jingbo Zhang](https://eckertzhang.github.io), [Menglei Chai](https://mlchai.com), [Mingming He](https://mingminghe.com), [Dongdong Chen](https://www.dongdongchen.bid), [Jing Liao](https://liaojing.github.io/html).*<br>
ICCV 2023. [[PDF](https://arxiv.org/abs/2303.17606)] [[Project](https://avatar-craft.github.io)] [[Code](https://github.com/songrise/avatarcraft)] [[Data](https://drive.google.com/drive/folders/1m97mmoAtDes0mBwkS4q2VNBivXSmRkOK)]

**StyleAvatar3D: Leveraging Image-Text Diffusion Models for High-Fidelity 3D Avatar Generation.**<br>
*Chi Zhang, Yiwen Chen, Yijun Fu, Zhenglin Zhou, Gang YU, Billzb Wang, Bin Fu, Tao Chen, Guosheng Lin, Chunhua Shen.*<br> 
ICCV 2023. [[PDF](http://arxiv.org/abs/2305.19012)] [[Project](https://x-zhangyang.github.io/2023_Get3DHuman)] [[Code](https://github.com/icoz69/StyleAvatar3D)]

**Get3DHuman: Lifting StyleGAN-Human into a 3D Generative Model using Pixel-aligned Reconstruction Priors.**<br>
*Zhangyang Xiong, Di Kang, Derong Jin, Weikai Chen, Linchao Bao, Xiaoguang Han.*<br>
ICCV 2023. [[PDF](https://arxiv.org/abs/2302.01162)] [[Code](https://github.com/X-zhangyang/Get3DHuman)]

**GETAvatar: Generative Textured Meshes for Animatable Human Avatars.**<br>
*Xuanmeng Zhang, Jianfeng Zhang, Rohan Chacko, Hongyi Xu, Guoxian Song, Yi Yang, Jiashi Feng.*<br>
ICCV 2023. [[PDF](https://arxiv.org/abs/2310.02714)] [[Project](https://getavatar.github.io)]

**AG3D: Learning to Generate 3D Avatars from 2D Image Collections.**<br>
*[Zijian Dong](https://ait.ethz.ch/people/zijian), [Xu Chen](https://ait.ethz.ch/people/xu), [Jinlong Yang](https://is.mpg.de/~jyang), [Michael J. Black](https://ps.is.mpg.de/~black), [Otmar Hilliges](https://ait.ethz.ch/people/hilliges), [Andreas Geiger](http://www.cvlibs.net).*<br> 
ICCV 2023. [[PDF](http://arxiv.org/abs/2305.02312)] [[Project](https://zj-dong.github.io/AG3D)] [[Code](https://github.com/zj-dong/AG3D)]

**Learning Locally Editable Virtual Humans.**<br>
*[Hsuan-I Ho](https://azuxmioy.github.io), [Lixin Xue](https://lxxue.github.io), [Jie Song](https://ait.ethz.ch/people/song), [Otmar Hilliges](https://ait.ethz.ch/people/hilliges).*<br>
CVPR 2023. [[PDF](https://files.ait.ethz.ch/projects/custom-humans/paper.pdf)] [[Project](https://custom-humans.github.io)] [[Code](https://github.com/custom-humans/editable-humans)]

**PersonNeRF: Personalized Reconstruction from Photo Collections.**<br>
*[Chung-Yi Weng](https://homes.cs.washington.edu/~chungyi), Pratul P. Srinivasan, Brian Curless, Ira Kemelmacher-Shlizerman.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2302.01162)] [[Project](https://grail.cs.washington.edu/projects/personnerf)]

**Latent-NeRF for Shape-Guided Generation of 3D Shapes and Textures.**<br>
*Gal Metzer, Elad Richardson, Or Patashnik, Raja Giryes, Daniel Cohen-Or.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2211.07600)]  [[Code](https://github.com/eladrich/latent-nerf)]

**EVA3D: Compositional 3D Human Generation from 2D Image Collections.**<br>
*[Fangzhou Hong](https://hongfz16.github.io), [Zhaoxi Chen](https://frozenburning.github.io), [Yushi Lan](https://github.com/NIRVANALAN), [Liang Pan](https://scholar.google.com/citations?user=lSDISOcAAAAJ&hl=zh-CN), [Ziwei Liu](https://liuziwei7.github.io).*<br>
ICLR 2023. [[PDF](https://arxiv.org/abs/2210.04888)] [[Project](https://hongfz16.github.io/projects/EVA3D.html)] [[Code](https://github.com/hongfz16/EVA3D)]

**CLIP-Actor: Text-Driven Recommendation and Stylization for Animating Human Meshes.**<br>
*Kim Youwang, Kim Ji-Yeon, Tae-Hyun Oh.*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2208.03550)] [[Project](https://clip-actor.github.io)] [[Code](https://github.com/postech-ami/CLIP-Actor)]

**AvatarCLIP: Zero-Shot Text-Driven Generation and Animation of 3D Avatars.**<br>
*[Fangzhou Hong](https://hongfz16.github.io), Mingyuan Zhang, Liang Pan, Zhongang Cai, Lei Yang, Ziwei Liu.*<br>
SIGGRAPH (TOG) 2022. [[PDF](https://arxiv.org/abs/2205.08535)] [[Project](https://hongfz16.github.io/projects/AvatarCLIP.html)] [[Code](https://github.com/hongfz16/AvatarCLIP)] 

**WildAvatar: Web-scale In-the-wild Video Dataset for 3D Avatar Creation.**<br>
*Zihao Huang, ShouKang Hu, Guangcong Wang, Tianqi Liu, Yuhang Zang, Zhiguo Cao, Wei Li, Ziwei Liu.*<br> 
arXiv 2024. [[PDF](https://arxiv.org/abs/2407.02165)] [[Project](https://wildavatar.github.io)]

**MagicAvatar: Multimodal Avatar Generation and Animation.**<br>
*Jianfeng Zhang, Hanshu Yan, Zhongcong Xu, Jiashi Feng, Jun Hao Liew.*<br> 
arXiv 2023. [[PDF](http://arxiv.org/abs/2308.14748)] [[Project](https://magic-avatar.github.io)] [[Code](https://github.com/magic-research/magic-avatar)]

**DELTA: Learning Disentangled Avatars with Hybrid 3D Representations.**<br>
*[Yao Feng](https://scholar.google.com/citations?user=wNQQhSIAAAAJ&hl=en&oi=ao), [Weiyang Liu](https://wyliu.com), [Timo Bolkart](https://sites.google.com/site/bolkartt), [Jinlong Yang](https://is.mpg.de/~jyang), [Marc Pollefeys](https://people.inf.ethz.ch/pomarc), [Michael J. Black](https://ps.is.mpg.de/person/black).*<br> 
arXiv 2023. [[PDF](https://arxiv.org/abs/2309.06441)] [[Project](https://yfeng95.github.io/delta)] [[Code](https://github.com/yfeng95/DELTA)]

**AvatarBooth: High-Quality and Customizable 3D Human Avatar Generation.**<br>
*[Yifei Zeng](https://github.com/zeng-yifei), [Yuanxun Lu](https://github.com/YuanxunLu), [Xinya Ji](https://github.com/jixinya), [Yao Yao](https://yoyo000.github.io), [Hao Zhu](http://zhuhao.cc), [Xun Cao](https://cite.nju.edu.cn/People/Faculty/20190621/i5054.html).*<br> 
arXiv 2023. [[PDF](https://arxiv.org/abs/2306.09864)] [[Project](https://zeng-yifei.github.io/avatarbooth_page)] [[Code](https://github.com/zeng-yifei/AvatarBooth)]

## 3D Head Animatable Avatar (from 2D Image Collections)

**PAV: Personalized Head Avatar from Unstructured Video Collection.**<br>
*Akin Caliskan, Berkay Kicanaoglu, Hyeongwoo Kim.*<br>
ECCV 2024. [[PDF](https://arxiv.org/abs/2407.21047)] [[Project](https://akincaliskan3d.github.io/PAV)] 

**Gaussian Head Avatar: Ultra High-fidelity Head Avatar via Dynamic Gaussians.**<br>
*Yuelang Xu, Benwang Chen, Zhe Li, Hongwen Zhang, Lizhen Wang, Zerong Zheng, Yebin Liu.*<br>
CVPR 2024. [[PDF](https://arxiv.org/abs/2312.03029)] [[Project](https://yuelangx.github.io/gaussianheadavatar)] 

**HeadArtist: Text-conditioned 3D Head Generation with Self Score Distillation.**<br>
*Hongyu Liu, Xuan Wang, Ziyu Wan, Yujun Shen, Yibing Song, Jing Liao, Qifeng Chen.*<br> 
SIGGRAPH 2024. [[PDF](http://arxiv.org/abs/2312.07539)] [[Project](https://kumapowerliu.github.io/HeadArtist)]

**GAN-Avatar: Controllable Personalized GAN-based Human Head Avatar.**<br>
*Berna Kabadayi, Wojciech Zielonka, Bharat Lal Bhatnagar, Gerard Pons-Moll, Justus Thies.*<br>
3DV 2024. [[PDF](https://arxiv.org/abs/2311.13655)] [[Project](https://ganavatar.github.io)] 

**NeRFEditor: Differentiable Style Decomposition for Full 3D Scene Editing.**<br>
*[Chunyi Sun](https://chuny1.github.io/NeRFEditor/nerfeditor.html), [Yanbin Liu](https://chuny1.github.io/NeRFEditor/nerfeditor.html), [Junlin Han](https://junlinhan.github.io), [Stephen Gould](https://chuny1.github.io/NeRFEditor/nerfeditor.html).*<br>
WACV 2024. [[PDF](https://arxiv.org/abs/2212.03848)] [[Project](https://chuny1.github.io/NeRFEditor/nerfeditor.html)]

**AlbedoGAN: Towards Realistic Generative 3D Face Models.**<br>
*[Aashish Rai](https://aashishrai3799.github.io), [Hiresh Gupta](https://hireshgupta1997.github.io), Ayush Pandey, Francisco Vicente Carrasco, Shingo Jason Takagi, Amaury Aubel, Daeil Kim, [Aayush Prakash](https://aayushp.github.io), [Fernando de la Torre](https://www.cs.cmu.edu/~ftorre).*<br>
WACV 2024. [[PDF](https://arxiv.org/abs/2304.12483)] [[Project](https://aashishrai3799.github.io/Towards-Realistic-Generative-3D-Face-Models)] [[Code](https://lnkd.in/gVz8Hzn3)]

**AvatarStudio: Text-driven Editing of 3D Dynamic Human Head Avatars.**<br>
*Mohit Mendiratta. Xingang Pan, Mohamed Elgharib, Kartik Teotia, Mallikarjun B R, Ayush Tewari, Vladislav Golyanik, Adam Kortylewski, Christian Theobalt.*<br> 
TOG 2024. [[PDF](http://arxiv.org/abs/2306.00547)] [[Project](https://vcai.mpi-inf.mpg.de/projects/AvatarStudio)]

**HQ3DAvatar: High Quality Controllable 3D Head Avatar.**<br>
*[Kartik Teotia](https://www.linkedin.com/in/kartik-teotia/?originalSubdomain=de), Mallikarjun B R, Xingang Pan, Hyeongwoo Kim, Pablo Garrido, Mohamed Elgharib, Christian Theobalt.*<br>
TOG 20234. [[PDF](https://vcai.mpi-inf.mpg.de/projects/HQ3DAvatar)] [[Project](https://vcai.mpi-inf.mpg.de/projects/HQ3DAvatar)]

**CLIPFace: Text-guided Editing of Textured 3D Morphable Models.**<br>
*[Shivangi Aneja](https://niessnerlab.org/members/shivangi_aneja/profile.html), [Justus Thies](https://is.mpg.de/~jthies), [Angela Dai](https://www.professoren.tum.de/en/dai-angela), [Matthias Nießner](https://niessnerlab.org/members/matthias_niessner/profile.html).*<br>
SIGGRAPH 2023. [[PDF](https://arxiv.org/abs/2212.01406)] [[Project](https://shivangi-aneja.github.io/projects/clipface)] [[Code](https://github.com/shivangi-aneja/ClipFace)]

**DreamFace: Progressive Generation of Animatable 3D Faces under Text Guidance.**<br>
*Longwen Zhang, Qiwei Qiu, Hongyang Lin, Qixuan Zhang, Cheng Shi, Wei Yang, Ye Shi, Sibei Yang, Lan Xu, Jingyi Yu.*<br>
SIGGRAPH 2023. [[PDF](https://arxiv.org/abs/2304.03117)] [[Project](https://sites.google.com/view/dreamface)] [[Demo](https://hyperhuman.deemos.com)] [[HuggingFace](https://huggingface.co/spaces/DEEMOSTECH/ChatAvatar)]

**StyleAvatar: Real-time Photo-realistic Neural Portrait Avatar from a Single Video.**<br>
*Lizhen Wang, Xiaochen Zhao, Jingxiang Sun, Yuxiang Zhang, Hongwen Zhang, Tao Yu✝, Yebin Liu.*<br>
SIGGRAPH 2023. [[PDF](https://arxiv.org/abs/2305.00942)]

**LatentAvatar: Learning Latent Expression Code for Expressive Neural Head Avatar.**<br>
*Yuelang Xu, Hongwen Zhang, Lizhen Wang, Xiaochen Zhao, Han Huang, Guojun Qi, Yebin Liu.*<br>
SIGGRAPH 2023. [[PDF](https://arxiv.org/abs/2305.01190)], [[Project](https://www.liuyebin.com/latentavatar)],[[Code](https://github.com/YuelangX/LatentAvatar)]

**NeRSemble: Multi-view Radiance Field Reconstruction of Human Heads.**<br>
*[Tobias Kirschstein](https://tobias-kirschstein.github.io), [Shenhan Qian](https://shenhanqian.com), [Simon Giebenhain](https://simongiebenhain.github.io), Tim Walter, Matthias Nießner.*<br> 
SIGGRAPH 2023. [[PDF](http://arxiv.org/abs/2305.03027)] [[Project](https://tobias-kirschstein.github.io/nersemble)] [[Video](https://youtu.be/a-OAWqBzldU)]

**GOHA: Generalizable One-shot Neural Head Avatar.**<br>
*[Xueting Li](https://sunshineatnoon.github.io), [Shalini De Mello](https://research.nvidia.com/person/shalini-de-mello), [Sifei Liu](https://www.sifeiliu.net), [Koki Nagano](https://luminohope.org), [Umar Iqbal](https://research.nvidia.com/person/umar-iqbal), [Jan Kautz](https://jankautz.com).*<br> 
NeurIPS 2023. [[PDF](https://arxiv.org/abs/2306.08768)] [[Project](https://research.nvidia.com/labs/lpr/one-shot-avatar)]

**GANHead: Towards Generative Animatable Neural Head Avatars.**<br>
*[Sijing Wu]((https://wsj-sjtu.github.io), [Yichao Yan](https://daodaofr.github.io), Yunhao Li, Yuhao Cheng, Wenhan Zhu, Ke Gao, Xiaobo Li, [Guangtao Zhai](https://scholar.google.com/citations?user=E6zbSYgAAAAJ&hl=en&oi=ao).*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2304.03950)] [[Project](https://wsj-sjtu.github.io/GANHead)]

**FitMe: Deep Photorealistic 3D Morphable Model Avatars.**<br>
*[Alexandros Lattas](https://alexlattas.com), [Stylianos Moschoglou](https://moschoglou.com), [Stylianos Ploumpis](https://www.ploumpis.com), [Baris Gecer](https://barisgecer.github.io), [Jiankang Deng](https://jiankangdeng.github.io), [Stefanos Zafeiriou](https://www.imperial.ac.uk/people/s.zafeiriou).*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2305.09641)] [[Project](https://alexlattas.com/fitme)]

**Next3D: Generative Neural Texture Rasterization for 3D-Aware Head Avatars.**<br>
*[Jingxiang Sun](https://mrtornado24.github.io), [Xuan Wang](https://xuanwangvc.github.io), [Lizhen Wang](https://lizhenwangt.github.io), [Xiaoyu Li](https://xiaoyu258.github.io), [Yong Zhang](https://yzhang2016.github.io/yongnorriszhang.github.io), [Hongwen Zhang](https://hongwenzhang.github.io), [Yebin Liu](http://www.liuyebin.com).*<br>
CVPR 2023 (Highlight). [[PDF](https://arxiv.org/pdf/2211.11208.pdf)] [[Project](https://mrtornado24.github.io/Next3D)] [[Code](https://github.com/MrTornado24/Next3D)]

**BlendFields: Few-Shot Example-Driven Facial Modeling.**<br>
*Kacper Kania, Stephan J. Garbin, Andrea Tagliasacchi, Virginia Estellers, Kwang Moo Yi, Julien Valentin, Tomasz Trzciński, Marek Kowalski.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2305.07514)] [[Project](https://blendfields.github.io)]

**OTAvatar: One-shot Talking Face Avatar with Controllable Tri-plane Rendering.**<br>
*Zhiyuan Ma, Xiangyu Zhu, Guojun Qi, Zhen Lei, Lei Zhang.*<br>
CVPR 2023. [[PDF](https://arxiv.org/pdf/2303.14662)] [[Code](https://github.com/theEricMa/OTAvatar)] [[Demo](https://youtu.be/qpIoMYFr7Aw)]

**PanoHead: Geometry-Aware 3D Full-Head Synthesis in 360∘.**<br>
*Sizhe An, Hongyi Xu, Yichun Shi, Guoxian Song, Umit Ogras, Linjie Luo.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2303.13071) [[Project](https://sizhean.github.io/panohead)]

**Efficient Meshy Neural Fields for Animatable Human Avatars.**<br>
*Xiaoke Huang, Yiji Cheng, Yansong Tang, Xiu Li, Jie Zhou, Jiwen Lu .*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2303.12965)] [[Project](https://xk-huang.github.io/ema)]

**Rodin: A Generative Model for Sculpting 3D Digital Avatars Using Diffusion.**<br>
*Tengfei Wang, Bo Zhang, Ting Zhang, Shuyang Gu, Jianmin Bao, Tadas Baltrusaitis, Jingjing Shen, Dong Chen, Fang Wen, Qifeng Chen, Baining Guo.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2212.06135)] [[Project](https://3d-avatar-diffusion.microsoft.com)]

**OmniAvatar: Geometry-Guided Controllable 3D Head Synthesis.**<br>
*Hongyi Xu, Guoxian Song, Zihang Jiang, Jianfeng Zhang, Yichun Shi, Jing Liu, Wanchun Ma, Jiashi Feng, Linjie Luo.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2303.15539)]

**PointAvatar: Deformable Point-based Head Avatars from Videos.**<br>
*Yufeng Zheng, Wang Yifan, Gordon Wetzstein, Michael J. Black, Otmar Hilliges.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2212.08377)] [[Project](https://zhengyuf.github.io/PointAvatar)] [[Code](https://github.com/zhengyuf/pointavatar)]

**MEGANE: Morphable Eyeglass and Avatar Network.**<br>
*Junxuan Li, Shunsuke Saito, Tomas Simon, Stephen Lombardi, Hongdong Li, Jason Saragih.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2302.04868)] [[Project](https://junxuan-li.github.io/megane)] 

**Reconstructing Personalized Semantic Facial NeRF Models From Monocular Video.**<br>
*Xuan Gao, ChengLai Zhong, Jun Xiang, Yang Hong, Yudong Guo, Juyong Zhang.*<br>
TOG 2022. [[PDF](https://arxiv.org/abs/2210.06108)] [[Project](https://ustc3dv.github.io/NeRFBlendShape)] [[Code](https://github.com/USTC3DV/NeRFBlendShape-code)]

**H3D-Net: Few-Shot High-Fidelity 3D Head Reconstruction.**<br>
*Eduard Ramon, Gil Triginer, Janna Escur, Albert Pumarola, Jaime Garcia, Xavier Giro-i-Nieto, Francesc Moreno-Noguer.*<br>
ICCV 2021. [[PDF](https://arxiv.org/abs/2107.12512)] [[Project](https://crisalixsa.github.io/h3d-net)] [[H3DS Dataset](https://docs.google.com/forms/d/e/1FAIpQLScbs-m-Me85KeMqJ2WnCwvToeSRIHC8sJckhxX3eknQu8ItRQ/viewform)]

**AvatarMe++: Facial Shape and BRDF Inference with Photorealistic Rendering-Aware GANs.**<br>
*[Alexandros Lattas](https://www.imperial.ac.uk/people/a.lattas), [Stylianos Moschoglou](https://www.doc.ic.ac.uk/~sm3515), [Stylianos Ploumpis](https://www.imperial.ac.uk/people/s.ploumpis), [Baris Gecer](http://barisgecer.github.io), [Abhijeet Ghosh](https://www.doc.ic.ac.uk/~ghosh), [Stefanos Zafeiriou](https://wp.doc.ic.ac.uk/szafeiri).*<br>
TPAMI 2021. [[PDF](https://arxiv.org/abs/2112.05957)]  [[Code](https://github.com/lattas/AvatarMe)]

**AvatarMe: Realistically Renderable 3D Facial Reconstruction "in-the-wild".**<br>
*Alexandros Lattas, Stylianos Moschoglou, Baris Gecer, Stylianos Ploumpis, Vasileios Triantafyllou, Abhijeet Ghosh, Stefanos Zafeiriou.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.13845)]  [[Code](https://github.com/lattas/AvatarMe)]

## (Clothed) Human Motion Generation

**SemGeoMo: Dynamic Contextual Human Motion Generation with Semantic and Geometric Guidance.**<br>
*Peishan Cong, Ziyi Wang, Yuexin Ma, Xiangyu Yue.*<br> 
CVPR 2025. [[PDF](https://arxiv.org/abs/2503.01291)] [[Project](https://4dvlab.github.io/project_page/semgeomo)]

**ReLoo: Reconstructing Humans Dressed in Loose Garments from Monocular Video in the Wild.**<br>
*Chen Guo, Tianjian Jiang, Manuel Kaufmann, Chengwei Zheng, Julien Valentin, Jie Song, Otmar Hilliges.*<br> 
ECCV 2024. [[PDF](https://arxiv.org/abs/2409.15269)] [[Project](https://moygcc.github.io/ReLoo)]

**TLControl: Trajectory and Language Control for Human Motion Synthesis.**<br>
*Weilin Wan, Zhiyang Dou, Taku Komura, Wenping Wang, Dinesh Jayaraman, Lingjie Liu.*<br> 
ECCV 2024. [[PDF](http://arxiv.org/abs/2311.17135)] [[Project](https://tlcontrol.weilinwl.com)]

**CoMo: Controllable Motion Generation through Language Guided Pose Code Editing.**<br>
*Yiming Huang, Weilin Wan, Yue Yang, Chris Callison-Burch, Mark Yatskar, Lingjie Liu.*<br> 
ECCV 2024. [[PDF](https://arxiv.org/abs/2403.13900)] [[Project](https://yh2371.github.io/como)]

**Total Selfie: Generating Full-Body Selfies.**<br>
*Bowei Chen, Brian Curless, Ira Kemelmacher-Shlizerman, Steve Seitz.*<br> 
CVPR 2024 (Highlight). [[PDF](http://arxiv.org/abs/2308.14740)] [[Project](https://homes.cs.washington.edu/~boweiche/project_page/totalselfie)]

**OmniControl: Control Any Joint at Any Time for Human Motion Generation.**<br>
*Yiming Xie, Varun Jampani, Lei Zhong, Deqing Sun, Huaizu Jiang.*<br> 
ICLR 2024. [[PDF](http://arxiv.org/abs/2310.08580)] [[Project](https://neu-vi.github.io/omnicontrol)]

**MotionDiffuse: Text-Driven Human Motion Generation with Diffusion Model.**<br>
*[Mingyuan Zhang](https://mingyuan-zhang.github.io), [Zhongang Cai](https://caizhongang.github.io), [Liang Pan](https://github.com/paul007pl), [Fangzhou Hong](https://hongfz16.github.io), [Xinying Guo](https://gxyes.github.io), [Lei Yang](https://yanglei.me), [Ziwei Liu](https://liuziwei7.github.io).*<br>
TPAMI 2024. [[PDF](https://arxiv.org/abs/2208.15001)] [[Project](https://mingyuan-zhang.github.io/projects/MotionDiffuse.html)] [[Code](https://github.com/mingyuan-zhang/MotionDiffuse)]

**TMR: Text-to-Motion Retrieval Using Contrastive 3D Human Motion Synthesis.**<br>
*Mathis Petrovich, Michael J. Black and Gül Varol.*<br>
ICCV 2023. [[PDF](https://arxiv.org/abs/2305.00976)] [[Project](https://mathis.petrovich.fr/tmr/index.html)] [[Code](https://github.com/Mathux/TMR)]

**SINC: Spatial Composition of 3D Human Motions for Simultaneous Action Generation.**<br>
*Nikos Athanasiou, Mathis Petrovich, Michael J. Black, Gül Varol.*<br>
ICCV 2023. [[PDF](https://arxiv.org/abs/2304.10417)] [[Project](https://sinc.is.tue.mpg.de)] [[Code](https://github.com/athn-nik/sinc)]

**HumanRF: High-Fidelity Neural Radiance Fields for Humans in Motion.**<br>
*[Mustafa Işık](https://www.mustafaisik.net), Martin Rünz, Markos Georgopoulos, Taras Khakhulin, Jonathan Starck, Lourdes Agapito, Matthias Nießner.*<br> 
SIGGRAPH 2023. [[PDF](http://arxiv.org/abs/2305.06356)] [[Project](http://www.synthesiaresearch.github.io/humanrf)] [[Code](https://github.com/synthesiaresearch/humanrf)] [[Data](http://www.actors-hq.com)]

**GestureDiffuCLIP: Gesture Diffusion Model with CLIP Latents.**<br>
*[Tenglong Ao](https://aubrey-ao.github.io), Zeyi Zhang, [Libin Liu](https://libliu.info).*<br>
SIGGRAPH 2023 (Journal Track). [[PDF](https://arxiv.org/abs/2303.14613)] [[Project](https://pku-mocca.github.io/GestureDiffuCLIP-Page)]

**MDM: Human Motion Diffusion Model.**<br>
*Guy Tevet, Sigal Raab, Brian Gordon, Yonatan Shafir, Daniel Cohen-Or, Amit H. Bermano.*<br>
ICLR 2023. [[PDF](https://arxiv.org/abs/2209.14916)] [[Project](https://guytevet.github.io/mdm-page)] [[Code](https://github.com/GuyTevet/motion-diffusion-model)]

**MoFusion: A Framework for Denoising-Diffusion-based Motion Synthesis.**<br>
*[Rishabh Dabral](https://www.cse.iitb.ac.in/~rdabral), [Muhammad Hamza Mughal](https://m-hamza-mughal.github.io), [Vladislav Golyanik](https://people.mpi-inf.mpg.de/~golyanik), [Christian Theobalt](https://people.mpi-inf.mpg.de/~theobalt).*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2212.04495)] [[Project](https://vcai.mpi-inf.mpg.de/projects/MoFusion)] 

**MotionCLIP: Exposing Human Motion Generation to CLIP Space.**<br>
*Guy Tevet, Brian Gordon, Amir Hertz, Amit H. Bermano, Daniel Cohen-Or.*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2203.08063)] [[Project](https://guytevet.github.io/motionclip-page)] [[Code](https://github.com/GuyTevet/MotionCLIP)]

**TEMOS: Generating diverse human motions from textual descriptions.**<br>
*[Mathis Petrovich](https://mathis.petrovich.fr), Michael J. Black, Gül Varol.*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2204.14109)] [[Project](https://mathis.petrovich.fr/temos)] [[Code](https://github.com/Mathux/TEMOS)]

**TEACH: Temporal Action Composition for 3D Human.**<br>
*Nikos Athanasiou, Mathis Petrovich, Michael J. Black, Gül Varol.*<br>
3DV 2022. [[PDF](https://arxiv.org/abs/2209.04066)] [[Project](https://teach.is.tue.mpg.de)] [[Code](https://github.com/athn-nik/teach)]

## Clothed Human Digitalization

[Project Splinter](https://project-splinter.github.io): Human Digitalization with Implicit Representation.

**LHM: Large Animatable Human Reconstruction Model from a Single Image in Seconds.**<br>
*Lingteng Qiu, Xiaodong Gu, Peihao Li, Qi Zuo, Weichao Shen, Junfei Zhang, Kejie Qiu, Weihao Yuan, Guanying Chen, Zilong Dong, Liefeng Bo.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2503.10625)] [[Project](https://lingtengqiu.github.io/LHM)] [[Github](https://github.com/aigc3d/LHM)]

**ETCH: Generalizing Body Fitting to Clothed Humans via Equivariant Tightness.**<br>
*Boqian Li, Haiwen Feng, Zeyu Cai, Michael J. Black, Yuliang Xiu.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2503.10624)] [[Project](https://boqian-li.github.io/ETCH)] [[Github](https://github.com/boqian-li/ETCH)]

**MultiGO: Towards Multi-level Geometry Learning for Monocular 3D Textured Human Reconstruction.**<br>
*Gangjian Zhang, Nanjie Yao, Shunsi Zhang, hanfeng Zhao, Guoliang Pang, Jian Shu, Hao Wan.*<br>
CVPR 2025. [[PDF]()] [[Project](https://multigohuman.github.io)]

**Free-form Generation Enhances Challenging Clothed Human Modeling.**<br>
*Hang Ye, Xiaoxuan Ma, Hai Ci, Wentao Zhu, Yizhou Wang.*<br>
CVPR 2025. [[PDF](https://arxiv.org/abs/2411.19942)]

**GBC: Generalizable Gaussian-Based Clothed Human Digitalization.**<br>
*Hanzhang Tu, Zhanfeng Liao, Boyao Zhou, Shunyuan Zheng, Xilong Zhou, Liuxin ZHANG, QianYing Wang, Yebin Liu.*<br>
CVPR 2025. [[PDF](https://cvpr.thecvf.com/virtual/2025/poster/34759)]

**Vid2Avatar-Pro: Authentic Avatar from Videos in the Wild via Universal Prior.**<br>
*Chen Guo, Junxuan Li, Yash Kant, Yaser Sheikh, Shunsuke Saito, Chen Cao.*<br>
CVPR 2025. [[PDF](https://arxiv.org/abs/2503.01610)] [[Project](https://moygcc.github.io/vid2avatar-pro)]

**PuzzleAvatar: Assembling 3D Avatars from Personal Albums.**<br>
*Yuliang Xiu, Yufei Ye, Zhen Liu, Dimitrios Tzionas, Michael J. Black.*<br>
SIGGRAPH Asia (TOG) 2024. [[PDF](https://arxiv.org/abs/2405.14869)]

**iHuman: Instant Animatable Digital Humans From Monocular Videos.**<br> 
*Pramish Paudel, Anubhav Khanal, Ajad Chhatkuli, Danda Pani Paudel, Jyoti Tandukar.*<br> 
ECCV 2024. [[PDF](https://arxiv.org/abs/2407.11174)]

**HiLo: Detailed and Robust 3D Clothed Human Reconstruction with High-and Low-Frequency Information of Parametric Models.**<br>
*Yifan Yang, Dong Liu, Shuhai Zhang, Zeshuai Deng, Zixiong Huang, Mingkui Tan.*<br> 
CVPR 2024. [[PDF](https://arxiv.org/abs/2404.04876)] [[Github](https://github.com/YifYang993/HiLo)]

**IntrinsicAvatar: Physically Based Inverse Rendering of Dynamic Humans from Monocular Videos Via Explicit Ray Tracing.**<br>
*Shaofei Wang, Božidar Antić, Andreas Geiger, Siyu Tang.*<br> 
CVPR 2024. [[PDF](http://arxiv.org/abs/2312.05210)] [[Project](https://neuralbodies.github.io/IntrinsicAvatar)]

**GaussianAvatar: Towards Realistic Human Avatar Modeling from A Single Video Via Animatable 3D Gaussians.**<br>
*Liangxiao Hu, Hongwen Zhang, Yuxiang Zhang, Boyao Zhou, Boning Liu, Shengping Zhang, Liqiang Nie.*<br> 
CVPR 2024. [[PDF](http://arxiv.org/abs/2312.02134)] [[Project](https://huliangxiao.github.io/GaussianAvatar)] [[Github](https://github.com/aipixel/GaussianAvatar)]

**SiTH: Single-view Textured Human Reconstruction with Image-Conditioned Diffusion.**<br>
*[Hsuan-I Ho](https://azuxmioy.github.io), [Jie Song](https://ait.ethz.ch/people/song), [Otmar Hilliges](https://ait.ethz.ch/people/hilliges).*<br> 
CVPR 2024. [[PDF](https://arxiv.org/abs/2311.15855)] [[Project](https://sith-diffusion.github.io)]

**Recovering 3D Human Mesh from Monocular Images: A Survey.**<br>
*[Yating Tian](https://github.com/tinatiansjz), [Hongwen Zhang](https://github.com/HongwenZhang), [Yebin Liu](https://www.liuyebin.com), [Limin Wang](https://wanglimin.github.io).*<br>
TPAMI 2023. [[PDF](https://arxiv.org/abs/2203.01923)] [[Project](https://github.com/tinatiansjz/hmr-survey)] [[Dataset](https://github.com/tinatiansjz/hmr-survey#datasets)] [[Benchmarks](https://github.com/tinatiansjz/hmr-survey#benchmarks)]

**Mirror-Aware Neural Humans.**<br>
*Daniel Ajisafe, James Tang, Shih-Yang Su, Bastian Wandt, Helge Rhodin.*<br> 
3DV 2024. [[PDF](https://arxiv.org/abs/2311.09221)] [[Project](https://danielajisafe.github.io/mirror-aware-neural-humans)]

**TeCH: Text-guided Reconstruction of Lifelike Clothed Humans.**<br>
*[Yangyi Huang](https://huangyangyi.github.io), [Hongwei Yi](https://xyyhw.top), [Yuliang Xiu](https://xiuyuliang.cn), [Tingting Liao](https://github.com/tingtingliao), [Jiaxiang Tang](https://me.kiui.moe), [Deng Cai](http://www.cad.zju.edu.cn/home/dengcai), [Justus Thies](http://justusthies.github.io).*<br>
3DV 2024. [[PDF](https://arxiv.org/abs/2308.08545)] [[Project](https://huangyangyi.github.io/TeCH)]

**Single-Image 3D Human Digitization with Shape-Guided Diffusion.**<br>
*Badour AlBahar, Shunsuke Saito, Hung-Yu Tseng, Changil Kim, Johannes Kopf, Jia-Bin Huang.*<br>
SIGGRAPH Asia 2023. [[PDF](https://arxiv.org/abs/2208.15001)] [[Project](https://human-sgd.github.io)]

**Global-correlated 3D-decoupling Transformer for Clothed Avatar Reconstruction.**<br>
*Zechuan Zhang, Li Sun, Zongxin Yang, Ling Chen, Yi Yang.*<br>
NeurIPS 2023. [[PDF](https://arxiv.org/abs/2309.13524)]

**ISP: Multi-Layered Garment Draping with Implicit Sewing Patterns.**<br>
*Ren Li, Benoît Guillard, Pascal Fua.*<br> 
NeurIPS 2023. [[PDF](http://arxiv.org/abs/2305.14100)]

**NCHO: Unsupervised Learning for Neural 3D Composition of Humans and Objects.**<br>
*[Taeksoo Kim](https://taeksuu.github.io), [Shunsuke Saito](https://shunsukesaito.github.io), [Hanbyul Joo](https://jhugestar.github.io).*<br>
ICCV 2023. [[PDF](https://arxiv.org/abs/2305.14345)] [[Project](https://taeksuu.github.io/ncho)]

**Chupa: Carving 3D Clothed Humans from Skinned Shape Priors using 2D Diffusion Probabilistic Models.**<br>
*[Byungjun Kim](https://bjkim95.github.io), Patrick Kwon, Kwangho Lee, Myunggi Lee, Sookwan Han, Daesik Kim, Hanbyul Joo.*<br>
ICCV 2023 (Oral). [[PDF](https://arxiv.org/abs/2305.11870)] [[Project](https://snuvclab.github.io/chupa)]

**SHERF: Generalizable Human NeRF from a Single Image.**<br>
*[Shoukang Hu](https://skhu101.github.io), [Fangzhou Hong](https://hongfz16.github.io), [Liang Pan](https://scholar.google.com/citations?user=lSDISOcAAAAJ), Haiyi Mei, [Lei Yang](https://scholar.google.com.hk/citations?user=jZH2IPYAAAAJ&hl=en), [Ziwei Liu](https://liuziwei7.github.io).*<br>
ICCV 2023. [[PDF](https://arxiv.org/abs/2303.12791)] [[Project](https://skhu101.github.io/SHERF)] [[Code](https://github.com/skhu101/SHERF)]

**SynBody: Synthetic Dataset with Layered Human Models for 3D Human Perception and Modeling.**<br>
*Zhitao Yang, Zhongang Cai, Haiyi Mei, Shuai Liu, Zhaoxi Chen, Weiye Xiao, Yukun Wei, Zhongfei Qing, Chen Wei, Bo Dai, Wayne Wu, Chen Qian, Dahua Lin, Ziwei Liu, Lei Yang.*<br>
ICCV 2023. [[PDF](https://arxiv.org/abs/2303.17368)] [[Project](https://maoxie.github.io/SynBody)]

**Cyclic Test-Time Adaptation on Monocular Video for 3D Human Mesh Reconstruction.**<br>
*Hyeongjin Nam, Daniel Sungho Jung, Yeonguk Oh, Kyoung Mu Lee.*<br>
ICCV 2023. [[PDF](https://arxiv.org/abs/2308.06554)]

**HumanRF: High-Fidelity Neural Radiance Fields for Humans in Motion.**<br>
*[Mustafa Işık](https://www.mustafaisik.net), Martin Rünz, Markos Georgopoulos, Taras Khakhulin, Jonathan Starck, Lourdes Agapito, Matthias Nießner.*<br> 
SIGGRAPH 2023. [[PDF](http://arxiv.org/abs/2305.06356)] [[Project](http://www.synthesiaresearch.github.io/humanrf)] [[Code](https://github.com/synthesiaresearch/humanrf)] [[Data](http://www.actors-hq.com)]

**AvatarReX: Real-time Expressive Full-body Avatars.**<br>
*Zerong Zheng, Xiaochen Zhao, Hongwen Zhang, Boning Liu, Yebin Liu.*<br>
SIGGRAPH 2023 [[PDF](https://arxiv.org/abs/2305.04789)] [[Project](https://liuyebin.com/AvatarRex)]

**PoseVocab: Learning Joint-structured Pose Embeddings for Human Avatar Modeling.**<br>
*Zhe Li, Zerong Zheng, Yuxiao Liu, Boyao Zhou, Yebin Liu.*<br>
SIGGRAPH 2023 [[PDF](https://arxiv.org/abs/2304.13006)] [[Project](https://lizhe00.github.io/projects/posevocab)]

**High-Fidelity Clothed Avatar Reconstruction from a Single Image.**<br>
*Tingting Liao, Xiaomei Zhang, Yuliang Xiu, Hongwei Yi, Xudong Liu, Guo-Jun Qi, Yong Zhang, Xuan Wang, Xiangyu Zhu, Zhen Lei.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2304.03903)] [[Code](https://github.com/TingtingLiao/CAR)]

**SeSDF: Self-evolved Signed Distance Field for Implicit 3D Clothed Human Reconstruction.**<br>
*[Yukang Cao](https://yukangcao.github.io), [Kai Han](https://www.kaihan.org), [Kenneth Kwan-Yee K. Wong](https://i.cs.hku.hk/~kykwong).*<br> 
CVPR 2023. [[PDF](https://arxiv.org/abs/2304.00359)] [[Project](https://yukangcao.github.io/SeSDF)] [[Code](https://yukangcao.github.io)]

**Structured 3D Features for Reconstructing Relightable and Animatable Avatars.**<br>
*Enric Corona, Mihai Zanfir, Thiemo Alldieck, Eduard Gabriel Bazavan, Andrei Zanfir, Cristian Sminchisescu.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2212.06820)] [[Project](https://enriccorona.github.io/s3f)]

**Reconstructing Animatable Categories from Videos.**<br>
*[Gengshan Yang](https://gengshan-y.github.io), [Chaoyang Wang](https://mightychaos.github.io), [N Dinesh Reddy](https://dineshreddy91.github.io), [Deva Ramanan](http://www.cs.cmu.edu/~deva).*<br> 
CVPR 2023. [[PDF](http://arxiv.org/abs/2305.06351)] [[Project](https://gengshan-y.github.io/rac-www)] [[Code](https://github.com/gengshan-y/rac)]

**Representing Volumetric Videos as Dynamic MLP Maps.**<br>
*Sida Peng, Yunzhi Yan, Qing Shuai, Hujun Bao, Xiaowei Zhou.*<br>
CVPR 2023. [[PDF](https://arxiv.org/pdf/2304.06717.pdf)] [[Project](https://zju3dv.github.io/mlp_maps)] [[Code](https://github.com/zju3dv/mlp_maps)]

**Learning Neural Volumetric Representations of Dynamic Humans in Minutes.**<br>
*[Chen Geng](https://chen-geng.com), Sida Peng, Zhen Xu, Hujun Bao, Xiaowei Zhou.*<br>
CVPR 2023. [[PDF](https://chen-geng.com/files/instant_nvr.pdf)] [[Project](https://zju3dv.github.io/instant_nvr)] [[Code](https://github.com/zju3dv/instant-nvr)]

**CloSET: Modeling Clothed Humans on Continuous Surface with Explicit Template Decomposition.**<br>
*[Hongwen Zhang](https://hongwenzhang.github.io), [Siyou Lin](https://jsnln.github.io), [Ruizhi Shao](https://dsaurus.github.io/saurus), [Yuxiang Zhang](https://zhangyux15.github.io), [Zerong Zheng](https://zhengzerong.github.io), [Han Huang](http://www.liuyebin.com/closet/#), [Yandong Guo](http://www.liuyebin.com/closet/#), [Yebin Liu](https://liuyebin.com).*<br>
CVPR 2023. [[PDF](http://www.liuyebin.com/closet/assets/CloSET_CVPR2023.pdf)] [[Project](http://www.liuyebin.com/closet)]

**MonoHuman: Animatable Human Neural Field from Monocular Video.**<br>
*Zhengming Yu, Wei Cheng, Xian Liu, Wayne Wu, Kwan-Yee Lin.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2304.02001)] [[Project](https://yzmblog.github.io/projects/MonoHuman)]

**FlexNeRF: Photorealistic Free-viewpoint Rendering of Moving Humans from Sparse Views.**<br>
*Vinoj Jayasundara, Amit Agrawal, Nicolas Heron, Abhinav Shrivastava, Larry S. Davis.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2303.14368)]

**High-fidelity 3D Human Digitization from Single 2K Resolution Images.**<br>
*Sang-Hun Han, Min-Gyu Park, Ju Hong Yoon, Ju-Mi Kang, Young-Jae Park, Hae-Gon Jeon.*<br>
CVPR 2023 (Highlight). [[PDF](https://arxiv.org/abs/2303.15108)] [[Code](https://github.com/SangHunHan92/2K2K)]

**Learning Neural Volumetric Representations of Dynamic Humans in Minutes.**<br>
*Chen Geng, Sida Peng, Zhen Xu, Hujun Bao, Xiaowei Zhou.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2302.12237)] [[Project](https://zju3dv.github.io/instant_nvr)] 

**Vid2Avatar: 3D Avatar Reconstruction from Videos in the Wild via Self-supervised Scene Decomposition.**<br>
*Chen Guo, Tianjian Jiang, Xu Chen, Jie Song, Otmar Hilliges.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2302.11566)] [[Project](https://moygcc.github.io/vid2avatar)]

**Rodin: A Generative Model for Sculpting 3D Digital Avatars Using Diffusion.**<br>
*Tengfei Wang, Bo Zhang, Ting Zhang, Shuyang Gu, Jianmin Bao, Tadas Baltrusaitis, Jingjing Shen, Dong Chen, Fang Wen, Qifeng Chen, Baining Guo.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2212.06135)] [[Project](https://3d-avatar-diffusion.microsoft.com)]

**ECON: Explicit Clothed humans Obtained from Normals.**<br>
*Yuliang Xiu, Jinlong Yang, Xu Cao, Dimitrios Tzionas, Michael J. Black.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs)] [[Project](https://xiuyuliang.cn/econ)] [[Code](https://github.com/YuliangXiu/ECON)]

**X-Avatar: Expressive Human Avatars.**<br>
*[Kaiyue Shen](https://skype-line.github.io), Chen Guo, Manuel Kaufmann, Juan Jose Zarate, Julien Valentin, Jie Song, Otmar Hilliges.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2303.04805)] [[Project](https://skype-line.github.io/projects/X-Avatar)] [[Code](https://github.com/Skype-line/X-Avatar)]

**InstantAvatar: Learning Avatars from Monocular Video in 60 Seconds.**<br>
*Tianjian Jiang, Xu Chen, Jie Song, Otmar Hilliges.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2212.10550)] [[Project](https://tijiang13.github.io/InstantAvatar)] [[Code](https://github.com/tijiang13/InstantAvatar)]

**Learning Visibility Field for Detailed 3D Human Reconstruction and Relighting.**<br>
*Ruichen Zheng, Peng Li, Haoqian Wang, Tao Yu.*<br> 
CVPR 2023. [[PDF](http://arxiv.org/abs/2304.11900)]

**HumanGen: Generating Human Radiance Fields with Explicit Priors.**<br>
*Suyi Jiang, Haoran Jiang, Ziyu Wang, Haimin Luo, Wenzheng Chen, Lan Xu.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2212.05321)]

**SHARP: Shape-Aware Reconstruction of People In Loose Clothing.**<br>
*Sai Sagar Jinka, Rohan Chacko, Astitva Srivastava, Avinash Sharma, P.J. Narayanan.*<br>
IJCV 2023. [[PDF](https://arxiv.org/abs/2106.04778)]

**Geometry-aware Two-scale PIFu Representation for Human Reconstruction.**<br>
*Zheng Dong, Ke Xu, Ziheng Duan, Hujun Bao, Weiwei Xu, Rynson W.H. Lau.*<br>
NeurIPS 2022. [[PDF](https://arxiv.org/abs/2112.02082)]

**TotalSelfScan: Learning Full-body Avatars from Self-Portrait Videos of Faces, Hands, and Bodies.**<br>
*[Junting Dong](https://jtdong.com), [Qi Fang](https://raypine.github.io), Yudong Guo, Sida Peng, Qing Shuai, Hujun Bao, Xiaowei Zhou.*<br>
NeurIPS 2022. [[PDF](https://openreview.net/pdf?id=lgj33-O1Ely)] [[Project](https://zju3dv.github.io/TotalSelfScan)] [[Data](http://jtdong.com)]

**FOF: Learning Fourier Occupancy Field for Monocular Real-time Human Reconstruction.**<br>
*[Qiao Feng](https://fengq1a0.github.io), [Yebin Liu](http://www.liuyebin.com), [Yu-Kun Lai](https://users.cs.cf.ac.uk/Yukun.Lai), [Jingyu Yang](http://seea.tju.edu.cn/info/1015/1608.htm), [Kun Li](http://cic.tju.edu.cn/faculty/likun).*<br>
NeurIPS 2022. [[PDF](https://arxiv.org/abs/2206.02194)] [[Project](https://cic.tju.edu.cn/faculty/likun/projects/FOF/index.html)] [[Code](https://github.com/fengq1a0/FOF)]

Dual-Space NeRF: Learning Animatable Avatars and Scene Lighting in Separate Spaces
Yihao Zhi, Shenhan Qian, Xinhao Yan, Shenghua Gao
3DV 2022. [[PDF](https://arxiv.org/abs/2208.14851)] [[Code](https://github.com/zyhbili/Dual-Space-NeRF)]

**Neural Point-based Shape Modeling of Humans in Challenging Clothing.**<br>
*Qianli Ma, Jinlong Yang, Michael J. Black, Siyu Tang.*<br>
3DV 2022. [[PDF](https://arxiv.org/abs/2209.06814)]

**HVTR: Hybrid Volumetric-Textural Rendering for Human Avatars.**<br>
*Tao Hu, Tao Yu, Zerong Zheng, He Zhang, Yebin Liu, Matthias Zwicker.*<br>
3DV 2022. [[PDF](https://arxiv.org/abs/2112.10203)] [[Project](https://www.cs.umd.edu/~taohu/hvtr)]

**Human Performance Modeling and Rendering via Neural Animated Mesh.**<br>
*[Fuqiang Zhao](https://zhaofuq.github.io), Yuheng Jiang, Kaixin Yao, Jiakai Zhang, Liao Wang, Haizhao Dai, Yuhui Zhong, Yingliang Zhang, Minye Wu, Lan Xu, Jingyi Yu.*<br>
SIGGRAPH Asia 2022. [[PDF](https://arxiv.org/abs/2209.08468)] [[Project](https://zhaofuq.github.io/NeuralAM)]

**FloRen: Real-time High-quality Human Performance Rendering via Appearance Flow Using Sparse RGB Cameras.**<br>
*Ruizhi Shao, Liliang Chen, Zerong Zheng, Hongwen Zhang, Yuxiang Zhang, Han Huang, Yandong Guo, Yebin Liu.*<br>
SIGGRAPH Asia 2022. [[PDF](https://dl.acm.org/doi/abs/10.1145/3550469.3555409)] 

**Occupancy Planes for Single-view RGB-D Human Reconstruction.**<br>
*Xiaoming Zhao, Yuan-Ting Hu, Zhongzheng Ren, Alexander G. Schwing.*<br>
AAAI 2023. [[PDF](https://arxiv.org/abs/2208.02817)] [[Code](https://github.com/Xiaoming-Zhao/oplanes)]

**HuMMan: Multi-Modal 4D Human Dataset for Versatile Sensing and Modeling.**<br>
*[Zhongang Cai](https://caizhongang.github.io), [Daxuan Ren](https://kimren227.github.io), [Ailing Zeng](https://ailingzeng.site), [Zhengyu Lin](https://www.linkedin.com/in/zhengyu-lin-a908aba8), [Tao Yu](https://ytrock.com), [Wenjia Wang](https://scholar.google.com/citations?user=cVWmlYQAAAAJ&hl), Xiangyu Fan, Yang Gao, Yifan Yu, Liang Pan, Fangzhou Hong, Mingyuan Zhang, Chen Change Loy, Lei Yang, Ziwei Liu.*<br>
ECCV 2022 (Oral). [[PDF](https://arxiv.org/abs/2204.13686)] [[Project](https://caizhongang.github.io/projects/HuMMan)]

**Unsupervised Learning of Efficient Geometry-Aware Neural Articulated Representations.**<br>
*Atsuhiro Noguchi, Xiao Sun, Stephen Lin, Tatsuya Harada.*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2204.08839)] [[Project](https://nogu-atsu.github.io/ENARF-GAN)] [[Code](https://github.com/nogu-atsu/ENARF-GAN)]

**NeuMan: Neural Human Radiance Field from a Single Video.**<br>
*Wei Jiang, Kwang Moo Yi, Golnoosh Samei, Oncel Tuzel, Anurag Ranjan.*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2203.10157)] [[Code](https://github.com/apple/ml-neuman)]

**ARAH: Animatable Volume Rendering of Articulated Human SDFs.**<br>
*[Shaofei Wang](https://taconite.github.io), [Katja Schwarz](https://katjaschwarz.github.io), [Andreas Geiger](http://www.cvlibs.net), [Siyu Tang](https://vlg.inf.ethz.ch/team/Prof-Dr-Siyu-Tang.html).*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2210.10036)] [[Project](https://neuralbodies.github.io/arah)] [[Code](https://github.com/taconite/arah-release)]

**DiffuStereo: High Quality Human Reconstruction via Diffusion-based Stereo Using Sparse Cameras.**<br>
*Ruizhi Shao, Zerong Zheng, Hongwen Zhang, Jingxiang Sun, Yebin Liu.*<br>
ECCV (Oral) 2022. [[PDF](https://arxiv.org/abs/2207.08000)] [[Code](https://github.com/DSaurus/DiffuStereo)]

**LoRD: Local 4D Implicit Representation for High-Fidelity Dynamic Human Modeling.**<br>
*Boyan Jiang, Xinlin Ren, Mingsong Dou, Xiangyang Xue, Yanwei Fu, Yinda Zhang.*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2208.08622)] [[Code](https://boyanjiang.github.io/LoRD)]

**Neural Capture of Animatable 3D Human from Monocular Video.**<br>
*Gusi Te, Xiu Li, Xiao Li, Jinglu Wang, Wei Hu, Yan Lu.*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2208.08728)]

**The One Where They Reconstructed 3D Humans and Environments in TV Shows.**<br>
*Georgios Pavlakos, Ethan Weber, Matthew Tancik, Angjoo Kanazawa.*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2207.14279)] [[Project](http://ethanweber.me/sitcoms3D)]

**UNIF: United Neural Implicit Functions for Clothed Human Reconstruction and Animation.**<br>
*Shenhan Qian, Jiale Xu, Ziwei Liu, Liqian Ma, Shenghua Gao.*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2207.09835)]

**3D Clothed Human Reconstruction in the Wild.**<br>
*Gyeongsik Moon, Hyeongjin Nam, Takaaki Shiratori, Kyoung Mu Lee.*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2207.10053)] [[Project](https://github.com/hygenie1228/ClothWild_RELEASE/blob/main)]

**NDF: Neural Deformable Fields for Dynamic Human Modelling.**<br>
*Ruiqi Zhang, Jie Chen.*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2207.09193)]

**Animatable Volume Rendering of Articulated Human SDFs.**<br>
*[Shaofei Wang](https://taconite.github.io), [Katja Schwarz](https://katjaschwarz.github.io), [Andreas Geiger](http://www.cvlibs.net), [Siyu Tang](https://vlg.inf.ethz.ch/team/Prof-Dr-Siyu-Tang.html).*<br>
ECCV 2022. [[PDF](https://drive.google.com/file/d/10yCrdOadwKNiDQBni23_W03ZwVafkfCJ/view)] [[Project](https://neuralbodies.github.io/arah)] [[Project](https://github.com/taconite/arah-release)]

**Learning Implicit Templates for Point-Based Clothed Human Modeling.**<br>
*Siyou Lin, Hongwen Zhang, Zerong Zheng, Ruizhi Shao, Yebin Liu.*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2207.06955)] [[Project](https://jsnln.github.io/fite)] [[Project](https://github.com/jsnln/fite)]

**DANBO: Disentangled Articulated Neural Body Representations via Graph Neural Networks.**<br>
*[Shih-Yang Su](https://lemonatsu.github.io), [Timur Bagautdinov](https://scholar.google.ch/citations?user=oLi7xJ0AAAAJ&hl=en), and [Helge Rhodin](http://helge.rhodin.de).*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2205.01666)] [[Project](https://lemonatsu.github.io/danbo)] [[Code](https://github.com/LemonATsu/DANBO-pytorch)]

**Geometry-Guided Progressive NeRF for Generalizable and Efficient Neural Human Rendering.**<br>
*Mingfei Chen, Jianfeng Zhang, Xiangyu Xu, Lijuan Liu, Jiashi Feng, Shuicheng Yan.*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2112.04312)]

**AvatarCap: Animatable Avatar Conditioned Monocular Human Volumetric Capture.**<br>
*Zhe Li, Zerong Zheng, Hongwen Zhang, Chaonan Ji, Yebin Liu.*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2207.02031)] [[Project](http://www.liuyebin.com/avatarcap/avatarcap.html)]

**Authentic Volumetric Avatars From a Phone Scan.**<br>
*[Chen Cao](https://sites.google.com/site/zjucaochen/home), Tomas Simon, Jin Kyu Kim, Gabe Schwartz, Michael Zollhoefer, Shunsuke Saito, Stephen Lombardi, Shih-en Wei, Danielle Belko, Shoou-i Yu, Yaser Sheikh, Jason Saragih.*<br>
SIGGRAPH 2022. [[PDF](https://drive.google.com/file/d/1i4NJKAggS82wqMamCJ1OHRGgViuyoY6R/view?usp=sharing)] [[Project](https://zollhoefer.com/papers/arXiv22_InstantAvatars/page.html)]

**HumanNeRF: Efficiently Generated Human Radiance Field from Sparse Inputs.**<br>
*[Fuqiang Zhao](https://zhaofuq.github.io), Wei Yang, Jiakai Zhang, Pei Lin, Yingliang Zhang, Jingyi Yu, Lan Xu.*<br>
CVPR 2022. [[PDF](https://arxiv.org/pdf/2112.02789.pdf)] [[Project](https://zhaofuq.github.io/humannerf)] 

**Photorealistic Monocular 3D Reconstruction of Humans Wearing Clothing.**<br>
*[Thiemo Alldieck](https://scholar.google.com/citations?user=tJlD24EAAAAJ), [Mihai Zanfir](https://scholar.google.com/citations?user=af68sKkAAAAJ), [Cristian Sminchisescu](https://scholar.google.com/citations?user=LHTI1W8AAAAJ).*<br>
CVPR 2022. [[PDF](https://phorhum.github.io/static/assets/alldieck2022phorhum.pdf)] [[Project](https://phorhum.github.io)]

**HumanNeRF: Free-viewpoint Rendering of Moving People from Monocular Video.**<br>
*[Chung-Yi Weng](https://homes.cs.washington.edu/~chungyi), Brian Curless, Pratul Srinivasan,Jonathan T. Barron, Ira Kemelmacher-Shlizerman.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2201.04127)] [[Project](https://grail.cs.washington.edu/projects/humannerf)]

**H4D: Human 4D Modeling by Learning Neural Compositional Representation.**<br>
*Boyan Jiang, Yinda Zhang, Xingkui Wei, Xiangyang Xue, Yanwei Fu.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2203.01247)]

**OcclusionFusion: Occlusion-aware Motion Estimation for Real-time Dynamic 3D Reconstruction.**<br>
*[Wenbin Lin](https://wenbin-lin.github.io), Chengwei Zheng, Jun-Hai Yong, Feng Xu.*<br>
CVPR 2022. [[PDF](https://arxiv.org/pdf/2203.07977.pdf)] [[Project](https://wenbin-lin.github.io/OcclusionFusion)]

**PINA: Learning a Personalized Implicit Neural Avatar from a Single RGB-D Video Sequence.**<br>
*Zijian Dong, Chen Guo, Jie Song, Xu Chen, Andreas Geiger, Otmar Hilliges.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2203.01754)] [[Project](https://zj-dong.github.io/pina)]

**SelfRecon: Self Reconstruction Your Digital Avatar from Monocular Video.**<br>
*[Boyi Jiang](https://scholar.google.com/citations?user=lTlZV8wAAAAJ&hl=zh-CN), Yang Hong, Hujun Bao, Juyong Zhang.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2201.12792)] [[Project](https://jby1993.github.io/SelfRecon)]

**Fourier PlenOctrees for Dynamic Radiance Field Rendering in Real-time.**<br>
*Liao Wang, Jiakai Zhang, Xinhang Liu, Fuqiang Zhao, Yanshun Zhang, Yingliang Zhang, Minye Wu, Lan Xu, Jingyi Yu.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2202.08614)]

**NeuralHOFusion: Neural Volumetric Rendering under Human-object Interactions.**<br>
*Yuheng Jiang, Suyi Jiang, Guoxing Sun, Zhuo Su, Kaiwen Guo, Minye Wu, Jingyi Yu, Lan Xu.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2202.12825)] [[Project](https://nowheretrix.github.io/neuralfusion)]

**JIFF: Jointly-aligned Implicit Face Function for High Quality Single View Clothed Human Reconstruction.**<br>
*[Yukang Cao](https://github.com/yukangcao), [Guanying Chen](https://guanyingc.github.io), [Kai Han](http://www.hankai.org), [Wenqi Yang](https://github.com/ywq), [Kwan-Yee K. Wong](http://i.cs.hku.hk/~kykwong).*<br>
CVPR 2022 (oral). [[PDF](https://arxiv.org/abs/2204.10549)] [[Project](https://yukangcao.github.io/JIFF)]

**High-Fidelity Human Avatars from a Single RGB Camera.**<br>
*Hao Zhao, [Jinsong Zhang](https://zhangjinso.github.io), [Yu-Kun Lai](https://users.cs.cf.ac.uk/Yukun.Lai), [Zerong Zheng](https://zhengzerong.github.io), Yingdi Xie, [Yebin Liu](http://www.liuyebin.com), [Kun Li](http://cic.tju.edu.cn/faculty/likun).*<br>
CVPR 2022. [[PDF](http://cic.tju.edu.cn/faculty/likun/projects/HF-Avatar/assets/main.pdf)] [[Project](http://cic.tju.edu.cn/faculty/likun/projects/HF-Avatar/index.html)] [[Project](https://github.com/hzhao1997/HF-Avatar)] [[Data](https://drive.google.com/file/d/1qh1dj5ZoUBst_02UJY7IWstQMhb8L5IA/view?usp=sharing)]

**ICON: Implicit Clothed humans Obtained from Normals.**<br>
*[Yuliang Xiu](https://ps.is.tuebingen.mpg.de/person/yxiu), [Jinlong Yang](https://ps.is.tuebingen.mpg.de/person/jyang), [Dimitrios Tzionas](https://ps.is.mpg.de/~dtzionas), [Michael J. Black](https://ps.is.tuebingen.mpg.de/person/black).*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2112.09127)] [[Code](https://github.com/YuliangXiu/ICON)]

**DoubleField: Bridging the Neural Surface and Radiance Fields for High-fidelity Human Rendering.**<br>
*Ruizhi Shao, Hongwen Zhang, He Zhang, Yanpei Cao, Tao Yu, Yebin Liu.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2106.03798)] [[Project](http://www.liuyebin.com/dbfield/dbfield.html)]

**Structured Local Radiance Fields for Human Avatar Modeling.**<br>
*[Zerong Zheng](https://zhengzerong.github.io), Han Huang, Tao Yu, Hongwen Zhang, Yandong Guo, Yebin Liu.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2203.14478)] [[Project](https://liuyebin.com/slrf/slrf.html)] [[Code](https://zhengzerong.github.io)]

**DoubleField: Bridging the Neural Surface and Radiance Fields for High-fidelity Human Reconstruction and Rendering.**<br>
*Ruizhi Shao, [Hongwen Zhang](https://hongwenzhang.github.io), He Zhang, Mingjia Chen, Yanpei Cao, Tao Yu, Yebin Liu.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2106.03798)] [[Project](http://www.liuyebin.com/dbfield/dbfield.html)]

**I M Avatar: Implicit Morphable Head Avatars from Videos.**<br>
*Yufeng Zheng, Victoria Fernández Abrevaya, Xu Chen, Marcel C. Bühler, Michael J. Black, Otmar Hilliges.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2112.07471)]

**Surface-Aligned Neural Radiance Fields for Controllable 3D Human Synthesis.**<br>
*Tianhan Xu, Yasuhiro Fujita, Eiichi Matsumoto.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2201.01683)]

**Neural Head Avatars from Monocular RGB Videos.**<br>
*[Philip-William Grassal](https://hci.iwr.uni-heidelberg.de/vislearn/people), [Malte Prinzler](https://de.linkedin.com/in/malte-prinzler), [Titus Leistner](https://titus-leistner.de/pages/about-me.html), [Carsten Rother](https://hci.iwr.uni-heidelberg.de/vislearn/people/carsten-rother), [Matthias Nießner](https://www.niessnerlab.org/members/matthias_niessner/profile.html), [Justus Thies](https://justusthies.github.io).*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2112.01554)] [[Project](https://philgras.github.io/neural_head_avatars/neural_head_avatars.html)]

**gDNA: Towards Generative Detailed Neural Avatars.**<br>
*[Xu Chen](https://ait.ethz.ch/people/xu), [Tianjian Jiang](https://ait.ethz.ch/people/zhengyuf), [Jie Song](https://ait.ethz.ch/people/song), [Jinlong Yang](https://is.mpg.de/person/jyang), [Michael J. Black](https://ps.is.mpg.de/~black), [Andreas Geiger](http://www.cvlibs.net), [Otmar Hilliges](https://ait.ethz.ch/people/hilliges).*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2201.04123)] [[Project](https://ait.ethz.ch/projects/2022/gdna/downloads)] [[Code](https://github.com/xuchen-ethz/gdna)]

**HumanNeRF: Generalizable Neural Human Radiance Field from Sparse Inputs.**<br>
*Fuqiang Zhao, Wei Yang, Jiakai Zhang, Pei Lin, Yingliang Zhang, Jingyi Yu, Lan Xu.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2112.02789)] [[Project](https://zhaofuq.github.io/humannerf)]

**PERGAMO: Personalized 3D Garments from Monocular Video.**<br>
*Andrés Casado-Elvira, Marc Comino Trinidad, Dan Casas.*<br>
CFG 2022. [[PDF](https://arxiv.org/abs/2210.15040)] [[Project](http://mslab.es/projects/PERGAMO)]

**Explicit Clothing Modeling for an Animatable Full-Body Avatar.**<br>
*Donglai Xiang, Fabian Andres Prada, Timur Bagautdinov, Weipeng Xu, Yuan Dong, He Wen, Jessica Hodgins, Chenglei Wu.*<br>
SIGGRAPH Asia 2021. [[PDF](https://arxiv.org/abs/2106.14879)]

**Driving-Signal Aware Full-Body Avatars.**<br>
*Timur Bagautdinov, Chenglei Wu, Tomas Simon, Fabian Prada, Takaaki Shiratori, Shih-En Wei, Weipeng Xu, Yaser Sheikh, Jason Saragih.*<br>
TOG 2021. [[PDF](https://arxiv.org/abs/2105.10441)]

**High-Fidelity 3D Digital Human Head Creation from RGB-D Selfies.**<br>
*Xiangkai Lin, Yajing Chen, Linchao Bao, Haoxian Zhang, Sheng Wang, Xuefei Zhe, Xinwei Jiang, Jue Wang, Dong Yu, Zhengyou Zhang.*<br>
TOG 2021. [[PDF](https://arxiv.org/abs/2010.05562)] [[Code](https://github.com/tencent-ailab/hifi3dface)] [[Project](https://github.com/tencent-ailab/hifi3dface_projpage)]

**Real-time Deep Dynamic Characters.**<br>
*Marc Habermann, Lingjie Liu, Weipeng Xu, Michael Zollhoefer, Gerard Pons-Moll, Christian Theobalt.*<br>
TOG 2021. [[PDF](https://arxiv.org/abs/2105.01794)] [[Project](https://people.mpi-inf.mpg.de/~mhaberma/projects/2021-ddc)]

**Learning Skeletal Articulations with Neural Blend Shapes.**<br>
*Peizhuo Li, Kfir Aberman, Rana Hanocka, Libin Liu, Olga Sorkine-Hornung, Baoquan Chen.*<br>
TOG 2021. [[PDF](https://arxiv.org/abs/2105.02451)] [[Video](https://youtu.be/antc20EFh6k)] [[Project](https://peizhuoli.github.io/neural-blend-shapes)]

**Detailed Avatar Recovery from Single Image.**<br>
*Hao Zhu, Xinxin Zuo, Haotian Yang, Sen Wang, Xun Cao, Ruigang Yang.*<br>
TPAMI 2021. [[PDF](https://arxiv.org/abs/2108.02931)]

**RSC-Net: 3D Human Pose, Shape and Texture from Low-Resolution Images and Videos.**<br>
*Xiangyu Xu, Hao Chen, Francesc Moreno-Noguer, Laszlo A. Jeni, Fernando De la Torre.*<br>
TPAMI 2021. [[PDF](https://arxiv.org/abs/2103.06498)] [[Code](https://github.com/xuxy09/RSC-Net)] [[Project](https://sites.google.com/view/xiangyuxu/3d_eccv20)]

**A Deeper Look into DeepCap.**<br>
*[Marc Habermann](http://people.mpi-inf.mpg.de/~mhaberma), [Weipeng Xu](http://people.mpi-inf.mpg.de/~wxu), [Michael Zollhoefer](https://zollhoefer.com), [Gerard Pons-Moll](https://www.mpi-inf.mpg.de/departments/computer-vision-and-multimodal-computing/people/gerard-pons-moll), [Christian Theobalt](http://www.mpi-inf.mpg.de/~theobalt).*<br>
TPAMI 2021. [[PDF](https://people.mpi-inf.mpg.de/~mhaberma/projects/2021-tpami-deeperdeepcap/data/paper.pdf)] [[Code](https://people.mpi-inf.mpg.de/~mhaberma/projects/2021-tpami-deeperdeepcap)] [[Data](https://gvv-assets.mpi-inf.mpg.de)]

**Learning Implicit 3D Representations of Dressed Humans from Sparse Views.**<br>
*Pierre Zins, Yuanlu Xu, Edmond Boyer, Stefanie Wuhrer, Tony Tung.*<br>
3DV 2021. [[PDF](https://arxiv.org/abs/2104.08013)]

**PIXIE: Collaborative Regression of Expressive Bodies using Moderation.**<br>
*Yao Feng, Vasileios Choutas, Timo Bolkart, Dimitrios Tzionas, Michael J. Black.*<br>
3DV 2021. [[PDF](https://arxiv.org/pdf/2105.05301.pdf)] [[Project](https://pixie.is.tue.mpg.de)] 

**A-NeRF: Articulated Neural Radiance Fields for Learning Human Shape, Appearance, and Pose.**<br>
*[Shih-Yang Su](https://lemonatsu.github.io), [Frank Yu](https://yu-frank.github.io), [Michael Zollhoefer](https://zollhoefer.com), [Helge Rhodin](http://helge.rhodin.de).*<br>
NeurIPS 2021. [[PDF](https://arxiv.org/abs/2102.06199)] [[Project](https://lemonatsu.github.io/ANeRF-Surface-free-Pose-Refinement)]

**Class-agnostic Reconstruction of Dynamic Objects from Videos.**<br>
*[Zhongzheng Ren](https://jason718.github.io), [Xiaoming Zhao](https://xiaoming-zhao.com/index.php), [Alexander G. Schwing](http://www.alexander-schwing.de).*<br>
NeurIPS 2021. [[PDF](https://arxiv.org/abs/2112.02091)] [[Project](https://jason718.github.io/redo)]

**Neural Human Performer: Learning Generalizable Radiance Fields for Human Performance Rendering.**<br>
*Youngjoong Kwon, Dahun Kim, Duygu Ceylan, Henry Fuchs.*<br>
NeurIPS 2021. [[PDF](https://arxiv.org/abs/2109.07448)]

**MetaAvatar: Learning Animatable Clothed Human Models from Few Depth Images.**<br>
*[Shaofei Wang](https://taconite.github.io), Marko Mihajlovic, Qianli Ma, Andreas Geiger, Siyu Tang.*<br>
NeurIPS 2021. [[PDF](https://arxiv.org/abs/2106.11944)] [[Project](https://neuralbodies.github.io/metavatar)] [[Code](https://github.com/taconite/MetaAvatar-release)]

**Garment4D: Garment Reconstruction from Point Cloud Sequences.**<br>
*[Fangzhou Hong](https://hongfz16.github.io), Liang Pan, Zhongang Cai, Ziwei Liu.*<br>
NeurIPS 2021. [[PDF](https://openreview.net/pdf?id=aF60hOEwHP)] [[Project](https://hongfz16.github.io/projects/Garment4D.html)] [[Code](https://github.com/hongfz16/Garment4D)]

**Learning Anchored Unsigned Distance Functions with Gradient Direction Alignment for Single-view Garment Reconstruction.**<br>
*Fang Zhao, Wenhao Wang, Shengcai Liao, Ling Shao.*<br>
ICCV 2021. [[PDF](https://arxiv.org/abs/2108.08478)] [[Code](https://github.com/zhaofang0627/AnchorUDF)]

**Dynamic Surface Function Networks for Clothed Human Bodies.**<br>
*Andrei Burov, Matthias Nießner, Justus Thies.*<br>
ICCV 2021. [[PDF](https://arxiv.org/abs/2104.03978)] [[Video](https://youtu.be/4wbSi9Sqdm4)] [[Code](https://github.com/andreiburov/DSFN)]

**THUNDR: Transformer-based 3D HUmaN Reconstruction with Markers.**<br>
*Mihai Zanfir, Andrei Zanfir, Eduard Gabriel Bazavan, William T. Freeman, Rahul Sukthankar, Cristian Sminchisescu.*<br>
ICCV 2021. [[PDF](https://arxiv.org/abs/2106.09336)]

**Neural Articulated Radiance Field.**<br>
*Atsuhiro Noguchi, Xiao Sun, Stephen Lin, Tatsuya Harada.*<br>
ICCV 2021. [[PDF](http://arxiv.org/abs/2104.03110)]

**3D Human Texture Estimation From a Single Image With Transformers.**<br>
*Xiangyu Xu, Chen Change Loy.*<br>
ICCV 2021. [[PDF](https://openaccess.thecvf.com/content/ICCV2021/html/Xu_3D_Human_Texture_Estimation_From_a_Single_Image_With_Transformers_ICCV_2021_paper.html)]

**ARCH++: Animation-Ready Clothed Human Reconstruction Revisited.**<br>
*Tong He, Yuanlu Xu, Shunsuke Saito, Stefano Soatto, Tony Tung.*<br>
ICCV 2021. [[PDF](https://openaccess.thecvf.com/content/ICCV2021/html/He_ARCH_Animation-Ready_Clothed_Human_Reconstruction_Revisited_ICCV_2021_paper.html)]

**DeePSD: Automatic Deep Skinning and Pose Space Deformation for 3D Garment Animation.**<br>
*Hugo Bertiche, Meysam Madadi, Emilio Tylson, Sergio Escalera.*<br>
ICCV 2021. [[PDF](https://openaccess.thecvf.com/content/ICCV2021/html/Bertiche_DeePSD_Automatic_Deep_Skinning_and_Pose_Space_Deformation_for_3D_ICCV_2021_paper.html)]

**EgoRenderer: Rendering Human Avatars From Egocentric Camera Images.**<br>
*Tao Hu, Kripasindhu Sarkar, Lingjie Liu, Matthias Zwicker, Christian Theobalt.*<br>
ICCV 2021. [[PDF](https://openaccess.thecvf.com/content/ICCV2021/html/Hu_EgoRenderer_Rendering_Human_Avatars_From_Egocentric_Camera_Images_ICCV_2021_paper.html)]

**SNARF: Differentiable Forward Skinning for Animating Non-Rigid Neural Implicit Shapes.**<br>
*[Xu Chen](https://ait.ethz.ch/people/xu), [Yufeng Zheng](https://ait.ethz.ch/people/zhengyuf), [Michael J. Black](https://ps.is.mpg.de/~black), [Otmar Hilliges](https://ait.ethz.ch/people/hilliges), [Andreas Geiger](http://www.cvlibs.net).*<br>
ICCV 2021. [[PDF](https://arxiv.org/abs/2104.03953)] [[Project](https://xuchen-ethz.github.io/snarf/] [[Code](https://github.com/xuchen-ethz/snarf)]

**Neural-GIF: Neural Generalized Implicit Functions for Animating People in Clothing.**<br>
*[Garvita Tiwari](https://virtualhumans.mpi-inf.mpg.de/people/Tiwari.html), Nikolaos Sarafianos, [Tony Tung](https://sites.google.com/site/tony2ng), Gerard Pons-Moll.*<br>
ICCV 2021. [[PDF](https://arxiv.org/abs/2108.08807)] [[Project](https://virtualhumans.mpi-inf.mpg.de/neuralgif)]

**The Power of Points for Modeling Humans in Clothing.**<br>
*[Qianli Ma](https://qianlim.github.io), Jinlong Yang, Siyu Tang, Michael J. Black.*<br>
ICCV 2021. [[PDF](https://arxiv.org/abs/2109.01137)] [[Project](https://qianlim.github.io/POP)] [[Code](https://github.com/qianlim/POP)]

**Learning to Regress Bodies from Images using Differentiable Semantic Rendering.**<br>
*[Sai Kumar Dwivedi](https://ps.is.tuebingen.mpg.de/person/sdwivedi), [Nikos Athanasiou](https://ps.is.tuebingen.mpg.de/employees/nathanasiou), [Muhammed Kocabas](https://ps.is.tuebingen.mpg.de/person/mkocabas), [Michael J. Black](https://ps.is.tuebingen.mpg.de/person/black).*<br>
ICCV 2021. [[PDF](https://arxiv.org/abs/2110.03480)] [[Project](https://dsr.is.tue.mpg.de)]

**imGHUM: Implicit Generative Models of 3D Human Shape and Articulated Pose.**<br>
*Thiemo Alldieck, Hongyi Xu, Cristian Sminchisescu.*<br>
ICCV 2021. [[PDF](https://arxiv.org/abs/2108.10842)] 

**DeepMultiCap: Performance Capture of Multiple Characters Using Sparse Multiview Cameras.**<br>
*[Yang Zheng](https://y-zheng18.github.io/zy.github.io), Ruizhi Shao, [Yuxiang Zhang](https://zhangyux15.github.io), [Zerong Zheng](https://zhengzerong.github.io), [Tao Yu](https://ytrock.com), [Yebin Liu](http://www.liuyebin.com/student.html).*<br>
ICCV 2021. [[PDF](http://www.liuyebin.com/dmc/assets/main.pdf)] [[Project](http://www.liuyebin.com/dmc/dmc.html)]

**Animatable Neural Radiance Fields for Human Body Modeling.**<br>
*[Sida Peng](https://pengsida.net), Junting Dong, Qianqian Wang, Shangzhan Zhang, Qing Shuai, Hujun Bao, Xiaowei Zhou.*<br>
ICCV 2021. [[PDF](https://arxiv.org/abs/2105.02872)] [[Project](https://zju3dv.github.io/animatable_nerf)] [[Code](https://github.com/zju3dv/animatable_nerf)]

**Animatable Neural Radiance Fields for Modeling Dynamic Human Bodies.**<br>
*Sida Peng, Junting Dong, Qianqian Wang, Shangzhan Zhang, Qing Shuai, Xiaowei Zhou, Hujun Bao.*<br>
ICCV 2021. [[PDF](https://arxiv.org/pdf/2203.08133.pdf)] [[Project](https://zju3dv.github.io/animatable_nerf)]

**Function4D: Real-time Human Volumetric Capture from Very Sparse Consumer RGBD Sensors.**<br>
*Tao Yu, Zerong Zheng, Kaiwen Guo, Pengpeng Liu, Qionghai Dai, Yebin Liu.*<br>
CVPR 2021 (oral). [[PDF](http://www.liuyebin.com/Function4D/assets/Function4D.pdf)] [[Project](http://www.liuyebin.com/Function4D/Function4D.html)] [[THuman2.0 Dataset](https://github.com/ytrock/THuman2.0-Dataset)]

**POSEFusion: Pose-guided Selective Fusion for Single-view Human Volumetric Capture.**<br>
*[Zhe Li](https://lizhe00.github.io), Tao Yu, Zerong Zheng, Kaiwen Guo, Yebin Liu.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.15331)] [[Project](http://www.liuyebin.com/posefusion/posefusion.html)]

**SCANimate: Weakly Supervised Learning of Skinned Clothed Avatar Networks.**<br>
*Shunsuke Saito, Jinlong Yang, Qianli Ma, Michael J. Black.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2104.03313)] [[Code](https://www.cs.cmu.edu/~aayushb/SST)]

**Normalized Avatar Synthesis Using StyleGAN and Perceptual Refinement.**<br>
*Huiwen Luo, Koki Nagano, Han-Wei Kung, [Qingguo Xu](https://qingguo-xu.com), Zejian Wang, Lingyu Wei, Liwen Hu, Hao Li.*<br>
CVPR 2021. [[PDF](http://arxiv.org/abs/2106.11423)]

**DeepSurfels: Learning Online Appearance Fusion.**<br>
*Marko Mihajlovic, Silvan Weder, Marc Pollefeys, Martin R. Oswald.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2012.14240)] [[Project](https://onlinereconstruction.github.io/DeepSurfels)] [[Code](https://github.com/onlinereconstruction/deep_surfels)]

**Semi-Supervised Synthesis of High-Resolution Editable Textures for 3D Humans.**<br>
*Bindita Chaudhuri, Nikolaos Sarafianos, Linda Shapiro, Tony Tung.*<br>
CVPR 2021. [[PDF](http://arxiv.org/abs/2103.17266)]

**StereoPIFu: Depth Aware Clothed Human Digitization via Stereo Vision.**<br>
*Yang Hong, [Juyong Zhang](http://staff.ustc.edu.cn/~juyong), Boyi Jiang, [Yudong Guo](https://yudongguo.github.io), Ligang Liu, Hujun Bao.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2104.05289)] [[Project](https://crishy1995.github.io/StereoPIFuProject)] [[Code](https://github.com/CrisHY1995/StereoPIFu_Code)]

**LASR: Learning Articulated Shape Reconstruction from a Monocular Video.**<br>
*Gengshan Yang, Deqing Sun, Varun Jampani, Daniel Vlasic, Forrester Cole, Huiwen Chang, Deva Ramanan, William T. Freeman, Ce Liu.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2105.02976)] [[Project](https://lasr-google.github.io)]

**Multi-person Implicit Reconstruction from a Single Image.**<br>
*Armin Mustafa, Akin Caliskan, Lourdes Agapito, Adrian Hilton.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2104.09283)]

**StylePeople: A Generative Model of Fullbody Human Avatars.**<br>
*Artur Grigorev, Karim Iskakov, Anastasia Ianina, Renat Bashirov, Ilya Zakharkin, Alexander Vakhitov, Victor Lempitsky.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2104.08363)]

**SCALE: Modeling Clothed Humans with a Surface Codec of Articulated Local Elements.**<br>
*Qianli Ma, Shunsuke Saito, Jinlong Yang, Siyu Tang, Michael J. Black.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2104.07660)] [[Project](https://qianlim.github.io/SCALE)]

**Semi-supervised Synthesis of High-Resolution Editable Textures for 3D Humans.**<br>
*Bindita Chaudhuri, Nikolaos Sarafianos, Linda Shapiro, Tony Tung.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.17266)]

**Monocular Real-time Full Body Capture with Inter-part Correlations.**<br>
*[Yuxiao Zhou](https://calciferzh.github.io), [Marc Habermann](https://people.mpi-inf.mpg.de/~mhaberma), Ikhsanul Habibie, Ayush Tewari, [Christian Theobalt](https://people.mpi-inf.mpg.de/~theobalt), [Feng Xu](http://xufeng.site).*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2012.06087)]

**SMPLicit: Topology-aware Generative Model for Clothed People.**<br>
*Enric Corona, Albert Pumarola, Guillem Alenyà, Gerard Pons-Moll, Francesc Moreno-Noguer.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.06871)] [[Project](http://www.iri.upc.edu/people/ecorona/smplicit)]

**A Deep Emulator for Secondary Motion of 3D Characters.**<br>
*Mianlun Zheng, Yi Zhou, Duygu Ceylan, Jernej Barbic.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.01261)]

**PVA: Pixel-aligned Volumetric Avatars.**<br>
*Amit Raj, Michael Zollhoefer, Tomas Simon, Jason Saragih, Shunsuke Saito, James Hays, Stephen Lombardi.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2101.02697)] [[Project](https://volumetric-avatars.github.io)]

**ANR: Articulated Neural Rendering for Virtual Avatars.**<br>
*Amit Raj, Julian Tanke, James Hays, Minh Vo, Carsten Stoll, Christoph Lassner.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2012.12890)] [[Project](https://anr-avatars.github.io)]

**SMPLpix: Neural Avatars from 3D Human Models.**<br>
*Sergey Prokudin, Michael J. Black, Javier Romero.*<br>
WACV 2021. [[PDF](https://arxiv.org/abs/2008.06872)] [[Code](https://github.com/sergeyprokudin/smplpix)]

**Synthetic Training for Monocular Human Mesh Recovery.**<br>
*Yu Sun, Qian Bao, Wu Liu, Wenpeng Gao, Yili Fu, Chuang Gan, Tao Mei.*<br>
BMVC 2020. [[PDF](https://arxiv.org/abs/2010.14036)]

**Realistic Virtual Humans from Smartphone Videos.**<br>
*Stephan Wenninger, Jascha Achenbach, Andrea Bartl, Marc Erich Latoschik, [Mario Botsch](https://ls7-gv.cs.tu-dortmund.de).*<br>
ACM VRST 2020 (Best Paper Award). [[PDF](https://ls7-gv.cs.tu-dortmund.de/downloads/publications/2020/vrst20.pdf)] [[Video](https://ls7-gv.cs.tu-dortmund.de/downloads/publications/2020/vrst20.mp4)] [[Talk](https://youtu.be/Mm318gs_fb8)]

**LoopReg: Self-supervised Learning of Implicit Surface Correspondences, Pose and Shape for 3D Human Mesh Registration.**<br>
*Bharat Lal Bhatnagar, Cristian Sminchisescu, Christian Theobalt, Gerard Pons-Moll.*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2010.12447)] [[Code](https://github.com/bharat-b7/LoopReg)]

**3D Multi-bodies: Fitting Sets of Plausible 3D Human Models to Ambiguous Image Data.**<br>
*Benjamin Biggs, Sébastien Ehrhadt, Hanbyul Joo, Benjamin Graham, Andrea Vedaldi, David Novotny.*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2011.00980)]

**HPBTT: Human Parsing Based Texture Transfer from Single Image to 3D Human via Cross-View Consistency.**<br>
*Fang Zhao, Shengcai Liao, Kaihao Zhang, Ling Shao.*<br>
NeurIPS 2020. [[PDF](https://papers.nips.cc/paper/2020/file/a516a87cfcaef229b342c437fe2b95f7-Paper.pdf)] [[Code](https://github.com/zhaofang0627/HPBTT)]

**Neural3D: Light-weight Neural Portrait Scanning via Context-aware Correspondence Learning.**<br>
*Xin Suo, Minye  Wu, Yanshun  Zhang, Yanshun Zhang, Yingliang  Zhang, Yingliang Zhang, Lan  Xu, Qiang  Hu, Jingyi  Yu.*<br>
ACM MM 2020. [[PDF](https://dl.acm.org/doi/abs/10.1145/3394171.3413734)]

**3DBooSTeR: 3D Body Shape and Texture Recovery.**<br>
*Alexandre Saint, Anis Kacem, Kseniya Cherenkova, Djamila Aouada.*<br>
ECCV 2020 Workshop. [[PDF](https://arxiv.org/abs/2010.12670)]

**BCNet: Learning Body and Cloth Shape from A Single Image.**<br>
*Boyi Jiang, Juyong Zhang, Yang Hong, Jinhao Luo, Ligang Liu, Hujun Bao.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2004.00214)]

**MonoPort: Monocular Real-Time Volumetric Performance Capture.**<br>
*Ruilong Li, Yuliang Xiu, Shunsuke Saito, Zeng Huang, Kyle Olszewski, Hao Li.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.13988)] [[Code](https://github.com/Project-Splinter/MonoPort)]

**3D Human Shape and Pose from a Single Low-Resolution Image with Self-Supervised Learning.**<br>
*Xiangyu Xu, Hao Chen, Francesc Moreno-Noguer, Laszlo A. Jeni, Fernando De la Torre.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.13666)] [[Project](https://sites.google.com/view/xiangyuxu/3d_eccv20)]

**BLSM: A Bone-Level Skinned Model of the Human Mesh.**<br>
*Haoyang Wang, Riza Alp Güler, Iasonas Kokkinos, George Papandreou, Stefanos Zafeiriou.*<br>
ECCV 2020. [[pdf](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123500001.pdf)] [[Supplement](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123500001-supp.zip)]

**STAR: Sparse Trained Articulated Human Body Regressor.**<br>
*Ahmed A. A. Osman, Timo Bolkart, Michael J. Black.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.08535)] [[Project](http://star.is.tue.mpg.de)]

**I2L-MeshNet: Image-to-Lixel Prediction Network for Accurate 3D Human Pose and Mesh Estimation from a Single RGB Image.**<br>
*Gyeongsik Moon, Kyoung Mu Lee.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.03713)] [[Code](https://github.com/mks0601/I2L-MeshNet_RELEASE)]

**Appearance Consensus Driven Self-Supervised Human Mesh Recovery.**<br>
*Jogendra Nath Kundu, Mugalodi Rakesh, Varun Jampani, Rahul Mysore Venkatesh, R. Venkatesh Babu.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.01341)]

**TexMesh: Reconstructing Detailed Human Texture and Geometry from RGB-D Video.**<br>
*Tiancheng Zhi, Christoph Lassner, Tony Tung, Carsten Stoll, Srinivasa G. Narasimhan, Minh Vo.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.00158)]

**NormalGAN: Learning Detailed 3D Human from a Single RGB-D Image.**<br>
*Lizhen Wang, Xiaochen Zhao, Tao Yu, Songtao Wang, [Yebin Liu](http://liuyebin.com).*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.15340)] [[Project](http://www.liuyebin.com/NormalGan/normalgan.html)]

**Reconstructing NBA Players.**<br>
*[Luyang Zhu](https://homes.cs.washington.edu/~lyzhu), [Konstantinos Rematas](http://www.krematas.com), [Brian Curless](https://homes.cs.washington.edu/~curless), [Steve Seitz](https://homes.cs.washington.edu/~seitz), [Ira Kemelmacher-Shlizerman](https://sites.google.com/view/irakemelmacher/home).*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.13303)] [[Code](https://github.com/luyangzhu/NBA-Players)] [[Project](http://grail.cs.washington.edu/projects/nba_players)]

**RobustFusion: Human Volumetric Capture with Data-driven Visual Cues using a RGBD Camera.**<br>
*Zhuo Su, [Xu Lan](https://www.xu-lan.com), Zerong Zheng, Tao Yu, Yebin Liu, Lu Fang.*<br>
ECCV 2020. [[PDF](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123490239.pdf)]

**IPNet: Combining Implicit Function Learning and Parametric Models for 3D Human Reconstruction.**<br>
*Bharat Lal Bhatnagar, Cristian Sminchisescu, Christian Theobalt, [Gerard Pons-Moll](http://virtualhumans.mpi-inf.mpg.de/publications.html).*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.11432)] [[Project](http://virtualhumans.mpi-inf.mpg.de/ipnet)] [[Code](https://github.com/bharat-b7/IPNet)]

**Neural Articulated Shape Approximation.**<br>
*Boyang Deng, JP Lewis, Timothy Jeruzalski, [Gerard Pons-Moll](http://virtualhumans.mpi-inf.mpg.de/publications.html), Geoffrey Hinton, Mohammad Norouzi, Andrea Tagliasacchi.*<br>
ECCV 2020. [[PDF](http://virtualhumans.mpi-inf.mpg.de/papers/NASA20/NASA.pdf)]

**SIZER: A Dataset and Model for Parsing 3D Clothing and Learning Size Sensitive 3D Clothing.**<br>
*Garvita Tiwari, Bharat Lal Bhatnagar, Tony Tung, [Gerard Pons-Moll](http://virtualhumans.mpi-inf.mpg.de/publications.html).*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.11610)] [[Data](https://nextcloud.mpi-klsb.mpg.de/index.php/s/nx6wK6BJFZCTF8C)] [[Code](https://github.com/garvita-tiwari/sizer)] [[Project](https://virtualhumans.mpi-inf.mpg.de/sizer)]

**TailorNet: Predicting Clothing in 3D as a Function of Human Pose, Shape and Garment Style.**<br>
*Chaitanya Patel, Zhouyingcheng Liao, Gerard Pons-Moll.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.04583)] [[Code](https://github.com/chaitanya100100/TailorNet)] [[Project](https://virtualhumans.mpi-inf.mpg.de/tailornet)] [[Data](https://github.com/zycliao/TailorNet_dataset)]

**Geo-PIFu: Geometry and Pixel Aligned Implicit Functions for Single-view Human Reconstruction.**<br>
*Tong He, John Collomosse, Hailin Jin, Stefano Soatto.*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2006.08072)] [[Code](https://github.com/simpleig/Geo-PIFu)]

**Self-Supervised Human Depth Estimation from Monocular Videos.**<br>
*Feitong Tan, Hao Zhu, Zhaopeng Cui, Siyu Zhu, Marc Pollefeys, Ping Tan.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2005.03358)]

**ARCH: Animatable Reconstruction of Clothed Humans.**<br>
*Zeng Huang, Yuanlu Xu, Christoph Lassner, Hao Li, Tony Tung.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.04572)]

**pix2surf: Learning to Transfer Texture from Clothing Images to 3D Humans.**<br>
*[Aymen Mir](https://virtualhumans.mpi-inf.mpg.de/people/Mir.html), Thiemo Alldieck, Gerard Pons-Moll.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.02050)] [[Code](https://github.com/aymenmir1/pix2surf)]

**PIFuHD: Multi-Level Pixel-Aligned Implicit Function for High-Resolution 3D Human Digitization.**<br>
*[Shunsuke Saito](http://www-scf.usc.edu/~saitos), [Tomas Simon](https://scholar.google.com/citations?user=7aabHgsAAAAJ), [Jason Saragih](https://scholar.google.com/citations?hl=en&user=ss-IvjMAAAAJ), [Hanbyul Joo](https://jhugestar.github.io).*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.00452)] [[Project](https://shunsukesaito.github.io/PIFuHD)] [[Code](https://github.com/facebookresearch/pifuhd)]

**DeepCap: Monocular Human Performance Capture Using Weak Supervision.**<br>
*Marc Habermann, Weipeng Xu, Michael Zollhoefer, erard Pons-Moll, Christian Theobalt.*<br>
CVPR 2020. [[PDF](https://gvv.mpi-inf.mpg.de/projects/2020-cvpr-deepcap/data/paper.pdf)] [[Project](https://gvv.mpi-inf.mpg.de/projects/2020-cvpr-deepcap)]

**EventCap: Monocular 3D Capture of High-Speed Human Motions using an Event Camera.**<br>
*Lan XU, Weipeng Xu, Vladislav Golyanik, Marc Habermann, Lu Fang, Christian Theobalt.*<br>
CVPR 2020. [[PDF](https://gvv.mpi-inf.mpg.de/projects/2020-cvpr-eventcap/data/paper.pdf)] [[Project](https://gvv.mpi-inf.mpg.de/projects/2020-cvpr-eventcap)]

**DeepDeform: Learning Non-rigid RGB-D Reconstruction with Semi-supervised Data.**<br>
*Aljaž Božič, Michael Zollhöfer, Christian Theobalt, Matthias Nießner.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/1912.04302)] [[Project](https://pure.mpg.de/pubman/faces/ViewItemOverviewPage.jsp?itemId=item_3187203)] [[Code](https://github.com/AljazBozic/DeepDeform)] [[DeepDeform Benchmark](http://kaldir.vc.in.tum.de/deepdeform_benchmark)]

**Implicit Functions in Feature Space for 3D Shape Reconstruction and Completion.**<br>
*Julian Chibane, [Thiemo Alldieck](https://graphics.tu-bs.de/people/alldieck), Gerard Pons-Moll.*<br>
CVPR 2020. [[PDF](https://virtualhumans.mpi-inf.mpg.de/papers/chibane20ifnet/chibane20ifnet.pdf)]

**DeepCap: Monocular Human Performance Capture Using Weak Supervision.**<br>
*Marc Habermann, Weipeng Xu, Michael and Zollhoefer, Gerard Pons-Moll, Christian Theobalt.*<br>
CVPR 2020. [[PDF](https://virtualhumans.mpi-inf.mpg.de)]

**TetraTSDF: 3D Human Reconstruction from A Single Image with A Tetrahedral Outer Shell.**<br>
*Hayato Onizuka, Zehra Hayirci, Diego Thomas, Akihiro Sugimoto, Hideaki Uchiyama, Rin-ichiro Taniguchi.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.10534)] [[Code](https://github.com/diegothomas/TetraTSDF)]

**Multi-View Consistency Loss for Improved Single-Image 3D Reconstruction of Clothed People.**<br>
*Akin Caliskan, Adrian Hilton.*<br>
ACCV 2020. [[PDF](https://arxiv.org/abs/2009.14162)] [[Code](https://github.com/akcalakcal/Multi_View_Consistent_Single_Image_3D_Human_Reconstruction)]

**PaMIR: Parametric Model-Conditioned Implicit Representation for Image-based Human Reconstruction.**<br>
*Zerong Zheng, Tao Yu, Yebin Liu, Qionghai Dai.*<br>
TPAMI 2020. [[PDF](http://www.liuyebin.com/pamir/assets/revised_paper.pdf)] [[Project](http://www.liuyebin.com/pamir/pamir.html)]

**MulayCap: Multi-layer Human Performance Capture Using A Monocular Video Camera.**<br>
*Zhaoqi Su, Weilin Wan, [Tao Yu](https://ytrock.com), [Lingjie Liu](https://lingjie0206.github.io), Lu Fang, Wenping Wang and Yebin Liu.*<br>
TVCG 2020. [[PDF](http://www.liuyebin.com/MulayCap/MulayCap_files/MulayCap.pdf)] [[Project](http://www.liuyebin.com/MulayCap/MulayCap.html)]

**Disentangled Human Body Embedding Based on Deep Hierarchical Neural Network.**<br>
*Boyi Jiang, Juyong Zhang, Jianfei Cai, Jianmin Zheng.*<br>
TVCG 2020. [[PDF](https://arxiv.org/abs/1905.05622)]

**SparseFusion: Dynamic Human Avatar Modeling from Sparse RGBD Images.**<br>
*Xinxin Zuo, Sen Wang, Jiangbin Zheng, Weiwei Yu, Minglun Gong, Ruigang Yang, Li Cheng.*<br>
TMM 2020. [[PDF](https://arxiv.org/abs/2006.03630)]

**UnstructuredFusion: Real-time 4D Geometry and Texture Reconstruction using Commercial RGBD Cameras.**<br>
*Lan Xu, Zhuo Su, Lei Han, Tao Yu, Yebin Liu, Lu Fang.*<br>
TPAMI 2019. [[PDF](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8708933)]

**PIFu: Pixel-Aligned Implicit Function for High-Resolution Clothed Human Digitization.**<br>
*Shunsuke Saito, Zeng Huang, Ryota Natsume, Shigeo Morishima, Angjoo Kanazawa, Hao Li.*<br>
ICCV 2019. [[PDF](https://arxiv.org/pdf/1905.05172.pdf)] [[Project](shunsukesaito.github.io/PIFu)] [[Code](https://github.com/shunsukesaito/PIFu)]

**Multi-Garment Net_Learning to Dress 3D people from Images.**<br>
*Bharat Lal Bhatnagar, Garvita Tiwari, Christian Theobalt, Gerard Pons-Moll.*<br>
ICCV 2019. [[Code](https://github.com/bharat-b7/MultiGarmentNetwork)] [[PDF](https://virtualhumans.mpi-inf.mpg.de/papers/bhatnagar2019mgn/bhatnagar2019mgn.pdf)]

**Learning to Reconstruct People in Clothing from a Single RGB Camera.**<br>
*Thiemo Alldieck, Marcus Magnor, Bharat Lal Bhatnagar, Christian Theobalt, Gerard Pons-Moll.* <br>
ICCV 2019. [[PDF](https://arxiv.org/abs/1903.05885)] [[Code](https://github.com/thmoa/octopus)]

**A Neural Network for Detailed Human Depth Estimation From a Single Image.**<br>
*Sicong Tang, Feitong Tan, Kelvin Cheng, Zhaoyang Li, Siyu Zhu, Ping Tan.* <br>
ICCV 2019. [[PDF](http://openaccess.thecvf.com/content_ICCV_2019/papers/Tang_A_Neural_Network_for_Detailed_Human_Depth_Estimation_From_a_ICCV_2019_paper.pdf)]

**TexturePose: Supervising Human Mesh Estimation with Texture Consistency.** <br>
*[Georgios Pavlakos](https://www.seas.upenn.edu/~pavlakos), [Nikos Kolotouros](https://www.seas.upenn.edu/~nkolot), [Kostas Daniilidis](http://www.cis.upenn.edu/~kostas).*<br>
ICCV 2019. [[PDF](https://arxiv.org/abs/1910.11322)] [[Project](https://www.seas.upenn.edu/~pavlakos/projects/texturepose)] [[Code](https://github.com/geopavlakos/TexturePose)]

**3DPeople: Modeling the Geometry of Dressed Humans.** <br>
*Albert Pumarola, Jordi Sanchez, Gary P. T. Choi, Alberto Sanfeliu, Francesc Moreno-Noguer.*<br>
ICCV 2019. [[PDF](https://arxiv.org/abs/1904.04571)] [[3DPeople-Dataset](https://github.com/albertpumarola/3DPeople-Dataset)]

**DeepHuman: 3D Human Reconstruction from a Single Image.**<br>
*Zerong Zheng, Tao Yu, Yixuan Wei, Qionghai Dai, Yebin Liu.*<br>
ICCV 2019. [[PDF](https://arxiv.org/abs/1904.04571)] [[Project](http://www.liuyebin.com/deephuman/deephuman.html)]

**Tex2Shape: Detailed Full Human Body Geometry From a Single Image.**<br>
*Thiemo Alldieck, Gerard Pons-Moll, Christian Theobalt, Marcus Magnor.* <br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1903.06473)] [[Code](https://github.com/thmoa/tex2shape)]

**SimulCap : Single-View Human Performance Capture with Cloth Simulation.**<br>
*Tao Yu, Zerong Zheng, Yuan Zhong, Jianhui Zhao, Qionghai Dai, Gerard Pons-moll, Yebin Liu.*<br>
CVPR 2019. [[PDF](http://www.liuyebin.com/simulcap/assets/SimulCap.pdf)] [[Project](http://www.liuyebin.com/simulcap/simulcap.html)]

**SiCloPe: Silhouette-Based Clothed People.** <br>
*Ryota Natsume, [Shunsuke Saito](http://www-scf.usc.edu/~saitos), Zeng Huang, Weikai Chen, Chongyang Ma, Hao Li, Shigeo Morishima.* <br>
CVPR 2019. [[PDF](http://openaccess.thecvf.com/content_CVPR_2019/papers/Natsume_SiCloPe_Silhouette-Based_Clothed_People_CVPR_2019_paper.pdf)]

**Textured Neural Avatars.**<br>
*Aliaksandra Shysheya, Egor Zakharov, Kara-Ali Aliev, Renat Bashirov, Egor Burkov, Karim Iskakov, Aleksei Ivakhnenko, Yury Malkov, Igor Pasechnik, Dmitry Ulyanov, Alexander Vakhitov, Victor Lempitsky.*<br>
CVPR 2019 (oral). [[PDF](https://arxiv.org/abs/1905.08776)] [[Project](https://saic-violet.github.io/texturedavatar)]

**MonoClothCap: Towards Temporally Coherent Clothing Capture from Monocular RGB Video.**<br>
*[Donglai Xiang](https://xiangdonglai.github.io), Fabian Prada, Chenglei Wu, Jessica Hodgins.*<br>
3DV 2020 (Best Paper Honorable Mention, Oral). [[PDF](https://arxiv.org/abs/2009.10711)]

**360-Degree Textures of People in Clothing from a Single Image.** <br>
*Verica Lazova, Eldar Insafutdinov, Gerard Pons-Moll.* <br>
3DV 2019. [[PDF](https://arxiv.org/pdf/1908.07117.pdf)] [[Project](http://virtualhumans.mpi-inf.mpg.de/360tex)] 

**Detailed Human Avatars from Monocular Video.**  <br>
*Thiemo Alldieck, Marcus Magnor, Weipeng Xu, Christian Theobalt, Gerard Pons-Moll.* <br>
3DV 2018. [[PDF](https://arxiv.org/abs/1808.01338)] [[Code](https://github.com/thmoa/semantic_human_texture_stitching)]

**BodyFusion: Real-time Capture of Human Motion and Surface Geometry Using a Single Depth Camera.**<br>
*[Tao Yu](https://ytrock.com), [Kaiwen Guo](http://www.guokaiwen.com), [Feng Xu](http://feng-xu.com), Yuan Dong, Zhaoqi Su, Jianhui Zhao, Jianguo Li, Qionghai Dai, Yebin Liu.*<br>
ICCV 2017. [[PDF](http://liuyebin.com/bodyfusion/bodyfusion_files/BdyFu_ICC7.pdf)]

## Cloth Modelling, Draping, Simulation, and Dressing

**4D-DRESS: A 4D Dataset of Real-world Human Clothing with Semantic Annotations.**<br>
*[Wenbo Wang](https://wenbwa.github.io), [Hsuan-I Ho](https://ait.ethz.ch/people/hohs), [Chen Guo](https://ait.ethz.ch/people/cheguo), [Boxiang Rong](https://ribosome-rbx.github.io), [Artur Grigorev](https://ait.ethz.ch/people/agrigorev), [Jie Song](https://ait.ethz.ch/people/song), [Juan Jose Zarate](https://ait.ethz.ch/people/jzarate), [Otmar Hilliges](https://ait.ethz.ch/people/hilliges).*<br>
CVPR 2024 (Highlight). [[PDF](https://arxiv.org/abs/2404.18630)] [[Project](https://eth-ait.github.io/4d-dress)] [[Data](https://4d-dress.ait.ethz.ch)] [[Code](https://github.com/eth-ait/4d-dress)]

**A Generative Multi-Resolution Pyramid and Normal-Conditioning 3D Cloth Draping.**<br>
*Hunor Laczkó, Meysam Madadi, Sergio Escalera, Jordi Gonzalez.*<br>
WACV 2024. [[PDF](https://arxiv.org/abs/2311.02700)]

**Towards Multi-Layered 3D Garments Animation.**<br>
*Yidi Shao, Chen Change Loy, Bo Dai.*<br>
ICCV 2023. [[PDF](https://arxiv.org/pdf/2305.10418.pdf)] [[Project](https://mmlab-ntu.github.io/project/layersnet/index.html)]

**REC-MV: REconstructing 3D Dynamic Cloth from Monocular Videos.**<br>
*[Lingteng Qiu](https://lingtengqiu.github.io), [Guanying Chen](https://guanyingc.github.io), Jiapeng Zhou, [Mutian Xu](https://mutianxu.github.io), Junle Wang, [Xiaoguang Han](https://mypage.cuhk.edu.cn/academics/hanxiaoguang).*<br> 
CVPR 2023. [[PDF](http://arxiv.org/abs/2305.14236)] [[Project](https://lingtengqiu.github.io/2023/REC-MV)] [[Code](https://github.com/GAP-LAB-CUHK-SZ/REC-MV)]

**HOOD: Hierarchical Graphs for Generalized Modelling of Clothing Dynamics.**<br>
*[Artur Grigorev](https://dolorousrtur.github.io), [Bernhard Thomaszewski](https://n.ethz.ch/~bthomasz/index.html), [Michael J. Black](https://ps.is.mpg.de/~black), [Otmar Hilliges](https://ait.ethz.ch/people/hilliges).*<br> 
CVPR 2023. [[PDF](https://arxiv.org/abs/2212.07242)] [[Project](https://dolorousrtur.github.io/hood)] [[Code](https://github.com/Dolorousrtur/HOOD)]

**Deep Deformation Detail Synthesis for Thin Shell Models.**<br>
*Lan Chen, Lin Gao, Jie Yang, Shibiao Xu, Juntao Ye, Xiaopeng Zhang, Yu-Kun Lai.*<br>
CGF 2023. [[PDF](https://arxiv.org/abs/2102.11541)]

**Motion Guided Deep Dynamic 3D Garments.**<br>
*[Meng Zhang](https://mengzephyr.com), [Duygu Ceylan](https://research.adobe.com/person/duygu-ceylan), [Niloy J. Mitra](http://www0.cs.ucl.ac.uk/staff/n.mitra).*<br>
SIGGRAPH Asia 2022. [[PDF](https://arxiv.org/pdf/2209.11449.pdf)] [[Project](http://geometry.cs.ucl.ac.uk/projects/2022/MotionDeepGarment)]

**Predicting Loose-Fitting Garment Deformations Using Bone-Driven Motion Networks.**<br>
*Xiaoyu Pan, Jiaming Mai, Xinwei Jiang, Dongxue Tang, Jingxiang Li, Tianjia Shao, Kun Zhou, Xiaogang Jin, Dinesh Manocha.*<br>
SIGGRAPH 2022. [[PDF](https://arxiv.org/abs/2205.01355)] [[Code](https://github.com/non-void/VirtualBones)]

**DiffCloth: Differentiable Cloth Simulation with Dry Frictional Contact.**<br>
*[Yifei Li](https://people.csail.mit.edu/liyifei), [Tao Du](https://people.csail.mit.edu/taodu), [Kui Wu](https://people.csail.mit.edu/kuiwu), [Jie Xu](http://people.csail.mit.edu/jiex), [Wojciech Matusik](https://cdfg.csail.mit.edu/wojciech).*<br>
TOG 2022. [[PDF](https://arxiv.org/abs/2106.05306)] [[Project](https://people.csail.mit.edu/liyifei/publication/diffcloth-differentiable-cloth-simulator)] [[Code](https://github.com/omegaiota/DiffCloth)]

**DIG: Draping Implicit Garment over the Human Body.**<br>
*Ren Li, Benoît Guillard, Edoardo Remelli, Pascal Fua.*<br>
ACCV 2022. [[PDF](https://arxiv.org/abs/2209.10845)]

**SNUG: Self-Supervised Neural Dynamic Garments.**<br>
*Igor Santesteban, Miguel A. Otaduy, Dan Casas.*<br>
CVPR 2022 (Oral). [[PDF](https://arxiv.org/abs/2204.02219)] [[Project](http://mslab.es/projects/SNUG)] [[Code](https://github.com/isantesteban/snug)]

**Registering Explicit to Implicit: Towards High-Fidelity Garment mesh Reconstruction from Single Images.**<br>
*Heming Zhu, Lingteng Qiu, Yuda Qiu, Xiaoguang Han.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2203.15007)] [[Project](https://kv2000.github.io/2022/03/28/reef)]

**Self-Supervised Collision Handling via Generative 3D Garment Models for Virtual Try-On.**<br>
*Igor Santesteban, Nils Thuerey, Miguel A. Otaduy, Dan Casas.*<br>
CVPR 2021. [[PDF](http://arxiv.org/abs/2105.06462)]

**Dynamic Neural Garments.**<br>
*[Meng Zhang](https://mengzephyr.com), [Duygu Ceylan](http://www.duygu-ceylan.com), [Tuanfeng Wang](http://geometry.cs.ucl.ac.uk/tuanfeng), [Niloy J. Mitra](http://www0.cs.ucl.ac.uk/staff/n.mitra).*<br>
TOG 2021. [[PDF](https://arxiv.org)] [[Project](http://geometry.cs.ucl.ac.uk/projects/2021/DynamicNeuralGarments)] [[Code](https://github.com/MengZephyr/DynamicNeuralGarments)]

**PBNS: Physically Based Neural Simulation for Unsupervised Outfit Pose Space Deformation.**<br>
*Hugo Bertiche, Meysam Madadi, Sergio Escalera.*<br>
SIGGRAPH Asia 2021. [[PDF](https://arxiv.org/abs/2012.11310)] [[Project](https://hbertiche.github.io/PBNS)] [[Code](https://github.com/hbertiche/PBNS)]

**Deep Detail Enhancement for Any Garment.**<br>
*Meng Zhang, Tuanfeng Wang, Duygu Ceylan, Niloy J. Mitra.*<br>
Eurographics 2021. [[PDF](https://arxiv.org/pdf/2008.04367.pdf)]

**Deep Physics-aware Inference of Cloth Deformation for Monocular Human Performance Capture.**<br>
*Yue Li, Marc Habermann, Bernhard Thomaszewski, Stelian Coros, Thabo Beeler, Christian Theobalt.*<br>
3DV 2021. [[PDF](https://arxiv.org/abs/2011.12866)]

**Neural Non-Rigid Tracking.**<br>
*Aljaž Božič, Pablo Palafox, Michael Zollhöfer, Angela Dai, Justus Thies, Matthias Nießner.*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2006.13240)]

**SIZER: A Dataset and Model for Parsing 3D Clothing and Learning Size Sensitive 3D Clothing.**<br>
*Garvita Tiwari, Bharat Lal Bhatnagar, Tony Tung, Gerard Pons-Moll.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.11610)]

**GAN-based Garment Generation Using Sewing Pattern Images.**<br>
*Yu Shen, Junbang Liang, Ming C. Lin.*<br>
ECCV 2020. [[PDF](http://cs.umd.edu/~liangjb/docs/ICCV2019.pdf)] [[Project](https://gamma.umd.edu/researchdirections/virtualtryon/garmentgeneration)] [[Code](https://github.com/williamljb/HumanMultiView)]

**Deep Fashion3D: A Dataset and Benchmark for 3D Garment Reconstruction from Single Images.**<br>
*Heming Zhu, Yu Cao, Hang Jin, Weikai Chen, Dong Du, Zhangye Wang, Shuguang Cui, Xiaoguang Han.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2003.12753)] [[Project](https://kv2000.github.io/2020/03/25/deepFashion3DRevisited)]

**GarNet++: Improving Fast and Accurate Static3D Cloth Draping by Curvature Loss.**<br>
*Erhan Gundogdu, Victor Constantin, Shaifali Parashar, Amrollah Seifoddini, Minh Dang, Mathieu Salzmann, Pascal Fua.*<br>
TPAMI 2020. [[PDF](https://arxiv.org/abs/2007.10867)]

**Homogenized Yarn-Level Cloth.**<br>
*[Georg Sperl](https://pub.ist.ac.at/~gsperl), Rahul Narain, Chris Wojtan.*<br>
SIGGRAPH (TOG) 2020. [[PDF](http://pub.ist.ac.at/group_wojtan/projects/2020_Sperl_HYLC/2020_HYLC_paper.pdf)] [[Project](http://visualcomputing.ist.ac.at/publications/2020/HYLC)] [[Data & Code](http://pub.ist.ac.at/group_wojtan/projects/2020_Sperl_HYLC/2020_HYLC_data_code.zip)]

**CLOTH3D: Clothed 3D Humans.**<br>
*Hugo Bertiche, Meysam Madadi, Sergio Escalera.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/1912.02792)]

**CAPE: Learning to Dress 3D People in Generative Clothing.**<br>
*[Qianli Ma](https://ps.is.tue.mpg.de/person/qma), Jinlong Yang, Anurag Ranjan, Sergi Pujades, Gerard Pons-Moll, Siyu Tang, [Michael J. Black](https://ps.is.tuebingen.mpg.de/person/black).*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/1907.13615v2)] 	[[Project](http://ps.is.mpg.de/publications/cape-cvpr-20)]

**Learning to Dress 3D People in Generative Clothing.**<br>
*Qianli Ma, Jinlong Yang, Anurag Ranjan, Sergi Pujades, Gerard Pons-Moll, Siyu Tang, Michael J. Black.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/1907.13615)]

**The Virtual Tailor: Predicting Clothing in 3D as a Function of Human Pose, Shape and Garment Style.**<br>
*Chaitanya Patel, Zhouyingcheng Liao, Gerard Pons-Moll.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.04583)]

**Learning to Transfer Texture from Clothing Images to 3D Humans.**<br>
*Aymen Mir, Thiemo Alldieck, Gerard Pons-Moll.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.02050)] [[Code](https://github.com/aymenmir1/pix2surf)]

**GarNet: A Two-Stream Network for Fast and Accurate 3D Cloth Draping.**<br>
*[Erhan Gundogdu](https://egundogdu.github.io), Victor Constantin, Amrollah Seifoddini, Minh Dang, Mathieu Salzmann, Pascal Fua.*<br>
ICCV 2019. [[PDF](https://arxiv.org/abs/1811.10983)] [[Supplementary Material](https://www.epfl.ch/labs/cvlab/wp-content/uploads/2019/04/GarNet_supplementary.pdf)] [[Project](https://cvlab.epfl.ch/research/garment-simulation/garnet)] [[Dataset](https://drive.switch.ch/index.php/s/7mAk9SoZ7J4uokt)]

**Multi-Garment Net: Learning to Dress 3D People from Images.**<br>
*Bharat Lal Bhatnagar, Garvita Tiwari, Christian Theobalt, [Gerard Pons-Moll](https://www.mpi-inf.mpg.de/departments/computer-vision-and-machine-learning/people/gerard-pons-moll)(REAL VIRTUAL HUMANS, MPII).*<br>
ICCV 2019. [[PDF](https://arxiv.org/abs/1908.06903)]

**DRAPE: DRessing Any PErson.**<br>
*Peng Guan, Loretta Reiss, David A. Hirshberg, Alexander Weiss, Michael J. Black.*<br>
TOG 2012. [[PDF](https://dl.acm.org/citation.cfm?doid=2185520.2185531)] [[Project](https://ps.is.tue.mpg.de/research_projects/drape-dressing-any-person)]

## Human Image and Video Generation

**FaceShot: Bring Any Character into Life.**<br>
*Junyao Gao, Yanan Sun, Fei Shen, Xin Jiang, Zhening Xing, Kai Chen, Cairong Zhao.*<br> 
ICLR 2025. [[PDF](https://arxiv.org/abs/2503.00740)] [[Project](https://faceshot2024.github.io/faceshot)]

**Gaussian Shell Maps for Efficient 3D Human Generation.**<br>
*Rameen Abdal, Wang Yifan, Zifan Shi, Yinghao Xu, Ryan Po, Zhengfei Kuang, Qifeng Chen, Dit-Yan Yeung, Gordon Wetzstein.*<br> 
CVPR 2024. [[PDF](http://arxiv.org/abs/2311.17857)] [[Project](https://rameenabdal.github.io/GaussianShellMaps)]

**HyperHuman: Hyper-Realistic Human Generation with Latent Structural Diffusion.**<br>
*Xian Liu, Jian Ren, Aliaksandr Siarohin, Ivan Skorokhodov, Yanyu Li, Dahua Lin, Xihui Liu, Ziwei Liu, Sergey Tulyakov.*<br> 
ICLR 2024. [[PDF](http://arxiv.org/abs/2310.08579)] [[Project](https://snap-research.github.io/HyperHuman)]

**VeRi3D: Generative Vertex-based Radiance Fields for 3D Controllable Human Image Synthesis.**<br>
*Xinya Chen, Jiaxin Huang, Yanrui Bin, Lu Yu, Yiyi Liao.*<br> 
ICCV 2023. [[PDF](http://arxiv.org/abs/2309.04800)]

**UnitedHuman: Harnessing Multi-Source Data for High-Resolution Human Generation.**<br>
*Jianglin Fu, Shikai Li, Yuming Jiang, Kwan-Yee Lin, Wayne Wu, Ziwei Liu.*<br>
ICCV 2023. [[PDF](https://arxiv.org/abs/2309.14335)] [[Project](https://unitedhuman.github.io)] [[Github](https://github.com/UnitedHuman/UnitedHuman)] 

**Text2Performer: Text-Driven Human Video Generation.**<br>
*Yuming Jiang, Shuai Yang, Tong Liang Koh, Wayne Wu, Chen Change Loy, Ziwei Liu.*<br>
ICCV 2023. [[PDF](https://arxiv.org/pdf/2304.08483.pdf)] [[Project](https://yumingj.github.io/projects/Text2Performer.html)] [[Code](https://github.com/yumingj/Text2Performer)]

**Text-guided 3D Human Generation from 2D Collections.**<br>
*Tsu-Jui Fu, Wenhan Xiong, Yixin Nie, Jingyu Liu, Barlas Oğuz, William Yang Wang.*<br> 
EMNLP 2023 (Findings). [[PDF](http://arxiv.org/abs/2305.14312)] [[Project](https://text-3dh.github.io)]

**Cross Attention Based Style Distribution for Controllable Person Image Synthesis.**<br>
*Xinyue Zhou, Mingyu Yin, Xinyuan Chen, Li Sun, Changxin Gao, Qingli Li.*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2208.00712)] 

**StyleGAN-Human: A Data-Centric Odyssey of Human Generation.**<br>
*Jianglin Fu, Shikai Li, [Yuming Jiang](https://yumingj.github.io), [Kwan-Yee Lin](https://kwanyeelin.github.io), [Chen Qian](https://scholar.google.com/citations?user=AerkT0YAAAAJ&hl=zh-CN), [Chen Change Loy](https://www.mmlab-ntu.com/person/ccloy), [Wayne Wu](https://dblp.org/pid/50/8731.html), [Ziwei Liu](https://liuziwei7.github.io).*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2204.11823)] [[Code](https://youtu.be/nIrb9hwsdcI)] [[Project](https://stylegan-human.github.io)] [[Colab Demo](https://colab.research.google.com/drive/1sgxoDM55iM07FS54vz9ALg1XckiYA2On)] [[Hugging Face Demo](https://huggingface.co/spaces/hysts/StyleGAN-Human)]

**Text2Human: Text-Driven Controllable Human Image Generation.**<br>
*Yuming Jiang, Shuai Yang, Haonan Qiu, Wayne Wu, Chen Change Loy, Ziwei Liu.*<br>
SIGGRAPH 2022. [[PDF](https://arxiv.org/abs/2205.15996)] [[Code](https://github.com/yumingj/Text2Human)] [[Project](https://yumingj.github.io/projects/Text2Human.html)] 

**Self-Supervised Correlation Mining Network for Person Image Generation.**<br>
*Zijian Wang, Xingqun Qi, Kun Yuan, Muyi Sun.*<br>
CVPR 2022. [[PDF](https://openaccess.thecvf.com/content/CVPR2022/html/Wang_Self-Supervised_Correlation_Mining_Network_for_Person_Image_Generation_CVPR_2022_paper.html)] 

**BodyGAN: General-Purpose Controllable Neural Human Body Generation.**<br>
*Chaojie Yang, Hanhui Li, Shengjie Wu, Shengkai Zhang, Haonan Yan, Nianhong Jiao, Jie Tang, Runnan Zhou, Xiaodan Liang, Tianxiang Zheng.*<br>
CVPR 2022. [[PDF](https://openaccess.thecvf.com/content/CVPR2022/html/Yang_BodyGAN_General-Purpose_Controllable_Neural_Human_Body_Generation_CVPR_2022_paper.html)] 

**InsetGAN for Full-Body Image Generation.**<br>
*[Anna Frühstück](https://afruehstueck.github.io), [Krishna Kumar Singh](http://krsingh.cs.ucdavis.edu), [Eli Shechtman](https://research.adobe.com/person/eli-shechtman), [Niloy J. Mitra](https://research.adobe.com/person/niloy-mitra), [Peter Wonka](http://peterwonka.net), [Jingwan Lu](https://research.adobe.com/person/jingwan-lu).*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2112.07200)] [[Project](http://afruehstueck.github.io/insetgan)]

**Neural Texture Extraction and Distribution for Controllable Person Image Synthesis.**<br>
*Yurui Ren, Xiaoqing Fan, Ge Li, Shan Liu, Thomas H. Li.*<br>
CVPR 2022 (oral). [[PDF](https://arxiv.org/abs/2203.10496)] [[Code](https://github.com/RenYurui/Neural-Texture-Extraction-Distribution)]

**Exploring Dual-task Correlation for Pose Guided Person Image Generation.**<br>
*Pengze Zhang, Lingxiao Yang, Jianhuang Lai, Xiaohua Xie.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2203.02910)]

**Structure-Transformed Texture-Enhanced Network for Person Image Synthesis.**<br>
*Munan Xu, Yuanqi Chen, Shan Liu, Thomas H. Li, Ge Li.*<br>
ICCV 2021. [[PDF](https://openaccess.thecvf.com/content/ICCV2021/html/Xu_Structure-Transformed_Texture-Enhanced_Network_for_Person_Image_Synthesis_ICCV_2021_paper.html)]

**PISE: Person Image Synthesis and Editing with Decoupled GAN.**<br>
*[Jinsong Zhang](https://zhangjinso.github.io), [Kun Li](http://cic.tju.edu.cn/faculty/likun), [Yu-Kun Lai](http://users.cs.cf.ac.uk/Yukun.Lai), [Jingyu Yang](http://tju.iirlab.org).*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.04023)] [[Project](http://cic.tju.edu.cn/faculty/likun/projects/PISE)] [[Code](https://github.com/Zhangjinso/PISE)]

**XingGAN for Person Image Generation.**<br>
*[Hao Tang](http://disi.unitn.it/~hao.tang), Song Bai, Li Zhang, Philip H. S. Torr, Nicu Sebe.*<br>
ECCV 2020.  [[Code](https://github.com/Ha0Tang/XingGAN)]

**Progressive Pose Attention Transfer for Person Image Generation.**<br> 
*Zhen Zhu, Tengteng Huang, Baoguang Shi, Miao Yu, Bofei Wang, Xiang Bai.*<br> 
CVPR 2019 (oral). [[PDF](https://arxiv.org/abs/1904.03349)] [[Code](https://github.com/tengteng95/Pose-Transfer.git)]

**Generating Person Images with Appearance-aware Pose Stylizer.**<br>
*Siyu Huang, Haoyi Xiong, Zhi-Qi Cheng, Qingzhong Wang, Xingran Zhou, Bihan Wen, Jun Huan, Dejing Dou.*<br>
IJCAI 2020. [[PDF](https://arxiv.org/abs/2007.09077)] [[Code](https://github.com/siyuhuang/PoseStylizer)]

## Image-Based Virtual Try-On

[[Awesome Virtual Try-on (VTON)](https://github.com/minar09/awesome-virtual-try-on)]

**FashionTex: Controllable Virtual Try-on with Text and Texture.**<br>
*Anran Lin, Nanxuan Zhao, Shuliang Ning, Yuda Qiu, Baoyuan Wang, Xiaoguang Han.*<br> 
SIGGRAPH 2023. [[PDF](http://arxiv.org/abs/2305.04451)]

**TryOnDiffusion: A Tale of Two UNets.**<br>
*[Luyang Zhu](https://homes.cs.washington.edu/~lyzhu), [Dawei Yang](http://www-personal.umich.edu/~ydawei), [Tyler Zhu](https://research.google/people/TylerZhu), [Fitsum Reda](https://fitsumreda.github.io), [William Chan](http://williamchan.ca), [Chitwan Saharia](https://scholar.google.co.in/citations?user=JApued4AAAAJ&hl=en), [Mohammad Norouzi](https://norouzi.github.io), [Ira Kemelmacher-Shlizerman](https://www.irakemelmacher.com).*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2306.08276)] [[Project](https://tryondiffusion.github.io)]

**High-Resolution Virtual Try-On with Misalignment and Occlusion-Handled Conditions.**<br>
*Sangyun Lee, Gyojung Gu, Sunghyun Park, Seunghwan Choi, Jaegul Choo.*<br>
ECCV 2022. [[PDF](https://arxiv.org/pdf/2206.14180.pdf)] [[Project](https://koo616.github.io/HR-VITON)] [[Code](https://github.com/sangyun884/HR-VITON)]

**Single Stage Virtual Try-on via Deformable Attention Flows.**<br>
*Shuai Bai, Huiling Zhou, Zhikang Li, Chang Zhou, Hongxia Yang.*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2207.09161)]

**MGN: A Regional Mask Guided Network for Parser-free Virtual Try-on.**<br>
*Chao Lin, Zhao Li, Sheng Zhou, Shichang Hu, Jialun Zhang, Linhao Luo, Jiarun Zhang, Longtao Huang, Yuan He.*<br>
IJCAI 2022. [[PDF](https://arxiv.org/abs/2204.11258)]

**ClothFormer: Taming Video Virtual Try-on in All Module.**<br> 
*Jianbin Jiang, Tan Wang, He Yan, Junhui Liu.*<br> 
CVPR 2022 (oral). [[PDF](https://arxiv.org/abs/2204.07154)] [[Project](https://arxiv.org/abs/2204.12151)]

**Style-Based Global Appearance Flow for Virtual Try-On.**<br>
*Sen He, Yi-Zhe Song, Tao Xiang.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2204.01046)] 

**Dressing in the Wild by Watching Dance Videos.**<br>
*Xin Dong, Fuwei Zhao, Zhenyu Xie, Xijin Zhang, Daniel K. Du, Min Zheng, Xiang Long, Xiaodan Liang, Jianchao Yang.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2203.15320)] [[Project](https://awesome-wflow.github.io)]

**CIT: Cloth Interactive Transformer for Virtual Try-On.**<br>
*[Bin Ren](https://scholar.google.com/citations?user=Md9maLYAAAAJ&hl=en), Hao Tang, Fanyang Meng, Runwei Ding, Ling Shao, Philip H.S. Torr, Nicu Sebe.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2104.05519)] [[Code](https://github.com/Amazingren/CIT)]

**Weakly Supervised High-Fidelity Clothing Model Generation.**<br>
*Ruili Feng, Cheng Ma, Chengji Shen, Xin Gao, Zhenjiang Liu, Xiaobo Li, Kairi Ou, Zhengjun Zha.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2112.07200)]

**WAS-VTON: Warping Architecture Search for Virtual Try-on Network.**<br>
*Zhenyu Xie, Xujie Zhang, Fuwei Zhao, Haoye Dong, Michael C. Kampffmeyer, Haonan Yan, Xiaodan Liang.*<br>
ACM MM 2021. [[PDF](https://arxiv.org/abs/2108.00386)] 

**Towards Scalable Unpaired Virtual Try-On via Patch-Routed Spatially-Adaptive GAN.**<br>
*Zhenyu Xie, Zaiyu Huang, Fuwei Zhao, Haoye Dong, Michael Kampffmeyer, Xiaodan Liang.*<br>
NeurIPS 2021. [[PDF](https://arxiv.org/abs/2111.10544)] [[Code](https://github.com/xiezhy6/PASTA-GAN)]

**ZFlow: Gated Appearance Flow-based Virtual Try-on with 3D Priors.**<br>
*Ayush Chopra, Rishabh Jain, Mayur Hemani, Balaji Krishnamurthy.*<br>
ICCV 2021. [[PDF](https://arxiv.org/abs/2109.07001)]

*Dressing in Order: Recurrent Person Image Generation for Pose Transfer, Virtual Try-On and Outfit Editing.*<br>
*Aiyu Cui, Daniel McKee, Svetlana Lazebnik.*<br>
ICCV 2021. [[PDF](https://openaccess.thecvf.com/content/ICCV2021/html/Cui_Dressing_in_Order_Recurrent_Person_Image_Generation_for_Pose_Transfer_ICCV_2021_paper.html)]

**FashionMirror: Co-Attention Feature-Remapping Virtual Try-On With Sequential Template Poses.**<br>
*Chieh-Yun Chen, Ling Lo, Pin-Jui Huang, Hong-Han Shuai, Wen-Huang Cheng.*<br>
ICCV 2021. [[PDF](https://openaccess.thecvf.com/content/ICCV2021/html/Chen_FashionMirror_Co-Attention_Feature-Remapping_Virtual_Try-On_With_Sequential_Template_Poses_ICCV_2021_paper.html)]

**M3D-VTON: A Monocular-to-3D Virtual Try-On Network.**<br>
*Fuwei Zhao, Zhenyu Xie, Michael Kampffmeyer, Haoye Dong, Songfang Han, Tianxiang Zheng, Tao Zhang, Xiaodan Liang.*<br>
ICCV 2021. [[PDF](https://arxiv.org/abs/2108.05126)]

**Shape Controllable Virtual Try-on for Underwear Models.**<br>
*Xin Gao, Zhenjiang Liu, Zunlei Feng, Chengji Shen, Kairi Ou, Haihong Tang, Mingli Song.*<br>
ACM MM 2021. [[PDF](https://arxiv.org/abs/2107.13156)]

**TryOnGAN: Body-aware Try-on via Layered Interpolation.**<br>
*[Kathleen M Lewis](https://katiemlewis.github.io), [Srivatsan Varadharajan](https://www.linkedin.com/in/srivatsan-varadharajan-9a570818), [Ira Kemelmacher-Shlizerman](https://www.irakemelmacher.com).*<br>
TOG 2021. [[PDF](https://arxiv.org/abs/2101.02285)] [[Project](https://tryongan.github.io/tryongan)] [[Demo](https://tryongan.github.io/tryongan/demo_rewrite.html)]

**VOGUE: Try-On by StyleGAN Interpolation Optimization.**<br>
*[Kathleen M Lewis](https://katiemlewis.github.io), [Srivatsan Varadharajan](https://www.linkedin.com/in/srivatsan-varadharajan-9a570818), [Ira Kemelmacher-Shlizerman](https://sites.google.com/view/irakemelmacher/home).*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2101.02285)] [[Project](https://vogue-try-on.github.io)] [[Code](https://github.com/Charmve/VOGUE-Try-On)]

**Dressing in Order: Recurrent Person Image Generation for Pose Transfer, Virtual Try-on and Outfit Editing.**<br>
*Aiyu Cui, Daniel McKee, Svetlana Lazebnik.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2104.07021)] [[Code](https://github.com/cuiaiyu/dressing-in-order)]

**Toward Accurate and Realistic Outfits Visualization With Attention to Details.**<br>
*Kedan Li, Min Jin Chong, Jeffrey Zhang, Jingen Liu.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2106.06593)] [[Demo](https://revery.ai/demo.html)]

**VITON-HD: High-Resolution Virtual Try-On via Misalignment-Aware Normalization.**<br>
*Seunghwan Choi, Sunghyun Park, Minsoo Lee, Jaegul Choo.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.16874)]

**HumanGAN: A Generative Model of Humans Images.**<br>
*Kripasindhu Sarkar, Lingjie Liu, Vladislav Golyanik, Christian Theobalt.*<br>
CVPR 2021. [[PDF](https://arxiv.org/pdf/2103.06902.pdf)] [[Project](http://gvv.mpi-inf.mpg.de/projects/HumanGAN)]

**DCTON: Disentangled Cycle Consistency for Highly-realistic Virtual Try-On.**<br>
*Chongjian Ge, Yibing Song, Yuying Ge, Han Yang, Wei Liu, and Ping Luo.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.09479)] [[Code](https://github.com/ChongjianGE/DCTON)]

**PF-AFN: Parser-Free Virtual Try-on via Distilling Appearance Flows.**<br>
*Yuying Ge, Yibing Song, Ruimao Zhang, Chongjian Ge, Wei Liu, Ping Luo.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.04559)] [[Code](https://github.com/geyuying/PF-AFN)] 

**Template-Free Try-on Image Synthesis via Semantic-guided Optimization.**<br>
*Chien-Lung Chou, Chieh-Yun Chen, Chia-Wei Hsieh, Hong-Han Shuai, Jiaying Liu, Wen-Huang Cheng.*<br>
TNNLS 2021. [[PDF](https://arxiv.org/abs/2102.03503)]

**Unpaired Person Image Generation with Semantic Parsing Transformation.**<br>
*Sijie Song, Wei Zhang, Jiaying Liuv, Zongming Guo, Tao Mei.*<br>
TPAMI 2020. [[PDF](https://arxiv.org/abs/1912.06324)] [[CVPR 2019](https://arxiv.org/abs/1904.03379)] [[TPAMI 2020](https://ieeexplore.ieee.org/document/9085915/authors#authors)] [[Code](https://github.com/JDAI-CV/Down-to-the-Last-Detail-Virtual-Try-on-with-Detail-Carving)]

**Do Not Mask What You Do Not Need to Mask: a Parser-Free Virtual Try-On.**<br>
*Thibaut Issenhuth, Jérémie Mary, Clément Calauzènes.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.02721)]

**Fully Convolutional Graph Neural Networks for Parametric Virtual Try-On.**<br>
*Raquel Vidaurre, Igor Santesteban, Elena Garces, Dan Casas.*<br>
ACM MM 2020. [[PDF](https://arxiv.org/abs/2009.04592)] [[Project](http://mslab.es/projects/FullyConvolutionalGraphVirtualTryOn)]

**Towards Photo-Realistic Virtual Try-On by Adaptively Generating Preserving Image Content.**<br>
*Han Yang, Ruimao Zhang, Xiaobao Guo, Wei Liu, Wangmeng Zuo, Ping Luo.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.05863)] [[Code](https://github.com/switchablenorms/DeepFashion_Try_On)]

**PSGAN: Pose and Expression Robust Spatial-Aware GAN for Customizable Makeup Transfer.**<br>
*Wentao Jiang, Si Liu, Chen Gao, Jie Cao, Ran He, Jiashi Feng, Shuicheng Yan.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/1909.06956)]

**GarmentGAN: Photo-realistic Adversarial Fashion Transfer.**<br>
*Amir Hossein Raffiee, Michael Sollami.*<br>
ICPR 2020. [[PDF](https://arxiv.org/abs/2003.01894)]

**SieveNet: A Unified Framework for Robust Image-Based Virtual Try-On.**<br>
*Surgan Jandial, Ayush Chopra, Kumar Ayush, Mayur Hemani, Abhijeet Kumar, Balaji Krishnamurthy.*<br>
WACV 2020. [[PDF](https://arxiv.org/abs/2001.06265)] [[Code](https://github.com/levindabhi/SieveNet)]

**TailorGAN: Making User-Defined Fashion Designs.**<br>
*Lele Chen, Justin Tian, Guo Li, Cheng-Haw Wu, Erh-Kan King, Kuan-Ting Chen, Shao-Hang Hsieh.*<br>
WACV 2020. [[PDF](https://arxiv.org/abs/2001.06427)] [[Code](https://github.com/gli-27/TailorGAN)]

**ClothFlow: A Flow-Based Model for Clothed Person Generation.**<br>
*Xintong Han, Xiaojun Hu, Weilin Huang, Matthew R. Scott.*<br>
ICCV 2019. [[PDF](https://openaccess.thecvf.com/content_ICCV_2019/html/Han_ClothFlow_A_Flow-Based_Model_for_Clothed_Person_Generation_ICCV_2019_paper.html)]

**VTNFP: An Image-Based Virtual Try-On Network With Body and Clothing Feature Preservation.**<br>
*Ruiyun Yu, Xiaoqi Wang, Xiaohui Xie.*<br>
ICCV 2019. [[PDF](https://openaccess.thecvf.com/content_ICCV_2019/html/Yu_VTNFP_An_Image-Based_Virtual_Try-On_Network_With_Body_and_Clothing_ICCV_2019_paper.html)]

**Toward Characteristic-Preserving Image-based Virtual Try-On Network.**<br>
*Bochao Wang, Huabin Zheng, Xiaodan Liang, Yimin Chen, Liang Lin, Meng Yang.*<br>
ECCV 2018. [[PDF](https://arxiv.org/abs/1807.07688)]

## Human Body Reshaping

**Structure-Aware Flow Generation for Human Body Reshaping.**<br>
*[Jianqiang Ren](https://github.com/JianqiangRen), Yuan Yao, Biwen Lei, Miaomiao Cui, Xuansong Xie.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2203.04670)] [[Code](https://github.com/JianqiangRen/FlowBasedBodyReshaping)]

**Real-Time Reshaping of Humans.**<br>
*Michal Richter, Kiran Varanasi, Nils Hasler, Christian Theobalt.*<br>
International Conference on 3D Imaging, Modeling, Processing, Visualization & Transmission, 2012. [[PDF](https://vcai.mpi-inf.mpg.de/files/3DimPVT/human_reshape.pdf)]

**MovieReshape: Tracking and Reshaping of Humans in Videos.**<br>
*Arjun Jain, Thorsten Thormählen, Hans-Peter Seidel, Christian Theobalt.*<br>
SIGGRAPH Asia 2010. [[PDF](http://www.mpi-inf.mpg.de/resources/MovieReshape/MovieReshape.pdf)] [[Project](https://resources.mpi-inf.mpg.de/MovieReshape)]

**Parametric reshaping of human bodies in images.**<br>
*Shizhe Zhou, Hongbo Fu,  Ligang Liu, Daniel Cohen-Or, Xiaoguang Han.*<br>
SIGGRAPH 2010. [[PDF](https://dl.acm.org/doi/10.1145/1833349.1778863)]

### Scene context-aware Human Body Generation

**Putting People in Their Place: Affordance-Aware Human Insertion Into Scenes.**<br>
*Sumith Kulal, Tim Brooks, Alex Aiken, Jiajun Wu, Jimei Yang, Jingwan Lu, Alexei A. Efros, Krishna Kumar Singh.*<br> 
CVPR 2023. [[PDF](http://arxiv.org/abs/2304.14406)] [[Project](https://sumith1896.github.io/affordance-insertion)]

**Generating 3D People in Scenes Without People.**<br>
*Yan Zhang, Mohamed Hassan, Heiko Neumann, Michael J. Black, Siyu Tang.*<br> 
CVPR 2020. [[PDF](https://openaccess.thecvf.com/content_CVPR_2020/html/Zhang_Generating_3D_People_in_Scenes_Without_People_CVPR_2020_paper.html)] [[Code](https://github.com/yz-cnsdqz/PSI-release)]

### Human Mesh Recovery

**GLAMR: Global Occlusion-Aware Human Mesh Recovery with Dynamic Cameras.**<br>
*[Ye Yuan](https://www.ye-yuan.com), [Umar Iqbal](http://www.umariqbal.info), [Pavlo Molchanov](https://research.nvidia.com/person/pavlo-molchanov), [Kris Kitani](http://www.cs.cmu.edu/~kkitani), [Jan Kautz](https://jankautz.com).*<br>
CVPR 2022 (Oral). [[PDF](https://arxiv.org/abs/2112.01524)] [[Project](https://nvlabs.github.io/GLAMR)] [[Code](https://github.com/NVlabs/GLAMR)]

**Shapy: Accurate 3D Body Shape Regression Using Metric and Semantic Attributes.**<br>
*Vasileios Choutas, Lea Muller, Chun-Hao P. Huang, Siyu Tang, Dimitrios Tzionas, Michael J. Black.*<br> 
CVPR 2022. [[PDF](http://arxiv.org/abs/2206.07036)] [[Project](https://shapy.is.tue.mpg.de)] [[Code](https://github.com/muelea/shapy)]

**PoseScript: 3D Human Poses from Natural Language.**<br>
*Ginger Delmas, Philippe Weinzaepfel, Thomas Lucas, Francesc Moreno-Noguer, Grégory Rogez.*<br> 
ECCV 2022. [[PDF](http://arxiv.org/abs/2210.11795)] [[Code](https://github.com/naver/posescript)]

### Human-Centric Perception

**Versatile Multi-Modal Pre-Training for Human-Centric Perception.**<br>
*[Fangzhou Hong](https://hongfz16.github.io), Liang Pan, Zhongang Cai, [Ziwei Liu](https://liuziwei7.github.io).*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2203.13815)] [[Code](https://github.com/hongfz16/HCMoCo)] [[Project](https://hongfz16.github.io/projects/HCMoCo.html;)]

### Challenge and workshop
- KDD Workshop on Fashion. [[2019]](https://kddfashion2019.mybluemix.net) [[2018]](https://kddfashion2018.mybluemix.net) [[2017]](https://kddfashion2017.mybluemix.net) [[2016]](http://kddfashion2016.mybluemix.net)
- Workshop on Computer Vision for Fashion, Art and Design. [[CVPR 2020]](https://sites.google.com/view/cvcreative2020) [[ICCV 2019]](https://sites.google.com/view/cvcreative/home) [[ECCV 2018]](https://sites.google.com/view/eccvfashion) [[ICCV 2017]](https://sites.google.com/zalando.de/cvf-iccv2017/home?authuser=0)
- NeurlPS workshop on Machine Learning for Creativity and Design. [[2019]](https://neurips2019creativity.github.io) [[2018]](https://nips2018creativity.github.io) [[2017]](https://nips2017creativity.github.io)
- SIGIR Workshop On eCommerce. [[2019]](https://sigir-ecom.github.io/index.html) [[2018]](https://sigir-ecom.github.io/ecom2018/index.html) [[2017]](http://sigir-ecom.weebly.com) 
- CVPR Deep Learning for Content Creation Tutorial. [[2019]](https://nvlabs.github.io/dl-for-content-creation)
- iMaterialist Fashion Challenge. [[CVPR 2019]](https://sites.google.com/view/fgvc6/competitions/imat-fashion-2019)
- iDesigner Challenge. [[CVPR 2019]](https://sites.google.com/view/fgvc6/competitions/idesigner-2019)
- FashionGen Challenge. [[ICCV 2019, ECCV 2018]](https://fashion-gen.com)
- JD AI Fashion Challenge. [[ChinaMM 2018]](https://fashion-challenge.github.io)
- Alibaba FashionAI Global Challenge. [[Tianchi]](http://fashionai.alibaba.com)
- Artificial Intelligence on Fashion and Textile Conference. [[AIFT 2018]](https://www.polyu.edu.hk/itc/aift2018)
- Fashion IQ Challenge. [[CVPR 2020]](https://sites.google.com/view/cvcreative2020/fashion-iq?authuser=0) [[ICCV 2019]](https://sites.google.com/view/lingir/fashion-iq)
- DeepFashion2 Challenge. [[CVPR 2020]](https://sites.google.com/view/cvcreative2020/deepfashion2?authuser=0) [[ICCV 2019]](https://sites.google.com/view/cvcreative/deepfashion2)

### Datasets
- WildAvatar (2024). [[Website]](https://arxiv.org/pdf/2407.02165)
- Fashionpedia. [[Website]](https://fashionpedia.github.io/home/index.html)
- DeepFashion2 Dataset. [[Website]](<https://github.com/switchablenorms/DeepFashion2>)
- DeepFashion Dataset. [[Website]](http://mmlab.ie.cuhk.edu.hk/projects/DeepFashion.html)
- FashionGen. [[Website]](https://fashion-gen.com)
- FashionAI. [[Tianchi]](http://fashionai.alibaba.com/datasets/?spm=a2c22.11190735.991137.8.501b6d83ilPJsX)
- TaobaoClothMatch. [[Tianchi]](TaobaoClothMatch)
- Fashion-MNIST. [[Fashion-MNIST]](https://github.com/zalandoresearch/fashion-mnist)
- Fashion IQ. [[Website]](https://www.spacewu.com/posts/fashion-iq)
- NTURGBD-Parsing-4K Dataset. [[Website](https://github.com/hongfz16/HCMoCo)]

## Garment Design

**Tailor: An Integrated Text-Driven CG-Ready Human and Garment Generation System.**<br>
*Zhiyao Sun, Yu-Hui Wen, Matthieu Lin, Ho-Jui Fang, Sheng Ye, Tian Lv, Yong-Jin Liu.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2503.12052)] [[Project](https://human-tailor.github.io)] [[Github](https://human-tailor.github.io)]

**DressCode: Autoregressively Sewing and Generating Garments from Text Guidance.**<br>
*Kai He, Kaixin Yao, Qixuan Zhang, Jingyi Yu, Lingjie Liu, Lan Xu.*<br>
SIGGRAPH 2024 (TOG). [[PDF](https://arxiv.org/abs/2401.16465)] [[Project](https://ihe-kaii.github.io/DressCode)] [[Github](https://github.com/IHe-KaiI/DressCode)]

**GarmentDreamer: 3DGS Guided Garment Synthesis with Diverse Geometry and Texture Details.**<br>
*Boqian Li, Xuan Li, Ying Jiang, Tianyi Xie, Feng Gao, Huamin Wang, Yin Yang, Chenfanfu Jiang.*<br>
3DV 2025. [[PDF](https://arxiv.org/abs/2405.12420)] [[Project](https://xuan-li.github.io/GarmentDreamerDemo)] [[Github](https://github.com/boqian-li/GarmentDreamer)]

**Knitting 4D Garment with Elasticity Controlled for Body Motion.**<br>
*[Zishun Liu](https://github.com/zishun), Xingjian Han, Yuchen Zhang, Xiangjia Chen, Yukun Lai, Eugeni L. Doubrovski, Emily Whiting, Charlie C.L. Wang.*<br>
TOG 2021. [[PDF](https://1drv.ms/b/s!AsZuzkRqeoh6gsUNhZKQ0bRp-BDaJQ?e=XIegdJ)] [[Project](https://zishun.github.io/projects/Knitting4D)]

**Garment Design with Generative Adversarial Networks.**<br>
*Chenxi Yuan, Mohsen Moghaddam.*<br>
KDD workshop on AdvML 2020. [[PDF](https://arxiv.org/abs/2007.10947)] 

## Fashion Style Influences

**From Paris to Berlin: Discovering Fashion Style Influences Around the World.**<br>
*Ziad Al-Halah, Kristen Grauman.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.01316)]

**From Culture to Clothing: Discovering the World Events Behind A Century of Fashion Images.**<br>
*Wei-Lin Hsiao, Kristen Grauman.*<br>
ICCV 2021. [[PDF](https://arxiv.org/abs/2102.01690)]

## Team and People

- [Real Virtual Humans](http://virtualhumans.mpi-inf.mpg.de), **Max Planck Institute for Informatics**, by [Gerard Pons-Moll](http://virtualhumans.mpi-inf.mpg.de/people/pons-moll.html).
- [Perceiving Systems, Tubingen Compus](http://ps.is.tuebingen.mpg.de), **Max Planck Institute for Intelligent Systems**, by [Michael Black](http://ps.is.tuebingen.mpg.de/person/black).
- [Visual Computer Lab](https://niessnerlab.org/opening.html), **Technical University Munich (TUM)**, by [Prof. Dr. Matthias Nießner](https://niessnerlab.org/members/matthias_niessner/profile.html) and his [team](https://niessnerlab.org/team.html).
- [Broadband Network and Digital Media Lab](http://www.liuyebin.com/student.html), Department of Automation, **Tsinghua University**, by [Yebin Liu](http://www.liuyebin.com).
- [Vision and Graphics Lab](https://ict.usc.edu), **University of Southern California**, by [Hao Li](http://hao-li.com/Hao_Li/Hao_Li_-_publications.html).

## Dataset

- `SMPL`. To download the [SMPL-X](https://smpl-x.is.tue.mpg.de), [SMPL+H](http://mano.is.tue.mpg.de) and SMPL ([Male and Female](http://smpl.is.tue.mpg.de), [Gender Neural Model](http://smplify.is.tue.mpg.de)) model, go to this project website and register to get access to the downloads section. [[Code](https://github.com/vchoutas/smplx#loading-smpl-x-smplh-and-smpl)]

- `THUmanDataset`. [THUman](https://github.com/ZhengZerong/DeepHuman/tree/master/THUmanDataset) is a 3D real-world human model dataset containing approximately 7000 models.

- `AGORA`. AGORA, proposed at CVPR 2021 [paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Patel_AGORA_Avatars_in_Geography_Optimized_for_Regression_Analysis_CVPR_2021_paper.pdf), consists of 4240 scans spanning more than 350 unique subjects, all paired with SMPL-X fits.

## Applications

### Fitness Training

**AIFit: Automatic 3D Human-Interpretable Feedback Models for Fitness Training.**<br>
*Mihai Fieraru, Mihai Zanfir, Silviu-Cristian Pirlea, Vlad Olaru, Cristian Sminchisescu.*<br>
CVPR 2021. [[PDF](https://openaccess.thecvf.com/content/CVPR2021/papers/Fieraru_AIFit_Automatic_3D_Human-Interpretable_Feedback_Models_for_Fitness_Training_CVPR_2021_paper.pdf)] [[Project](http://vision.imar.ro/fit3d)]
