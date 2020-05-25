# COVIDSim

![GUI](GraphicalAbs.png)

The current global health emergency triggered by the pandemic COVID-19 is one of the greatest challenges mankind face in this generation. Computational simulations have played an important role to predict the development of the current pandemic. Such simulations enable early indications on the future projections of the pandemic and is useful to estimate the efficiency of control action in the battle against the SARS-CoV-2 virus. The SEIR model is a well-known method used in computational simulations of infectious viral diseases and it has been widely used to model other epidemics such as Ebola, SARS, MERS, and influenza A. This paper presents a modified SEIRS model with additional exit conditions in the form of death rates and resusceptibility, where we can tune the exit conditions in the model to extend prediction on the current projections of the pandemic into three possible outcomes; death, recovery, and recovery with a possibility of resusceptibility. The model also considers specific information such as ageing factor of the population, time delay on the development of the pandemic due to control action measures, as well as resusceptibility with temporary immune response. Owing to huge variations in clinical symptoms exhibited by COVID-19, the proposed model aims to reflect better on the current scenario and case data reported, such that the spread of the disease and the efficiency of the control action taken can be better understood. The model is verified using two case studies for verification and prediction studies, based on the real-world data in South Korea and Northern Ireland, respectively.

More preliminary details about this work can be found in our preprint on arXiv [here](https://arxiv.org/abs/2004.01974). As such, if you use this simulation package in your research, please cite the following:
* K. Y. Ng and M. M. Gui, COVID-19: Development of A Robust Mathematical Model and Simulation Package with Consideration for Ageing Population and Time Delay for Control Action and Resusceptibility. ([arXiv:2004.01974](https://arxiv.org/abs/2004.01974))

Data are obtained from the following sources:
* [2019 Novel Coronavirus COVID-19 (2019-nCoV) Data Repository by Johns Hopkins CSSE](https://github.com/CSSEGISandData/COVID-19)
* [COVID-19 UK Historical Data](https://github.com/tomwhite/covid-19-uk-data)
