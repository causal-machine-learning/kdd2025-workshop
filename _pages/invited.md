---
permalink: /invited/
layout: default
title: Invited Speakers
search_exclude: true
---

# **Invited Speakers**

## [Pedro H.C. Sant’Anna, Emory University](https://psantanna.com/)

![]({{site.baseurl}}/images/pedro.jpeg "Pedro H.C. Sant’Anna")

### Bio
Pedro H.C. Sant’Anna is a passionate applied econometrician, working in causal inference and semi- and non-parametric methods. Much of his recent work aims to develop, better understand, and further improve Difference-in-Differences (DiD) methods.

He is an Associate Professor of Economics at Emory University and an Amazon Scholar. He also serves as Associate Editor at the Journal of Econometrics and at the Journal of Business and Economic Statistics.

Previously, Pedro Sant’Anna was an Assistant Professor at Vanderbilt University and a Principal Researcher at Microsoft. Pedro earned his PhD in Econometrics from Universidad Carlos III de Madrid, Spain, and his BA in Economics from Ibmec-MG, Brazil.

Pedro has published in top journals in economics and has given guest lectures and seminars on DiD topics at leading universities around the world. He is also a co-author of several open-source packages for DiD methods, giving him first-hand experience with the practicalities of these modern tools. His industry experience also allows him to effectively communicate with a broad audience from many different backgrounds.

### Title
Efficient Difference-in-Differences and Event Study Estimators

### Abstract
This paper investigates efficient Difference-in-Differences (DiD) and Event Study (ES) estimation using short panel data sets within the heterogeneous treatment effect framework, free
from parametric functional form assumptions and allowing for variation in treatment timing.
We provide an equivalent characterization of the DiD potential outcome model using sequential
conditional moment restrictions on observables, which shows that the DiD identification assumptions typically imply nonparametric overidentification restrictions. We derive the semiparametric
efficient influence function (EIF) in closed form for DiD and ES causal parameters under commonly imposed parallel trends assumptions. The EIF is automatically Neyman orthogonal and
yields the smallest variance among all asymptotically normal, regular estimators of the DiD and
ES parameters. Leveraging the EIF, we propose simple-to-compute efficient estimators. Our
results highlight how to optimally explore different pre-treatment periods and comparison groups
to obtain the tightest (asymptotic) confidence intervals, offering practical tools for improving
inference in modern DiD and ES applications even in small samples. Calibrated simulations and
an empirical application demonstrate substantial precision gains of our efficient estimators in
finite samples.

## [Linbo Wang, University of Toronto](https://sites.google.com/site/linbowangpku/home)

![]({{site.baseurl}}/images/linbo-wang.png "Linbo Wang")

### Bio
Linbo Wang is Canada Research Chair in Causal Machine Learning, and an associate professor in the Department of Statistical Sciences and the Department of Computer and Mathematical Sciences, University of Toronto. He is also a faculty affiliate at the Vector Institute and holds affiliate positions in the Department of Statistics at the University of Washington and the Department of Computer Science at the University of Toronto. His research focuses on causality and its interaction with statistics and machine learning.

### Title
The Promises of Parallel Outcomes

### Abstract
A key challenge in causal inference from observational studies is the identification and estimation of causal effects in the presence of unmeasured confounding. In this paper, we introduce a novel approach for causal inference that leverages information in multiple outcomes to deal with unmeasured confounding. The key assumption in our approach is conditional independence among multiple outcomes. In contrast to existing proposals in the literature, the roles of multiple outcomes in our key identification assumption are symmetric, hence the name parallel outcomes. We show nonparametric identifiability with at least three parallel outcomes and provide parametric estimation tools under a set of linear structural equation models. Our proposal is evaluated through a set of synthetic and real data analyses.

## [Wenjing Zheng, Roblox](https://www.linkedin.com/in/wenjing-zheng/)

![]({{site.baseurl}}/images/wenjing-zheng.jpg "Wenjing Zheng")

### Bio
Wenjing Zheng is a Senior Data Science Manager at Roblox, where she leads the Ecosystem and Learning Platforms data science team in building scalable, impact-driven solutions. She holds dual PhDs from UC Berkeley and Université Paris Cité and brings over a decade of experience in causal machine learning. Prior to Roblox, Wenjing led experimentation and ads growth initiatives at Netflix. Her expertise spans causal inference, machine learning, and applied data science. Before entering the industry, she was an academic researcher focused on developing doubly robust semiparametric methods for causal inference.

### Title
Applications of Causal Machine Learning in Building a Unified Metric System

### Abstract
Roblox has a mission of connecting a billion people every day with optimism and civility. To guide our day-to-day decisions and operations across product areas towards this shared goal, we use a unified system of metrics measured at different levels to capture the long-term impact of our product decisions on users. This system spans multiple levels: company-level decomposition of the north star metric, product area-level metrics tied to specific levers, and objective functions that drive high-value user actions.
In this talk, I’ll share how we use causal machine learning to construct this metric system—linking short-term impact to long-term values, identifying mechanisms of impact, and high-value user actions. I’ll cover how this framework informs experiment decisions and defines objective functions across product areas. Along the way, I’ll highlight practical lessons we’ve learned—what’s worked, what hasn’t, our validation efforts, and how we’ve balanced technical rigor with real-world constraints.

## [Jeffrey Wong, Airbnb](https://www.linkedin.com/in/jeffctwong/)

![]({{site.baseurl}}/images/jeffrey-wong.jpeg "Jeffrey Wong")

### Bio
Jeffrey Wong is a Senior Staff Engineer for Airbnb's Experimentation Platform, and previously Principle Data Scientist for Experimentation at Netflix. Having dual roles in engineering and data science, Jeff's research is in dynamic policy making rooted in causal effects, and highly performant software to build them. He applies this to build smart engineering systems for adtech, content promotion and experimentation.

In the community, Jeff is leading an open field in computational casual inference, where he is promoting the intersection of software, numerical methods, and causal inference. He is joining us at CMLKDD2025 to share more about these needs and opportunities.

### Title
Engineering Patterns in Causal Inference

### Abstract
We tend to think about Causal Inference as a mathematical field. As we think about deploying causal inference to make more intelligent engineering systems, what role should software engineering play? In this talk, we ground ourselves in how causal inference from experimentation can help with developing a product, but then look backwards at what it takes to integrate causal reasoning into engineering systems. It takes both people, and a highly optimized stack. First we need to make model training more efficient to benefit data science teams and engineering systems. Then, we discuss how to “design for many”, the often overlooked engineering challenge of designing a system that analyzes multiple metrics across multiple actions with multiple heterogeneous effects. Finally, we describe the need for a software grammar that is optimized for human-computer interaction, but is also a robust and general API for engineering systems. The conclusion of this talk will highlight the demand for thoughtful engineering design to support causal reasoning.