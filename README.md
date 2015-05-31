# Overview
The subject of this project is a renewable source company called XYZ MicroTurbines which deals with the design, installation and maintenance of wind-powered electricity generation. This company is considering transferring its business processes to the Web in the form of E-business technologies such as WS-BPEL orchestration and XML schema documentation. As part of feasibility study, I was asked to carry out prototyping activities to act as proof-of-concept for this transformation.

The aim of this project is to illustrate what is involved in designing and implementing two facets of an e-business process: XML schema and BPEL orchestration. Especially important are the choices that must be made, the problems that might be encountered during implementation and testing, and what lessons can be passed on to start-ups and businesses.

In order to carry out the project, I picked out representative examples that illustrate key design choices and special features that might help XYZ MicroTurbines reach a decision about its e-business strategy.

# XML schema 
With XML schema, I create a single XML schema document that defines the structure and data types of the Order and OrderResponse documents of the company.

Within the code sample, I explain – by reference to the schema and instance documents – what I consider to be the key design choices that I made, the problems that might be encountered and the lessons that could be learned. Of particular importance are the steps I took with regard to reuse and adoption of constraints. I do this by commenting out my code and adding comments within my schema to identify these areas.

# BPEL orchestration 
XYZ MicroTurbines has requested an example of what a BPEL orchestration might do for its business, and specifically an example that will help the company respond more rapidly to its customers. My task was to evaluate the development of a Web Service-BPEL orchestration which can seamlessly and rapidly process requests for a quotation.

# The business scenario
XYZ MicroTurbines was established three years ago and specialises in the design, installation and maintenance of wind-powered electricity generation. The company does not manufacture any components for its wind turbines; all parts are bought in for assembly as required. Design is a core activity for the company, involving site surveys (to assess the installation requirements) and extended discussions to ensure that a proposed solution fulfils all of a customer's requirements.

Although the product line is small, the large number of options (turbines, generators, control modules, batteries, etc.) creates some challenges for the supply logistics. These challenges are likely to grow over the next few years as new technologies emerge. The majority of the company's business is derived from contracts with individual companies and users in remote locations (e.g. farms, mobile phone masts).

The management team is very dynamic and the product range is regarded as highly innovative. The team has been willing to take risks when it comes to the deployment of new technology, especially in areas where there is a proven return on investment. In terms of e-business technologies, the company has a corporate web site that acts as a brochure for its business and a corporate intranet that supports several innovative knowledge-sharing tools (e.g. wind pattern mapping, turbine power simulations). These developments have favoured open-source software installed by systems integrators.

One of the company's directors has been actively following recent developments in e-business technologies and the initiatives of the Office of Government Commerce (OGC), the agency responsible for central government procurement. These developments are encouraging small and medium-sized organisations (SMEs) to adopt electronic document handling in their procurement processes. 
The OGC has been an active participant in the development of the Universal Business Language (UBL) standards for e-business, in collaboration with other member states of the EU. The emerging standard from this group is known as NES-UBL, or the Northern European Subset of UBL. Active promotion of this standard has enabled local and central government in Denmark to handle 100 million procurement documents a year, with potential annual savings of around 200 million Euros (Schade-Sørensen, H. and Brun, M.H. (2006) From 15 to 100 million UBL messages, UBL International, 16 November, Allerød, Denmark).

The recent economic downturn had an impact on XYZ MicroTurbines' core business and has forced the company to review all its non-assembly costs and existing business partnerships. Of special interest to the company is the opportunity to reduce its paper-based processes by exploiting electronic communication options. The proposal, in line with UK and EU policy, is for the company to have moved to full electronic procurement within five years. So the key question is: 'What does the company have to do and learn in order to achieve this goal?' My project attempts to answer this question.

# The business partners 
The business partnerships of XYZ MicroTurbines can be modelled and outlined as follows (the role of each partner is outlined below):
 
•	Suppliers – represents the suppliers of materials and services, for example: steel tubing and boxes (UK); electronic controls (Germany, USA); batteries (Germany, China); turbine blades (UK, Netherlands); generators (Germany, USA); packaging materials (UK); logistics and insurance (UK).
•	Local Councils – represents the city and county councils responsible for approving the installation of wind turbines. 
•	Architects – represents the various architectural practitioners responsible for specifying the wind turbines used in new construction projects. They need access to XYZ MicroTurbines' product catalogues and specifications, but do not place any orders directly. 
•	Customers – represents the individual businesses and users that place orders for new wind-turbine products or spare parts. Some of these customers have enquired about the option to order online so as to reduce the amount of time spent purchasing single items. 
•	Central Government – represents those bodies that deal with imports, exports and taxation, and those responsible for compliance of electrical testing of products.

# Medium-term business objectives 
The medium-term business objectives (2–3 years) are as follows: 
•	Electronic information – to the extent that is reasonable, all information will be captured, edited, stored, manipulated, distributed and shared electronically. This will apply to internal and external communications. 
•	Standardisation – input and output data will be entered and displayed in a consistent format; data entry forms and output report formats will be standardised by means of templates. 
•	 Interface with external systems – when exchanging information between the business and external partners, a stream of valid transactions will be created that can be read by the receiving application in other organisations. 
•	 User responsibilities – staff will be responsible and accountable for providing accurate, timely and complete information for the electronic system. 
•	Security and authority – authority to access, create and change information will be provided to appropriate individuals based on their role within the business. Controls necessary to prevent unauthorised access to information will be implemented. 
•	Procurement - e-business services will be developed to support the production and maintenance of electronic product catalogues; the automated processing of 'request for quote' (RFQ) documents, orders and invoices; and the ordering and payment of goods and services from suppliers.

# The task 
XYZ MicroTurbines has requested my help with establishing the benefits, or drawbacks, of its proposed e-business strategy. The management team has a good understanding of the existing business and recognises the potential benefits of e-business technologies. Of particular interest to the company are the various e-Procurement initiatives being promoted by UK central and local government, which promise to reduce the cost to suppliers and speed up payments for goods and services.

Preliminary investigations undertaken by XYZ MicroTurbines have identified three possible options:

1. Implement some form of bespoke e-business solution for all customers and suppliers. 
2. Join one of the e-Procurement marketplaces to conduct business with suppliers, and continue to use the existing system for purchases by individual customers. 
3. Join one of the e-Procurement marketplaces to conduct business with suppliers, and create a bespoke solution for online purchases by individual customers.
 
Option 1 has already been ruled out as too expensive, given the recent economic downturn.

Option 2 is considered the low-risk option, as many of the e-Procurement marketplace developments are available at zero or very low cost. However, it would require the company to maintain two separate finance systems (electronic for suppliers and manual for individual customers), which could prove expensive and would provide little opportunity for the company to learn about e-business technologies.

The management therefore, is focusing on option 3, since this would provide the opportunity to learn about the challenges and choices they would face if they decided to take the e-business route.
