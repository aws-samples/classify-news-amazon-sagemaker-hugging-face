## Bring your own data to classify news with Amazon SageMaker and Hugging Face

In this [example notebook](./byod-news-sm-sf.ipynb), we explore how to bring your own data for a Text Classification task, by fine-tuning and deploying SOTA models with Amazon SageMaker, the Hugging Face containers, and the SageMaker Python SDK.

![](./images/arch.png)

We also rely on the library of pre-trained models available in Hugging Face. We will demonstrate how you can bring your own custom data to fine tune the models, and use the processing scripts available in the Hugging Face hub for speeding up the process on tasks such as tokenization and data loading. Finally, we will deploy the model to a SageMaker endpoint and perform real-time inferences with sample phrases on our text classification use case.

For more details on this example check the AWS ML Blog post: [here](LINK)

Note this example uses the AG News dataset cited in the paper [Character-level Convolutional Networks for Text Classification](https://arxiv.org/abs/1509.01626) by Xiang Zhang and [Yann LeCun](https://twitter.com/ylecun). This dataset is available on the [AWS Open Data Registry](https://registry.opendata.aws/fast-ai-nlp/).

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.

