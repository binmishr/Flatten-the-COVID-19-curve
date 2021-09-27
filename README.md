# Flatten-the-COVID-19-curve
The details of the codeset and plots are included in the attached Adobe Acrobat reader (.pdf) file in this repository. 
You need to download the same to view the contents. There are referrals to other contents in BLUE colour also to follow.

A Brief Introduction
=======================

Motivation

Current discussions about interventions for the ongoing COVID-19 outbreak talk a lot about flattening the epidemic curve, i.e. to slow down the outbreak dynamics. Because of limited health capacities, stretching out the outbreak over a longer time period will ensure, that a larger proportion of those in need of hospital treatment will actually get it. Other advantages of this approach are to win time in order to find better treatment forms and, possibly, to eventually develop a vaccine. Visualization of the flatten-the-curve-effect often look like this one taken from Twitter:

    Our #FlattenTheCurve graphic is now up on (???) with proper attribution & a CC-BY-SA licence. Please share far & wide and translate it into any language you can! Details in the thread below. #Covid_19 #COVID2019 #COVID19 #coronavirus Thanks to (???) & (???) pic.twitter.com/BQop7yWu1Q

    — Dr Siouxsie Wiles ((???)) March 10, 2020 


The origin of these illustration is discussed here.
=====================================================

As much as I support the message and reasons for flattening the curve, some of the visualizations have shortcomings from an infectious disease modelling point of view: They transport the message that the number of individuals, which -as an result of the outbreak- will need hospitalization, is fixed. Hence, the figure suggests that it’s impossible to avoid a certain number of infected (say 40-70% of the population), but we save lives by stretching out hospital cases over time. Although the conclusion is correct, the premise is IMHO wrong: Reducing the basic reproduction number by drastically reducing contacts or quickly isolating infectious diseases also reduces the size of the outbreak. Also others, like Ben Bolker have pointed out this flaw.

We shall use a simple and common mathematical model from infectious disease modelling to illustrate this point. This model is easily implemented in R – showing how is a secondary objective of this post. The R code is attached in this post.

A word of caution at this point: The numbers and illustrations used in this post address the point of visualization and are not an attempt to generate actual policy advice.
