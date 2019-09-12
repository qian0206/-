# -
在现代网络平台上，推荐系统对于让用户参与到个性化内容中来起着至关重要的作用。深度学习使许多研究领域发生了革命性的变化，最近人们对将其应用于协同过滤(CF)的兴趣激增。然而，现有的方法组成了包含潜在因素模型的深度学习体系结构，忽略了CF模型的主要类、邻域或基于内存的方法。利用潜在因子模型的全局结构和局部邻域结构的优势，提出了协同记忆网络(CMN)，这是一种将两类CF模型结合起来的深层体系结构。在记忆网络成功的激励下，我们将记忆构件与神经注意机制融合为邻域构件。记忆模块中与用户和项记忆的关联寻址方案，结合神经注意机制，对复杂的用户-项关系进行编码，以学习用户-项特定的邻域。最后，输出模块与用户和项目内存共同利用邻域来生成排名分数。将多个记忆模块叠加在一起可以产生更深层次的体系结构，从而捕获日益复杂的用户-项目关系。此外，我们还展示了CMN组件、内存网络和三类CF模型之间的强大连接。综合实验结果表明，CMN在三个公共数据集上的有效性优于竞争基线。注意力权重的定性可视化提供了对模型srecommendation过程的深入了解，并表明存在更高阶的交互
