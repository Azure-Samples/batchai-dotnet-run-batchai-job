---
services: Batch-AI
platforms: dotnet
author: yaohaizh
---

# Getting started on creating a Batch AI cluster and executing an AI job using C# #

          Azure Batch AI sample.
           - Create Storage account and Azure file share
           - Upload sample data to Azure file share
           - Create a workspace and experiment
           - Create Batch AI cluster that uses Azure file share to host the training data and scripts for the learning job
           - Create Microsoft Cognitive Toolkit job to run on the cluster
           - Wait for job to complete
           - Get output files
         
          Please note: in order to run this sample, please download and unzip sample package from <a href="https://batchaisamples.blob.core.windows.net/samples/BatchAIQuickStart.zip?st=2017-09-29T18%3A29%3A00Z&se=2099-12-31T08%3A00%3A00Z&sp=rl&sv=2016-05-31&sr=b&sig=hrAZfbZC%2BQ%2FKccFQZ7OC4b%2FXSzCF5Myi4Cj%2BW3sVZDo%3D">here</a> 
          Export path to the content to $SAMPLE_DATA_PATH.


## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-net/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/batchai-dotnet-run-batchai-job.git

    cd batchai-dotnet-run-batchai-job
  
    dotnet build
    
    bin\Debug\net452\ManageBatchAI.exe

## More information ##

[Azure Management Libraries for C#](https://github.com/Azure/azure-sdk-for-net/tree/Fluent)
[Azure .Net Developer Center](https://azure.microsoft.com/en-us/develop/net/)
If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.