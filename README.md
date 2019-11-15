# Ligue 1 Result Prediction

We are extending present researches in the same field with added parameters which we hope will give us better and more accurate predictions.
In present studies, to predict the future results they have used the past history (rankings in the past years) and in some cases odds 
to predict the future results but in football, the results of past 10 years don't hold as much significance as they used to. Consider a team
like Manchester United, 10 years back they were one of the best teams in the world, now they are fighting for a top 6 place in the Premier League,
same goes for a team like PSG or Monaco or Wolves, who back then were not a known quantity but are now.
In our prediction we have used these as we believe they still hold some value, not as much they used to, but they still have some value, then comes
odds, we have taken odds from 6 different websites, the main difference in our project is we are taking the average quality of each side, which we
believe is the most important factor in prediction, as considering the incredible Ajax season or Monaco season, it's not always about the history but
also about the quality each team possesses, so to do this we will be using FIFA Datasets to get the quality of each side in a particular year. This, we
hope will give better results.

For the case of Odds, they are released before a match every week, this needs to be fetched dynamically and put into the dataset (Schema 3).

## Getting Started

We used Google Colab to allow different team members to work on the same project at the same time and also for better processing power.
So you might want to remove the google colab inclusion part and add your own location for the datasets.

### Prerequisites

These are basic Machine Learning Libraries and may need to be installed if not already installed.

```
python -m pip install -U matplotlib 
pip install pandas
```
Or installation in anaconda environment

```
!python -m pip install -U matplotlib 
!pip install pandas
```
### Installing

*Find our entire architecture of the project in the research paper uploaded
1) In the code folder find Creating_Schema_1.ipynb, run this python code to create our 1st schema.
2) Then run Creating_Schema_1.ipynb to create the 2nd Schema.
3) Then run Schema_3.ipynb to create our 3rd and final schema.
4) Then run Prediction.ipynb to get your prediction (vary the parameters to get different results).

* We are still updating our Web_Mine.ipynb to dynamically add rows to Schema 3 and similarly we are updating
Prediction.ipynb to get prediction dynamically and every week automatically. Any and all help would be appreciated.

## Built With

* [Google Colab](https://colab.research.google.com/) - The online Environment we used to run the code
* Python - Language Used
* Machine Learning Libraries - Used several ML Models to test the accuracy

## Contributing

Please contact any of the initial authors with any ideas and updates you would want to bring to the project.

## Authors

* **Shashanka Shekhar Das** - *Initial work* - [HiTShT](https://github.com/HiTShT)
* **Aneesh Dhanuka** - *Initial work* 
* **Rahul Saw** - *Initial work* 

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Dr. G. Suganya for all the help and guidance in every part of the project.
