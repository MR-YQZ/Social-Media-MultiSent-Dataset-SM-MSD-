# Social-Media-Dataset
This repository contains dataset for the papaer "A Social Media Dataset and H-GNN Based Contrastive Learning Scheme for Multimodal Sentiment Analysis"
We crawled over 100w tweets and used the VGG19 pre-training model to screen out non-emoji pictures, 95% of which were coarsely screened. Then manually filter, retain the graphic dual-modal data, about 40% removed. Next, complex data processing is performed, using tools such as regular expressions to extract emojis from the text, and the embedded text in the emoji is obtained using the PaddleOCR platform and manual correction. So far, all four modal data have been obtained.
Our dataset will be available after accepted. 







# 社会媒体数据集
这个仓库包含了论文"A Social Media Dataset and H-GNN Based Contrastive Learning Scheme for Multimodal Sentiment Analysis"的数据集。
我们爬取了大于100万的推特数据，使用 VGG19预训练模型筛选出非标签图片，95%被初筛。然后手动筛选，保留图文双模态数据，大约去除40%。接下来，进行复杂的数据处理，使用正则表达式等工具从文本中提取表情符号，并使用PaddleOCR平台和人工校正获得表情包中的嵌入文本。目前已经获取了所有四个模态数据。
我们的数据集将在论文被接受后开源。
