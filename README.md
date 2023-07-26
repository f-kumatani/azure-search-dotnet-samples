# C# samples for Azure Cognitive Search fundamentals

This repository contains C# code samples used in Azure Cognitive Search "Day One" quickstarts and tutorials. Unless noted otherwise, all samples run on the shared (free) pricing tier of an [Azure Cognitive Search service](https://learn.microsoft.com/azure/search/search-create-service-portal).

## In this repository

| Sample | Description |
|--------|-------------|
| quickstart-full-text | Learn the fundamental tasks of working with a search index: create, load, and query for full text search scenarios. This quickstart is a .NET Core console application. The index is modeled on a subset of the Hotels dataset, widely used in Cognitive Search samples, but reduced here for readability and comprehension. |
| quickstart-semantic-search | Adds semantic search to the previous quickstart.|
| tutorial-skills-enrichment | This .NET Core console app creates an AI enrichment pipeline consisting of an index, indexer, data source, and skillset. The skillset calls Azure Cognitive Services image analysis and OCR, and natural language processing, extract information and structure from heterogeneous blob content, making it searchable in Azure Cognitive Search. |
| tutorial-create-mvc-app | This ASP.NET Core MVC sample demonstrates server-side search behaviors, such as filters and sorting. |
| tutorial-search-website-functions-v4 | This sample builds a website to search through a catalog of books then deploys the website to an Azure Static Web App. The search experience includes a React app for the front-end. This app includes a search bar for free text queries, suggestions for type-ahead queries, and document lookup. |

## Previously in this repository

The following samples are relocated to new repositories that align content to specific categories. 

| Sample | New location |
|--------|--------------|
| check-storage-usage | [azure-search-dotnet-utilities](https://github.com/Azure-Samples/azure-search-dotnet-utilities/check-storage-usage) |
| data-lake-gen2-acl-indexing | [azure-search-dotnet-utilities](https://github.com/Azure-Samples/azure-search-dotnet-utilities/data-lake-gen2-acl-indexing) |
| export-data | [azure-search-dotnet-utilities](https://github.com/Azure-Samples/azure-search-dotnet-utilities/export-data) |
| index-backup-restore | [azure-search-dotnet-utilities](https://github.com/Azure-Samples/azure-search-dotnet-utilities/index-backup-restore)|
| search-aggregations |  [azure-search-dotnet-utilities](https://github.com/Azure-Samples/azure-search-dotnet-utilities/search-aggregations)|

## More resources

See [.NET samples in Azure Cognitive Search](https://learn.microsoft.com/azure/search/samples-dotnet) for a comprehensive list of all Azure Cognitive Search code samples that run on .NET.

See [Azure Cognitive Search documentation](ttps://learn.microsoft.com/azure/search) for product documentation.
