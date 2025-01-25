---
layout: page
permalink: /research/
title: Research
description:
nav: true
nav_order: 2
---

<script>
function toggleAbstract(id) {
  var x = document.getElementById(id);
  if (x.style.display === "none" || x.style.display === "") {
    x.style.display = "block";
  } else {
    x.style.display = "none";
  }
}
</script>

## Working Papers  

**Working Income Tax Benefits, Minimum Wage, and Employment Transitions of Low-Skilled Workers: Evidence From Canada**  
[Abstract](#) | [Paper](https://ratzanyelrincon.github.io/assets/pdf/WITB&MW_Ratzanyel_Rincon.pdf)

<span id="abstract1" style="display: none;">
This paper examines how the Workers Income Tax Benefit (WITB) —now called Canada Workers Benefit— and its interaction with the minimum wage affect the labour market transitions for low-skilled workers using Canadian data from 1979 to 2022. Exploiting provincial variation on the maximum real tax credit and real minimum wage rates, I find that higher WITB benefits are associated with lower separation and layoff rates of single-type workers with short job tenure, while the interaction between the WITB and the minimum wage mitigates these effects. Positive effects led by the WITB are found for hiring rates of single-type teenagers, young adults, and recently unemployed people, but the overall impact of the maximum benefits on singles’ transition rate from out-of-the-labour force to in-the-labour force is negative. In contrast, family-type workers reduce their job-to-job transitions and increase their flow from out-of-labour force to in-labour force as the maximum WITB benefits increase. Importantly, the interaction between the two policies negatively affects the hiring rate of this group. Overall, these results indicate that the effects of the interaction between the WITB and the minimum wage counterbalance the direct effects of the WITB, and suggest that WITB benefits are insufficient to cover the associated costs of entering the workforce for some individuals in the target population.
</span>

<br>


## Work in Progress  

**The Effects of Suppressing Company Unions: Evidence from Mexico**  
<span style="font-size: smaller; font-style: italic;">with Ángel Espinoza and León Fernández Bujanda</span>

**Causal Inference with Groupwise Matching**  
<span style="font-size: smaller; font-style: italic;">with Kevin Song</span>

**Are Immigrants Particularly Entrepreneurial? Policy Lessons from a Selective Immigration System**  
<span style="font-size: smaller; font-style: italic;">with David A. Green, Huju Liu, Yuri Ostrovsky, and Garnett Picot</span>

<br>


## Publications  

**Quarterly Multidimensional Poverty in Mexico Using Machine Learning Algorithms**  
<span style="font-size: smaller;">Estudios Económicos, Vol. 38, No. 1, January, 2023, pp. 3-68.</span>  
[Abstract](#) | [Paper](https://ratzanyelrincon.github.io/assets/pdf/QuarterlyMultidimensionalPoverty_Ratzanyel_Rincon.pdf)

<span id="abstract2" style="display: none;">
This article addresses the lack of timely information about multidimensional poverty in Mexico. Three machine learning algorithms—the LASSO logistic regression, random forest, and support vector machines—are trained with the ENIGH to find generalizable patterns of multidimensional poverty in the raw data. The fitted models are used to classify each individual in the ENOE as poor or non-poor to obtain aggregated poverty rates on a quarterly basis. These estimates are closer to the official levels of multidimensional poverty than the labor poverty measurement and provide an accurate poverty outlook more than a year ahead of the official measure.
</span>

<script>
document.querySelectorAll('a[href="#"]').forEach(function(abstractLink, index) {
  abstractLink.addEventListener('click', function(event) {
    event.preventDefault();
    toggleAbstract('abstract' + (index + 1));
  });
});
</script>
