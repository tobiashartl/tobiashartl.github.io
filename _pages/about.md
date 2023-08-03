---
permalink: /
title: "Welcome..."
title-heading: false
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

...to my website. I'm a Postdoc in econometrics at the University of Regensburg and the Institute for Employment Research (IAB) Nuremberg.

In my research, I aim to improve the econometric toolkit to address the puzzles of 
our time in a data-driven way. In particular, I develop estimation methods for strongly 
persistent, non-stationary time series. 

You can download my job market paper [here](http://tobiashartl.github.io/files/Hartl_fUCM.pdf){:target="_blank"}, and my CV [here](http://tobiashartl.github.io/files/CV_Tobias_Hartl.pdf){:target="_blank"}.


Peer-Reviewed Publications
----------
<details>
<summary>Haimerl, P., and <b>Hartl, T.</b> (2023).<a href="https://doi.org/10.3390/econometrics11020010" target="_blank">Modeling the COVID-19 infection rates by regime-switching unobserved components models.</a> <i>Econometrics</i>, 11(2) </summary>
<hr>
<b>Abstract:</b> The COVID-19 pandemic is characterized as a recurring sequence of infection ebbs and flows. This article proposes a regime-switching unobserved components (UC) approach to model the trend of COVID-19 infections as a function of this peak and trough pattern. Estimated regime probabilities indicate the prevalence of either an infection up- or down-turning regime for every day of the observational period. This method provides an intuitive real-time analysis of the state of the pandemic as well as a tool to identify structural changes ex post. We find that when applied to U.S. data, the model closely tracks regime changes caused by viral mutations, policy interventions and public behavior.
<hr>
</details>



<details>
<summary><b>Hartl, T.</b>, and Jucknewitz, R. (2022). <a href="https://doi.org/10.1093/jjfinec/nbab022" target="_blank">Multivariate fractional components analysis.</a> <i>Journal of Financial Econometrics</i>, (forthcoming)
</summary>
<hr>
<b>Abstract:</b> We propose a setup for fractionally cointegrated time series which is formulated in terms of latent integrated and short-memory components. It accommodates nonstationary processes with different fractional orders and cointegration of different strengths and is applicable in high-dimensional settings. In an application to realized covariance matrices, we find that orthogonal short- and long-memory components provide a reasonable fit and competitive out-of-sample performance compared with several competing methods.
<hr>
</details>

<details>
<summary><b>Hartl, T.</b>, and Jucknewitz, R. (2022). <a href="https://doi.org/10.1080/07474938.2020.1841444" target="_blank">Approximate state space modelling of unobserved fractional components.</a> <i>Econometric Reviews</i>, 41(1), 75-98 
</summary>
<hr>
<b>Abstract:</b> We propose convenient inferential methods for potentially nonstationary multivariate unobserved components models with fractional integration and cointegration. Based on finite-order ARMA approximations in the state space representation, maximum likelihood estimation can make use of the EM algorithm and related techniques. The approximation outperforms the frequently used autoregressive or moving average truncation, both in terms of computational costs and with respect to approximation quality. Monte Carlo simulations reveal good estimation properties of the proposed methods for processes of different complexity and dimension.
<hr>
</details>




Working Papers
-----------


<details>
<summary><b>Hartl, T.</b> (2022). <a href="http://tobiashartl.github.io/files/Hartl_fUCM.pdf" target="_blank">The fractional unobserved components model: a generalization of trend-cycle decompositions to data of unknown persistence</a></summary>
<hr>
<b>Abstract:</b> This paper provides a data-driven solution to the specification of the long-run dynamics in trend-cycle decompositions. A novel state space model of form y<sub>t</sub> = x<sub>t</sub> + c<sub>t</sub> is introduced, allowing the unobserved trend x<sub>t</sub> ∼ I(d) to be fractionally integrated of order d, whereas c<sub>t</sub> represents an unobserved stationary cyclical component. The new model encompasses the two major specifications in the literature that either assume x<sub>t</sub> ∼ I(1) in spirit of the Beveridge-Nelson decomposition, or x<sub>t</sub> ∼ I(2) as for the Hodrick-Prescott filter. As d can take any value on the positive real line, the new model allows for intermediate solutions between integer-integrated specifications and thus for richer long-run dynamics. Trend and cycle can be estimated via the Kalman filter, for which a closed-form solution is provided. The integration order d is treated as unknown and is estimated jointly with the other model parameters via the conditional sum-of-squares estimator. The paper derives the asymptotic theory for parameter estimation under relatively mild assumptions, showing the conditional sum-of-squares estimator to be consistent and asymptotically normally distributed. While the proofs are carried out for a prototypical model, the asymptotic theory carries over to generalizations allowing for deterministic terms and correlated innovations, but also to (quasi-) maximum likelihood estimation. An application to annual CO2 emission reveals a smooth trend component starting to exhibit an inverted U-shape, together with cyclical CO2 emissions that are closely coupled to the business cycle.
<hr>
</details>


<details>
<summary><b>Hartl, T.</b>, Hutter, C., and Weber, E. (2021). <a href="https://doku.iab.de/discussionpapers/2021/dp0121.pdf" target="_blank">Matching for three: big data evidence on search activity of workers, firms, and employment service</a></summary>
<hr>
<b>Abstract:</b> We generate measures for search intensity of employers and job seekers and - as a novel feature - for placement intensity of employment agencies. For this purpose, we tap big data on online activity from the job exchange of the German Federal Employment Agency and its internal placement-software. We use these data to estimate an enhanced matching function where the efficiency parameter varies with the search and placement intensities. The results show that the intensity measures significantly contribute to the variation in job findings.
<hr>
</details>

<details>
<summary><b>Hartl, T.</b>, Tschernig, R., and Weber, E. (2020). <a href="https://arxiv.org/pdf/2005.03988.pdf" target="_blank">Fractional trends in unobserved components models</a></summary>
<hr>
<b>Abstract:</b> We develop a generalization of unobserved components models that allows for a wide range of long-run dynamics by modelling the permanent component as a fractionally integrated process. The model allows for cointegration, does not require stationarity, and can be cast in state space form. We derive the Kalman filter estimator for the common fractionally integrated component and establish consistency and asymptotic (mixed) normality of the maximum likelihood estimator. We apply the model to extract a com- mon long-run component of three US inflation measures, where we show that the <i>I(1)</i> assumption is likely to be violated for the common trend.
<hr>
</details>

<details>
<summary><b>Hartl, T.</b>, Tschernig, R., and Weber, E. (2020). <a href="http://tobiashartl.github.io/files/Hartl_Tschernig_Weber_Puzzle.pdf" target="_blank">Solving the unobserved components puzzle: A fractional approach to measuring the business cycle</a></summary>
<hr>
<b>Abstract:</b> Measures for the business cycle obtained from trend-cycle decompositions are puzzling, as they often are noisy, at odds with the NBER chronology, and not well in line with economic theory. We argue that these results are driven by the neglect of fractionally integrated trends in log US real GDP. To account for fractional integration we develop a generalization of trend-cycle decompositions that avoids prior assumptions about the long-run dynamic characteristics and treats the integration order as a random variable. The integration order is jointly estimated with the other model parameters via a quasi maximum likelihood estimator that is shown to be consistent and asymptotically normal. In addition, single-step estimators for the latent components that are identical to the Kalman filter and smoother but computationally superior are derived. We find that log US real GDP is integrated of order around 1.3, the resulting trend-cycle decomposition is in line with the NBER chronology, and the model well explains the puzzling results in the literature that result from model misspecification.
<hr>
</details>

<details>
<summary><b>Hartl, T.</b> (2020). <a href="https://arxiv.org/pdf/2005.04897.pdf" target="_blank">Macroeconomic forecasting with fractional factor models</a></summary>
<hr>
<b>Abstract:</b> We combine high-dimensional factor models with fractional integration methods and derive models where nonstationary, potentially cointegrated data of different persistence is modelled as a function of common fractionally integrated factors. A two-stage estimator, that combines principal components and the Kalman filter, is proposed. The forecast performance is studied for a high-dimensional US macroeconomic data set, where we find that benefits from the fractional factor models can be substantial, as they outperform univariate autoregressions, principal components, and the factor-augmented error-correction model.
<hr>
</details>


Work in Progress
-----------


<details>
<summary>Ammon, D., <b>Hartl, T.</b>, and Tschernig, R. (2022). Determining the number of factors in fractionally integrated factor models</summary>
<hr>
<b>Abstract:</b> This paper proposes three different approaches to overcome limitations for factor selection in fractionally integrated factor models. Two of our methods for determining the number of factors include the approach of Zhang, Robinson and Yao (2019, JASA) that was designed for identifying the cointegration rank in VAR models. We extend their model selection approach by generalizing it to fractionally integrated factor models. In our two-step procedure we first estimate the cointegration rank as in Zhang, Robinson and Yao (2019, JASA) to obtain the non-stationary fractional factors. In the second step we generalize the model selection criteria by Bai and NG (2002, ECTA) to fractionally integrated factors with memory smaller <i>1/2</i> to obtain the number of asymptotically stationary factors. Before carrying out the second step the non-stationary factors need to be removed from the data. We investigate two alternatives: i) subtract the estimated non-stationary part from the observable variables, ii) project out the non-stationary factors. In our third approach we directly consider the model selection criteria of Bai and NG (2002, ECTA) without prior removing the non-stationary variation in the observable data. In the Monte-Carlo simulations all three methods show satisfactory results, in particular the third approach performs surprisingly well.
<hr>
</details>





<details>
<summary><b>Hartl, T.</b>, Tschernig, R., and Weber E. (2022). Multivariate fractional unobserved components and the cyclicality of labor market flows</summary>
<hr>
<b>Abstract:</b> We generalize bivariate unobserved components models by allowing the long- run components to be fractionally integrated. The model decomposes time series into latent components of different persistence and covers a variety of economic variables that are found to exhibit long memory. The model is identified under weaker restrictions than standard unobserved components models and thus allows for a parsimonious parametrization of the cycles. We apply the fractional unobserved components model to extract trend and cycle measures for German labor market flows, where we find unemployment in- and outflows to be cointegrated and I(0.8564), while a linear combination that is I(0.5537) exists.
<hr>
</details>



