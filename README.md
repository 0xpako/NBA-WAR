## General

In the NBA, Wins Above Replacement (WAR) is one of many metrics used to measure player performance. WAR denotes how much better (or worse) a player is when compared to an average level replacement player of the same position. Higher WARs are better, and typically will cluster closer to values in the single digits, with all-star players reaching into the high-20s in exceptional cases.

This tool will allow a user to select a season and then a player from those who played in the NBA that year to see that player's performance to that point plus a five year projection. A season dropdown allows the user to select a new season to see how the projection changes over time.

## Functionality

This is a simple tool to exercise a few functions that are available from HuggingFace. They are:

* [Ingest a datasource from HuggingFace.](https://huggingface.co/datasets/andrewkroening/538-NBA-Historical-Raptor) This dataset was built from a dataset available from [fivethirtyeight.com.](https://github.com/fivethirtyeight/data/tree/master/nba-raptor)

* Use the Prophet package to construct a five-year prediction from the performance of a player up to a designated point (I won't be trying this again with this type of data).

* Set up a HuggingFace Space and use Gradio to deploy a simple web app.

* Add some user functionality to the app to improve experience and engagement.
