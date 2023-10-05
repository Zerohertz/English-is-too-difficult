# [PAN++: Towards Efficient and Accurate End-to-End Spotting of Arbitrarily-Shaped Text](https://arxiv.org/abs/2105.00405)

> PAN++ is based on the kernel representation that reformulates a text line as a text kernel (central region) surrounded by `peripheral` pixels.

+ Peripheral: 주변적인, 지엽적인, 주변부의

> By systematically comparing with existing scene text representations, we show that our kernel representation can not only describe `arbitrarily`-shaped text but also well `distinguish` `adjacent` text.

+ Arbitrarily: 임의적인
+ Distinguish: 구별하다, 구별 짓다
+ Adjacent: 인접한, 가까운

> However, the features produced by the lightweight backbone network often have small `receptive` fields and weak representation capabilities.

+ Receptive: 수용적인

> To handle this problem, we propose a feature enhancement network that can `refine` the features efficiently.

+ Refine: 정제하다, 개선하다

> In the `inference` phase, we firstly feed an input image of a size of H × W × 3 to a lightweight backbone network (e.g., ResNet18 [19]).

+ Inference: 추론

> “2×” indicates 2× `bilinear` upsampling.

+ Bilinear: 쌍일차의, 쌍일차 방정식의

> After obtaining enhanced feature pyramid Fe (see Fig. 4 (d)), we upsample and `concatenate` the feature maps of feature pyramid Fe into the final feature map for follow-up text detection and recognition.

+ Concatenate: 사슬같이 잇다, 연쇄시키다, 연쇄된, 이어진, 연결된

> the ReLU function, `ensuring` the output is non-negative.

+ Ensure: 반드시 ...하게 하다, 보장하다

> This condition `alleviates` the problem of assigning conflict pixels to incorrect text kernels.

+ Alleviate: 완화하다

> In the testing phase, we `utilize` the predicted instance vector to guide the pixels in text regions to the corresponding text kernel.

+ Utilize: 활용하다

> finding the connected components in the segmentation result of text kernels, and each connected component is `regarded` as a text kernel

+ Regard: ...을 ...으로 여기다

---

# [EfficientDet: Scalable and Efficient Object Detection](https://arxiv.org/abs/1911.09070)

> Secoond, we proposed a `compound` scaling method that uniformly scales the resolution, depth, and width for all backbone, feature network, and box/class prediction networks at the same time.

+ Compound: 복합체, 합성(복합)의

> Based on these optimizations and better `backbones`, we have developed a new family of object detectors, called EfficientDet, which `consistently` achieve much better efficiency than prior art across a wide spectrum of resource `constraints`.

+ Backbone: 척추, 등뼈, 근간, 중추
+ Consistent: 한결같은, 일관된, 거듭되는, ~와 일치하는
+ Constraint: 제약, 제한, 통제

> Multi-scale feature fusion aims to aggregate features at different resolutions.

+ Aggregate: 합계, 총액

> To `address` this issue, PANet adds an extra bottom-up path aggregation network, as shown in Figure 2(b).

+ Address: (문제, 상황 등에 대해) 고심하다, 해결하다

> Recently, NAS-FPN employs neural architecture search to search for better cross-scale feature network `topology`, but it requires thousands of GPU hours during search and the found network is `irregular` and difficult to `interpret` or modify, as hown in Figure 2(c).

+ Topology: 체계적인 분류, 위상 배치
+ Irregular: 가지런하지 못한, 불규칙적인
+ Interpret: 설명(해석)하다, 이해하다, 통역하다

> All previous methods treat all input features equally without `distinction`.

+ Distinction: 차이, 대조, 뛰어남, 탁월함, 특별함

---

# [Deep Learning Logo Detection with Data Expansion by Synthesising Context](https://arxiv.org/abs/1612.09322)

> Logo detection in `unconstrained` images is challenging, particularly when only very `sparse` labelled training images are accessible due to high labelling costs

+ Unconstrained: 제한받지 않는
+ Sparse: 드문, 희박한

> In this work, we describe a model training image `synthesising` method `capable` of improving significantly logo detection performance when only a handful of (e.g., 10) labelled training images captured in realistic context are available, avoiding extensive manual labelling costs.

+ Synthesis: 종합, 합성
+ Capable: ~을 할 수 있는, 유능한

> Specifically, we design a novel algorithm for generating Synthetic Context Logo (SCL) training images to increase model robustness against unknown background `clutters`, resulting in superior logo detection performance

+ Clutter: 채우다, 잡동사니, 어수선함

---

# [Logo detection and brand recognition with one-stage logo detection framework and simplified resnet50 backbone](https://ieeexplore.ieee.org/document/9144794)

> Similar to the framework proposed by Lin, Ai, & Doll [8], the `objective` of model training is to find model parameters that optimized Focal Loss (See Eq. 1) as the objective function.

+ Objective: 목적, 객관적인, 실재하는, 실증적인

> Interestingly, although each model `convergen` toward its optimum parameter values during training process, the average classification of loss and average regression of Model 2 outperforrmeds those of ResNet-18 and ResNet-34, and Model 2 was faster than the other model, (see Figure 4).

+ Convergen: 수렴, 모이다 (Spanish)

> At this stage the testing was `carried out` by using seven models, which were in `accordance` to the models used in the previous process, which was in the training phase.

+ Carry out: 수행하다
+ Accordance: 일치, 합치, 조화, 인가, 수여

> The different frameworks proposed were frameworks in which the backbone is an `off-the-shelf` model.

+ Off-the-shelf: (특별히 디자인하거나 주문하지 않고) 규격품으로 (바로 살 수 있는)

---

# [Character Region Awareness for Text Detection](https://arxiv.org/abs/1904.01941)

> To overcome the lack of individual character level annotations, our proposed framework `exploits` both the given character-level annotations for `synthetic` images and the estimated character-level ground-truths for real images acquired by the learned interim model.

+ Exploit: 이용하다, 위업, 착취하다
+ Synthetic: 합성한, 인조 물질, 종합적인

> Unlike a binary segmentation map, which labels each pixel `discretely`, we `encode` the probability of the character center with a Gaussian heatmap.

+ Discretely: 분리되어, 따로따로
+ Encode: 암호로 바꾸다, 부호화하다, 표현하다

> Since we have image `blobs` of word regions separated by CCL, the bounding box for a word is simply defined by the single `enclosing` rectangle.

+ Blob: (작은) 방울, (작은) 색깔 부분, 
+ Enclosing: (담, 울타리 등으로) 두르다 (둘러싸다), 에워 (둘러) 싸다, 동봉하다

> On a different note, our character linking process is `conducted` at a pixel-level, which differs from other linking-based methods [32, 12] relying on searching relations between text components `explicitly`.

+ Conduct: 하다, 행동, 경영
+ Explicitly: 명쾌하게

> The proposed method provides the character region score and the character `affinity` score that, together, fully cover various text shapes in a bottom-up `manner`.

+ Affinity: 친밀감, 관련성
+ Manner: 방식

> Since real datasets provided with character-level annotations are rare, we proposed a weakly-supervised learning method that generates `pseudo`-ground truthes from an `interim` model.

+ Pseudo: 허위의, 가짜의, 모조의
+ Interim: (영구적인 것이 나올 때까지 존속시키기 위한) 중간 (임시/과도)의

---

# [DINOv2: Learning Roubust Visual Features without Supervision](https://arxiv.org/abs/2304.07193)

> The recent `breakthroughs` in natural language processing for model pretraining on large quantities of data have opened the way for similar foundation models in computer vision.

+ Breakthrough: 돌파구

> This work shows that existing pretraining methods, expecially self-supervised methods, can produce such features if trained on enough `curated` data from `diverse` sources.

+ Curated: 전문적인 식견으로 엄선한
+ Diverse: 다양한

> `In terms of` data, we propose an automatic pipeline to build a `dedicated`, diverse, and curated image dataset instead of uncurated data, as `typically` done in the self-supervised `literature`.

+ In terms of: ...면에서, ...에 관하여
+ Dedicated: 전념하는, 헌신적인, 전용의
+ Typically: 보통, 일반적으로, 전형적으로, 특징적으로
+ Literature: 문학, 문헌

> In terms of models, we train a ViT model with 1B parameters and distill it into a series of smaller models that `surpass` the best available all-purpose features, OpenCLIP on most of the benchmarks at image and pixel levels.

+ Surpass: 능가하다, 뛰어넘다

> Learning `task-agnostic` pretrained `representations` have become the standard in Natural Language Proceesing (NLP).

+ Task-agnostic: 작업에 구애받지 않는
+ Representation: 묘사, 표현, 나타낸 것, 대표자를 내세움

> One can use these features "`as they are`", i.e., without fine-tuning, and achieve performances on downstream tasks that are significantly better than those produced by task-specific models.

+ As they are: 그대로

> This success has been `fueled` by pretraining on large quantities of raw text using `pretext` objectives, such as language modeling or word vectors, that require no supervision.

+ Fueled: 준비된, 흥분한
+ Pretext: 구실, 핑계, Pretrain 과정에서 사용되는 간접적인 학습 목표나 작업

|항목|Pretrain (사전 학습)|Pretext (사전 텍스트 또는 간접적인 작업)|
|:-:|:-:|:-:|
|정의|모델을 특정한 주요 작업에 대해 학습시키기 전에 먼저 다른 데이터셋이나 작업에 대해 학습시키는 과정입니다.|사전 학습 과정에서 사용되는 간접적인 학습 목표나 작업을 나타냅니다.|
|목적|모델에 기본적인 패턴, 특징, 구조 등을 학습시키기 위한 것입니다.|특정 작업에 직접적으로 사용되지 않더라도, 유용한 특징이나 표현을 학습하는 데 도움을 주는 작업입니다.|
|예시|대량의 텍스트 데이터를 사용하여 언어 모델을 사전 학습시킨 후, 특정 작업(예: 감정 분석)을 위해 미세 조정됩니다.|이미지를 임의로 변형하고 원래 형태로 복원하는 작업, 문장의 다음 단어 예측 등 레이블이 필요하지 않거나 적은 양의 레이블만 필요로 하는 작업입니다.|

> These models should generate visual features that work `out of the box` on any task, both at the image level, e.g., image classification, and pixel level, e.g., segmentation.

+ Out of the box: 발군의, 특별 취급, 즉시 사용 가능하게, 별도의 추가 조정 없이

> We `revisit` existing `discriminative` self-supervised approaches that learn features at both the image and patch level, such as iBOT, and we `reconsider` some of their design choices `under the lens of` a larger dataset.

+ Revisit: 다시 방문하다, 다시 논의하다, 재검토하다
+ Discriminative: 식별하는, 차이를 분간하는, 차별적인
+ Reconsider: 재고하다, 재검토하다
+ Under the lens of: ~의 관점에서, ~의 시각에서

> Most of our technical contributions are `tailored` toward stabilizing and accelerating discriminative self-supervised learning when scaling in model and data sizes.

+ Tailored: 잘 맞도록 만든, 맞춤의

> These improvements make our approach around 2× faster and require 3× less memory than similar discriminative self-supervised methods, allowing us to `leverage` longer training with larger batch sizes.

+ Leverage: 영향력

> This idea has become `prevalent` with the work of Doersch et al. (2015), where they train by predicting the context of a given patch.

+ Prevalent: 일반적인, 널리 퍼져 있는

> Recently, the `emergence` of patch-based architectures, like ViTs, has led to a revisit of inpainting for pre-training, potentially in feature space.

+ Emergence: 나오다, 드러나다, 알려지다, 부상하다