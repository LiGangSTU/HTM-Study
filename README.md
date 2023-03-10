# HTM-Study
HTM 层级时序记忆
### 1. HIERARCHICAL TEMPORAL MEMORY HTM白皮书

​          解释HTM算法，实现空间沉积，时间沉积和伪代码，对生物神经元细胞和HTM对比

1. 什么是HTM？

   层级实时记忆，捕捉新大脑皮层的结构和特性 

### 2. HTM模型在海德堡计算平台上的使用 03

​		分层时间记忆 (HTM) 是基于对新皮质的详细研究的机器智能计算理论。作为人脑计划 (HBP) 的一部分开发的海德堡神经形态计算平台是一个混合信号（模拟和数字）大型平台，用于对尖峰神经元网络进行建模。在本文中，我们展示了将 HTM 网络移植到该平台的首次尝试。我们描述了一个使用尖峰网络模型模拟关键 HTM 操作的框架。然后，我们描述了特定的空间池和时间内存实现，以及证明基本属性得以保持的模拟。我们讨论了使用 SpikeTiming Dependent Plasticity (STDP) 实施整套可塑性规则的问题，以及粗略的布局和布线计算。尽管还需要进一步的工作，但我们的初步研究表明应该可以在海德堡平台上高效地运行大规模 HTM 网络（包括可塑性规则）。更一般地，将高级 HTM 算法移植到生物物理神经元模型的练习有望成为未来研究的一个富有成果的研究领域。

### 3. 评估实时异常检测——numenta异常基准

​		世界上的大部分数据都是流式的、时间序列的数据，其中异常在危急情况下会提供重要信息；金融、IT、安全、医疗和能源等领域的例子比比皆是。然而，检测流数据中的异常是一项艰巨的任务，需要检测器实时而不是批量处理数据，并在进行预测的同时进行学习。没有基准来充分测试和评分实时异常检测器的功效。在这里，我们提出了 Numenta Anomaly Benchmark (NAB)，它试图提供一个受控和可重复的开源工具环境，以测试和测量流数据上的异常检测算法。完美的检测器将尽快检测到所有异常情况，不会触发误报，处理各个领域的真实时间序列数据，并自动适应不断变化的统计数据。奖励这些特征在 NAB 中被形式化，使用为流数据设计的评分算法。 NAB 使用标记的真实时间序列数据在基准数据集上评估检测器。我们展示了这些组件，并为几个开源的、商业使用的算法提供了结果和分析。 NAB 的目标是提供一个标准的开源框架，研究社区可以通过该框架比较和评估用于检测流数据异常的不同算法。

参考代码【https://github.com/djy120/VariableLengthSubsequenceClustering/tree/5eda9fc5f51508fe40036681a1118882ed1615a4/Dataset/NAB-master】

### 4 解释神经元如何在稀疏分布上运行？稀疏性，神经元和活性树突之间的数学理论

这篇值得仔细阅读

### 5. HTM的编码解释

分层时间记忆（HTM）是一种受生物学启发的机器智能技术，它模仿了大脑皮层的结构和过程。在本白皮书中，我们描述了如何将数据编码为稀疏分布式表示（SDR），以便在HTM系统中使用。我们解释了几种现有的编码器，它们可以通过名为NuPIC1的开源项目获得，并讨论了为新类型的数据创建编码器的要求。

### 6. 使用无监督神经网络模型进行连续在线序列学习

​     识别和预测感官输入时间序列的能力对于在自然环境中生存至关重要。基于皮层神经元的许多已知特性，层次时间记忆（HTM）序列记忆最近被提出作为皮层序列学习的理论框架。本文分析了HTM序列存储器的特性，并将其应用于流数据序列学习和预测问题。我们证明了该模型能够使用无监督的类Hebbian学习规则连续学习大量可变阶时间序列。该模型形成的稀疏时态码通过保持多个预测，直到有足够的消歧证据为止，能够稳健地处理分支时态序列。我们将HTM序列记忆与其他序列学习算法进行了比较，包括统计方法：自回归综合移动平均（ARIMA）、前馈神经网络：在线序列极端学习机（ELM）和递归神经网络：长短时记忆（LSTM）和回声状态网络（ESN），关于人工和真实数据的序列预测问题。HTM模型的精度与其他最先进的算法相当。该模型还展示了对序列学习至关重要的特性，包括连续在线学习、利用高阶统计量处理多个预测和分支序列的能力、对传感器噪声和容错的鲁棒性，以及无需特定任务超参数调整的良好性能。因此HTM序列记忆不仅促进了我们对大脑如何解决序列学习问题的理解，而且也适用于广泛的现实世界问题，如离散和连续序列预测、异常检测和序列分类。



