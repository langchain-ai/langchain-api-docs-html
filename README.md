> [!IMPORTANT]
> API Reference docs have moved to [reference.langchain.com/python/](https://reference.langchain.com/python/) [(source)](https://github.com/langchain-ai/docs)

This repo is decoupled from the api ref build process in [langchain](https://github.com/langchain-ai/langchain/tree/master/docs) but gets absorbed back in [during the Vercel build process](https://github.com/langchain-ai/langchain/blob/395515762e99619e60389b97770e228c8c29017f/docs/Makefile#L104-L106).

Currently, this repo only gets updated when [`api_doc_build.yml`](https://github.com/langchain-ai/langchain/blob/master/.github/workflows/api_doc_build.yml) is kicked off (manually).

> [!IMPORTANT]
> The ref docs build process currently scans the codebase from `master`/`main` for all packages. To freeze, we'll need to make a checkpoint branch from each repo and adjust the build script.
