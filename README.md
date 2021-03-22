
**In this repository are stored all of data used and obtained through the experiments**

### AGM

Here is presented the solutions for the optimization of AGM PLA

![AGM](https://raw.githubusercontent.com/otimizes/experiment-package-clustering/master/AGM.png)

### BeT

Here is presented the solutions for the optimization of BeT PLA

![BeT](https://raw.githubusercontent.com/otimizes/experiment-package-clustering/master/BET.png)

### K-Means++

Here is presented the solutions to the K-Means++
#### AGM Solutions

![AGM KMEANS](https://raw.githubusercontent.com/otimizes/experiment-package-clustering/master/AGM-KMEANS.png)

#### BeT Solutions

![BeT KMEANS](https://raw.githubusercontent.com/otimizes/experiment-package-clustering/master/BET-KMEANS.png)

### DBSCAN

Here is presented the solutions to the DBSCAN

#### AGM Solutions

![AGM Solutions](https://github.com/otimizes/experiment-package-clustering/blob/master/AGM-DBSCAN.png)

#### BeT Solutions

![AGM Solutions](https://github.com/otimizes/experiment-package-clustering/blob/master/BET-DBSCAN.png)

#### R Scripts

The script used to generate the charts are presented bellow

```sh
// Do not need to normalize because it is betwen 1-5, according the Likert Scale
data <- c(3,4,2,3,4,3,4,5,5,4,4,3,4,4,4,4,3,4)
dm1 <- c(3,4,2,3)
dm2 <- c(4,3,4,4)
dm3 <- c(5,5,4,4)
dm4 <- c(3,4,4,4,4,3,4)

// Standard Deviation
sd(data)
sd(dm1)
sd(dm2)
sd(dm3)
sd(dm4)

// Variance
var(data)
var(dm1)
var(dm2)
var(dm3)
var(dm4)

// Mean
mean(data)
mean(dm1)
mean(dm2)
mean(dm3)
mean(dm4)

// Median
median(data)
median(dm1)
median(dm2)
median(dm3)
median(dm4)


// It uses the shapiro-wik to verify if the data are in normal distribution
shapiro.test(dados)

// Not normal distribution uses Mann-Whitney
wilcox.test(mm_cros,mm_sem) 

---------------------------------------------------------------
// data:  mm_cros and mm_sem
// W = 102, p-value = 0.02229
// alternative hypothesis: true location shift is not equal to 0

// In case p-value lower than 0.05, reject null hypothesis
// If greater, accepts, that is, do not have statistic difference
 
// Boxplot:

boxplot(mm_cros, mm_sem, names=c("crossover","sem crossover"), xlab="mm")
cliff.delta(mm_cros, mm_sem)
```

#### Analysis (PT-Br)

[In this link the analysis about DM answers of forms are described](https://raw.githubusercontent.com/otimizes/experiment-package-clustering/master/AGM-Qualitative-Experiment/Analysis-pt_br.pdf)

#### DM1 - FM

[In this link you can download the form filled in by the DM 1](https://raw.githubusercontent.com/otimizes/experiment-package-clustering/master/AGM-Qualitative-Experiment/DM1-FM.pdf)

[In this link you can download the solutions analyzed by DM 1](https://raw.githubusercontent.com/otimizes/experiment-package-clustering/master/AGM-Qualitative-Experiment/DM1-FM.zip)

#### DM2 - ACLASS

[In this link you can download the form filled in by the DM 2](https://raw.githubusercontent.com/otimizes/experiment-package-clustering/master/AGM-Qualitative-Experiment/DM2-ACLASS.pdf)

[In this link you can download the solutions analyzed by DM 2](https://raw.githubusercontent.com/otimizes/experiment-package-clustering/master/AGM-Qualitative-Experiment/DM2-ACLASS.zip)

#### DM3 - TRADEOFF

[In this link you can download the form filled in by the DM 3](https://raw.githubusercontent.com/otimizes/experiment-package-clustering/master/AGM-Qualitative-Experiment/DM3-TRADEOFF.pdf)

[In this link you can download the solutions analyzed by DM 3](https://raw.githubusercontent.com/otimizes/experiment-package-clustering/master/AGM-Qualitative-Experiment/DM3-TRADEOFF.zip)

#### DM4 - COE

[In this link you can download the form filled in by the DM 4](https://raw.githubusercontent.com/otimizes/experiment-package-clustering/master/AGM-Qualitative-Experiment/DM4-COE.pdf)

[In this link you can download the solutions analyzed by DM 4](https://raw.githubusercontent.com/otimizes/experiment-package-clustering/master/AGM-Qualitative-Experiment/DM4-COE.zip)

#### All PLA alternativas

[Click here if you want to download all PLA alternatives](https://raw.githubusercontent.com/otimizes/experiment-package-clustering/master/AGM-Qualitative-Experiment/pla-alternatives.zip)

OBS: If you want to see the personal informations about DMs, create a pull request with your e-mail and we will be in touch. Best Regards.
