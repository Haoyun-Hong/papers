# How artificial intelligence and machine learning can help healthcare system respond to COVID-19

### Managing limited healthcare resources

Merging clinical data with a variety of diverse social data
* EHR data can predict clinical risk factor
* link to other big data on human interactions (traffic, airlines, social media)
* A combination of clinical and social data can be mapped into personalized prediction of risk (which ML is especially good at)

Determine the risk of experience adverse events (mortality)
* key factors of determining risk include age, comorbidities, transplants, chemotherapy 
* current risk-scoring methods are crude, fail to account for subtle interactions between comorbidities
* not just a single time point prediction, but an evolution of disease severity 

2 routes of resource allocation using AI 
1. patient level decisions (admission to ICU, discharge from hospital)
2. measurement level decisions on what to measure and when to measure it 
	* trade off between the value of information and the cost of acquisition


### Develop personalized patient management and treatment plans
One size fits all treatment plans are developed at population level, not at individualized patient level 

personalized treatment using AI 
* Models that learn individual-level effects of treatment on the basis of observational data: Gaussian processes, generative adversarial networks and deep neural network 
	* identify patients groups where some tretment might be effective
* Need to model patient's health state over time as they respond to different treatments and care 
	* predict counterfactual health trajectories under different management plans for each individual (counterfactual recurrent network)

### Informing policies and enable effective collaboration 

