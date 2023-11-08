ART 需要在 TensorFlow 中禁用 "eager execution"

在代码的开头，添加上述代码来禁用 eager execution，然后再创建 ART 的 KerasClassifier 对象。

在 CIFAR-10 数据集上使用 AdvBox 进行基于预处理的对抗防御或基于对抗训练的对抗防御需要多个步骤，包括数据加载、模型构

建、对抗样本生成、对抗训练等。以下是一个完整的 Python 代码，演示如何使用 AdvBox 在 CIFAR-10 数据集上进行对抗防

御。请确保您已经安装了 AdvBox 和 CIFAR-10 数据集。