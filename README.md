# Trine

# 项目计划安排

## 任务分配
- 每个成员需找到之前的一个方案，并在此基础上进行改进。
- 论文结构应根据导师的要求进行组织。
- 代码部分需要标记每个人的贡献，此部分在评分中占20%。
- 每个人需要走完全流程。
- 使用GitHub进行版本控制。
- 使用Overleaf进行文档编写。

## 时间线
### 2024/4/9
1. Title 要改，加San Juan，Iquitos
2. Introduction
  - 介绍dengue fever
  - 前人经验，趋势
3. 3.1.1 Data Analysis  -- **Weiyi**
    
4. **3.1.3 增加feature selection -- **steffi**   【DONE】**
  
5. 3.2 回归方法简化
6. 4.1 Data analysis results -- **weiyi**
   
7. **4.3.1 XGBoost， LSTM模型参数  -- **steffi, allen** 【partially completed】**
  
8. XGBoot 不使用guardian的性能比较  -- **allen**

9. **4.3.2 模型比较， 增加base model (LR, MLP, RF)  【DONE】**
    
10. 4.2 XGBoost 特征选择的结果，feature importance -- **allen**
    
11. **5 discussion, 已递进的方式先base model 再XGBoost,LSTM 讨论  -- **steffi**  【DONE】**
    
![IMG_5585](https://github.com/allenNero/Trine/assets/150453591/c0dc705c-8864-4266-9983-1ab1cc2b6746)

    

- **3.29之前**
  - 找到之前的方案。
- **5.9交论文**
  - **4.22**前两周专门用于撰写文章。
  - **4.05**完成加强版的工作。
  - **3.25**完成各自版本的开发。
  - 每周一下午四点到五点，在cs building进行面对面会议。
  - **3.05-3.11**确定自己的参考内容和技术方向。
  - **3.12-3.18**完成第一版技术实现。
    - Azc: 第一版使用XGBoost。
    - Jj: LSTM与时序数据处理。
    - Swy: EDA与特征选择。
  - 0318-0325 交流技术实现，完成个人版本
  - 2024年3月26日 会议
    - 已有的
      - Lstm
      - Random forest
      - Xgboost
    - 计划模型
      - Mlp azc
      - Lm jj
      - autoML swy
      - 预处理，feature selection swy
      - 上传到drivendata上看结果
      - 删除github文件
    - 下次开会时间
      - 周二 四月二日 11点 改为线上
      - code结束，准备写论文
  - 2024年4月2日 会议
    - Jj 第一个城市mae19左右 feature selection有一点提升，但是不多.
      - LSTM MAE 5.9
      - 周数数值前向填充
      - 使用了归一化
        - MinMaxScaler/RobustScaler 使用了两种对比，但是前一个效果更好
    - azc xgboost 第一个城市 20多。第二个城市iq17.2
      - 特征重要性MDI 从xgboost中得出，选择了三个特征
      - xgboost 没有预处理（归一化）
    - jj 有三个模型，azc 两个模型
    - jj FS用了五种方法 PCA方法还需要测试
    - TBD: EDA还需要进行。进行PCA方法，不用加上year weekofyear week start date
    - 每个人写一个自己的readme 写在自己的分支的首页
    - 论文任务分配
      - 每个人写一段literature review
        - 第一段 xgboost allen
        - 第二段 LSTM steffi
        - 第三段 MLP weiyi
  - 2024年4月9日 会议
    - 标题：写上两个城市，使用多种模型的机器学习
    -  intro TBD
    -  训练集和测试集五五分开，第二个城市效果更好
    -  3.1.2 预处理的其他方法，添加其他的
    -  3.1.3 加上 feature selection
    -  3 方法论 不用写那么多，到时候每个模型争取一句话
    -  4.1 解释一下之前放的图的一些内容和特点，按两个城市写
    -  5 discussion 需要改进
