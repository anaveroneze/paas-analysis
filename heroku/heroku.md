# [Heroku](https://www.heroku.com/)

## About

Deployment: public and virtual private\
Scaling: vertical and horizontal\
Basic oficial support: Ruby, Javascript, Java, PHP, Python, Go, Scala, Clojure and Groovy\
Frameworks: Rails, Django, Play, Grails and Flask\
Services: Postgresql and Redis\
Add-ons: 179\
Infrastructure located in: Europe and North America\
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
