# EzCommit

## Introduction
EzCommit is a CLI tool that helps you automatically generate commit message, pull request description and summarize changes using LLM with Retrieval Augmented Generation.

## Setup
To install, type **pip install ezcommit**. If the process do not succeed, you can install the dependant packages manually with the specs in "requirements.txt".

To initialize EzCommit in your repo, type "ezcommit --init".

## Main features
- Generate commit message: "ezcommit --gen-cmt" / "ezcommit --gen-cmt -fast" to run with / without RAG.
- Generate pull request description: "ezcommit --gen-pr"
- Summarize change: "ezcommit --sum"
- Visualize commit history: "ezcommit --visual"
- Set convention: "ezcommit --convention-path \<path-to-convention-file\>"

## Framework
The project is developed using **Click** as CLI framework and **chromadb** for RAG.
