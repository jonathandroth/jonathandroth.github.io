---
title: 
layout: single
classes: wide
permalink: /papers/
---
<br/> 

<!-- Google Tag Manager (noscript) -->
<noscript><iframe src="https://www.googletagmanager.com/ns.html?id=GTM-PNS829G"
height="0" width="0" style="display:none;visibility:hidden"></iframe></noscript>
<!-- End Google Tag Manager (noscript) -->

# <center> Recent Working Papers </center>
- - -

**Evaluating Counterfactual Policies Using Instruments** (with Michal Kolesár and José Luis Montiel Olea). 2025. 
<br/>
<small>[ <a href="#/" onclick="visib('evalcf')">Abstract</a> | [Draft][evalcf] ] </small>

<div id="evalcf" style="display: none; text-align: justify; line-height: 1.2" ><small>

We study settings in which a researcher has an instrumental variable (IV) and
seeks to evaluate the effects of a counterfactual policy that alters treatment
assignment, such as a directive encouraging randomly assigned judges to release more
defendants. We develop a general and computationally tractable framework for
computing sharp bounds on the effects of such policies. Our approach does not
require the often tenuous IV monotonicity assumption. Moreover, for an important
class of policy exercises, we show that IV monotonicity---while crucial for a
causal interpretation of two-stage least squares---does not tighten the bounds on
the counterfactual policy impact. We analyze the identifying power of
alternative restrictions, including the policy invariance assumption used in the
marginal treatment effect literature, and develop a relaxation of this
assumption. We illustrate our framework using applications to quasi-random
assignment of bail judges in New York City and prosecutors in Massachusetts.

</small><br><br/></div>

[evalcf]:{{ site.baseurl }}{% link assets/files/EvaluatingCounterfactualsWithIV.pdf %}


**Testing Monotonicity in a Finite Population** (with Jiafeng Chen and Jann Spiess). 2026 (First version: 2025). 
<br/>
<small>[ <a href="#/" onclick="visib('testingmon')">Abstract</a> | [Draft][testingmon] ] </small>

<div id="testingmon" style="display: none; text-align: justify; line-height: 1.2" ><small>

We consider the extent to which we can learn from a completely randomized experiment whether all individuals have treatment effects that are weakly of the same sign, a condition we call monotonicity. From a classical sampling perspective, it is well-known that monotonicity is not falsifiable. By contrast, we show from the design-based perspective---in which the units in the population are fixed and only treatment assignment is stochastic---that the distribution of treatment effects in the finite population (and hence whether monotonicity holds) is formally identified. We argue, however, that the usual definition of identification is unnatural in the design-based setting because it imagines knowing the distribution of outcomes over different treatment assignments for the same units. We thus evaluate the informativeness of the data by the extent to which it enables frequentist testing and Bayesian updating. We show that frequentist tests can have nontrivial power against some alternatives, but power is generically limited. Likewise, we show that there exist (non-degenerate) Bayesian priors that never update about whether monotonicity holds. We conclude that, despite the formal identification result, the ability to learn about monotonicity from data in practice is severely limited.

</small><br><br/></div>

[testingmon]:{{ site.baseurl }}{% link assets/files/TestingMon.pdf %}




**Testing Mechanisms** (with Soonwoo Kwon). 2025. (First version: 2024) *Conditionally accepted, Review of Economic Studies* <br/>
<small>[ <a href="#/" onclick="visib('testingmechs')">Abstract</a> | [Draft][testingmechs-main] | [R Package][testingmechs-package] ] </small>

<div id="testingmechs" style="display: none; text-align: justify; line-height: 1.2" ><small>

Economists are often interested in the mechanisms by which a treatment affects an outcome. We develop tests for the "sharp null of full mediation" that a treatment D affects an outcome Y only through a particular mechanism (or set of mechanisms) M. Our approach exploits connections between mediation analysis and the econometric literature on testing instrument validity. We also provide tools for quantifying the magnitude of alternative mechanisms when the sharp null is rejected: we derive sharp lower bounds on the fraction of individuals whose outcome is affected by the treatment despite having the same value of M under both treatments ("always-takers"), as well as sharp bounds on the average effect of the treatment for such always-takers. An advantage of our approach relative to existing tools for mediation analysis is that it does not require stringent assumptions about how M is assigned. We illustrate our methodology in two empirical applications.




</small><br><br/></div>
[testingmechs-main]:{{ site.baseurl }}{% link assets/files/TestingMechanisms_Draft.pdf %}

[testingmechs-package]:https://github.com/jonathandroth/TestMechs?tab=readme-ov-file#testmechs




# <center> Published and Forthcoming Papers </center>
- - -

[**Interpreting Event-Studies from Recent Difference-in-Differences Methods**](https://link.springer.com/article/10.1007/s42973-026-00235-x). 2026. *Japanese Economic Review (special issue)*. <br/>
<small>[ <a href="#/" onclick="visib('heteventstudies')">Abstract</a> | [Draft][heteventstudies-draft] ] </small>

<div id="heteventstudies" style="display: none; text-align: justify; line-height: 1.2" ><small>


This note discusses the interpretation of event-study plots produced by recent difference-in-differences methods. I show that even when specialized to the case of non-staggered treatment timing, the default plots produced by software for several of the most popular recent methods do not match those of traditional two-way fixed effects (TWFE) event-studies. The plots produced by the new methods may show a kink or jump at the time of treatment even when the TWFE event-study shows a straight line. This difference stems from the fact that the new methods construct the pre-treatment coefficients asymmetrically from the post-treatment coefficients. As a result, visual heuristics for evaluating violations of parallel trends using TWFE event-study plots should not be immediately applied to those from these methods. I conclude with practical recommendations for constructing and interpreting event-study plots when using these methods.

</small><br><br/></div>
[heteventstudies-draft]:{{ site.baseurl }}{% link assets/files/HetEventStudies.pdf %}


[**Design-Based Uncertainty for Quasi-Experiments**](https://www.tandfonline.com/doi/full/10.1080/01621459.2025.2526700#abstract) (with Ashesh Rambachan). *Forthcoming, Journal of the American Statistical Association*. <br/>
<small>[ <a href="#/" onclick="visib('design-based')">Abstract</a> | [Draft][design-based-arxiv] ] </small>

<div id="design-based" style="display: none; text-align: justify; line-height: 1.2" ><small>
Design-based frameworks of uncertainty are frequently used in settings where the treatment is (conditionally) randomly assigned. This paper develops a design-based framework suitable for analyzing quasi-experimental settings in the social sciences, in which the treatment is at least partially determined by idiosyncratic factors but there are concerns about endogenous selection into treatment. 
In our framework, treatments are stochastic, but units may differ in their probabilities of receiving treatment, thereby allowing for rich forms of selection. 
We provide conditions under which the estimands of popular quasi-experimental estimators correspond to interpretable finite-population causal parameters. 
We characterize the biases and distortions to inference that arise when these conditions are violated. 
These results can be used to conduct sensitivity analyses when there are concerns about selection into treatment. 
Taken together, our results establish a rigorous foundation for quasi-experimental analyses that more closely aligns with the way empirical researchers discuss the variation in the data.
</small><br><br/></div>
[design-based-arxiv]: https://arxiv.org/pdf/2008.00602.pdf


[**(Empirical) Bayes Approaches to Parallel Trends**](https://www.aeaweb.org/articles?id=10.1257/pandp.20241048) (with Soonwoo Kwon). 2024. *AEA P&P* <br/>
<small>[ <a href="#/" onclick="visib('honestbayespp')">Abstract</a> | [Draft][honestbayespp-main] | [Appendix][honestbayespp-appendix] ] </small>

<div id="honestbayespp" style="display: none; text-align: justify; line-height: 1.2" ><small>

We consider Bayes and Empirical Bayes (EB) approaches for dealing with violations of parallel trends. In the Bayes approach, the researcher specifies a prior over both the pre-treatment violations of parallel trends $\delta_{pre}$ and the post-treatment violations $\delta_{post}$. The researcher then updates their posterior about the post-treatment bias $\delta_{post}$ given an estimate of the pre-trends $\delta_{pre}$. This allows them to form posterior means and credible sets for the treatment effect of interest, $\tau_{post}$. In the EB approach, the prior on the violations of parallel trends is learned from the pre-treatment observations. We illustrate these approaches in two empirical applications.



</small><br><br/></div>
[honestbayespp-main]:{{ site.baseurl }}{% link assets/files/BayesHonestDiD_main.pdf %}
[honestbayespp-appendix]:{{ site.baseurl }}{% link assets/files/BayesHonestDiD_appendix.pdf %}


**[Logs with zeros? Some problems and solutions](https://academic.oup.com/qje/article/139/2/891/7473710?utm_source=etoc&utm_campaign=qje&utm_medium=email)** 
[Previously titled "Log-like? Identified ATEs defined with zero-valued outcomes are (arbitrarily) scale-dependent"] (with Jiafeng Chen). 2024. *Quarterly Journal of Economics* <br/>
<small>[ <a href="#/" onclick="visib('log0')">Abstract</a> | [Draft][log0-draft] ] </small>

<div id="log0" style="display: none; text-align: justify; line-height: 1.2" ><small>
When studying an outcome Y that is weakly-positive but can equal zero (e.g., earnings), researchers frequently estimate an average treatment effect (ATE) for a "log-like" transformation that behaves like log(Y) for large Y but is defined at zero (e.g., log(1+Y), arcsinh(Y)). We argue that ATEs for log-like transformations should not be interpreted as approximating percentage effects, since unlike a percentage, they depend on the units of the outcome. In fact, we show that if the treatment affects the extensive margin, one can obtain a treatment effect of any magnitude simply by re-scaling the units of Y before taking the log-like transformation. This arbitrary unit-dependence arises because an individual-level percentage effect is not well-defined for individuals whose outcome changes from zero to non-zero when receiving treatment, and the units of the outcome implicitly determine how much weight the ATE for a log-like transformation places on the extensive margin. We further establish a trilemma: when the outcome can equal zero, there is no treatment effect parameter that is an average of individual-level treatment effects, unit-invariant, and point-identified. We discuss several alternative approaches that may be sensible in settings with an intensive and extensive margin, including (i) expressing the ATE in levels as a percentage (e.g., using Poisson regression), (ii) explicitly calibrating the value placed on the intensive and extensive margins, and (iii) estimating separate effects for the two margins (e.g., using Lee bounds). We illustrate these approaches in three empirical applications.
</small><br><br/></div>

[log0-draft]:{{ site.baseurl }}{% link assets/files/LogUniqueHOD0_Draft_Accepted.pdf %}

**[Efficient Estimation for Staggered Rollout Designs](https://www.journals.uchicago.edu/doi/abs/10.1086/726581)** (with Pedro Sant'Anna). 2023.
*Journal of Political Economy Microeconomics*
<br/>
<small>[ <a href="#/" onclick="visib('staggeredefficient')">Abstract</a> | [Draft][staggeredefficient-arxiv] | Packages: [R][staggeredefficient-package] [Stata][staggeredefficient-stata-package] ]</small>

<div id="staggeredefficient" style="display: none; text-align: justify; line-height: 1.2" ><small>
We study estimation of causal effects in staggered rollout designs, i.e. settings where there is staggered treatment adoption and the timing of treatment is as-good-as randomly assigned. We derive the most efficient estimator in a class of estimators that nests several popular generalized difference-in-differences methods. A feasible plug-in version of the efficient estimator is asymptotically unbiased with efficiency (weakly) dominating that of existing approaches. We provide both t-based and permutation-test-based methods for inference. In an application to a training program for police officers, confidence intervals for the proposed estimator are as much as eight times shorter than for existing approaches.
</small><br><br/></div>

[staggeredefficient-arxiv]: https://arxiv.org/pdf/2102.01291.pdf
[staggeredefficient-package]: https://github.com/jonathandroth/staggered
[staggeredefficient-stata-package]: https://github.com/mcaceresb/stata-staggered



**[Inference for Linear Conditional Moment Inequalities](https://academic.oup.com/restud/advance-article/doi/10.1093/restud/rdad004/6994475)** (with Isaiah Andrews and Ariel Pakes). 2023.
*Review of Economic Studies*
<br/>
<small>[ <a href="#/" onclick="visib('arp')">Abstract</a> | [Draft][arp-draft] |  [Previous version][arp-arxiv-v1] | [Matlab package][arp-code]    ] </small>

<div id="arp" style="display: none; text-align: justify; line-height: 1.2" ><small>
We show that moment inequalities in a wide variety of economic applications have a particular linear conditional structure. We use this structure to construct uniformly valid confidence sets that remain computationally tractable even in settings with nuisance parameters. We first introduce least favorable critical values which deliver non-conservative tests if all moments are binding. Next, we introduce a novel conditional inference approach which ensures a strong form of insensitivity to slack moments. Our recommended approach is a hybrid technique which combines desirable aspects of the least favorable and conditional methods. The hybrid approach performs well in simulations calibrated to Wollmann (2018), with favorable power and computational time comparisons relative to existing alternatives.
</small><br><br/></div>

[arp-draft]:{{ site.baseurl }}{% link assets/files/arp-draft.pdf %}
[arp-draft-v1]:{{ site.baseurl }}{% link assets/files/arp-draft-v1.pdf %}
[arp-supp-v1]:{{ site.baseurl }}{% link assets/files/arp-supp-v1.pdf %}
[arp-code]: https://github.com/jonathandroth/LinearMomentInequalities
[arp-arxiv-v1]: https://arxiv.org/pdf/1909.10062v1.pdf


**[A More Credible Approach to Parallel Trends](https://doi.org/10.1093/restud/rdad018)** 
[Previously titled "An Honest Approach to Parallel Trends"] (with Ashesh Rambachan). 2023.
*Review of Economic Studies*
<br/>
<small>[ <a href="#/" onclick="visib('hpt')">Abstract</a> | [Draft][1] | [Supplement][2] | Packages: [R][hpt-package] [Stata][hpt-package-stata] | [JMP Version (old)][3] ] </small>

<div id="hpt" style="display: none; text-align: justify; line-height: 1.2" ><small>
This paper proposes tools for robust inference in difference-in-differences and event-study designs where the parallel trends assumption may be violated. Instead of requiring that parallel trends holds exactly, we impose restrictions on how different the post-treatment violations of parallel trends can be from the pre-treatment differences in trends ("pre-trends"). The causal parameter of interest is partially identified under these restrictions. We introduce two approaches that guarantee uniformly valid inference under the imposed restrictions, and we derive novel results showing that they have desirable power properties in our context. We illustrate how economic knowledge can inform the restrictions on the possible violations of parallel trends in two economic applications. We also highlight how our approach can be used to conduct sensitivity analyses showing what causal conclusions can be drawn under various restrictions on the possible violations of the parallel trends assumption.
</small><br><br/></div>

[1]: {{ site.baseurl }}{% link assets/files/HonestParallelTrends_Main.pdf %}
[2]: {{ site.baseurl }}{% link assets/files/HonestParallelTrends_Supp.pdf %}
[3]: {{ site.baseurl }}{% link assets/files/roth_jmp_honestparalleltrends_main_jmp_version.pdf %}
[hpt-package]: https://github.com/asheshrambachan/HonestDiD
[hpt-package-stata]: https://github.com/mcaceresb/stata-honestdid#honestdid



**[What's Trending in Difference-in-Differences? A Synthesis of the Recent Econometrics Literature](https://www.sciencedirect.com/science/article/pii/S0304407623001318)** (with Pedro Sant'Anna, Alyssa Bilinski, and John Poe). 2023. *Journal of Econometrics*
<br/>
<small>[ <a href="#/" onclick="visib('did-review')">Abstract</a> | [Draft][did-review-draft] ] </small>

<div id="did-review" style="display: none; text-align: justify; line-height: 1.2" ><small>
This paper synthesizes recent advances in the econometrics of difference-in-differences (DiD) and provides concrete recommendations for practitioners. We begin by articulating a simple set of "canonical" assumptions under which the econometrics of DiD are well-understood. We then argue that recent advances in DiD methods can be broadly classified as relaxing some components of the canonical DiD setup, with a focus on (i) multiple periods and variation in treatment timing, (ii) potential violations of parallel trends, or (iii) alternative frameworks for inference. Our discussion highlights the different ways that the DiD literature has advanced beyond the canonical model, and helps to clarify when each of the papers will be relevant for empirical work. We conclude by discussing some promising areas for future research.
</small><br><br/></div>

[did-review-draft]:{{ site.baseurl }}{% link assets/files/DiD_Review_Paper.pdf %}





**[When Is Parallel Trends Sensitive to Functional Form?](https://www.econometricsociety.org/publications/econometrica/2023/03/01/When-Is-Parallel-Trends-Sensitive-to-Functional-Form)** (with Pedro Sant'Anna). 2023.
*Econometrica*
<br/>
<small>[ <a href="#/" onclick="visib('ptinvariance')">Abstract</a> | [Draft][pt-arxiv] | [Longer version (old)][pt-arxiv-v1] ] </small>

<div id="ptinvariance" style="display: none; text-align: justify; line-height: 1.2" ><small>
This paper assesses when the validity of difference-in-differences depends on functional form. We provide a novel characterization: the parallel trends assumption holds under all strictly monotonic transformations of the outcome if and only if a stronger "parallel trends"-type condition holds for the cumulative distribution function of untreated potential outcomes. This condition for parallel trends to be insensitive to functional form is satisfied if and essentially only if the population can be partitioned into a subgroup for which treatment is effectively randomly assigned and a remaining subgroup for which the distribution of untreated potential outcomes is stable over time. These conditions have testable implications, and we introduce falsification tests for the null that parallel trends is insensitive to functional form.
</small><br><br/></div>

[pt-arxiv]:{{ site.baseurl }}{% link assets/files/2010.04814.pdf %}
[pt-arxiv-v1]:{{ site.baseurl }}{% link assets/files/2010.04814_v1.pdf %}



**[Pre-test with Caution: Event-study Estimates After Testing for Parallel Trends](https://pubs.aeaweb.org/doi/pdfplus/10.1257/aeri.20210236)**. 2022. *American Economic Review: Insights*
<br/>
<small>[ <a href="#/" onclick="visib('pretest')">Abstract</a> | [Draft][pretest-draft] | [Appendix][pretest-appendix] | Packages: [R][pretrends-package] [Stata](https://github.com/mcaceresb/stata-pretrends#pretrends) [Shiny][pretrends-shiny] | [Longer Version (old)][pretest-draft-longer] | [Replication][codeocean-link] ] </small>

<div id="pretest" style="display: none; text-align: justify; line-height: 1.2" ><small>
This paper discusses two important limitations of the common practice of testing for pre-existing differences in trends (''pre-trends'') when using difference-in-differences and related methods. First, conventional pre-trends tests may have low power. Second, conditioning the analysis on the result of a pre-test can distort estimation and inference, potentially exacerbating the bias of point estimates and undercoverage of confidence intervals. I analyze these issues both in theory and in simulations calibrated to a survey of recent papers in leading economics journals, which suggest that these limitations are important in practice.  I conclude with practical recommendations for mitigating these issues.
</small><br><br/></div>

[pretest-draft]:{{ site.baseurl }}{% link assets/files/roth_pretrends_testing.pdf %}
[pretest-appendix]:{{ site.baseurl }}{% link assets/files/roth_pretrends_testing_appendix.pdf %}
[pretest-draft-longer]:{{ site.baseurl }}{% link assets/files/roth_pretrends_testing_longer_version.pdf %}
[pretrends-package]:https://github.com/jonathandroth/pretrends#pretrends
[pretrends-shiny]:https://github.com/jonathandroth/PretrendsPower#pretrendspower
[codeocean-link]: https://codeocean.com/capsule/9953973/tree/v1


**[An Outcome Test of Discrimination for Ranked Lists](https://dl.acm.org/doi/10.1145/3531146.3533102)** (with Guillaume Saint-Jacques and YinYin Yu). 2022. *2022 ACM Conference on Fairness, Accountability, and Transparency (FAccT 2022)*
<br/>
<small>[ <a href="#/" onclick="visib('outcometest')">Abstract</a> | [Draft][outcometest-draft] ] </small>

<div id="outcometest" style="display: none; text-align: justify; line-height: 1.2" ><small>
This paper extends Becker (1957)'s outcome test of discrimination to settings where a (human or algorithmic) decision-maker produces a ranked list of candidates. Ranked lists are particularly relevant in the context of online platforms that produce search results or feeds, and also arise when human decisionmakers express ordinal preferences over a list of candidates. We show that non-discrimination implies a system of moment inequalities, which intuitively impose that one cannot permute the position of a lower-ranked candidate from one group with a higher-ranked candidate from a second group and systematically improve the objective. Moreover, we show that that these moment inequalities are the \textit{only} testable implications of non-discrimination when the auditor observes only outcomes and group membership by rank. We show how to statistically test the implied inequalities, and validate our approach in an application using data from LinkedIn.
</small><br><br/></div>

[outcometest-draft]: {{ site.baseurl }}{% link assets/files/outcome_test.pdf %}



**[Why Do Sectoral Employment Programs Work? Evidence from WorkAdvance](https://www.journals.uchicago.edu/doi/abs/10.1086/717932)** (with Lawrence F. Katz, Richard Hendra, and Kelsey Schaberg).  2022. *Journal of Labor Economics*
<br/>
<small>[ <a href="#/" onclick="visib('workadvance')">Abstract</a> | [Draft][workadvance-paper] ] </small>

<div id="workadvance" style="display: none; text-align: justify; line-height: 1.2" ><small>
This paper examines the evidence from randomized evaluations of sector-focused training programs that target low-wage workers and combine upfront screening, occupational and soft skills training, and wraparound services.  The programs generate substantial and persistent earnings gains (12 to 34 percent) following training. Theoretical mechanisms for program impacts are explored for the WorkAdvance demonstration. Earnings gains are generated by getting participants into higher-wage jobs in higher-earning industries and occupations not just by raising employment. Training in transferable and certifiable skills (likely under-provided from poaching concerns) and reductions of employment barriers to high-wage sectors for non-traditional workers appear to play key roles.
</small><br><br/></div>

[workadvance-paper]:{{ site.baseurl }}{% link assets/files/krhs_sectoral_jole_final.pdf %}

**[Bias In, Bias Out? Evaluating the Folk Wisdom](https://drops.dagstuhl.de/opus/volltexte/2020/12022/pdf/LIPIcs-FORC-2020-6.pdf)** (with Ashesh Rambachan). 2020. *1st Symposium on the Foundations of Responsible Computing (FORC 2020)*
<br/>
<small>[ <a href="#/" onclick="visib('biasinbiasout')">Abstract</a> | [Draft][biasinbiasout-draft] ] </small>

<div id="biasinbiasout" style="display: none; text-align: justify; line-height: 1.2" ><small>
We evaluate the folk wisdom that algorithmic decision rules trained on data produced by biased human decision-makers necessarily reflect this bias. We consider a setting where training labels are only generated if a biased decision-maker takes a particular action, and so "biased" training data arise due to discriminatory selection into the training data. In our baseline model, the more biased the decision-maker is against a group, the more the algorithmic decision rule favors that group. We refer to this phenomenon as bias reversal. We then clarify the conditions that give rise to bias reversal. Whether a prediction algorithm reverses or inherits bias depends critically on how the decision-maker affects the training data as well as the label used in training. We illustrate our main theoretical results in a simulation study applied to the New York City Stop, Question and Frisk dataset.
</small><br><br/></div>

[biasinbiasout-draft]:{{ site.baseurl }}{% link assets/files/bias-in-bias-out-final.pdf %}

# <center> Inactive Working Papers </center>


**Union Reform and Teacher Turnover: Evidence from Wisconsin's Act 10**. 2019.
<br/>
<small>[ <a href="#/" onclick="visib('act10')">Abstract</a> | [Draft][act10-draft] ] </small>

<div id="act10" style="display: none; text-align: justify; line-height: 1.2" ><small>
This paper studies teacher attrition in Wisconsin following Act 10, a policy change which severely weakened teachers’ unions and capped wage growth for teachers. I document a sharp short-run increase in teacher turnover after the Act was passed, driven almost entirely by teachers over the minimum retirement age of 55, whose turnover rate doubled from 17 to 35 percent. Such teachers faced strong incentives to retire before the end of pre-existing collective bargaining agreements in order to secure collectively-bargained retirement benefits (e.g. healthcare), which no longer fell under the scope of collective bargaining after the Act. I find much more modest long-run increases in teacher turnover, consistent with previous estimates of labor supply elasticities. I then attempt to evaluate the effect of the wave of retirements following Act 10 on education quality using grade-level value-added metrics. I find suggestive evidence that student academic performance increased in grades with teachers who retired following the reform, and I obtain similar results when instrumenting for retirement using the pre-existing age distribution of teachers. Differences in value-added between retirees and their replacements can potentially explain some, but not all, of the observed academic improvements.
</small><br><br/></div>

[act10-draft]:{{ site.baseurl }}{% link assets/files/roth_act10.pdf %}



# <center> Comments </center>
- - -
**Comments and Revised Findings for "Procedural justice training reduces police use of force and complaints against officers"** (with Pedro Sant'Anna, George Wood, Andrew Papachristos, and Tom Tyler). 2020.
<br/>
<small>[ <a href="#/" onclick="visib('woodetal')">Abstract</a> | [Initial Letter][woodetal-letter] | [Reanalysis][woodetal-reanalysis] ] </small>

<div id="woodetal" style="display: none; text-align: justify; line-height: 1.2" ><small>
Pedro Sant'Anna and I discovered a statistical error in a recent PNAS paper by Wood, Papachristos, and Tyler that led to spuriously large estimates of the effect of a procedural justice training for police officers. Below are links to our initial letter to the authors detailing the problem and to a re-analysis co-authored with the original authors that corrects the statistical error.
</small><br><br/></div>

[woodetal-letter]:{{ site.baseurl }}{% link assets/files/Wood-et-al-comment-20200714.pdf %}
[woodetal-reanalysis]:{{ site.baseurl }}{% link assets/files/wood-et-al-revisited.pdf %}


[//]: This java script is the button to show abstract
<script>
 function visib(id) {
  var x = document.getElementById(id);
  if (x.style.display === "block") {
    x.style.display = "none";
  } else {
    x.style.display = "block";
  }
}
</script>

[//]:&emsp;<button onclick="visib('polariz')" class="btn btn--inverse btn--small">Abstract</button>
