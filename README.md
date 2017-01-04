# Survival-Data-Analysis-
Competing risks arise in studies when subjects are exposed to more than one cause of event and event due to one cause excludes event due to other causes.  If we want real world probabilities of events and separate the probability of event into different causes, competing risks methodology should be used as opposed to standard survival analysis methods. The traditional analysis for competing risks is to perform a separate analysis for each event type, treating other events as censoring (cause-specific approach). The biggest drawback of cause-specific analysis is the requirement that times for different event types be independent, which is often not the case.  Although cause-specific approach can give cause-specific hazards, it could not provide actual probability of event.  Recently, cumulative incidence function (CIF) and its following sub-distribution approach have been developed to overcome the above two problems by accounting for competing risks. CIF is useful in estimating the probabilities of events, but we cannot examine covariate effects on the CIF. Sub-distribution approach allows us to test covariate effects on the CIF, but sub-distribution hazards are difficult to interpret and so should be used with caution. In summary, the currently available approaches for competing risks have their own advantages and disadvantages. How to analyze compete risks correctly depends on the aim of study and the characteristics of event types.
