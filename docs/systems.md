# Systems

The engineering required to train and serve large models efficiently. This covers distributed training strategies, inference optimization (quantization, speculative decoding, KV cache management), and serving systems for production deployment. These papers turn theoretical models into practical, deployable systems.

## Distributed training

<table>
  <tr>
    <th>Title</th>
    <th>Authors</th>
    <th>Year</th>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/1909.08053">Megatron-LM: Training Multi-Billion Parameter Language Models Using Model Parallelism</a></td>
    <td>Shoeybi et al.</td>
    <td>2019</td>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/1910.02054">ZeRO: Memory Optimizations Toward Training Trillion Parameter Models</a></td>
    <td>Rajbhandari et al.</td>
    <td>2020</td>
  </tr>
</table>

## Inference optimization

<table>
  <tr>
    <th>Title</th>
    <th>Authors</th>
    <th>Year</th>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/2208.07339">LLM.int8(): 8-bit Matrix Multiplication for Transformers at Scale</a></td>
    <td>Dettmers et al.</td>
    <td>2022</td>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/2211.17192">Fast Inference from Transformers via Speculative Decoding</a></td>
    <td>Leviathan et al.</td>
    <td>2022</td>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/2309.06180">Efficient Memory Management for Large Language Model Serving with PagedAttention</a></td>
    <td>Kwon et al.</td>
    <td>2023</td>
  </tr>
</table>

## Serving & deployment

<table>
  <tr>
    <th>Title</th>
    <th>Authors</th>
    <th>Year</th>
  </tr>
  <tr>
    <td><a href="https://www.usenix.org/conference/osdi22/presentation/yu">Orca: A Distributed Serving System for Transformer-Based Generative Models</a></td>
    <td>Yu et al.</td>
    <td>2022</td>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/2308.16369">SARATHI: Efficient LLM Inference by Piggybacking Decodes with Chunked Prefills</a></td>
    <td>Agrawal et al.</td>
    <td>2023</td>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/2401.09670">DistServe: Disaggregating Prefill and Decoding for Goodput-optimized Large Language Model Serving</a></td>
    <td>Zhong et al.</td>
    <td>2024</td>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/2312.07104">SGLang: Efficient Execution of Structured Language Model Programs</a></td>
    <td>Zheng et al.</td>
    <td>2024</td>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/2406.02294">Infinite-LLM: Efficient LLM Service for Long Context with DistAttention and Distributed KVCache</a></td>
    <td>Lin et al.</td>
    <td>2024</td>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/2406.18665">RouteLLM: Learning to Route LLMs with Preference Data</a></td>
    <td>Ong et al.</td>
    <td>2024</td>
  </tr>
</table>
