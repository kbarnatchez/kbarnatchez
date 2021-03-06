---
title: " "

# View.
#   1 = List
#   2 = Compact
#   3 = Card
#   4 = Citation
view: 4

# Optional header image (relative to `static/media/` folder).
header:
  caption: ""
  image: ""
---

# Publications and Working Papers

### [The National Establishment Time Series (NETS) Database](https://www.federalreserve.gov/econres/feds/files/2017110pap.pdf)
Detailed data on United States businesses is very hard to come by. Unless you have access to government sources like the Longitudinal Businesses Database (LBD), the majority of alternatives are regionally-aggregated to avoid confidentiality issues. While interning at the Federal Reserve Board of Governors, my main project involved doing a lot of diagnostic work with a potential alternative source called the National Establishment Time Series (NETS), which the Fed had purchased access to. The NETS database is impressive in its scope, but came with some questionable lapses in coverage (in particular, construction and mining industries) that we wanted to understand better. To assess its re(liability as a static indicator of business activity, my bosses and I analyzed NETS relative to other well-known, establishment-level government data sources (such as the QCEW) in static environments (check out the dynamic analysis, which came out a few years later, [here](https://conference.nber.org/conf_papers/f142811.pdf)). 

### [The Impacts of Various Economic Policies on Economic Dynamism](https://kbarnatchez.github.io/assets/coep.12194.pdf)
A key component of any healthy economy is the constant churning of businesses and employment -- as new, innovative businesses open and expand, older and less innovative businesses close up. The workers and equipment from these closing businesses get reallocated to other opening and existing businesses, and the cycle continues on and on. This phenomenom, sometimes referred to as _economic dynamism_, ensures that productive employees and equipment are constantly flowing towards compatible businesses. In this paper, which I cowrote with Rob Lester while working as his RA, we look at the effects of various government policies (e.g. property taxes, labor market regulations ) on different measures of economic dynamism. The goal was to provide policymakers an idea of the "levers" they can pull when wanting to adjust economic dynamism -- we do not attempt to analyze the implicit tradeoffs, as this itself could be the topic of its own paper! Among our most interesting findings is that higher levels of taxation are often associated with higher levels of dynamism, which suggests that corporate tax breaks may not be as beneficial as they're often advocated to be.

# Other projects

Below is a compilation of stuff I've worked on in the past few years, mostly pointed towards topics in biostats, health economics and sports. Projects range in their seriousness, from school projects to journal papers to small apps for visualizing data. If anything catches your interest, feel free to click to associated link to the project!

# Biostats

### [Centenarians](https://kbarnatchez.github.io/assets/final_project.pdf)
A popular question in biostats surrounds the determinants of healthy aging. Naturally, there is promise in studying characteristics of the offspring of people who have exhibited exceptional longevity -- in particular, centenarians. In this short report for my Bayesian Modeling for Public Health course, I explore whether centernarian offspring tend to exhibit healthier cognitive aging by analysing data from Boston University's Telephone Interview for Cognitive Status (TICS) survey. There are frequent, non-random instances of missing values in the TICS data which, along with the data's hierarchical structure, lends itself to well to Bayesian methods. Among my findings are that centenarian offspring tend to have higher baseline levels of cognitive function, but no marked difference in rates of cognitive decline relative to offspring of non-centenarians.

# Health Economics

### [Effects of the ACA's Employer Mandate on Businesses](http://www.colby.edu/econ/wp-content/uploads/sites/73/2018/08/kb_thesis-4.pdf)
(My senior thesis!) Many people in the US depend on employer-provided plans for health insurance coverage, and in many countries universal plans are implemented through employers. The Employer Mandate, a policy embedded within the affordable care act, tried to move the US closer to this popular healthcare model by requiring firms with 50 or more employees to offer insurance plans, or else pay a fine. This project explores some of the potential long-term effects of the policy, such as 1) **is the policy effective in increasing overall insurance coverage?** 2) **are small businesses affected differently than large ones?**  and (importantly) 3) **under what circumstances are people better off under this policy?**

### [Wages and Health Insurance Trade-offs](https://kbarnatchez.github.io/assets/kmb_ec318.pdf)
How much do people value health insurance benefits vs. wages/salaries? Or, more directly, **how much of a pay cut would the average person be willing to take to switch from a job with health benefits to a job without them?** This is a very popular question in health economics, and it turns out to be very difficult to address with standard statistical techniques. In this paper, I try to circumvent some of the statistical issues that arise with standard analyses by focusing on employment changes during the rollout of the Affordable Care Act's [Individual Mandate](https://en.wikipedia.org/wiki/Individual_mandate) policy.

# Sports

### [Optimal 4x100 Relay Strategies](https://kbarnatchez.github.io/assets/kb_exchanges.pdf)
While at Colby I ran on the track team. We had one of the better 4x100 teams in our conference, but with one caveat: we got DQ'd a _lot_ for failed handoffs, most notably at our conference championship meet where we finished the event in first, only to find out that we'd be DQ'd for a handoff that occurred just outside of the allowed boundaries. During the time that this happened, I was taking a math modeling course that focused on modeling sports phenomena. We had free reign to choose a topic for our final project, and it seemed appropriate to spend the time working on a model that could help us stop getting DQ'd so much!

### RunPlots: Strava Data Visualization
A very lazily named RShiny app that gives Strava users numerous ways to visualize their runs that are not currently offered on the app. A work in progress that will be updated soon!
