# XMU-Subject-Practice3-Craft-beer-recommendation-system
精酿啤酒推荐系统
## 项目结构
单独的html文件即可运行

## 快速开始
打开html文件，点击导入数据即可使用
<img width="982" height="417" alt="导入数据-1" src="https://github.com/user-attachments/assets/7039a7a4-72a4-4cbd-87fe-b2c15c9eb8f0" />


切换本地前端模型
点击模型/训练
<img width="982" height="417" alt="image" src="https://github.com/user-attachments/assets/8943572e-306e-49b2-9ab1-417e05d1cc7c" />

点击开始训练，训练完成后自动切换
<img width="935" height="812" alt="image-1" src="https://github.com/user-attachments/assets/a845200c-9135-4ae6-9c8d-988c46c88c6e" />

<img width="937" height="722" alt="image-2" src="https://github.com/user-attachments/assets/bb743630-4815-4f56-b5e5-5e333a8c0393" />


切换本地强模型
点击设置
<img width="982" height="417" alt="image-3" src="https://github.com/user-attachments/assets/b459aa68-025e-4a4a-b5d1-d484d11b91a3" />

打开开关设置URL即可使用
<img width="551" height="457" alt="image-4" src="https://github.com/user-attachments/assets/3d52771d-4ec1-4483-8af3-6202acb446d4" />


## 具体功能
* 相似度推荐
<img width="457" height="322" alt="image-7" src="https://github.com/user-attachments/assets/82aa001e-7a3a-43a6-9b45-ddac104ce392" />

点击一款啤酒后会基于当前的啤酒推荐 3 款最相似的啤酒

* 猜你喜欢
<img width="447" height="262" alt="image-8" src="https://github.com/user-attachments/assets/0d0a5a91-43b5-4187-913a-49c964c90977" />

基于您的评分记录来推荐您可能喜欢的啤酒

* 手气不错
<img width="522" height="87" alt="image-9" src="https://github.com/user-attachments/assets/d3ae0702-539e-4287-84da-0a3d185db105" />

随机从当前筛选列表中抽取一款啤酒

* 筛选排序
<img width="633" height="106" alt="image-5" src="https://github.com/user-attachments/assets/2b03b451-ddb9-4e2f-a621-994141383c91" />

根据风格、酒厂筛选
根据评分、热度、酒精排序

* 搜索
<img width="267" height="76" alt="image-6" src="https://github.com/user-attachments/assets/51324c32-29d5-415a-9679-d4e568530554" />

可搜索名字、酒厂、风格




## 项目数据
项目数据来源于开源啤酒数据集[Beer Reviews from Beer Advocate (1.5 Million)](https://www.kaggle.com/datasets/thedevastator/1-5-million-beer-reviews-from-beer-advocate)，数据集进行了精简，仅保留985种啤酒和相关评论、用户数据。


## 实现的模型
* LightGBM 经验公式
* 多元线性回归
