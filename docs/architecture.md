# Architecture

The architectural choices that define how language models process and generate text. This section covers the Transformer and its variants, attention mechanisms, positional encodings, normalization strategies, and alternative architectures like state space models. These papers establish the fundamental building blocks that determine a model's capabilities and efficiency.

## Core Designs

<table>
  <tr>
    <th>Title</th>
    <th>Authors</th>
    <th>Year</th>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/1706.03762">Attention Is All You Need</a></td>
    <td>Vaswani et al.</td>
    <td>2017</td>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/2005.14165">Language Models are Few-Shot Learners</a></td>
    <td>Brown et al.</td>
    <td>2020</td>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/2302.13971">LLaMA: Open and Efficient Foundation Language Models</a></td>
    <td>Touvron et al.</td>
    <td>2023</td>
  </tr>
</table>

### Mixture-of-Experts

<table>
  <tr>
    <th>Title</th>
    <th>Authors</th>
    <th>Year</th>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/1701.06538">Outrageously Large Neural Networks: The Sparsely-Gated Mixture-of-Experts Layer</a></td>
    <td>Shazeer et al.</td>
    <td>2017</td>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/2101.03961">Switch Transformers: Scaling to Trillion Parameter Models with Simple and Efficient Sparsity</a></td>
    <td>Fedus et al.</td>
    <td>2021</td>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/2112.06905">GLaM: Efficient Scaling of Language Models with Mixture-of-Experts</a></td>
    <td>Du et al.</td>
    <td>2022</td>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/2401.04088">Mixtral of Experts</a></td>
    <td>Jiang et al.</td>
    <td>2024</td>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/2405.04434">DeepSeek-V2: A Strong, Economical, and Efficient Mixture-of-Experts Language Model</a></td>
    <td>DeepSeek-AI</td>
    <td>2024</td>
  </tr>
</table>

## Components

### Positional encodings

<table>
  <tr>
    <th>Title</th>
    <th>Authors</th>
    <th>Year</th>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/2104.09864">RoFormer: Enhanced Transformer with Rotary Position Embedding</a></td>
    <td>Su et al.</td>
    <td>2021</td>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/2108.12409">Train Short, Test Long: Attention with Linear Biases Enables Input Length Extrapolation</a></td>
    <td>Press et al.</td>
    <td>2022</td>
  </tr>
</table>

### Normalization

<table>
  <tr>
    <th>Title</th>
    <th>Authors</th>
    <th>Year</th>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/1607.06450">Layer Normalization</a></td>
    <td>Ba et al.</td>
    <td>2016</td>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/1910.07467">Root Mean Square Layer Normalization</a></td>
    <td>Zhang et al.</td>
    <td>2019</td>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/2002.04745">On Layer Normalization in the Transformer Architecture</a></td>
    <td>Xiong et al.</td>
    <td>2020</td>
  </tr>
</table>

### Attention variants

<table>
  <tr>
    <th>Title</th>
    <th>Authors</th>
    <th>Year</th>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/1911.02150">Fast Transformer Decoding: One Write-Head is All You Need</a></td>
    <td>Shazeer</td>
    <td>2019</td>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/2305.13245">GQA: Training Generalized Multi-Query Transformer Models from Multi-Head Checkpoints</a></td>
    <td>Ainslie et al.</td>
    <td>2023</td>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/2004.05150">Longformer: The Long-Document Transformer</a></td>
    <td>Beltagy et al.</td>
    <td>2020</td>
  </tr>
</table>

### Activations

<table>
  <tr>
    <th>Title</th>
    <th>Authors</th>
    <th>Year</th>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/1606.08415">Gaussian Error Linear Units (GELUs)</a></td>
    <td>Hendrycks et al.</td>
    <td>2016</td>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/2002.05202">GLU Variants Improve Transformer</a></td>
    <td>Shazeer</td>
    <td>2020</td>
  </tr>
</table>

### Efficient attention

<table>
  <tr>
    <th>Title</th>
    <th>Authors</th>
    <th>Year</th>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/2205.14135">FlashAttention: Fast and Memory-Efficient Exact Attention with IO-Awareness</a></td>
    <td>Dao et al.</td>
    <td>2022</td>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/2307.08691">FlashAttention-2: Faster Attention with Better Parallelism and Work Partitioning</a></td>
    <td>Dao</td>
    <td>2023</td>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/2310.01889">Ring Attention with Blockwise Transformers for Near-Infinite Context</a></td>
    <td>Liu et al.</td>
    <td>2023</td>
  </tr>
</table>

## Alternative Architectures

<table>
  <tr>
    <th>Title</th>
    <th>Authors</th>
    <th>Year</th>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/2312.00752">Mamba: Linear-Time Sequence Modeling with Selective State Spaces</a></td>
    <td>Gu et al.</td>
    <td>2023</td>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/2111.00396">Efficiently Modeling Long Sequences with Structured State Spaces</a></td>
    <td>Gu et al.</td>
    <td>2021</td>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/2305.13048">RWKV: Reinventing RNNs for the Transformer Era</a></td>
    <td>Peng et al.</td>
    <td>2023</td>
  </tr>
</table>
