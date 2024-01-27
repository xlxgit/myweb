# Welcome to X-Lab

# Molecular Generation using Bidirectional generation model

__Introduction__:

Deep generative models play significant roles in generating novel molecules during the lead optimization step in drug design. The deep generative model plays an important role in generating new molecules with required structural property. However, most molecular generation models only deal with one-way input information. To solve this limitation, we propose an improved deep learning architecture, which improves the expression and discrimination of molecular structure by embedding BiLSTM in the generator and attention mechanism in the discriminator.

**Methods and Problem**:

The BiLSTM in the generator can capture the relevant information in the molecular sequence and generate the molecular structure with target properties. The attention mechanism in the discriminator improves its ability to distinguish the molecular structure. Through the evaluation indexes such as Tanimoto similarity and MOSES, it is verified that the new generation model has the advantages of generating highly similar and diversified molecular structures, thus enhancing the diversity and medicinal potential of molecular generation, and can explore the known and unexplored regions of chemical space, which provides a promising choice for drug optimization or molecular generation in active molecular generation. Tanimoto similarity measures the similarity between the generated molecule and the target molecule, while MOSES assesses the diversity and medicinal potential of the generated molecule.

**Conclusions**:

The results show that the new model successfully improves the diversity and medicinal potential of molecular production. The model introduces two-way short-term memory network (BiLSTM) and attention mechanism, so that it can better express and distinguish the molecular structure. By capturing information in molecular sequences and paying attention to the key features, it provides a new way to solve the problems of diversity and medicinal potential in the field of molecular generation. Through these innovative technologies, the new model can better express and distinguish the molecular structure, thus improving the diversity and medicinal potential of molecular formation. In addition, the model can also provide useful reference and inspiration for molecular design and generation in other fields, and expand its application potential.


![de_novo.png](attachment:de_novo.png)

**简介**：

深度生成模型在生成新分子方面发挥着重要作用。然而，大多数分子生成模型只处理单向输入的信息。为解决这一限制，《BD-CycleGAN: Innovating CycleGAN model by embedding BiLSTM and attention mechanism to improve structural diversity of de novo molecular generation》提出一种改进的深度学习架构，通过在生成器中嵌入BiLSTM和在判别器中嵌入注意力机制，提高了分子结构的表达能力和判别性。

**方法和问题**：
为解决生成模型只处理单向输入信息的问题，新模型通过引入双向长短时记忆网络（BiLSTM）和注意力机制，提高了生成器和判别器的性能。生成器中的BiLSTM能够捕捉分子序列中的相关信息，并生成具有目标性质的分子结构。判别器中的注意力机制则提高了其对分子结构的判别能力。通过谷本相似度和MOSES等评价指标，验证了新型生成模型具有生成高度相似且多样化分子结构的优势，从而增强了分子生成的多样性和药用潜力，可以探索化学空间的已知和未探索区域，为药物优化或活性分子生成中的分子生成提供了一个很有前途的选择。使用谷本相似度和MOSES等评价指标对模型生成的六组具有不同结构特征的分子进行评估。谷本相似度衡量了生成的分子与目标分子之间的相似性，而MOSES评估了生成的分子的多样性和药用潜力。

**结论**：

结果表明提出的新模型成功地提高了分子生成的多样性和药用潜力。该模型引入了双向长短时记忆网络（BiLSTM）和注意力机制，从而使其能够更好地表达和判别分子结构。通过捕捉分子序列中的关联信息和关注关键特征，为解决分子生成领域中的多样性和药用潜力问题提供了一种新的途径。通过这些创新技术，新模型能够更好地表达和判别分子结构，从而提高了分子生成的多样性和药用潜力。此外，该模型还可为其他领域的分子设计和生成提供有益的借鉴和启示，拓展了其应用潜力。


Return to Research.
