
## 使用说明

1. **文件目录：** 确保文件目录正确，以下是结构：
```
I:.
├─.idea
│  └─inspectionProfiles
├─templates
│  ├─data - 数据文件存放处
│  └─plt_imgs - 图片保存处
├─[data_kmeans.py] - k均值算法文件
├─[data_processing.py] - 数据处理文件
├─[main.py] - 主函数
├─[modeling.py] - 建模文件
├─[visualization.py] - 可视化文件 
└─[README.md] - 说明文档

```

2. **安装依赖：** 确保已安装所需的 Python 库，可以通过运行以下命令安装：

    ```bash
    pip install pandas seaborn matplotlib scikit-learn
    ```
   (可选)使用清华园pip镜像安装:
    ```bash
    pip install -i https://pypi.tuna.tsinghua.edu.cn/simple pandas seaborn matplotlib scikit-learn
    ```

3. **运行主程序：** 在终端中运行以下命令启动主程序：

    ```bash
    python main.py
    ```

4. **结果查看：** 程序将加载数据，进行数据处理、建模和可视化，最终展示陨石质量与年份关系散点图、相关性矩阵热力图和 K-Means 聚类结果可视化。
