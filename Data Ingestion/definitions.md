# What is data injestion

Data ingestion is the transportation of data from assorted sources to a storage medium where it can be accessed, used, and analyzed by an organization. The destination is typically a data warehouse, data mart, database, or a document store. Sources may be almost anything — including SaaS data, in-house apps, databases, spreadsheets, or even information scraped from the internet.

## Why is data injection critically important ?
- The data ingestion layer is the backbone of any business analytics software as all downstream reporting and analytics systems rely on consistent and accessible data.

## What are the types of data injections ?
- Batched 
- Realtime Streaming
- Micro Batch Ingestion


### Batched 
- The most common kind of data ingestion is batch processing. Here, the ingestion layer periodically collects and groups source data and sends it to the destination system. Groups may be processed based on any logical ordering, the activation of certain conditions, or a simple schedule. When having near-real-time data is not important, batch processing is typically used, since it’s generally easier and more affordably implemented than streaming ingestion.


### Real Time Streaming 
- Involves no grouping at all. Data is sourced, manipulated, and loaded as soon as it’s created or recognized by the data ingestion layer. This kind of ingestion is more expensive, since it requires systems to constantly monitor sources and accept new information. However, it may be appropriate for analytics that require continually refreshed data.

### Micro Batch Ingestion

