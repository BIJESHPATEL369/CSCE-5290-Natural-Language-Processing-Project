# CSCE-5290-Natural-Language-Processing-Project

The [Amazon KDD](https://www.aicrowd.com/challenges/esci-challenge-for-improving-product-search) cup Challenge is project with platform to apply Natural Language processing concepts to practical usage. The challenge has three sub tasks, each dealing with different problems. Of the diverse tasks listed out for the challenge, two of the three tasks have been implemented with the possibility of applying the theoretical aspects learned thus far. 

## Task 1
The input will contain the user query, and the output will be products for each Query that will be ranked based on the most relevant ones.

## Task 2
The input will be product and Query pair along with product features like product title, description, brand, color, locale, etc., and the target labels will be following four categories:
* Exact: the most relevant product from the Query.
* Substitute: somewhat suitable product from the Query.
* Complement: the product will be mapped with other products to match the Query.
* Irrelevant: Product that is not relevant to the Query.

## Instructions to execute task 2 code:
1. open the notebook in Google Colab with the link available on top of the file "Increment_2_Task_2_Muticlass_Product_Classification_Final.ipynb".
2. Connect to GPU (required high Gpu ==> colab pro)
3. Execute the notebook(datasets are pre-loaded within the notebooks)
