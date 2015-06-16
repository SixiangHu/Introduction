Introduction
========================================================
author: Sixiang Hu
date: 18th Jun, 2015

Wanted
========================================================

- Name      :   Sixiang Hu (Steven) 
- Gender    :   Male
- From      :   Wuhan, China (middle part of China)
- Major (UG):   Maths in Wuhan University 
- Major (PG):   Actuarial Science in Heroit-Watt University

```{r setOptions, echo=FALSE, message=FALSE}
library(googleVis)
options(gvis.plot.tag="chart")
```

Where is so called "middle part of China"?
========================================================

```{r echo=FALSE,results='asis',tidy=FALSE}
Wuhan <- data.frame(LatLong = c("30:114"),Tip = c("This is Wuhan in Hubei Province"))
plot(gvisMap(Wuhan, "LatLong" , "Tip", 
       options=list(showTip=TRUE, 
                    showLine=TRUE, 
                    enableScrollWheel=TRUE,
                    mapType='terrain', 
                    width='800px',
                    height= '600px',
                    zoomlevel = 6,
                    useMapTypeControl=TRUE)))
```

Hobbies
========================================================

- Programming (C, C++, C#/WPF, R, SAS,SQL, JavaScript, etc.)
- Classical Music (Piano)
- PC Games (Adventure, e.g. [Nancy Drew](https://en.wikipedia.org/wiki/Nancy_Drew))
- Castels (e.g. Edinburgh Castel, Arudal Castel, Windsor Castel, etc.)
- And, of cause, R!

***
  ![Nancy Drew](https://upload.wikimedia.org/wikipedia/en/thumb/b/bf/ND1tsotoc.JPG/220px-ND1tsotoc.JPG)
