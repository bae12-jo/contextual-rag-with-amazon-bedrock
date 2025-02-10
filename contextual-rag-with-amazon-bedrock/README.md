# Contextual RAG Workshop

This project implements [Contextual Retrieval Augmented Generation (RAG)](https://www.anthropic.com/news/contextual-retrieval) system as introduced by Anthropic, using Amazon Bedrock, Amazon OpenSearch Service and Amazon Bedrock Reranker Model.

## Useful commands

## Installation
1. Clone this repository
2. Deploy CDK stack
```bash
npm i --save-dev @types/node
cdk bootstrap
cdk synth
cdk deploy --all --require-approval never
```
3. Install dependencies
```bash
pip install -r requirements.txt
```

## Usage
1. Go to Amazon SageMakerAI on your AWS Management Console.
2. Open Notebook named 'contextual-rag-workshop-instance'
3. Move to 
```bash
cd ~~
```