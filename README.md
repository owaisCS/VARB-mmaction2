<div align="center">
<h1>Video Action Recognition Benchmark (VARB)</h1>
</div>

## Video Action Recognition & Need for a Benchmark

Video action recognition is one of the major challenges in visual scene understanding. With the advent of deep learning (DL), research in this field has witnessed significant improvements over the last decade where the deep models learn higher dimensional video representation that helps classifying actions. Although there has been a remarkable progress, the lack of any unified evaluation makes it difficult to gauge the potential of the various contributing factors viz. sensitive hyperparameters, pretraining datasets, size of downstream datasets and transfer learning algorithm (full-network, linear or limited fine-tuning). 

## What is VARB?

- VARB stands for Video Action Recognition Benchmark
- VARB provides a comprehensive study of transfer learning for video action recognition
- Through VARB, we analyze $6$ different video activity recognition models, starting from the simpler ones like $2$-D CNNs to the more intricate ones like $3$-D CNNs and transformer architectures ($2$-D and $3$-D).
- For evaluation, VARB uses $14$ publicly available action recognition datasets with videos from $7$ distinct domains namely daily actions, sports, actions in the dark, indoor actions, masked-depth actions and construction actions.
- VARB introduces a new dataset _Construction-Actions_ by trimming and manually annotating activity videos of construction sites from YouTube-8M.
- VARB bridges a significant gap in video action recognition research by bringing different action recognition models and datasets to a standard benchmark

## Setup

