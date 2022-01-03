**Ball Possession**

**Table of Contents**

- Summary
- Motivation
- Data Question
- Key Findings
- Known Issues and Challenges
- Technologies
- Sources

**Summary**

This is the capstone project for my Data Analytics course at the Nashville Software School.

Ball possession has become an increasingly popular measure in soccer broadcasting. Statistics about the ball possession of each team are displayed regularly. But what does ball possession tell a viewer about the quality of each team? What other factors does ball possession influence? The Major League Soccer 2021 season will be analyzed to answer these questions.

**Motivation**

The debate around ball possession in soccer has dramatically increased in recent years. It started with the Spanish &quot;tiki-taka, &quot;which became &quot;viral&quot; thanks to Pep Guardiola&#39;s FC Barcelona&#39;s aerial victories and the Spanish national team.

The perception of the importance of ball possession is not so recent, though. One of the foremost popularizers was undoubtedly the Dutch legend Johan Cruijff. Cruijff&#39;s Ajax, Holland, and Barcelona have revolutionized soccer in many ways, ball possession included. Johan Cruijff used to say, &quot;Without the ball, you can&#39;t win. If we have the ball, they can&#39;t score. &quot;

I decided to investigate ball possession in the Major League Soccer Season 2021 to assess any correlation with other statistics and, ultimately, team success.

**Data Question**

1. Is there a correlation between ball possession and passes taken by a team?
2. Can we find that ball possession is a good indicator for the outcome of a game?
3. Do high ball possession and a higher passing rate leads to more positive team outcomes?

**Key Findings**

It is true that higher ball possession teams also have more passes. Or that teams that pass more have higher ball possession.

![](Assets/ballpossessionpasses.png)

However, ball possession tells little about the outcome of a game. There is little evidence that higher ball possession leads to fewer goals against, more goals scored, and more fouls received.

![](Assets/ballpossessionga.png)

![](Assets/ballpossessionfouls.png) ![](Assets/ballpossessiongoals.png)

The same can be said about the number of passes a team takes. More passes are not leading to more goals for a team or fewer goals against.

![](Assets/gapasses.png) ![](Assets/goalspasses.png)

**Known Issues and Challenges**

Large Excel files that cover all events from all Major League Soccer seasons from 1996 to 2021.

Limitations in the use of APIs.

It was rather difficult to scrape the MLS webpage.

**Technologies**

- Python (Pandas)
- Jupyter notebooks
- PowerBI
- Excel

**Sources**

- [https://www.mlssoccer.com/stats/clubs/](https://www.mlssoccer.com/stats/clubs/)
- [https://www.mlssoccer.com/stats/players/](https://www.mlssoccer.com/stats/players/)
- [https://www.kaggle.com/josephvm/major-league-soccer-dataset?select=matches.csv](https://www.kaggle.com/josephvm/major-league-soccer-dataset?select=matches.csv)
