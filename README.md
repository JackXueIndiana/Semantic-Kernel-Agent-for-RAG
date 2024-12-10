# Semantic-Kernel-Service-for-RAG
This is a simple example on how to use Semantic Kernel to build a RAG with GPT-4o and text-embedding-ada-002 as completion and embedding models and Qdrant Memory Store.

Vector Search Engine Qdrant can be downloaded from https://github.com/qdrant/qdrant and run in local docker environment. The commands worked for me is:
~~~
# Pull the image
docker pull qdrant/qdrant

# Run the service
docker run -p 6333:6333 /path/to/data:/qdrant/storage qdrant/qdrant
~~~

This notebook is initially cloned from https://github.com/microsoft/SemanticKernelCookBook/blob/main/notebooks/python/05/EmbeddingsWithSK.ipynb. Several updates are needed to make it work in SK 1.27.
