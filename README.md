# Social identities and their effect on people's attitudes towards refugees.
## Poster

Using a template from `posterdown`, I developed a poster showcasing some findings when analyzing the effects of National and European identity salience on the likelyhood of sharing prosocial attitudes towards refugees. 

## Argument

Since the Russian invasion to Ukraine last year, public opinion seems to have shifted into a more favorable opinion towards asylum seekers. Here, we argue that when individuals are more likely to perceive refugees as part of the in-group (i.e.: fellow Europeans), they are more likely to express prosocial attitudes towards them.

## Empirical Strategy

Our dependent variable is the share of prosocial attitudes towards refugees. In this context, we used data collected by the GESIS Leibniz Institute for the Social Sciences’ (GESIS) in 2021 and 2022 to compare the effect of our predictors before and after the beginning of the war. 

The independent variables (predictor) are National and European identity. The GESIS surveys don't have a clear measurement for self-defined social identity, therefore we used party identification as a proxy for European and National identity salience. 

The Manifesto Project Database (MARPOR)  categorizes party within party families, measures favorable views toward the (1) national way of life and (2) the European Union.  

The package `survey` was used to obtain accurate regression coefficients. 
