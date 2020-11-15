+++
abstract = "Background: Joint modelling of longitudinal and time-to-event outcomes has received considerable attention over recent years. Commensurate with this has been a rise in statistical software options for fitting these models. However, these tools have generally been limited to a single longitudinal outcome. Here, we describe the classical joint model to the case of multiple longitudinal outcomes, propose a practical algorithm for fitting the models, and demonstrate how to fit the models using a new package for the statistical software platform R, joineRML. Results: A multivariate linear mixed sub-model is specified for the longitudinal outcomes, and a Cox proportional hazards regression model with time-varying covariates is specified for the event time sub-model. The association between models is captured through a zero-mean multivariate latent Gaussian process. The models are fitted using a Monte Carlo Expectation-Maximisation algorithm, and inferences are based on approximate standard errors from the empirical profile information matrix, which are contrasted to an alternative bootstrap estimation approach. We illustrate the model and software on a real data example for patients with primary biliary cirrhosis with three repeatedly measured biomarkers. Conclusions: An open-source software package capable of fitting multivariate joint models is available. The underlying algorithm and source code makes use of several methods to increase computational speed."
authors = ["Hickey GL", "Philipson P", "Jorgensen A", "Kolamunnage-Dona R"]
date = "2018-06-07"
math = true
publication_types = ["2"]
publication = "*BMC Medical Research Methodology*"
publication_short = "*BMC Med Res Methodol*"
featured = true
title = "joineRML: a joint model and software package for time-to-event and multivariate longitudinal outcomes"
url_code = "https://github.com/graemeleehickey/joineRML"
url_dataset = "https://github.com/graemeleehickey/joineRML"
url_pdf = "https://bmcmedresmethodol.biomedcentral.com/track/pdf/10.1186/s12874-018-0502-1"

+++
