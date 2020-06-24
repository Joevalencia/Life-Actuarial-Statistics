# Life-Actuarial-Stats
This quick Jupyter Notebook aims to introduce some basic concepts of Actuarial Statistics, particularlly life actuarial.<br>

## *Introduction*
When defining **Actuarial Science** we mean that discipline in which the risks assumed by insurance and financial entities are evaluated through the application of statistical and mathematical techniques. So, in this subject the main scope refers to assessing *financial risks* specially into insurance industry using quantitative tools opportunely reliables. <br>
Of course, there are a lot of fields in which this topic has evolved over the course of years. For instance: Casualty issues, Pensions, Reinsurance and many others. Nowadays, being straightforward, since the dawn of **The Industrial Revolution** we have witnessed an upward trend in <font color='red'>**Life Expectancy Worlwide**</font>. Moreover, science progress has brought a widespread of benefits in lifestyle of Mankind. As a matter of fact, there has been a secular tendency to work less and increase productivity, increasing leisuring. It is for this reason that the various jurisdictions were able to adopt retirement policies thanks to detailed **Demographic Studies** as well.<br> As some Europe Populations are struggling with aging and a negative gap in births, others Continents such as Africa are facing high rates but as a result of other factors their Life Expectancy is quite far from the Occidental one. To some extent, aging features such as Schooling or GDP are relevant in which *Spock* would have said <font color='green'>**"Life long and prosper"**</font>.   <br> In this brief Jupyter Notebook we are going to intruduce some basic concepts of Life Actuarial Statistics hoping make clear ideas through Python and its powerful libraries.<br>
## Biometric model**
The Basic Biometric model is a stochastic model defined around a random variable $X$ that we call the **age of death** of the individual. <br> Therefore, $X$ is a variable defined in the set of **positive real numbers**, although in the practical constructions it accepts the existence of an actuarial infinite or actuarial age denoting as $\omega$. The information referring to the age of death in census studies or samples of specific populations refers to the complete years that the deceased has lived, so it would be much more reasonable to treat $X$ as a discrete variable though. <br> Both approach are conciliables and they only conduct to slight divergencies indeed.<br>

**Basic Hypotesis of Biometric Model**<br>
**1.Homogenity** : Individuals form up a homogeneous group, that is, the statistical behavior of their age of death is identical.<br>
**2.Independence** : The variables that describe the ages of death of the different individuals they are statistically independent. <br>
**3.Stationarity** : The biometric properties of individuals do not depend on their date of birth, but only on their age. This hypothesis is accepted in practice for short periods of time.

Before going any further let's recall some useful **notation**:<br> 
* $X =$ The death's age of the induvidual<br> 
* $x =$ Current age of the individual<br> 
* $T(x)$ or $X$ - $x =$ Residual life at age $x$. It takes values into the interval (0, $\omega$ - $x$)<br>
* $F(x)$ or $P(X \le x) =$ Distribution fuction of the death's age<br>
* $S(x) = P(X > x) = 1 - F(x) =$ Survival function (e.g. I survive at $x$ age)<br>
* $G_{x}(t) = P(T(x) \le t) = P(X - x \le | X > x) = P(X \le x+t | X > x)$ = Distribution function of residual age
[Spain](https://joevalencia.github.io/Life-Actuarial-Stats/Spain.html)

