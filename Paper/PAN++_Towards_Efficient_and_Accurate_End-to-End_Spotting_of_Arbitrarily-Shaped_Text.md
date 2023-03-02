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