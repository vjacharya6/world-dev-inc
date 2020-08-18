# world-dev-inc

This excercise demonstrates some of the most basic features of 

- SQL

- Pandas 

- some regression methods 

- sklearn pipelines and composite estimators

- matplotlib

The focus is on 

- data retrieval, imputation, visualization

- manipulating DataFrames in Pandas

- preprocessing data for machine learning algorithms

- comparing training, validation and test accuracy of basic regression algorithms in sklearn

The machine learning tasks themeselves are rudimentary because making superaccurate predictions is not the goal here. 

The World Bank's Health, Population and Nutrition data can be accessed from Google's *BigQuery* data warehouse. More processed versions are also available at Kaggle and elsewehere. The goal here to show how to get started with raw data. I focus on identifying social, health and population indicators (such as hospital beds per 1000 inhabitants) that have a bearing on maternal child mortality. I focus on indicators whose utility can influence policy decisions. For example, I will not look at per-capita GDP because I don't think "get rich" is a particularly useful policy recommendation and because it influences maternal-child mortality indirectly through other health, population and social indicators. 

I have commented out the parts of the code in _mch.ipynb_ that retrieve data from *BigQuery*. Instead I load data to _mch.ipynb_ from files _country_names.csv_, _indicator_codes_data.csv_ and _maternal_child_health.csv_. 



