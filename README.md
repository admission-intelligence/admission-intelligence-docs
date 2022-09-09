## Admission Intelligence

*  [Introduction](#Introduction)
    *  [The Challenge](#the-challenge)
    *  [Submission Summary](#submission-summary)
*  [Reference Architecture](#Reference-Architecture)
*  [Data Format and Rules](#data-format-and-rules)
*  [Running the Software](#running-the-software)
*  [Future Functionality and Next Steps](#future-functionality-and-next-steps)

### Introduction

Admission Intelligence is a submission to the Future of Healthcare Hackathon. 

#### The Challenge
Preventable hospital admissions cost US healthcare more than $33B annually and it is estimated that more than 15 percent
of all adult inpatient stays with a primary expected payer of Medicare were potentially preventable ([HCUP](https://www.hcup-us.ahrq.gov/reports/statbriefs/sb259-Potentially-Preventable-Hospitalizations-2017.jsp
) and [NIH](https://www.ncbi.nlm.nih.gov/books/NBK559945/)). Studies indicate that the preventable admission 
problem disproportionately impacts disadvantaged communities and individuals, especially individuals at an economic disadvantage.

A one size fits all approach won't work. The scope of the challenge means tmproving preventable admission rates requires a data driven architecture
that can operate at scale and bring the best decision making and automation tools available to life. 

Under the following guiding architectural requirements:

* __Targeted Care__
    * Enhance and empower the experts. Enable clinicians and subject matter experts to target care and attention to the patients most at risk of admission
    * Personalized automation. Automated communication to patients must meet them where they are in life and connectivity. The system must be adaptable to a wide range of circumstances.

* __Modern Architecture and Infrastructure__
    * Utilize modern software infrastructure to provide automated communication, feedback, and outcome tracking across a broad population
    * Build for scale. The problem is huge and requires massive amounts of data and decision making

* __Self Improving Systems__
    * Close the loop. The architecture must capture feedback and outcomes to improve models, rules, and alerts
    * Observability is key. Utilize the available data to track outcomes in as close to real time as possible. 
    
* __Data and Models at the Core__
    * Bring models to life. The architecture must enable new models and machine learning techniques must be brought 
    * Adapt to the data. Decoupled systems and an event driven architecure allow models to evolve and get to production faster and with bigger impact


#### Hackathon Submission Summary
The submission consists of two parts. 

The first part of the submission is a [reference architecture](#Reference-Architecture) that describes a set of services and technology that 
could support a real world deployment with the scale, automation and software based decision making required to make a meaningful impact on 
preventable admissions in US health care.

The second part of the submission is a proof of concept implementation of the [decision services](#decision-services) and dashboard systems of
the architecture. The code for the submission is available on the [admission-intelligence github page](https://github.com/admission-intelligence) and
the [dashboard can be viewed here](TODO - deploy the thing) 

### Reference Architecture

<!---
![Architecture](images/Architecture.png)
-->

#### Model as a Service

- standardization
- feature store

#### Identity and Security

- okta
- keycloak


#### Data Lake


#### Infrastructure, Messaging, and Standards

- Kafka
- Microservices
- Decoupled domains
- Kubernetes


#### Decision Services

#### Dashboards and User Experience

### Technology Survey


#### Model hosting
- Sagemaker
- Azure ML
- Databricks

### Simulating Patient Scenarios


### Future Functionality and Next Steps

- Model development
- Develop model as a service
- Clinical feedback/partnership


### Running the Software

### Additional Resources
