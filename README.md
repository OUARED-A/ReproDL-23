# COMORP Project
## Project Title:
Rapid Prototyping for Mathematical Database Cost Models Development
### Project Description
Our framework called COMORP to assist modelers (expert/novice designers) to produce database CM and that production is helped by the availability of parameters and units cost functions. COMORP provides a general guideline better explore the possible design space of CM and allowing to quickly test how a given design fits a workload and hardware setting. A tool support is developed to support the whole framework based on our previous the CM description language called CostDL  and the repository called MetricStore. To ease the understanding, we provide the URL of a demonstration video of the MetricStore repository. The demonstration video of MetricStore is available at: https://youtu.be/rHIVvJEOrbM.

### Implementation
COMORP has been implemented as as open-source Eclipse plugins. Our solution offer possible way to create a cost model expressed in COMORP design language: via a tool based on Java EMF (Eclipse Modeling Framework) API and has been integrated as a plugin in Eclipse (Eclipse Modeling Project. www.eclipse.org/modeling/) which is an integrated development environment (IDE). Through the editor tool, every $\mathcal{CM}$ instance is saved as an XMI (XML Metadata Interchange) file. In our laboratory we have developed a third party tool that transforms XMI files corresponding to database cost model to a C-program based on the PostgreSQL API. This generator tool has been tested. That is, by using Acceleo language we have developed a code generator which generate C-programs based on PostgreSQL API.

### Design tool for instantiating and visualization of cost models

Our design tool allowing to create and visualize cost models conform to our design language.
The structure of the developed design tool is based on Java EMF (Eclipse Modeling Framework) API and has been integrated as a plugin in Eclipse: www.eclipse.org/modeling/emf which is an IDE (Integrated Development Environment). 
Figure below sketches this structure where the abstract syntax of COMORP have been implemented using Ecore meta-modeling language and the implementation of concrete syntax is based on Sirius framework. Thanks to Sirius and Ecore plugins, users of COMORP language can instantiate their cost models in a user-friendly manner by using the Tree editor and suitable properties tab. 
Through to the design tool, every cost model instance is saved as an XMI (XML Metadata Interchange  file, hence every CM become a machine-interpretable entity which can be exploited via several usage.

![image](https://user-images.githubusercontent.com/42803883/185497491-1eb39c9a-5ee2-4d97-b2b3-b7a915e03459.png)

Furthermore, to develop the front-end side of our design tool, we  have developed a web user interface that provides a designing work-space divided into four parts (see Figure \ref{fig:toolSimCost2}): (1) Context and Design Question, (2) Parameters Analysis, (3) CM Construction and (4) Results-Reports and Cost Exploration. 

![image](https://user-images.githubusercontent.com/42803883/185498629-8297a5ca-9fb5-45a3-ad21-5b8096488957.png)

## Further improvements

If you wish, you're welcome to participate in the Explain-Tun or to make suggestions ! 

## Authors Anonymous
