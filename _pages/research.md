---
layout: page
permalink: /research/
title: Research
description:
nav: true
nav_order: 2
---

<style>
.abstract-box {
  display: none;
  margin: 0.6rem 0 0.4rem 0;
  padding: 0.85rem 1.1rem;
  font-size: smaller;
  line-height: 1.55;
  text-align: justify;
  background: rgba(38, 152, 186, 0.06);
  border: 1px solid var(--global-divider-color, #e3e3e3);
  border-left: 4px solid var(--global-theme-color, #2698ba);
  border-radius: 6px;
  opacity: 0;
  transform: translateY(-4px);
  transition: opacity 0.25s ease, transform 0.25s ease;
}
.abstract-box.open {
  display: block;
  opacity: 1;
  transform: translateY(0);
}
.abstract-box::before {
  content: "Abstract";
  display: block;
  font-weight: 600;
  font-size: 0.75rem;
  letter-spacing: 0.06em;
  text-transform: uppercase;
  color: var(--global-theme-color, #2698ba);
  margin-bottom: 0.35rem;
}
</style>

<script>
function toggleAbstract(id, link) {
  var box = document.getElementById(id);
  if (box.classList.contains("open")) {
    box.classList.remove("open");
    setTimeout(function () { box.style.display = "none"; }, 250);
    link.textContent = "Abstract";
  } else {
    box.style.display = "block";
    requestAnimationFrame(function () { box.classList.add("open"); });
    link.textContent = "Hide abstract";
  }
}
</script>

## **Job Market Paper**

- **Suppressing Paper Unions: Evidence from the USMCA's Labour Provisions in Mexico**<br>
  <span style="font-size: smaller;">With Ángel Espinoza and León Fernández Bujanda</span><br>
  <span style="font-size: smaller;">[Abstract](#) | [Paper](https://ratzanyelrincon.github.io/assets/pdf/JMP_Ratzanyel_Rincon.pdf)</span>
  <div id="abstract1" class="abstract-box">
  We study the effects of a major labour reform induced by the U.S.–Mexico–Canada Trade Agreement (USMCA) on Mexico's union system, which aimed to improve workers' wages and working conditions by eliminating <em>paper unions</em>—unions that exist only on paper, do not represent workers, and allow firms to forestall real unionization. The reform required existing collective bargaining agreements (CBAs) to be legitimized by workers through secret-ballot votes and introduced stricter requirements for signing new CBAs. As a result, 78% of pre-reform CBAs were terminated, with few new CBAs created subsequently. We combine the universe of pre-reform CBAs with matched employer–employee and survey data and employ a matched difference-in-differences design to estimate the effects on union firms. We find that the reform had a null effect on average wages, but employment and the wage bill at union firms increased by 3.6% and 3.1%, respectively, by 2026. Profits at union establishments in manufacturing also increased by 5.4% following the reform. To rationalize these findings, we develop a model of optimal firm sorting in which the reform reduces firms' marginal labour costs by eliminating payments to paper unions and weakens the union threat by raising the cost of unionization.
  </div>

<br>


## **Working Papers**

- **Are Immigrants Particularly Entrepreneurial? Firm Ownership as a Key Element in Immigrant Income Assimilation**<br>
  <span style="font-size: smaller;">With David A. Green, Huju Liu, Yuri Ostrovsky, and Garnett Picot</span><br>
  <span style="font-size: smaller; font-style: italic;">Accepted at the Journal of Labor Economics</span><br>
  <span style="font-size: smaller;">[Abstract](#) | [Paper](https://ratzanyelrincon.github.io/assets/pdf/Are_Immigrants_Particularly_Entrepreneurial.pdf)</span>
  <div id="abstract2" class="abstract-box">
  Firm ownership is a defining feature of immigrant adaptation: 46% of immigrants own a firm at some point in their first 15 years post-arrival. We use Canadian data linking immigrant arrival records with individual and firm tax data to examine the process of entering firm ownership for immigrants. Higher immigrant firm ownership rates are mainly due to nonincorporated firm ownership, which looks like a last resort. Human capital plays no role in the opening of preferable, incorporated firms. Immigrants are not more entrepreneurial in terms of opening incorporated firms with employees, and standard policy levers appear to have limited effects.
  </div>

- **Causal Inference with Groupwise Matching**<br>
  <span style="font-size: smaller;">With Kevin Song</span><br>
  <span style="font-size: smaller;">[Abstract](#) | [Paper](https://ratzanyelrincon.github.io/assets/pdf/Causal_Inference_Groupwise_Matching.pdf) | [SCD package in R](https://github.com/ratzanyelrincon/scd)</span>
  <div id="abstract3" class="abstract-box">
  This paper examines methods of causal inference based on groupwise matching when we observe multiple large groups of individuals over several periods. We formulate causal inference validity through a generalized matching condition, generalizing the parallel trend assumption in difference-in-differences designs. We show that difference-in-differences, synthetic control, and synthetic difference-in-differences designs are distinguished by the specific matching conditions that they invoke. Through regret analysis, we demonstrate that difference-in-differences and synthetic control with differencing are complementary; the former dominates the latter if and only if the latter's extrapolation error exceeds the former's matching error up to a term vanishing at the parametric rate. The analysis also reveals that synthetic control with differencing is equivalent to difference-in-differences when the parallel trend assumption holds for both the pre-treatment and post-treatment periods. We develop a statistical inference procedure based on synthetic control with differencing and present an empirical application demonstrating its usefulness.
  </div>

- **Working Income Tax Benefits, Minimum Wage, and Employment Transitions of Low-Skilled Workers: Evidence From Canada**<br>
  <span style="font-size: smaller;">[Abstract](#) | [Paper](https://ratzanyelrincon.github.io/assets/pdf/WITB&MW_Ratzanyel_Rincon.pdf)</span>
  <div id="abstract4" class="abstract-box">
  This paper examines how the Workers Income Tax Benefit (WITB) —now called Canada Workers Benefit— and its interaction with the minimum wage affect the labour market transitions for low-skilled workers using Canadian data from 1979 to 2022. Exploiting provincial variation on the maximum real tax credit and real minimum wage rates, I find that higher WITB benefits are associated with lower separation and layoff rates of single-type workers with short job tenure, while the interaction between the WITB and the minimum wage mitigates these effects. Positive effects led by the WITB are found for hiring rates of single-type teenagers, young adults, and recently unemployed people, but the overall impact of the maximum benefits on singles' transition rate from out-of-the-labour force to in-the-labour force is negative. In contrast, family-type workers reduce their job-to-job transitions and increase their flow from out-of-labour force to in-labour force as the maximum WITB benefits increase. Importantly, the interaction between the two policies negatively affects the hiring rate of this group. Overall, these results indicate that the effects of the interaction between the WITB and the minimum wage counterbalance the direct effects of the WITB, and suggest that WITB benefits are insufficient to cover the associated costs of entering the workforce for some individuals in the target population.
  </div>

<br>


## **Work in Progress**

- **Inside the Collective Agreement: Text, Linked Microdata, and the Economics of Union Bargaining**<br>
  <span style="font-size: smaller;">With Pierre-Loup Beauregard and João Galindo da Fonseca</span>

<br>


## **Publications**

- **Quarterly Multidimensional Poverty in Mexico Using Machine Learning Algorithms**<br>
  <span style="font-size: smaller;">Estudios Económicos, Vol. 38, No. 1, January, 2023, pp. 3-68.</span><br>
  <span style="font-size: smaller;">[Abstract](#) | [Paper](https://ratzanyelrincon.github.io/assets/pdf/QuarterlyMultidimensionalPoverty_Ratzanyel_Rincon.pdf)</span>
  <div id="abstract5" class="abstract-box">
  This article addresses the lack of timely information about multidimensional poverty in Mexico. Three machine learning algorithms—the LASSO logistic regression, random forest, and support vector machines—are trained with the ENIGH to find generalizable patterns of multidimensional poverty in the raw data. The fitted models are used to classify each individual in the ENOE as poor or non-poor to obtain aggregated poverty rates on a quarterly basis. These estimates are closer to the official levels of multidimensional poverty than the labor poverty measurement and provide an accurate poverty outlook more than a year ahead of the official measure.
  </div>

<script>
document.querySelectorAll('a[href="#"]').forEach(function(abstractLink, index) {
  abstractLink.addEventListener('click', function(event) {
    event.preventDefault();
    toggleAbstract('abstract' + (index + 1), abstractLink);
  });
});
</script>
