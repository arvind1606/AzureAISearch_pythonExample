# AzureAISearch_pythonExample
### Azure AI Search (formerly known as "Azure Cognitive Search") is an AI-powered information retrieval platform that helps developers build rich search experiences and generative AI apps that combine large language models with enterprise data.

# Azure AI Search is well suited for the following application scenarios:

###	Use it for traditional full text search and next-generation vector similarity search. Back your generative AI apps with information retrieval that leverages the strength of keyword and similarity search. Use both modalities to retrieve the most relevant results.

###	Consolidate heterogeneous content into a user-defined and populated search index composed of vectors and text. You own and control what's searchable.

###	Integrate data chunking and vectorization for generative AI and RAG apps.

# Key concepts

An Azure AI Search service contains one or more indexes that provide persistent storage of searchable data in the form of JSON documents. (If you're brand new to search, you can make a very rough analogy between indexes and database tables.) The Azure.Search.Documents client library exposes operations on these resources through three main client types.

SearchClient helps with:

Searching your indexed documents using vector queries, keyword queries and hybrid queries
Vector query filters and Text query filters
Semantic ranking and scoring profiles for boosting relevance
Autocompleting partially typed search terms based on documents in the index
Suggesting the most likely matching text in documents as a user types
Adding, Updating or Deleting Documents documents from an index
SearchIndexClient allows you to:

Create, delete, update, or configure a search index
Declare custom synonym maps to expand or rewrite queries
SearchIndexerClient allows you to:
Start indexers to automatically crawl data sources
Define AI powered Skillsets to transform and enrich your data
Azure AI Search provides two powerful features: semantic ranking and vector search.

Semantic ranking enhances the quality of search results for text-based queries. By enabling semantic ranking on your search service, you can improve the relevance of search results in two ways:

It applies secondary ranking to the initial result set, promoting the most semantically relevant results to the top.
It extracts and returns captions and answers in the response, which can be displayed on a search page to enhance the user's search experience.
