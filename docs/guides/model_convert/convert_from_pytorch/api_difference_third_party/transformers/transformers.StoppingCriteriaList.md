## [仅参数名不一致]transformers.StoppingCriteriaList

### [transformers.StoppingCriteriaList](https://github.com/huggingface/transformers/blob/d625294d79341662784495551abdf45e6cb9372f/src/transformers/generation/stopping_criteria.py#L503)

```python
transformers.StoppingCriteriaList(input_ids: torch.LongTensor, scores: torch.FloatTensor, **kwargs)
```

### [paddlenlp.generation.StoppingCriteriaList](https://github.com/PaddlePaddle/PaddleNLP/blob/e336e78c338d2514ee6c937982ce5d8c960b85ff/paddlenlp/generation/stopping_criteria.py#L72)

```python
paddlenlp.generation.StoppingCriteriaList(input_ids: paddle.Tensor, scores: paddle.Tensor, **kwargs)
```

两者功能一致，仅参数名不一致，具体如下：

### 参数映射

| PyTorch           | PaddlePaddle      | 备注                                     |
| ----------------- | ----------------- | --------------------------------------- |
| input_ids         | input_ids         | 输入(tokens) 的 id 组成的 Tensor。 |
| scores            | logits            | 得分组成的 Tensor，仅参数名不一致。 |
