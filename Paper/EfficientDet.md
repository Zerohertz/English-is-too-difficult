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