# FIFA 2019

## Design in 3NF
[Intro.pdf](https://github.com/ZhijunLiu96/sql_project/blob/master/2%20ER-diagram.pdf)
<img src="https://github.com/ZhijunLiu96/sql_project/blob/master/figure/DR.png">

## ETL Process
> ### Extract: Data Source
>> - [FIFA 2018 Complete Player Dataset: Kaggle](https://www.kaggle.com/thec03u5/fifa-18-demo-player-dataset)
>>> - [Club coach: ClubWorldRanking](https://www.clubworldranking.com/ranking-coaches?wd=16&yr=2019&index=0) 
      (see the [code](https://github.com/ZhijunLiu96/sql_project/blob/master/5%20coach%20scraping.py))
>> - [League and Club: Skysports](https://www.skysports.com/football/teams)(see the [code](https://github.com/ZhijunLiu96/sql_project/blob/master/5%20league%20scraping.py))
>> - [Standing: Skysports](https://www.skysports.com/football/tables)(see the [code](https://github.com/ZhijunLiu96/sql_project/blob/master/5%20standings%20scraping.py))
> ### Transform (see the [code](https://github.com/ZhijunLiu96/sql_project/blob/master/3%20data%20cleaning.Rmd))
>> - Data cleaning
>> - Recalculate 
>> - Impute/Delete missing data
> ### Load 
>> Load the data into database using [Rmd](https://github.com/ZhijunLiu96/sql_project/blob/master/4%203NF%20populate.Rmd)

## Dashboard: Rshiny
> Homepage
<img src="https://github.com/ZhijunLiu96/sql_project/blob/master/figure/1.png" hight = "50%" width = "50%">

>Player
>>Profile

<img src="https://github.com/ZhijunLiu96/sql_project/blob/master/figure/2.png" hight = "50%" width = "50%">

>>Position

<img src="https://github.com/ZhijunLiu96/sql_project/blob/master/figure/2.1.png" hight = "50%" width = "50%">

>>Skills

<img src="https://github.com/ZhijunLiu96/sql_project/blob/master/figure/3.png" hight = "50%" width = "50%">

>Country
>>World Cup

<img src="https://github.com/ZhijunLiu96/sql_project/blob/master/figure/4.png" hight = "50%" width = "50%">

>>Map Explorer

<img src="https://github.com/ZhijunLiu96/sql_project/blob/master/figure/5.png" hight = "50%" width = "50%">

>Leagure

<img src="https://github.com/ZhijunLiu96/sql_project/blob/master/figure/6.png" hight = "50%" width = "50%">

>Pitch

<img src="https://github.com/ZhijunLiu96/sql_project/blob/master/figure/7.png" hight = "50%" width = "50%">
