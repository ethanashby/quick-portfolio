## Simulating DIII National Cross Country Meets

**Check out our powerpoint presentation [here](/Math154-FinalProject-Slides.pdf)**
**Check out our <a href="https://n8stringham.shinyapps.io/CrossCountry_Simulator/">shiny app simulator</a> for this project.**

I am a Division III Cross Country runner, and much of my time outside of class is spent training 75 miles a week to compete in long distance Cross Country and Track races. Long distance running is notoriously difficult to predict, because performance is highly stochastic and races are influenced by many factors: weather, health, level of competition, etc.

In the running world, athletes spend a lot of time predicting race outcomes and analyzing past races to understand what individuals/teams are favorites, and which teams over/underperform relative to expectations. Along with my classmates and teammates Daniel Rosen and <a href="https://github.com/n8stringham">Nathan Stringham</a>, we took a data-driven approach to this problem, which could provide useful information for evaluating coaches and providing information to recruits.

We scraped publically availble race data over the 2018 and 2019 cross country seasons off of <a href="https://www.tfrrs.org/">TFRRS</a> and adjusted the race times based on course difficulty. Then we modeled each individual athlete's performance using a normal distribution, and drew random times for each athlete. Then times for every runner at the national meet were ranked, simulating a virtual race. Team scores were computed by the place of the top 5 runners, and teams were ranked based on these scores.

Our simulated results indicated the competitive landscape for each year. Teams were classified as overperformers or underperformers based on how many points they beat their expected simulated score by, and how likely they were to beat that score based on empirical probabilities. Carleton and Pomona-Pitzer (my team!) were found to be overperformers over those two seasons, while Carnegie-Mellon profoundly underperformed over those two seasons.

<p align="center">
  <img src="/PPNats.jpg" width="600" height="375">
</p>

This was an especially poigniant project for me, since I got the opportunity to run at the 2019 NCAA DIII National Cross Country Meet. At the meet, I helped our team capture the first national championship in school history. Check out the picture of us with the trophy on the podium above!



