Bangalore Metropolitain Transport Corporation Network Data
====

[Bangalore Metropolitan Transport Corporation](https://en.wikipedia.org/wiki/Bangalore_Metropolitan_Transport_Corporation) operates over 2000 routes. We [scraped](https://github.com/openbangalore/bmtc) some of the data to understand this network better.
This repository is a collection of scripts to run analysis and data derived from them.

Maps
====

![](https://cloud.githubusercontent.com/assets/371666/12720005/69b1df2c-c91e-11e5-8e7f-b3c26bfc939d.png)

*This map shows bus stops and frequency of their routes. Evidently, north Bangalore has less routes but more frequency while south Bangalore has many routes which are less frequent. [View interactive map.](https://www.mapbox.com/bites/00212/)*

![](https://cloud.githubusercontent.com/assets/371666/12720007/6c6d93e6-c91e-11e5-95b5-b42ba20a2702.png)

*BMTC operates many long routes. The longest is route 600 with 117 km and takes over 5 hours. [View interactive map.](https://api.mapbox.com/styles/v1/geohacker/cik0utr150130bfm2jjfto236.html?title=true&access_token=pk.eyJ1IjoiZ2VvaGFja2VyIiwiYSI6ImFIN0hENW8ifQ.GGpH9gLyEg0PZf3NPQ7Vrg#10.88/12.9119/77.6292)*

![](https://cloud.githubusercontent.com/assets/371666/12720015/705d6b70-c91e-11e5-9213-5b3b0ae2fbbe.png)

*Routes 401M, 252F, 96G are the most frequent with 217 trips every day. [View interactive map.](https://api.mapbox.com/styles/v1/geohacker/cik1h9fwu017kbpm3t34v9hw3.html?title=true&access_token=pk.eyJ1IjoiZ2VvaGFja2VyIiwiYSI6ImFIN0hENW8ifQ.GGpH9gLyEg0PZf3NPQ7Vrg#12.07/12.9703/77.5287)*

![](https://cloud.githubusercontent.com/assets/371666/12720017/723352de-c91e-11e5-965a-7b512512729e.png)

*Most routes start from Krishnarajendra Market as opposed the notion that is Kempegowda Bus Station.*

![screen shot 2016-02-01 at 18 37 14](https://cloud.githubusercontent.com/assets/371666/12720023/75fb220c-c91e-11e5-9e52-7952cacc6405.png)

*North - South and East - West routes are equally distributed. [View interactive map.](https://api.mapbox.com/styles/v1/geohacker/cik2wox7a01aecakwuqhzae39.html?title=true&access_token=pk.eyJ1IjoiZ2VvaGFja2VyIiwiYSI6ImFIN0hENW8ifQ.GGpH9gLyEg0PZf3NPQ7Vrg#10/12.9862/77.5808)*

![](https://cloud.githubusercontent.com/assets/371666/12815760/4ec9a116-cb6e-11e5-8498-235cf7e628e1.png)

*2 (blue) series and 3 (green) series routes cover ~76% of the entire BMTC network. [View interactive map.](https://api.mapbox.com/styles/v1/geohacker/cik512qjx006l9um6tn14khq5.html?title=true&access_token=pk.eyJ1IjoiZ2VvaGFja2VyIiwiYSI6ImFIN0hENW8ifQ.GGpH9gLyEg0PZf3NPQ7Vrg#9.86/12.9837/77.5740)*

![](http://i.imgur.com/l6hqX9p.gif)

*2 series routes coverage*

![screen shot 2016-02-04 at 5 50 33 pm](https://cloud.githubusercontent.com/assets/371666/12845827/91a5a94c-cc2e-11e5-9a45-1c0fb69c28b3.png)

*Node density - number of bus stops passing through a stop. [View interactive map](https://api.mapbox.com/styles/v1/arunasank/cik7yec2z00iv9um6nnanuexa.html?title=true&access_token=pk.eyJ1IjoiYXJ1bmFzYW5rIiwiYSI6ImRKNlNQa3MifQ.SIx-g-J1oWWlP4grTXopcg#11.01/12.9548/77.5782)*

![screen shot 2016-02-05 at 16 01 41](https://cloud.githubusercontent.com/assets/371666/12845786/54721060-cc2e-11e5-92a7-8c92b54f35b1.png)

*Reachability - destinations you can get to from a stop without switching. [View interactive map.](https://api.mapbox.com/styles/v1/geohacker/cik98dpzk0005cilxrc9fhiih.html?title=true&access_token=pk.eyJ1IjoiZ2VvaGFja2VyIiwiYSI6ImFIN0hENW8ifQ.GGpH9gLyEg0PZf3NPQ7Vrg#10.8/12.9915/77.5707)*