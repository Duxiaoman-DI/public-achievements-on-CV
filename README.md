# public-achievements-on-CV
在金融行业，计算机视觉（以下简称“CV”）技术，比如人脸识别、防深伪、OCR识别等已经广泛应用于身份核验、风险控制、安防等场景。作为注重技术创新的金融科技企业，度小满在CV领域也自研了创新算法和产品，在ICDAR等国际比赛与顶会中都取得了优秀成绩。    

**公开比赛**
* [2023 ICDAR 密集小文本视频OCR比赛 视频文本定位赛道：第三名](#icdar_ocr)
* [2022 CVPR 轻量NAS挑战赛：第四名](#cvpr_2022)
* 2021 ICDAR 视频文本追踪赛：第二名
* 2021 ICDAR 视频文本定位赛：第二名
* 2021 ICDAR 视频文本检测赛：第三名
* [NeurIPS 2021 VisDA视觉域适应挑战赛：第四名](#visda)  

**顶会论文**
* [CVPR 2022 NAS workshop 收录：超网排序相关性论文](#cvpaper)    

**产品与能力认证**
* 信通院人脸识别安全专项评测：活体检测安全防护能力 - 优秀级   


## 公开比赛    
### <span id='icdar_ocr'>2023 ICDAR</span> 密集小文本视频OCR比赛 视频文本定位赛道    
我们利用视觉Transformer模型集成高分辨率卷积网络提高小文本召回率，并在公开数据集的基础上生成小文本数据做预训练，有效提高了跟踪精度。方案效果优于天津大学、北邮、中国移动研究院、上海人工智能实验室等单位。     

###  <span id='cvpr_2022'>2022 CVPR</span> 轻量NAS挑战赛    
我们提出了从one-shot NAS到few-shot NAS的逐步训练超网的方案。    
在训练方案中，我们首先以one-shot的方式训练超网，然后通过将其分割成多个子网并逐渐训练它们来解耦超网的权重。我们的方法在CVPR2022第三届轻量级NAS挑战赛Track1中排名第四。   
[相关论文](#cvpaper)被CVPR 2022 NAS workshop 收录。    

###  <span id='visda'>NeurIPS 2021 VisDA视觉域适应挑战赛</span>    
我们提出了一种基于伪标签的通用域适应系统用于领域适应性和开放集分类。我们使用OVANet架构进行类内分类和类外置信度预测，然后使用带有伪标签的无标签数据多次训练模型以提高性能。    
此外，我们训练了多个不同的模型，并通过对这些模型的预测结果进行投票来实现模型集成。    
我们的方法在NeurIPS 2021视觉域适应挑战赛(VisDA-2021)中排名第四。    
**论文链接：**[Universal Domain Adaption and Open Set Classification with focus on Visual Domain Adaption Challenge 2021](https://github.com/liujiawei2333/NeurIPS-2021-Visual-Domain-Adaptation-Challenge-4th-solution/blob/master/NeurIPS%202021%20Visual%20Domain%20Adaptation%20Challenge%204th%20solution.pdf)     
**相关代码：**[NeurIPS-2021-Visual-Domain-Adaptation-Challenge-4th-solution](https://github.com/liujiawei2333/NeurIPS-2021-Visual-Domain-Adaptation-Challenge-4th-solution/tree/master)


## 顶会论文     
### <span id='cvpaper'>Improve Ranking Correlation of Super-net through Training Scheme from One-shot NAS to Few-shot NAS</span>
**论文链接:**  [论文pdf](https://arxiv.org/pdf/2206.05896v1.pdf)     
**论文简介:**   One-shot神经结构搜索（NAS）的算法已经被广泛用于减少计算量。然而，由于共享权重的子网之间的干扰，从这些算法训练出来的超网继承下来的子网在精度排名上一致性较差。于是我们提出了一个从one-shot NAS到few-shot NAS的逐步训练超网的方案。在训练方案中，我们首先以one-shot的方式训练超网，然后通过将其分割成多个子网并逐渐训练它们来解耦超网的权重。     
**论文代码:**  [CVPR2022-NAS-competition-Track-1-4th-solution](https://github.com/liujiawei2333/CVPR2022-NAS-competition-Track-1-4th-solution)       
![CVPR图片](https://github.com/Duxiaoman-DI/public-achievements-on-CV/blob/main/naspdc.PNG)




## 产品与能力认证
