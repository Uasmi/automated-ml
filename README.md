# Automated ML Lab
Automated ML Lab

## Creating Workspace
Go to https://portal.azure.com and search for Machine Learning and press Create.

<img src="https://githubpics.blob.core.windows.net/automated-ml/mlworkspace_creation.jpg" width="50%">

Choose West or North Europe, and Enterprise for Workspace Edition.

Then switch to https://ml.azure.com/ and press Sign In.
Choose your workspace:

Press **+New** and select a Datastore 

<img src="https://githubpics.blob.core.windows.net/automated-ml/add-datastore.jpg" width="50%">

Enter Datastore name and choose your Blob storage containing the dataset
![](https://githubpics.blob.core.windows.net/automated-ml/aml-creation.gif)

Go to your storage account, copy your Account Key and paste it to the Datastore creation page.

<img src="https://githubpics.blob.core.windows.net/automated-ml/access-keys.jpg" width="50%">

## Running Automated ML
Press **+New** and choose Automated ML Run.

Start off by adding **Dataset** to experiment run, enter a name for it and select a **Datastore** you added before. 

Go to **Path** and choose a **.csv** file. For now, skip other options.

Select added Dataset and press Next.

Then, add a name for an experiment and select **SalePrice** for a target column. 

Create new **Compute Target** (the default is fine). 

Go Next and choose a **Regression**.
![](https://githubpics.blob.core.windows.net/automated-ml/automatedrun.gif)
## Deploying Model

## Testing Performance
