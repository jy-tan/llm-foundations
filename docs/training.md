# Training & Optimization

The optimization techniques and objectives used to train language models from scratch. This includes optimizers, learning rate schedules, pretraining objectives (masked language modeling, next-token prediction), and techniques for stable training at scale. Understanding these fundamentals is essential for anyone training or debugging large models.

## Optimizers

<table>
  <tr>
    <th>Title</th>
    <th>Authors</th>
    <th>Year</th>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/1412.6980">Adam: A Method for Stochastic Optimization</a></td>
    <td>Kingma et al.</td>
    <td>2014</td>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/1711.05101">Decoupled Weight Decay Regularization</a></td>
    <td>Loshchilov et al.</td>
    <td>2017</td>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/1804.04235">Adafactor: Adaptive Learning Rates with Sublinear Memory Cost</a></td>
    <td>Shazeer et al.</td>
    <td>2018</td>
  </tr>
  <tr>
    <td><a href="https://kellerjordan.github.io/posts/muon/">Muon: An optimizer for hidden layers in neural networks</a></td>
    <td>Jordan et al.</td>
    <td>2024</td>
  </tr>
</table>

## Learning rate schedulers

<table>
  <tr>
    <th>Title</th>
    <th>Authors</th>
    <th>Year</th>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/1810.04805">BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding</a></td>
    <td>Devlin et al.</td>
    <td>2018</td>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/1608.03983">SGDR: Stochastic Gradient Descent with Warm Restarts</a></td>
    <td>Loshchilov et al.</td>
    <td>2016</td>
  </tr>
</table>

## Pretraining objectives

<table>
  <tr>
    <th>Title</th>
    <th>Authors</th>
    <th>Year</th>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/1810.04805">BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding</a></td>
    <td>Devlin et al.</td>
    <td>2018</td>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/1910.10683">Exploring the Limits of Transfer Learning with a Unified Text-to-Text Transformer</a></td>
    <td>Raffel et al.</td>
    <td>2019</td>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/2205.05131">UL2: Unifying Language Learning Paradigms</a></td>
    <td>Tay et al.</td>
    <td>2022</td>
  </tr>
</table>

## Stability & precision

<table>
  <tr>
    <th>Title</th>
    <th>Authors</th>
    <th>Year</th>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/1710.03740">Mixed Precision Training</a></td>
    <td>Micikevicius et al.</td>
    <td>2017</td>
  </tr>
</table>
