# PNAS


![](https://web-api.textin.com/ocr_image/external/0b8c61009df72c51.jpg)

# Supporting Information for

**Why more social interactions lead to more polarization in** balanced social systems

**Stefan Thurner, Markus** Hofer,and **Jan Korbel**

5 **Corresponding Author** Stefan Thurner.

6 **E-mail**: stefan.thurner@meduniwien.ac.at

# 7 This PDF file includes:

8 Supporting text

9 Figs. S1 to S4

10 Tables S1 to S2

11 SI References

<!-- **Stefan Thurner, Markus Hofer, and Jan Korbel** -->

<!-- 1 of 8 -->

<!-- 12 **Supporting Information Text** -->

**13** **1. Analysis of the polarization measure** $ψ$ 

**14** A. **Minimum** **of the** **polarization** **measure.** We demonstrate that the minimum possible value of $ψ$  is zero, which occurs only 15 when all opinions are identical, given that N is sufficiently big. Since $ψ$  is proportional to the variance of $a_{ij}$ $ψ=0$ when all 16 $a_{ij}$  are identical. For a more dletailed analysis, we consider the two scenarios:

17

1. $a_{ij}=1$ for all $i,j:$ Everyone shares the same opinions.

18

2. $a_{ij}=a$  where $a\neq 1$ :Every pair of nodes disagrees equally.

19

22

To show that the second scenario is not feasible for most parameter values(N,G), we use the maximum number of unique 20 opinion vectors, $2^{G}$ , as an upper bound for the set of opinion vectors satisfying $a_{ij}=a.$  Despite this generous upper bound, if 21 $N>2^{G}$ ,at least two opinion vectors must be identical, resulting in an agreement value of one. All simulations discussed in this paper satisfy the condition $N>2^{G}$ and therefore only scenario 1 can occur.

23 **B. Maximum of the polarization measure.** Since $a_{ij}$  is bounded from below by -1 and from above by 1, we can apply the 24 Bhatia-Davis inequality (1) for variances of X on the interval $[a,b]$ 

25

$$\text {Var}(X)\leq (b-μ)(μ-a)$$

$$27$$

26 where $μ$  represents the mean of the bounded variable. To determine the most conservative estimate for the mean, we set the derivative of the function $f(μ)=(b-μ)(μ-a)$ to zero. Solving $f^{\prime }(μ)=0$ $yields$ $μ^{*}=0$ .Consequently, we haave

28

$$\text {Var}\left(a_{ij}\right)\leq 1\quad \Rightarrow \quad ψ\leq 1.$$

**29**

35

**C. Polarization for independent and identically distributed opinions.** To obtain a reference value for a "random" system,we 30 calculate the polarization in a system with independent and identically distributed opinions. Let $p$  be the probability that an 31 opinion (an element of the opinion vector) is1 and $(-$ the probability that an opinion is $-1$ . Therefore two opinions are 32 identical with probability $q=p^{2}+(-p^{2}$ and different from each other with probability $(1-q)=2p(1-p)$ .The number of 33 identical opinions between two vectors of size G then follows the binomial distribution $B(G,q)$ ,with variance $Gq(1-q)$ .Based 34 on this we can calculate the variance of $a_{ij}$  and finally $ψ$  As expected, $ψ$  is maximal for $p^{*}=1/2,$ resulting in $ψ^{*}=1/G$ .This value is shown as the dotted line in Fig. 1D in the main text.

36

40

**D. Comparison between** $\bar {s}_{i}$ **and** $a_{ij}$ .We use the relative number of matching opinions between two opinion vectors as the 37 foundation for the polarization measure, $ψ$ . Alternatively, one could compare the ideological positions $\bar {s}_{i}$  for all $i$  in the 38 population,e.g. $φ=\text {Avg}\left(\left|s_{i}-s_{j}\right|\right)$ . However,this approach is arguably less informative. For instance, consider the two 39 opinion vectors $\mathbf {s}_{i}=(-1,1,-1)$ and $\mathbf {}_{j}=(-1-11)$ . These vectors share the same ideological position, $\bar {}_{i}=\bar {}_{j}=-\frac {1}{3}$ .As a result, $φ=0,$ even though the two individuals in this example are clearly ideological enemies.

41 In contrast, the relative number of matching opinions between two opinion vectors better captures the polarization in the 42 system. For this example,since $a_{ij}=-\frac {1}{3}$ ,a population evenly split between the opinion vectors $\mathbf {S}_{i}$  and $\mathbf {S}_{j}$  would show a 43 non-zero polarization of $ψ=\frac {1}{36}$ 

# 44 2. Survey Data: Selected Questions and their Ideological Interpretation

47

45 The table below presents the survey questions about political opinions selected for this study. The surveys were conducted 46 by the Pew Research Center in the years 1999, 2004,2011,2014,2015,and 2017,with 985,2000,3029,10013,6004,and 5009participants, respectively.

48

52

Participants were either asked to choose the statement they agreed with more (when presented with two opposing statements) 49 or,in cases where only one statement was shown, to indicate their level of agreement with it. If a question allowed multiple 50 levels of agreement (e.g.,“strongly agree" and “not strongly agree"), we treated both responses as agreement for analytical 51 consistency. If a pparticipant refused to answer, their response was recorded as 0. To standardize responses, we encoded agreement with the liberal position as $-1$  in the opinion vector and agreement with the conservative position as $+1$ .

<!-- **2 of 8** -->

<!-- **Stefan Thurner, Markus Hofer,and Jan Korbel** -->


| Year | ID Liberal Statement | ID Liberal Statement | Conservative Statement |
| --- | --- | --- | --- |
| Efficiency of the Government | Efficiency of the Government | Efficiency of the Government | Efficiency of the Government |
| 1999<br>2004<br>2011<br>2014<br>2015<br>2017 | q9k When something is run by the government, it is usually inefficient and<br>wasteful (disagree)<br>q11a<br>q17a<br>q25a Government often does a better job than people give it credit for<br>q42a<br>q25a | q9k When something is run by the government, it is usually inefficient and<br>wasteful (disagree)<br>q11a<br>q17a<br>q25a Government often does a better job than people give it credit for<br>q42a<br>q25a | When something is run by the government, it is usually inefficient and wasteful (agree)<br>Government is almost always wasteful and inefficient |
| Control of Markets | Control of Markets | Control of Markets | Control of Markets |
| 1999<br>2004<br>2011<br>2014<br>2015<br>2017 | q9i Government regulation of business usually does more harm than<br>good (disagree)<br>q11b<br>q17b<br>q25b Government regulation of business is necessary to protect the public<br>q42b interest<br>q25b | q9i Government regulation of business usually does more harm than<br>good (disagree)<br>q11b<br>q17b<br>q25b Government regulation of business is necessary to protect the public<br>q42b interest<br>q25b | Government regulation of business usually does more harm than good(agree)<br>Government regulation of business usually does more harm than good |
| Social Safety | Social Safety | Social Safety | Social Safety |
| 1999<br>2004<br>2011<br>2014<br>2015<br>2017 | q15e It is the responsibility of the government to take care of people who<br>can't take care of themselves (agree)<br>q11c<br>q17c<br>q25c Poor people have hard lives because government benefits don't go<br>q42c far enough to help them live decently<br>q25c | q15e It is the responsibility of the government to take care of people who<br>can't take care of themselves (agree)<br>q11c<br>q17c<br>q25c Poor people have hard lives because government benefits don't go<br>q42c far enough to help them live decently<br>q25c | It is the responsibility of the government to take care of people who can't take care of themselves (disagree)<br>Poor people today have it easy because they can get government benefits without doing anything in return |
| Social Debt | Social Debt | Social Debt | Social Debt |
| 1999 | q15f The government should help more needy people even if it means<br>going deeper in debt (agree)<br>q11d<br>q17d<br>q25d The government should do more to help needy Americans, even if it<br>q42d means going deeper into debt | q15f The government should help more needy people even if it means<br>going deeper in debt (agree)<br>q11d<br>q17d<br>q25d The government should do more to help needy Americans, even if it<br>q42d means going deeper into debt | The government should help more needy people even if it means going deeper in debt (disagree)<br>The government today can't afford to do much more to help the needy |
| 2004<br>2011<br>2014<br>2015 | q15f The government should help more needy people even if it means<br>going deeper in debt (agree)<br>q11d<br>q17d<br>q25d The government should do more to help needy Americans, even if it<br>q42d means going deeper into debt | q15f The government should help more needy people even if it means<br>going deeper in debt (agree)<br>q11d<br>q17d<br>q25d The government should do more to help needy Americans, even if it<br>q42d means going deeper into debt | The government should help more needy people even if it means going deeper in debt (disagree)<br>The government today can't afford to do much more to help the needy |
| 2017 | q25d | q25d |  |
| Extent of Racial Discrimination | Extent of Racial Discrimination | Extent of Racial Discrimination | Extent of Racial Discrimination |
| 1999<br>2004<br>2011<br>2014<br>2015<br>2017 | q15m Discriminations against blacks are rare today (disagree)<br>q11f<br>q17f<br>q25f Racial discrimination is the main reason why many black people can't<br>q42f get ahead these days<br>q25f | q15m Discriminations against blacks are rare today (disagree)<br>q11f<br>q17f<br>q25f Racial discrimination is the main reason why many black people can't<br>q42f get ahead these days<br>q25f | Discriminations against blacksare rare today (agree)<br>Blacks who can't get ahead in this country are mostly responsible for their own condition |
| Immigration | Immigration | Immigration | Immigration |
| 1999<br>2004<br>2011<br>2014<br>2015<br>2017 | q15n<br>q11g<br>q17g<br>q25g<br>q42g<br>q25g | We should restrict and control people coming into our country to live... more than we do now (disagree)<br>Immigrants today strengthen our country because of their hard work<br>and talents | We should restrict and control people coming into our country to live... more than we do now (agree)<br>Immigrants today are a burden on our country because they take our jobs,housing and health care |
| Military and Diplomacy | Military and Diplomacy | Military and Diplomacy | Military and Diplomacy |
| 1999<br>2004<br>2011<br>2014<br>2015<br>2017 | q15p q11i<br>q17i<br>125i<br>q42h<br>q25i | The best way to ensure peace is through military strength (disagree)<br>Good diplomacy is the best way to ensure peace | The best way to ensure peace is through military strength (agree)<br>The best way to ensure peace is through military strength |
| Profit of Corporations | Profit of Corporations | Profit of Corporations | Profit of Corporations |
| 1999<br>2004<br>2011<br>2014<br>2015<br>2017 | q9p<br>q11n<br>q17n<br>q25i<br>q42i<br>q25n | Business corporations make too much profit (agree)<br>Business corporations make too much profit | Business corporations make too much profit (disagree)<br>Most corporations make a fair and reasonable amount of profit |
| Environmental Regulations | Environmental Regulations | Environmental Regulations | Environmental Regulations |
| 1999<br>2004<br>2011<br>2014<br>2015<br>2017 | q15a<br>q20r<br>q37n<br>q50r<br>q1060<br>q50r | There needs to be stricter laws and regulations to protect the environ-ment(agree)<br>Stricter environmental laws and regulations are worth the cost | There needs to be stricter laws and regulations to protect the environ-ment(disagree)<br>Stricter environmental laws and regulations cost too many jobs and hurt the economy |
| Homosexuality | Homosexuality | Homosexuality | Homosexuality |
| 1999<br>2004<br>2011<br>2014<br>2015<br>2017 | q21e<br>q20u | School boards ought to have the right to fire teachers who are known<br>homosexuals (disagree)<br>Homosexuality is a way of life that should be accepted by society<br>Homosexuality should be accepted by society | School boards ought to have the right to fire teachers who are known homosexuals (agree)<br>Homosexuality is a way of life that should be discouraged in society Homosexuality should be discouraged by society |
| 1999<br>2004<br>2011<br>2014<br>2015<br>2017 | q37u | School boards ought to have the right to fire teachers who are known<br>homosexuals (disagree)<br>Homosexuality is a way of life that should be accepted by society<br>Homosexuality should be accepted by society | School boards ought to have the right to fire teachers who are known homosexuals (agree)<br>Homosexuality is a way of life that should be discouraged in society Homosexuality should be discouraged by society |
| 1999<br>2004<br>2011<br>2014<br>2015<br>2017 | q50u | School boards ought to have the right to fire teachers who are known<br>homosexuals (disagree)<br>Homosexuality is a way of life that should be accepted by society<br>Homosexuality should be accepted by society | School boards ought to have the right to fire teachers who are known homosexuals (agree)<br>Homosexuality is a way of life that should be discouraged in society Homosexuality should be discouraged by society |
| 1999<br>2004<br>2011<br>2014<br>2015<br>2017 | q42m<br>q50u | School boards ought to have the right to fire teachers who are known<br>homosexuals (disagree)<br>Homosexuality is a way of life that should be accepted by society<br>Homosexuality should be accepted by society | School boards ought to have the right to fire teachers who are known homosexuals (agree)<br>Homosexuality is a way of life that should be discouraged in society Homosexuality should be discouraged by society |


<!-- **Stefan Thurner, Markus Hofer, and Jan Korbel** -->

<!-- **3 of 8** -->

**Table S1. Statements and their ideological classification for the calculation of si. Years with identical statements are indicated by brackets.**

# 53 3. Estimation of the average number of close friends

**54**

60

A. **Study** **Selection** **Criteria.** The literature on friendship network sizes employs various definitions, leading to reported network 55 sizes ranging into the hundreds. However, since our analysis focuses only on ties strong enough to influence opinions or reinforce 56 social identity when opinions align, we restrict our scope to close friendships, core discussion networks, and strong ties. These 57 relationships represent an individual's innermost social circle, characterized by frequent interaction and emotional significance. 58 In contrast, broader networks-including acquaintances and weak ties-may facilitate information diffusion but are unlikely to 59 exert the same persuasive influence. By limiting our analysis to the most influential social connections, we ensure that our estimates are directly relevant to the mechanisms under investigation.

<!-- **4 of 8** -->

<!-- **Stefan Thurner, Markus Hofer, and Jan Korbel** -->


| Acronym | Example for the Question Type | Answer Choices | Sources |
| --- | --- | --- | --- |
| ESS | How many people are there with whom you can discuss intimate and personal matters? | [0,1,2,3,4-6,7-9 $10+]$ | (2-7) |
| GSS | From time to time, most people discuss important matters with other people. Look-ing back over the last six months- who are the people with whom you discussed matters important to you? Just tell me their first names or initials. | [0,1,2,3,4,5,6] | (8) |
| SSND | With whom have you discussed important personal matters during the past six months? (in addition to already named people, five new persons at maximum) | [0,1,2,3,4,5] | (9) |
| SCAL | Not counting your relatives, about how many close friends would you say you have? | [$0,1,2,3,4,5,6-9,10+]$ | (10) |
| SCRI | Participants fill in the blank with the first name or initials of up to seven (7) people that they would say are their friends | [0,1,2,3,4,5,6,7] | (11) |
| YGov | For the followving question, by "close friends" we mean people who you trust,look out for youand have your best interests at heart. How many people in your life would you class as close friends? | [0,1,2-3,4-5,,6-10,11-15,<br>16-20,20+] | (12) |


**Table S2. Comparison of survey questions used to measure the size of personal social networks, detailing the question wording, answer** **choices, and sources.**

**61**

B. **Parameter** **Estimation.** When the average number of close friends is not directly available, but counts are provided in bins, 62 we estimate the mean using midpoint estimation for bins with width greater than 1. For a bin $[a,b]$  , the midpoint is $m=\frac {a+b}{2}$ 63 The mean is then approximated as the weighted average of these midpoints. For the last open-ended bin, we assume its width 64 equals that of the preceding bin. If the last closed bin extends from $x_{n-2}$ to $x_{n-1}$ ,we set $x_{n}=x_{n-1}+\left(x_{n-1}-x_{n-2}\right)$ 

65 **C. Logistic** **Regression.** A detailed comparison of individual countries and question types is beyond the scope of this study. 66 Instead, we treat all gathered data points as equivalent, operating under the assumption that a transition from low connectivity 67 to high connectivity occurred around 2008. Based on this premise, we classify the selected data into two categories:“low”and 68 “high” connectivity. To approximate the nature of this transition, we apply logistic regression, which provides a quantitative 69 estimate of how connectivity levels may have shifted over time. This approach allows us to capture the general trend without 70 going into country-specific variations.

# 71 4. Details of the used social opinion model, Ref (13)

72 A. **Model Definition.** In this study, we use a model adapted from (13), which is formulated using social stress functions:

73

$\mathcal {H}^{(i)}=-\frac {α}{G}\sum \mathbf {s}_{i}·\mathbf {s}_{j}+\frac {1-α}{G}$ $\mathbf {s}_{i}·\mathbf {s}_{j}$ rendoi jlj enemy of i

74 Despite being composed solely of dyadic interactions, this model predominantly results in the formation of balanced triads. As 75illustrated in Fig. S1, balanced triads are characterized by either all positive relationships $(+++)$ or one positive and two 76 negative relationships $(+--)$ ,,while unbalanced triads consist of either two positive and one negative relationship ( $(++-)$ or all 77 negative relationships $(--)$ .. The prevalence of these triad types within the system is demnonstrated in Fig.S2,which shows 78 the fraction of each of the four triad types as a function of $α$  and $\beta$  in a system with $N=10^{5},$ $k=4$ $γ=0.0,$ and $ε=0.3.$ 

**Balanced Triads** **Unbalanced Triads**

<!-- $+++$ -->
![](https://web-api.textin.com/ocr_image/external/5e31a7cad4a0f5b1.jpg)


![](https://web-api.textin.com/ocr_image/external/5257329c71e5d912.jpg)

<!-- $++-$ -->
![](https://web-api.textin.com/ocr_image/external/74d894cf93d3a4b3.jpg)


![](https://web-api.textin.com/ocr_image/external/8f1e69bbbf45b05a.jpg)

Fig. S1. Illustrations of balanced and unbalanced triads according to social balance theory.

$$79$$

## B. Transformation of the Social Stress Function $H_{i}$ using $s_{i},s_{j}\rightarrow a_{ij}$ .Following (13) the social stress function is defined as

80 $\mathcal {H}^{(i)}=-\frac {α}{G}\sum _{j|j\text {friendofi}}\mathbf {s}_{i}·\mathbf {s}_{j}+\frac {1-α}{G}\sum _{j|j\text {enemyofi}}\mathbf {s}_{i}·\mathbf {s}_{j}$  [1]

81 Here, $α$  is a parameter that balances the contributions from friends and enemies, $G$  is the length of opinion vectors,and 82 $\mathbf {s}_{i}·\mathbf {s}_{j}$  is the social stress between two individuals $i$  and $j$ 

<!-- **Stefan Thurner, Markus Hofer, and Jan Korbel** -->

<!-- **5 of 8** -->

<!-- +++ +-- 1.00 0.75 0.50 0.25 0.00 ++- 1.00 0.75  0.50 0.25 0.00 0 1 2 3 4 5 0 1 2 3 4 5 $\beta$ β β $\beta$ fraction of nodes 0 0.5 1.0 -->
![](https://web-api.textin.com/ocr_image/external/4215422c6a0dd455.jpg)

Fig. S2. Fraction of triads for each of the four types in a system with $N=10^{5}$ $k=4,γ=0.0,\text {and}$ $ε=0.3.$ 

83

To express the cumulative social stress $H^{(i)}$ in terms $a_{ij}$ ,we use the relation

84 $\frac {\mathbf {s}_{i}·\mathbf {s}_{j}}{G}=\frac {1}{G}\left(2n_{ij}-1\right)=a_{ij}$  [2]

85 where $n_{ij}$  is the number of opinions the two opinion vectors $s_{i}$  and $s_{j}$ have in common. Substituting this into Eq. (1),we 86 rewrite the social stress function as

87 $\mathcal {H}^{(i)}=-α$  $<$ $.$ $a_{ij}+(1-α)\sum _{j|\mathrm {j}\text {enemyofi}}a_{ij}$  [3]

90

**88** **C.Comparison with empirical data.** The average friendship degree, $\left\langle k_{+}\right\rangle$ , is an emergent property of our simulations, not a 89 directly controlled parameter. It results from agent interactions within a network defined by the total average degree, $<k>$ &gt;which includes both positive (friendly) and negative (antagonistic) ties.

93

91 To relate model predictions to empirical observations, we perform a two-step procedure. First, we run simulations for a 92 range of total average degrees, $<k>$ . For each simulation, we measure the resulting average friendship degree $\left\langle k_{+}\right\rangle$  and the final polarization $ψ$ . This yields a set of points $\left(\left\langle k_{+}\right\rangle _{i},ψ_{i}\right)$ 

94 Second, we use Gaussian Process Regression to interpolate these points, obtaining a non-parametric Bayesian model for the 95 continuous function, $ψ=f\left(\left\langle k_{+}\right\rangle \right)$ ,mapping friendship degree to system polarization. We note that for all relevant values of 96 $\left\langle k_{+}\right\rangle$ , the standard deviation of this process is less than $2*10^{-3}$ , and we therefore do not discuss it further.

99

97 We then sample from this Gaussian process assuming the average friendship degree, $\left\langle k_{+}\right\rangle$ ,estimated for each year (see 98 SI Section 3). This allows for a direct comparison between the model's polarization predictions and the values derived from political surveys.

# 100 5. Parameter dependence of polarization and group formation

101

102

103

105

107

In Fig. S3 we demonstrate the parameter dependence of the model, with respect to parameters $α$ , $\beta$ , $γ$ , and $E$ . It illustrates how variations in parameters lead to the changes in model outcomes. The first column shows the polarization transition as a function of average positive degree. Higher levels of $α$ , that represent a stronger focus on friendly interactions, shift the 104 transition onset to slightly higher connectivities. A larger $\beta$  value shifts the onset towards lower levels. With respect to $γ$  and $E$ the polarization onset is relatively robust. The second column contains the group size as a function of average positive degree. 106 A similar picture emerges as for the polarization transition. While higher $α$  shifts the transition to the right,higher $\beta$  shifts it to lower values. Results remain relatively constant under a variation of $r$ and e.

<!-- **6 of 8** -->

<!-- **Stefan Thurner, Markus Hofer, and Jan Korbel** -->

108 The third column shows the ppolarization transition over time. It is immediately obvious that all parameters have an effect 109 on the level of polarization. Higher $α$  values lower the polarization level, perfectly in line with intuition. High levels of $\beta$ , $γ$ ,110 and $E$  all increase polarization. This parameter dependence is expected: lower 'tolerance' levels increase polarization, more 111 influencers increase the level of polarization, and, finally, more shortcuts in the small world network help spread polarization 112 easier across larger parts of the network.

<!-- polarization transition group formation comparison with data 0.5 0.3 α 0.6 0.49 $ab$ ·0.50 0.51 Sapout% 2 $4$ 0.1 0.0 0.1 0.5 0.3 $\beta$ β 0.6 2.6 $ab$ $ab$ 2.7 2.8 Sepout% 0.1 0.0 0.1 0.5 0.3 γ 0.6 0.01 2 $4$ $4$ 2 ·0.02 0.03 Sapout% 0.1 0.0 0.1 0.5 0.3 3 0.6 0.150 $4$ ·0.175 0.200 Sepou% 2 $ab$ 0.1 0.0 0.1 2 3 4 5 6 2 3 4 5 6 2000 2008 2016 $\left\langle k_{+}\right\rangle$ $\left\langle k_{+}\right\rangle$ year -->
![](https://web-api.textin.com/ocr_image/external/468b1a9415feb579.jpg)

Fig. S3. Parameter dependence of polarization (ψ) and group formation (percentage of nodes). The first column shows the polarization transition, the second column depicts group formation, and the third column compares model predictions of polarization over time with empirical data. Each row explores the effect of a different model parameter: 'friendliness' (α), 'inverse tolerance' (β), 'influencer density' (γ), and percentage of rewired links in the network $(e)$ . Unless otherwise specified, simulations are conducted with the parameters: $N=10^{5}G=9α=05$ $\beta =2.7,$ $γ=0.02$ $ε=0.175.$ 

<!-- **Stefan Thurner, Markus Hofer, and Jan Korbel** -->

<!-- **7 of 8** -->

# 113 6. Hysteresis of polarization and group formation

114

118

We demonstrate hysteresis by computing the polarization $ψ$  (as in the main text) for networks with varying initial average 115 degrees (Fig. S4, blue circles). To observe the reversal of polarization, we prepare a network in equilibrium at an average 116 degree of $k=16$ (resulting in $\left.\left\langle k_{+}\right\rangle \approx 8.0\right)$ and remove links at random until the desired lower connectivity is reached (Fig. S4, 117 downward triangles). Even without explicit influencers, this depolarization process proceeds smoothly, resembling that of systems initialized directly at $\left\langle k_{+}\right\rangle$ with influencers.

120

119 This hysteresis occurs because politically aligned subgroups emerge in the highly connected, polarized state. These subgroups remain cohesive even as links are removed, effectively acting as influencers that sustain polarization and delay its reversal.

<!-- without influencers $(Y=0\%)$ with influencers $(Y=2\%)$ A reduced to (k+) after polarization C initialized at (k+) 0.5 $ab$ 0.3 0.1 0.5 B D SepOu% 0.3 0.1 3.5 $4.5$ 5.5 3.5 4.5 5.5 $\left\langle k_{+}\right\rangle$ $\left\langle k_{+}\right\rangle$ -->
![](https://web-api.textin.com/ocr_image/external/f51a7ed5cb7f4427.jpg)

**Fig.S4.** Hysteresis of polarization (ψ) and group formation (percentage of nodes) with respect to the average number of positive connections, $\left\langle k_{+}\right\rangle .$  Sub-figures A and B show the system without influencers $(γ=0\%)$ ,while the sub-figures C and D include influencers $(γ=2\%)$ .Blue circles represent simulations where $\left\langle k_{+}\right\rangle$ was set to the displayed value from the beginning. Red downwards triangles represent simulations where $\left\langle k_{+}\right\rangle$ was initially set to 16 and decreased to the displayed value after the system reached a steady state. Simulations were conducted with the parameters: $N=10^{5},G=9,α=0.5,$ $\beta =2.7,$ $ε=0.175.$ 

# 121 References

122

1. R Bhatia, C Davis, A Better Bound on the Variance. The Am. Math. Mon. 107, 353-357 (2000).

123

2. European Social Survey European Research Infrastructure (ESS ERIC), ESS6 - integrated file, edition 2.6 (2023).

124

3. European Social Survey European Research Infrastructure (ESS ERIC), ESS7 - integrated file, edition 2.3 (2023).

125 4. European Social Survey European Research Infrastructure (ESS ERIC), ESS8 - integrated file, edition 2.3 (2023).

126

5.European Social Survey European Research Infrastructure (ESS ERIC), ESS9 - integrated file, edition 3.2(2023).

127 6.European Social Survey European Research Infrastructure (ESS ERIC), ESS10 - integrated file, edition 3.2 (2023).

128

7.European Social Survey European Research Infrastructure (ESS ERIC), ESS11 - integrated file, edition 2.0 (2024).

129 8. TW Smith, M Hout, PV Marsden, General Social Survey, 1972-2016 [Cumulative File]: Version 1 (2017).

130

131

132

9. KN Hampton,R Ling, Explaining communication displacement and large-scale social change in core Networks: A cross-national comparison of why bigger is not better and less can mean more. Information, Commun. & Soc. 16, 561-589(2013).

133 10. American Survey Center, May 2021 american perspectives survey (2021) Accessed: 2025-06-03.

134 11. N Pennington, JA Hall, AJ Holmstrom, The American Friendshipo Project: A report on the status and health of friendship 135 in America. PLOS ONE 19, e0305834 (2024).

137

136 12. How many close friends do Americans have? - today.yougov.com (https://today.yougov.com/topics/society/trackers/ how-many-close-friends-do-americans-have) (2025) [Accessed 12-02-2025].

138

139

13. TM Pham, J Korbel, R Hanel, S Thurner, Empirical social triad statistics can be explained with dyadic homophylic interactions. Proc. Natl. Acad. Sci. **119,** e2121103119 (2022).

<!-- **8 of 8** -->

<!-- **Stefan Thurner, Markus Hofer, and Jan Korbel** -->

