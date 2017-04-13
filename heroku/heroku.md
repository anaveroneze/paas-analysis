# [Heroku](https://www.heroku.com/)

## About

Deployment: public and virtual private\
Scaling: vertical and horizontal\
Basic oficial support: Ruby, Javascript, Java, PHP, Python, Go, Scala, Clojure and Groovy\
Frameworks: Rails, Django, Play, Grails and Flask\
Services: Postgresql and Redis\
Add-ons: 179\
Infrastructure located in: Europe (Ireland) and North America (Northern Virginia)\
Deploy with: **version control**\
Program resources stored in: **slugs**\
Computing environments: **dynos** - *web dynos*, *worker dynos*, *one-off dynos*\
Other programming languages: associate **buildpacks** (git repository)\
Free mode: 1 web dyno and 1 worker dyno, 512GB RAM, sleeps after 30mins inactivity 

## Presented as ...

### HW
Xen virtual machine running on Intel(R) Xeon(R) CPU E5-2670\
8 cores\
cache memory: L1 32KB  L2 256KB  L3 20MB\
RAM: 60GB 

### SW
Ubuntu\
Linux version 3.13.0-105-generic

## Performance monitoring

### top

![topheroku](/topheroku.png?raw=true "top")

Using infrastructure hosted in Europe (3h+)\
System running over: 35 days\
Users currently authenticated to the system: 0\
<!--- Provavelmente sem acesso a essa info ---->
Load average of 5min - 28.65, 10min - 26.60, 15min - 25.82\
CPU usage: 66.7% user processes, 15.4% kernel processes, 11.4% idle, 6.4% software interruption\
 <!--- Wa, tempo para I/O: tempo de CPU esperando a conclusão de operação de entrada/saída no disco (I/O) 
* hi: CPU tempo servindo interrupções de hardware - tem acesso? ---->
RAM: 63GB\
Swap: 64GB\

## Statistical analyzes
|Number threads | Average | Variance | Standard deviation | Coefficient of variation | Minimum time | Maximum time | Margin of error (99%) |
|------ | ------- | -------- | ------------------ | ------------------------ | ------------ | ------------ |------------------------ |
| 1 | 53,800 | 106,960 | 10,342 | 0,192 | 19,096 | 80,329 | 3,806 |
| 2 | 43,747 | 161,423 | 12,705 | 0,290 | 20,534 | 82,698 | 4,675 |
| 4 | 41,269 | 239,306 | 15,470 | 0,375 | 21,128 | 86,640 | 5,692 |
| 8 | 48,645 | 422,833 | 20,563 | 0,423 | 17,499 | 84,516 | 7,567 |

## Performance analysis

| Number threads | Speedup | Efficiency | 
|--------------- | ------- | ---------- |
| 2 | 1,230 | 0,615 |
| 4 | 1,304 | 0,326 |
| 8 | 1,106 | 0,138 |
