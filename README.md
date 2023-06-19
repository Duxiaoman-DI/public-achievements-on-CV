# public-achievements-on-CV
在金融行业，计算机视觉（以下简称“CV”）技术，比如人脸识别、防深伪、OCR识别等已经广泛应用于身份核验、风险控制、安防等场景。作为注重技术创新的金融科技企业，度小满在CV领域也自研了创新算法和产品，在ICDAR等国际比赛与顶会中都取得了优秀成绩。    

**公开比赛**
* [2023 ICDAR 密集小文本视频OCR比赛 视频文本定位赛道：第三名](#2023ICDAR)
* [2022 CVPR 轻量NAS挑战赛：第四名](#2022CVPR)
* 2021 ICDAR 视频文本追踪赛：第二名
* 2021 ICDAR 视频文本定位赛：第二名
* 2021 ICDAR 视频文本检测赛：第三名
* NeurIPS 2021 VisDA视觉域适应挑战赛：第四名  

**顶会论文**
* CVPR 2022 NAS workshop 收录：超网排序相关性论文    

**产品与能力认证**
* 信通院人脸识别安全专项评测：活体检测安全防护能力 - 优秀级   


## 公开比赛    
### <span id='2023ICDAR'>2023 ICDAR</span> 密集小文本视频OCR比赛 视频文本定位赛道    
我们利用视觉Transformer模型集成高分辨率卷积网络提高小文本召回率，并在公开数据集的基础上生成小文本数据做预训练，有效提高了跟踪精度。方案效果优于天津大学、北邮、中国移动研究院、上海人工智能实验室等单位。     

###  <span id='2022CVPR'>2022 CVPR</span> 轻量NAS挑战赛    
我们提出了从零样本NAS到小样本NAS的逐步训练超网的方案。    
在训练方案中，我们首先以一次性的方式训练超网，然后通过将其分割成多个子网并逐渐训练它们来解耦超网的权重。我们的方法在CVPR2022第三届轻量级NAS挑战赛Track1中排名第四。   
[相关论文](#2022CVpaper)被CVPR 2022 NAS workshop 收录。



## 顶会论文     
### <span id='2022CVpaper'>Improve Ranking Correlation of Super-net through Training Scheme from One-shot NAS to Few-shot NAS</span>
**论文链接:**  [论文pdf](https://arxiv.org/pdf/2206.05896v1.pdf)     
**论文简介:**   一次性神经结构搜索（NAS）的算法已经被广泛用于减少计算量。然而，由于共享权重的子网之间的干扰，从这些算法训练出来的超网继承下来的子网在精度排名上一致性较差。于是我们提出了一个从一次性NAS到少次性NAS的逐步训练超网的方案。在训练方案中，我们首先以一次性的方式训练超网，然后我们通过将其分割成多个子网并逐渐训练它们来解耦超网的权重。     
**论文代码:**  [CVPR2022-NAS-competition-Track-1-4th-solution](https://github.com/liujiawei2333/CVPR2022-NAS-competition-Track-1-4th-solution)       
![CVPR图片](https://github.com/Duxiaoman-DI/public-achievements-on-CV/blob/main/naspdc.PNG)




## 产品与能力认证
