# RAG

Issue:
# 1. masalah dengan sentence-transformers:
## Solusi yang dicoba:
### A. sudah coba diinstall di environment baru dan script di run di environment yang baru tersebut, tetap tidak bisa. error yang muncul:
  Creating vector embeddings...
Error during embedding creation: Could not import sentence_transformers python package. Please install it with `pip install sentence-transformers`.
C:\Users\user\AppData\Local\Temp\ipykernel_13872\1730095962.py:12: LangChainDeprecationWarning: The class `HuggingFaceEmbeddings` was deprecated in LangChain 0.2.2 and will be removed in 1.0. An updated version of the class exists in the :class:`~langchain-huggingface package and should be used instead. To use it run `pip install -U :class:`~langchain-huggingface` and import as `from :class:`~langchain_huggingface import HuggingFaceEmbeddings``.
  embeddings = HuggingFaceEmbeddings(

