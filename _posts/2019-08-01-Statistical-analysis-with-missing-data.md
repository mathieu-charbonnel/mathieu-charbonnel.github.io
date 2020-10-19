---
layout: post
title: "Statistical Analysis with Missing Data"
date: 2019-08-01
---
Missing data are ubiquitous in real world data analysis tasks and,  since the mechanism leading to missingness is frequently unknown, 
present a serious challenge  to  predictive  modelling. For  example,  values could be missing due to a broken sensor or communication pipeline, 
or missing in the responses to a formor questionnaire, and these situations could arise due to chance, due to the state of other values we can 
measure, or due to the actions of an adversary or unwilling respondent. In particular values may be ‘missingcompletely at random’ (MCAR),
in which case the absence of a value depends on neither observed nor unobserved values, ‘missing at random’ (MAR) in which case absence can 
depend only on observed values, and ‘missing  not  at  random’ (MNAR) in which case absence depends on unobserved values.  
The MCAR and MAR cases are often referred to as ‘ignorable’ cases, since  the  missing  values  can  be  estimated  from  
the sample  when  modelling  the  data  generator.   On  the other  hand  when  values  are  MNAR  one  cannot  relyon sample information by itself, 
since the presence or absence  of  a  variable  may  depend  on  its  own  unobserved  value,  for  example.   
Various  approaches  havebeen proposed to manage the problem effectively, especially from the perspective of modelling.

