Tsz Shun Chow (Jason)
============

----

> Author of the book titled "Software Architecture with Kotlin".
> More than 20 years hands-on experience in software development.
> Strong technical background in low-latency financial systems.

----

## Speciality

Low-latency trading systems | Core banking systems and integration | Product-oriented engineering | A/B testing
experiment
design | Public API designer and writer | Event-driven systems | Multi-threaded real-time systems | CQRS | Event
sourcing |
Domain-driven development

## Technical Experiences

Webinar
:   **Source Talk Community**: *"Transitioning to
Kotlin"* (https://www.source-technology.com/source-talks-transitioning-to-kotlin/)

Publications
:   **Book**: *"Software Architecture with Kotlin: Combine various architectural styles to create sustainable and scalable software solutions"* (https://amzn.eu/d/dqBxdkW)
:   **Article**: *"Building a bank? Here’s why you should use
Kotlin"* (https://content.11fs.com/article/building-a-bank-heres-why-you-should-use-kotlin)
:   **Technical Blog**:   *Strictly Programming* (https://jasition.github.io/)

Community
:   **Open Source contributions**: *quickfixj*: https://github.com/quickfix-j/quickfixj/pull/212

## Skills

Languages
:   Kotlin | Core Java (21+) | Bash | SQL

Frameworks
:   Spring Boot | Http4K | Ktor | Micronaut | Arrow | Disruptor | Flyway | Exposed | Jooq | JDBI |
Protobuf | REST | GraphQL | Kotest | Mockk | Testcontainers

Messaging
:   Kafka | Rabbit MQ | Quickfix

Databases
:   mySQL | Postgres | Oracle

Methods
:   A/B Testing | Functional Programming | SOLID Principles | Event Sourcing | CQRS | Ports and Adapters | TDD | BDD | Scrum | Kanban | Continuous Delivery | Trunk-based development

Source Repo
:   Github | Gitlab

Build / CI / CD
:   Gradle | Kubernetes | Docker | Kubectl | Github actions | Gitlab CI | ArgoCD | Kustomize

Infrastructure
:   Terraform | CDKTF

Monitors
:   DataDog | Kibana

Platforms
:   AWS | Azure | GCP | Mac OSX | Linux | Windows

Tools
:   Jira | Confluence | Figma | Miro | Notions | Lucidcharts

## Working Experiences

### Senior Vice President, CAIS, London, March 2023 - Present

**CAIS Alternative Investment Platform** (https://www.caisgroup.com/). A wealth management platform provider for
financial advisors, fund managers, fund administrators, and broker-dealers on alternative investments and marketplace. 
Transformed the pre-trade experience from a legacy monolithic application to micorservice architecture under AWS 
platform. Led an engineering team of 3 frontend, 3 backend, and one testing engineers. Heavily involved in product 
ideation, requirement gathering, and project planning with designers, product managers, and project managers. Led 
technical analysis in pre-trade and general engineering topics. Used Kotlin as the primary language, Spring Boots as 
the fundamental frameworks. Applied DDD in the strategic and tactical designs in the pre-trade space. 

### Principal Engineer, 11:FS Group, London, May 2021 - March 2023

Worked in the Venture department as an engineer consultant working for contracted clients.

**Bitcoin Payroll System and Integration** (https://nydig.com/). A Bitcoin-oriented company that integrates Bitcoin
with various financial services. The payroll project aims at automating employees' salary payment with Bitcoin purchase,
meanwhile facilitating existing Bitcoin trading services. Worked on the proof-of-concept of the core banking integration
with MVB Financial Corp (https://mvbbanking.com/) via Helix API (https://docs.helix.q2.com/docs). Built the basic
mechanics of transaction ingestion, bulk transfer request, and system integration layer. The communication transports
were primarily REST APIs, AMQP events, and batch files. Used Micronaut as the primary frameworks.

Also worked on the backend-for-frontend service that primarily served the onboarding, wallet, buy/sell and account
flows. The microservices were running in AWS using EKS. Infrastructure was configured using Terraform. Kotlin was the
primary language and sometimes Python.

Also worked on the tax reporting integration via Taxbit (https://taxbit.com/). Configured and implemented retrying and
dead lettering mechanism using RabbitMQ. Used CDKTF in templating Terraform configurations.

### Tech Lead, N26, Barcelona, Mar 2019 - May 2021

**Product Service** (http://www.n26.com). An online branch-less modern retail bank that operates entirely in AWS Cloud
using Docker and Kubernetes/Nomad. Product Service was created in managing the lifecycle of a premium membership
subscription and promoting customers the values of premium memberships. It was a monolithic service that was being
slimmed down by extracting microservices out of its scope. Heavily exercised A/B testing in verifying product ideas
before fully invested in a comprehensive solution. Heavily exercised event-driven design, hexagonal architecture, and
domain-driven design principles in re-defining the bounded-context of microservices around the service eco-system. Each
responsible microservice went through CQRS analysis and event storming. Used Kotlin as primary language and Java 11 as
secondary.

### Technical Lead, IG Group, London, Jun 2015 - Mar 2019

**Spectrum Markets** (https://www.spectrum-markets.com). A new institutional Exchange system as a Greenfield project.
Designed and written the matching algorithms. Combined Event-Sourcing, CQRS, SOLID Principles, Functional Programming,
Full TDD / BDD at all levels in Testing Pyramid. Used Hexagonal Architecture as application methodology. Used Docker as
the local dev tool and built a CI/CD pipeline for future. Used Confinity (formerly IBM) Low-latency Messaging, Reuters
RFA, Elektron, QuickfixJ, Spring Boot, Core Java 8 and other Java utilities (Lombok, Vavr, Guava, Immutables, Cucumber,
JMH Benchmarking) as the technology stack. The sole author of the public FIX Rules of Engagement for the Exchange.
Matching latency was down to 9 microseconds for 5-level depth book.

**NADEX** (https://www.nadex.com/). As the trade volume doubled every two years, the Exchange system finally saturated
and needed scaling up. Terracotta FX was replaced by local cache. Redhat MRG QPID was replaced by IBM LLM. Reuters RFA
was used to distribute Market data. Quote throughput was boosted from 3000 to 6000 per second, and order latency was
down to sub-milliseconds.

**FX Price Aggregator**. The FX Spot price aggregator and order router required a separation of price streams between
client orders and hedging function. Connected with 14 liquidity providers (e.g. BAML, Barclays, Morgan Stanley, HSBC) in
setting up and onboarding of the new price FIX feeds and new trade FIX feeds. Performed conformity testing and conducted
live test trades with the dealers.

### Assistant Vice President, Bank of America Merrill Lynch, London, Oct 2013 - Jun 2015

Front office support and development for Interests Rate Swaps trading application. Enhanced EURIBOR and LIBOR Interests
Rate Swaps real-time trading GUI between the bank and other systems such as iSwap, Bloomberg, Tradeweb, etc. Worked as a
part of the global team including New York, Singapore and India. Introduced the feature in the GUI to support Sterling
swaps with multi-legs. Added the support for IMM and MAC swaps. Fixed urgent bugs and investigated queries from traders.
Worked with traders on urgent issues and GUI upgrade. The GUI was written in Java/Swing/JIDE.

### Technical Lead, IG Index, London, April 2008 - Oct 2013

**NADEX** (https://www.nadex.com). Re-written the HedgeStreet system with Terracotta and QPID. Scrum and Test-Driven
Development were used. Utilised data grid technology to achieve data partitioning and high availability. The system
went live in October 2010. Designed the FIX application protocol and maintained the public NADEX FIX Specifications.
Built the framework for messaging for JMS and FIX. Profiled java code and debugged memory leaks. Designed data-driven
test framework for order matching. Designed concurrent and multi-threaded distributed caching mechanism. Revamped the
ledgering component in Clearing House. Built the frameworks and utilities for Swing GUI using JIDE.

**HedgeStreet**. The first internet-based futures exchange regulated by CFTC in Chicago. This n-tier J2EE system
consists of a Designated Contract Market (Exchange), a Derivatives Clearing Organisation (Clearing House), FIX
connectivity for Order Entry and Market Data, and a JSP / Servlet website. Analysed and re-architected to boost trading
throughput from 20 orders per second to 1000.

### Systems Analyst, Hong Kong Housing Authority, Hong Kong, Sep 2006 - Dec 2007

**Domestic Tenancy Management System**. Led a team of 4 engineers to analyse, design and develop a n-tier J2EE housing
management system using Websphere and DB2, with agile methodologies and Paired Programming. Gathered user requirements.

### Technical Analyst, OOCL Limited, Hong Kong, Jul 2005 - Sep 2006

**Real-time Event Engine**. A Real-time multi-threaded messaging system based on JMS. Developed a proprietary
multiple-read-single-write object cache to boost performance by 50%.

### Systems Analyst, Peopleware Systems Limited, Hong Kong, May 2004 - Jul 2005

**Clearing House System of the Trans Link Systems**. The national public transport backoffice system in The Netherlands.
Led the team of 2 engineers on this n-tier J2EE system used Weblogic and Oracle. Enhanced the multi-threaded framework
to complete clearing and settlement for 16 million transactions within 2 hours.

### Software Engineer, Agile Software, Hong Kong, Oct 2002 - May 2004

**Product Lifecycle Management system** (https://www.oracle.com/uk/scm/product-lifecycle-management/). Led a team of 3
engineers working on a n-tier J2EE content management system based on Weblogic and Oracle. . Enhanced the proprietary
distributed object cache and reduced application response time by 30%.

### Software Specialist, Intelligence Plus Limited, Hong Kong, Jul 2001 - Oct 2002

**Learning Plus**. A Core Java e-learning system using mySQL, JDBC, Swing, Java2D, multi-threading, and UML.

## Education

2006
:   **Master of Sceience in Computer Science**; The Chinese University of Hong Kong; Average GPA 3.3.

2001
:   **Bachelor of Cognitive Science**; The University of Hong Kong; 2.1 Degree; Average GPA 3.1.

## Extras

Nationality
:   British Citizen

Languages
:   English (native) | Cantonese (native) | Mandarin (fluent) | Spanish (elementary)

Availability
:   2 months

Hobbies
:   Yoga | Tango

Contacts
:   jasition@gmail.com | https://www.linkedin.com/in/jason-chow-b7418624/

Github
:   https://github.com/jasition
