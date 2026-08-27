# Awesome-Public-Transit-Management

## Top Public Transit Management Platforms Ecosystem



**Curated List of SaaS/Hosted Platforms & Open-Source GitHub Projects**

*Focused on Public Transit Planning, Scheduling, Operations, Dispatch, CAD/AVL, Fleet Management, Paratransit, Passenger Information, Route Optimization & Transit Data*

**Last updated: August 2026**



This repository tracks notable **SaaS/Hosted platforms** and **open-source projects** for **Public Transit Management**.



Public transit management is a broad software category spanning **network planning, route design, timetabling, vehicle scheduling, crew scheduling, rostering, dispatch, CAD/AVL, real-time operations, paratransit, demand-responsive transportation, passenger information, fare integration, fleet management, service analytics, GTFS/GTFS-RT, and transit simulation**.



**Open-source emphasis:** The open-source ecosystem is particularly strong around **GTFS data, multimodal journey planning, real-time passenger information, CAD/AVL building blocks, transit simulation, routing, data validation, and open mobility standards**. It is less mature as a direct one-to-one replacement for large enterprise scheduling suites such as HASTUS or Trapeze, particularly for highly constrained vehicle blocking, crew rostering, labor-rule optimization, and agency-scale operations.



> **Important distinction:** There is no single dominant open-source project that completely replaces an enterprise transit-management suite. A realistic open-source architecture is usually assembled from several components such as **OpenTripPlanner, OneBusAway, MOTIS, Navitia, Transitland, OpenStreetMap, GTFS tooling, AVI, SUMO, R5, and custom optimization software**.



The commercial market is increasingly moving toward integrated platforms. For example, Optibus describes its platform as covering planning, scheduling, rostering, operations, real-time control/monitoring, and passenger information, while HASTUS spans planning, scheduling, operations, on-demand transport, customer information, and integrations. INIT similarly combines planning, operations, and passenger-experience capabilities around its MOBILE suite.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites or repositories.



## Table of Contents



* [SaaS/Hosted Platforms](#saashosted-platforms)

* [Open-Source GitHub Projects](#open-source-github-projects)

* [Additional Strong Open-Source Options](#additional-strong-open-source-options)

* [Open-Source Public Transit Stack](#open-source-public-transit-stack)

* [Commercial Platform Capability Map](#commercial-platform-capability-map)

* [SaaS vs Open Source](#saas-vs-open-source)

* [How to Contribute](#how-to-contribute)

* [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

### Major Transit Management SaaS Platforms

| Platform / Vendor | Focus Areas & Core Capabilities | Description | Pricing (Starting Tier) | Free Tier / Free Trial Limits |
| :--- | :--- | :--- | :--- | :--- |
| **INIT** | Integrated ITS, Planning, CAD/AVL, Ticketing | Integrated public transport technology provider covering planning, scheduling, intermodal transport control (MOBILE-ITCS), fleet management, passenger info, and account-based ticketing. | $3,333 / month ($40,000 / year base license) | No free forever plan; 30-day sandbox pilot trial limited to synthetic telemetry of 15 test vehicles |
| **Trapeze Group** | Enterprise Scheduling, Workforce, CAD/AVL, Paratransit | Major enterprise transit software ecosystem spanning fixed-route scheduling, operations dispatch, operator bidding/workforce management, paratransit, and EAM. | $2,083 / month ($25,000 / year base single module) | No free forever plan; 30-day guided pilot evaluation limited to 20 vehicle records and 5 operator rosters |
| **GIRO HASTUS** | Advanced Timetabling, Vehicle/Crew Optimization, Rostering | Leading enterprise transit planning and operations suite known for mathematical optimization algorithms handling complex vehicle blocking, collective bargaining, and crew scheduling. | $2,500 / month ($30,000 / year base scheduling tier) | No free forever plan; 30-day proof-of-concept sandbox trial limited to 1 depot and up to 30 vehicle blocks |
| **Optibus** | Cloud-Native Scheduling, Rostering, EV & Operations | Cloud-native public transportation platform powered by AI optimization for route planning, timetabling, vehicle blocking, crew rostering, EV charging scheduling, and live operations. | $1,500 / month ($18,000 / year base planning tier) | No free forever plan; 14-day sandbox trial limited to 1 agency network model and up to 50 route variations |
| **Swiftly** | Real-Time Transit Data, CAD/AVL, Prediction Analytics | Cloud-based transit data engine providing high-accuracy vehicle arrival predictions, real-time dispatch tools, speed maps, and on-time performance analytics. | $1,000 / month ($12,000 / year base GPS tier) | No free forever plan; 30-day live pilot trial limited to 25 tracked vehicles and 5 active routes |
| **Remix (by Via)** | Transit Network Planning, Scenario Modeling, Demographics | Map-based transit planning and scheduling tool enabling transit planners to design routes, evaluate Title VI demographic impacts, and compute operational cost estimates instantly. | $833 / month ($10,000 / year base tier for <20 routes) | No free forever plan; 14-day interactive sandbox trial limited to 1 municipality boundary & standard census layers |
| **Spare** | On-Demand Transit, Paratransit, Microtransit Dispatch | Cloud-based microtransit and paratransit software providing automated on-demand dispatch, driver apps, pooling optimization, and rider booking interfaces. | $20 / vehicle / month ($1,200 / month minimum tier) | No free forever plan; 14-day sandbox dispatch trial limited to 5 test vehicles and 50 simulated bookings |
| **RideCo** | Demand-Responsive Transit & Microtransit Optimization | High-capacity microtransit and paratransit platform focusing on dynamic routing, shared-ride optimization, automated dispatch, and agency fleet coordination. | $3,500 / month ($42,000 / year base platform tier) | No free forever plan; 30-day agency pilot simulation limited to 1 designated zone and 10 active vehicles |
| **Transit** | Consumer Journey Planning & Real-Time Tracking | Passenger-facing mobile navigation app providing real-time vehicle positions, crowdsourced trip tracking (GO), multimodal routing, and agency mobility integrations. | $4.99 / month or $24.99 / year (Transit Royale); Agency sponsorship from $1,200 / year | Free forever plan includes real-time ETA for 2 closest routes per mode and navigation; 7-day free trial for Transit Royale (unlimited routes/maps) |
| **Moovit** | Multimodal MaaS, Transit Data APIs, On-Demand Routing | Urban mobility platform and data service providing passenger navigation, transit APIs, trip planning SDKs, and flexible on-demand microtransit dispatch. | $1.99 / month (Moovit+ app) or $500 / month for Developer Transit Data API | Free forever plan includes ad-supported multimodal journey planning & arrival alerts; 7-day free trial for Moovit+ (ad-free & SafeRide) |
| **Passio Technologies** | Real-Time Fleet Tracking, Passenger Info, Smart Signage | Transit technology suite delivering passenger apps (Passio GO!), automated passenger counting (APC), GPS fleet tracking, and on-board digital display integration. | $100 / vehicle / month ($1,200 / vehicle / year starting tier) | Free forever mobile app for riders; 30-day agency evaluation trial limited to 5 test vehicle tracking feeds |
| **Ecolane** | Paratransit Scheduling, NEMT, Dynamic Dispatch | Specialized demand-response scheduling engine designed for paratransit and non-emergency medical transportation with automated dispatch and driver manifest management. | $1,250 / month ($15,000 / year base tier) | No free forever plan; 30-day pilot trial limited to historical simulation of up to 100 daily paratransit trips |
| **Clever Devices** | Intelligent Transportation Systems (ITS), CAD/AVL, RTPI | Provider of on-board vehicle computers, transit signal priority, automated voice announcements, automated vehicle monitoring, and control center CAD/AVL. | $2,083 / month ($25,000 / year base cloud analytics tier) | No free forever plan; 30-day telemetry evaluation sandbox limited to 10 vehicle tracking data streams |
| **Avail Technologies** | Municipal CAD/AVL, ITS, Fixed-Route Operations | Transit operations and CAD/AVL software tailored to small and medium-sized public transit agencies for dispatch, tracking, and NTD compliance reporting. | $1,667 / month ($20,000 / year base municipal software tier) | No free forever plan; 30-day staging demo limited to 1 pre-configured agency network and 10 simulated buses |
| **Vontas** | Fixed-Route CAD/AVL, Dispatch, Planning & Yard Management | Transit management spin-off of Trapeze providing CAD/AVL (TransitMaster), passenger communications, yard management, and modular scheduling tools. | $2,083 / month ($25,000 / year base module tier) | No free forever plan; 30-day software evaluation sandbox limited to 15 vehicle connections and 2 dispatch seats |
| **Modaxo Transit** | Global Transportation Software Portfolio Solutions | Global conglomerate operating dedicated transit technology business units covering scheduling, ticketing, CAD/AVL, and passenger data systems. | $2,500 / month ($30,000 / year base portfolio module tier) | No free forever plan; 30-day pilot deployment limited to 1 selected subsidiary tool and 15 simulated vehicles |
| **RouteMatch** | Paratransit Dispatch, Demand-Response & Billing | Paratransit and flexible-route scheduling platform (part of Trapeze) providing trip booking, automated vehicle scheduling, and coordinated human services transit. | $1,500 / month ($18,000 / year base rural/small-agency tier) | No free forever plan; 14-day paratransit dispatch simulation limited to 10 test vehicles and 50 reservations |
| **Via Transportation** | Microtransit, On-Demand Routing & Autonomous Transit | Turnkey and SaaS microtransit platform offering algorithmic vehicle pooling, dynamic routing, driver dispatch apps, and rider booking interfaces. | $4,000 / month ($48,000 / year base on-demand SaaS tier) | No free forever plan; 30-day simulation environment limited to 1 virtual service zone and 10 vehicle simulations |
| **KUBA** | Account-Based Ticketing, cEMV Payments & Back Office | Smart transit ticketing platform delivering open-loop contactless cEMV payments, mobile ticketing, validation hardware integrations, and cloud fare engines. | $1,000 / month base cloud fee plus 2.5% + $0.05 per fare transaction | No free forever plan; 14-day developer sandbox trial limited to 100 test ticketing transactions and 2 virtual validators |
| **GMV** | ITS, Fleet Management, CAD/AVL & Ticketing | Global intelligent transport systems provider offering cloud-based CAD/AVL (Syncromatics), real-time passenger info displays, and ticketing hardware. | $1,800 / month ($21,600 / year base cloud tracking tier) | No free forever plan; 30-day live tracking portal trial limited to 10 active GPS trackers / test vehicles |
| **Conduent Transportation** | Enterprise Fare Collection, Tolling & Fleet CAD/AVL | Enterprise transit technology suite delivering automated fare collection (AFC), transit operations management, CAD/AVL integration, and mobility analytics. | $4,166 / month ($50,000 / year base enterprise tier) | No free forever plan; 30-day integration testbed limited to 5 test fare gates and 20 simulated vehicle transponders |

---

### Specialized SaaS Modules & Sub-Systems

| Product / Module | Parent Platform | Functional Area | Description | Pricing (Starting Tier) | Free Tier / Free Trial Limits |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **INIT MOBILE-ITCS** | INIT | CAD/AVL & Dispatch | Real-time intermodal transport control system for dispatchers and operations control centers with live incident intervention. | $2,500 / month ($30,000 / year base tier) | No free forever plan; 30-day testbed limited to 10 virtual vehicle telemetry feeds |
| **INIT MOBILE-PLAN** | INIT | Network Planning | Planning and scheduling component for designing route networks, timetables, block creation, and vehicle duties. | $2,000 / month ($24,000 / year base tier) | No free forever plan; 30-day evaluation trial limited to 1 transit sub-network (max 20 lines) |
| **INIT MOBILE-PERDIS** | INIT | Crew Rostering & Dispatch | Personnel disposition and duty rostering system considering driver preferences, working hour regulations, and shift bidding. | $1,800 / month ($21,600 / year base tier) | No free forever plan; 30-day staging sandbox limited to 25 driver profiles and 1 roster cycle |
| **INIT MOBILEguide** | INIT | Passenger Information | Omnichannel real-time passenger information engine feeding web widgets, mobile apps, and smart displays. | $800 / month ($9,600 / year base tier) | No free forever plan; 14-day API sandbox limited to 5 stop location feeds |
| **INIT MOBILEstop** | INIT | Station Infotainment | Station and stop digital signage management for electronic paper and LED/LCD passenger arrival displays. | $600 / month ($7,200 / year base tier) | No free forever plan; 14-day digital display sandbox limited to 3 virtual digital sign outputs |
| **INIT MOBILEefficiency** | INIT | Eco-Driving & Fleet Analytics | Vehicle driving style analysis, energy consumption optimization, and electric bus battery state-of-charge monitoring. | $1,200 / month ($14,400 / year base tier) | No free forever plan; 30-day analytics trial limited to 10 vehicle CAN-bus streams |
| **INIT MOBILEvario** | INIT | Fare Management | Modular fare calculation and fare collection software managing multi-tariff structures and smart card ticketing. | $1,500 / month ($18,000 / year base tier) | No free forever plan; 14-day tariff simulation sandbox limited to 50 test transactions |
| **Trapeze PASS** | Trapeze Group | Paratransit Scheduling | Comprehensive demand-response and paratransit scheduling tool managing client eligibility, ride booking, and routing. | $2,000 / month ($24,000 / year base tier) | No free forever plan; 30-day pilot trial limited to 10 test vehicles and 100 client records |
| **Trapeze OPS** | Trapeze Group | Dispatch & Real-Time Ops | Real-time operations management tool handling day-of-service operator sign-ins, vehicle pull-outs, and detour logging. | $1,750 / month ($21,000 / year base tier) | No free forever plan; 30-day operational sandbox limited to 20 daily runs |
| **Trapeze Workforce** | Trapeze Group | Crew Bidding & Timekeeping | Operator workforce platform managing automated seniority bidding, daily dispatch rosters, timekeeping, and payroll export. | $1,500 / month ($18,000 / year base tier) | No free forever plan; 30-day workforce sandbox limited to 30 operator profiles |
| **Trapeze FX** | Trapeze Group | Fixed-Route Scheduling | Fixed-route scheduling software for creating master timetables, vehicle interlining, and driver run-cutting. | $1,800 / month ($21,600 / year base tier) | No free forever plan; 30-day scheduling demo limited to 10 route master files |
| **Trapeze EAM** | Trapeze Group | Fleet Asset Management | Enterprise transit asset management software for preventative vehicle maintenance, parts inventory, and work order tracking. | $1,600 / month ($19,200 / year base tier) | No free forever plan; 30-day maintenance sandbox limited to 25 vehicle asset records |
| **Trapeze PASS-Web** | Trapeze Group | Rider Web Portal | Web booking interface allowing paratransit riders and care facilities to book and manage trips online. | $750 / month ($9,000 / year base tier) | No free forever plan; 14-day web portal trial limited to 20 test passenger accounts |
| **HASTUS-PLAN** | GIRO HASTUS | Network Design & Timetabling | Strategic network design and corridor timetable development with multi-scenario service evaluation. | $2,000 / month ($24,000 / year base tier) | No free forever plan; 30-day planning sandbox limited to 15 route alignments |
| **HASTUS-Vehicle** | GIRO HASTUS | Vehicle Blocking Optimization | High-performance vehicle block optimization minimizing deadhead mileage, vehicle requirements, and layover times. | $2,200 / month ($26,400 / year base tier) | No free forever plan; 30-day optimization trial limited to 25 peak vehicle schedules |
| **HASTUS-Crew** | GIRO HASTUS | Crew Run-Cutting & Rostering | Mathematical crew scheduling optimizer satisfying union rules, break regulations, overtime constraints, and shift preferences. | $2,500 / month ($30,000 / year base tier) | No free forever plan; 30-day optimization sandbox limited to 30 operator duties |
| **HASTUS-MiniBus** | GIRO HASTUS | Small Fleet & EV Scheduling | Specialized scheduling module for paratransit, on-demand shuttles, and electric bus battery replenishment management. | $1,500 / month ($18,000 / year base tier) | No free forever plan; 30-day trial limited to 10 electric/minibus vehicles |
| **HASTUS-OnDemand** | GIRO HASTUS | Microtransit Integration | Integrated planning module bridging scheduled fixed routes with on-demand and flexible transit feeder zones. | $1,400 / month ($16,800 / year base tier) | No free forever plan; 30-day simulation trial limited to 2 flexible service zones |
| **HASTUS-Operations** | GIRO HASTUS | Daily Dispatch & Service Control | Day-of-service dispatch management, vehicle assignments, operator substitution, and delay remediation. | $2,000 / month ($24,000 / year base tier) | No free forever plan; 30-day live dispatch testbed limited to 20 active service runs |
| **HASTUS-Customer** | GIRO HASTUS | Passenger Timetable Publishing | Automated generation of passenger timetables, web timetable APIs, and GTFS schedule exports. | $900 / month ($10,800 / year base tier) | No free forever plan; 14-day export sandbox limited to 5 published timetables |
| **Passio GO!** | Passio Technologies | Passenger Mobile App | Passenger-facing mobile app providing live GPS bus tracking, estimated arrival times, and agency push alerts. | Free for riders; Agency setup from $1,200 / year | Free forever for riders; 30-day agency trial limited to 5 bus GPS feeds |
| **Passio Transit Technologies**| Passio Technologies | Agency Fleet Management | Cloud fleet tracking, automated passenger counts (APC), driver behavior tracking, and maintenance logs. | $100 / vehicle / month ($1,200 / vehicle / year) | No free forever plan; 30-day pilot portal limited to 5 test vehicles |
| **Swiftly Transit Data** | Swiftly | GTFS-RT Pipeline & Data Cleaner | Normalization and validation engine turning raw GPS and CAD/AVL feeds into clean, standardized GTFS-RT data. | $800 / month ($9,600 / year base tier) | No free forever plan; 30-day data pipeline trial limited to 2 GTFS-RT feed outputs |
| **Swiftly Prediction Engine**| Swiftly | Machine Learning ETAs | Machine-learning arrival prediction engine generating accurate real-time predictions for passengers and displays. | $900 / month ($10,800 / year base tier) | No free forever plan; 30-day prediction validation trial limited to 15 bus routes |
| **Remix Planning** | Via / Remix | Route Design & Demographics | Fast transit mapping and demographic accessibility analysis tool used by transit planners for service redesign. | $833 / month ($10,000 / year base tier) | No free forever plan; 14-day sandbox trial limited to 1 urban planning area |
| **Ecolane Scheduler** | Ecolane | Automated Paratransit Routing | Automated continuous optimization engine generating efficient shared-ride paratransit trip itineraries. | $1,000 / month ($12,000 / year base tier) | No free forever plan; 30-day scheduling trial limited to 50 simulated trip manifests |
| **Ecolane Dispatch** | Ecolane | Real-Time Demand Dispatch | Real-time paratransit dispatch console managing same-day cancellations, will-call trips, and driver messaging. | $800 / month ($9,600 / year base tier) | No free forever plan; 30-day dispatch sandbox limited to 10 active driver tablets |
| **Spare Platform** | Spare | Microtransit & Paratransit SaaS | Full-stack platform supporting rider app booking, automated pooling algorithms, driver turn-by-turn navigation, and billing. | $20 / vehicle / month ($1,200 / month min) | No free forever plan; 14-day sandbox trial limited to 5 simulated vehicles |
| **RideCo On-Demand** | RideCo | Dynamic Microtransit SaaS | Cloud routing platform optimizing shared-ride microtransit, paratransit commingling, and first/last mile services. | $3,500 / month ($42,000 / year base tier) | No free forever plan; 30-day simulation pilot limited to 1 microtransit zone and 10 vehicles |
| **Clever Devices CAD/AVL** | Clever Devices | Computer-Aided Dispatch & AVL | Centralized CAD/AVL software giving dispatchers real-time visibility over fleet locations, schedules, and headways. | $2,083 / month ($25,000 / year base tier) | No free forever plan; 30-day telemetry sandbox limited to 10 vehicle tracking streams |
| **Clever Devices TransitMaster**| Clever Devices | Comprehensive ITS Suite | Full-suite intelligent transportation system connecting on-board hardware, voice announcements, APC, and central dispatch. | $3,000 / month ($36,000 / year base tier) | No free forever plan; 30-day pilot testing portal limited to 15 virtual vehicle endpoints |
| **Avail CAD/AVL** | Avail Technologies | Dispatch & GPS Tracking | Dispatch and automatic vehicle location system tailored for fixed-route transit agencies to monitor headway and schedules. | $1,667 / month ($20,000 / year base tier) | No free forever plan; 30-day demo sandbox limited to 10 simulated buses |
| **Vontas TransitMaster** | Vontas | Fleet CAD/AVL & Dispatch | Real-time vehicle management and dispatch platform providing headway management, incident tracking, and driver comms. | $2,083 / month ($25,000 / year base tier) | No free forever plan; 30-day evaluation sandbox limited to 15 vehicle connections |
| **Vontas Planning** | Vontas | Transit Timetabling & Run-Cut | Timetabling, route design, and run-cutting software built for mid-size transit operators. | $1,500 / month ($18,000 / year base tier) | No free forever plan; 30-day scheduling sandbox limited to 10 route files |
| **Moovit Transit Data** | Moovit | Global Transit APIs & Feeds | Developer APIs providing global GTFS schedule queries, multimodal routing, and real-time transit disruption data. | $500 / month ($6,000 / year developer base tier) | Free forever plan for public mobile app; 14-day developer API trial limited to 1,000 test API requests |
| **Via Microtransit** | Via Transportation | Demand-Responsive Software | Algorithmic shared-ride routing platform powering municipal microtransit, night shuttles, and paratransit operations. | $4,000 / month ($48,000 / year base tier) | No free forever plan; 30-day simulation sandbox limited to 1 service zone and 10 vehicles |
| **Via TransitTech** | Via Transportation | Integrated Transit OS | Unified mobility suite uniting fixed-route planning, microtransit dispatch, paratransit operations, and rider apps. | $5,000 / month ($60,000 / year base tier) | No free forever plan; 30-day enterprise evaluation trial limited to 1 unified service zone |



## Open-Source GitHub Projects



### Multimodal Journey Planning



* **OpenTripPlanner**

  One of the most important open-source public-transit projects. Provides multimodal journey planning using transit schedules, OpenStreetMap, bike sharing, ride-hailing, and other mobility services. Supports GTFS, GTFS-RT, NeTEx, OSM, APIs, and real-time service changes.

  Repository: https://github.com/opentripplanner/OpenTripPlanner

  **License:** LGPL.



* **MOTIS**

  Open-source multimodal routing system supporting public transit, walking, cycling, driving, and other mobility modes. Designed as a high-performance journey-planning and mobility-information backend.



* **Navitia**

  Open-source multimodal journey-planning platform originally developed by Kisio Digital/Keolis. Provides routing, schedules, disruption information, and APIs for transit applications.



* **R5**

  Open-source routing engine from Conveyal for multimodal transport analysis. Particularly useful for accessibility analysis, travel-time computation, transit planning, and transport research.



* **Transitous**

  Open-source/open-data public-transit routing ecosystem providing multimodal transit routing using openly available transit feeds and open standards.



* **OpenTripPlanner Analyst**

  Analytical capabilities built around OpenTripPlanner for accessibility and travel-time analysis.



### Real-Time Transit / Passenger Information



* **OneBusAway**

  Open-source real-time transit information system providing APIs and applications for vehicle locations, arrival predictions, route information, and passenger information.



* **AVI**

  Open-source automatic vehicle-location system designed to track public-transit vehicle fleets. It accepts GTFS schedules and vehicle assignments and produces GTFS-Realtime vehicle-location and prediction feeds.



* **Transitime**

  Open-source real-time transit tracking and prediction system capable of ingesting vehicle-location data and generating arrival predictions.



* **The Transit Clock**

  Open-source components and tools for working with transit schedule and real-time information.



* **OpenTransitTools**

  Open-source ecosystem of tools for working with transit data, GTFS, routing, and passenger-information systems.



### GTFS / Transit Data



* **MobilityData GTFS Validator**

  Open-source validator for checking General Transit Feed Specification feeds for structural and semantic problems.



* **GTFS-realtime Validator**

  Tools for validating GTFS-Realtime feeds and identifying errors in vehicle positions, trip updates, alerts, and related real-time data.



* **gtfs-lib**

  Open-source libraries for parsing, generating, and manipulating GTFS datasets.



* **gtfs-kit**

  Python toolkit for working with GTFS feeds, including reading, analysis, validation, and transformation.



* **Partridge**

  Python library for reading GTFS datasets and working with transit schedule data.



* **Transitland**

  Open-source transit-data ecosystem aggregating and exposing transit feeds using open standards.



* **Feed Registry**

  Open-data ecosystem components for discovering and managing public-transit GTFS feeds.



* **osm2gtfs**

  Open-source tooling for generating GTFS transit feeds from OpenStreetMap and related schedule information.



* **TODS**

  Transit Operational Data Standard ecosystem providing an open standard for operational transit schedules and related operational data.



* **GTFS Static**

  Open standard used throughout the transit software ecosystem for scheduled routes, stops, trips, calendars, and service information.



* **GTFS-Realtime**

  Open standard for real-time vehicle positions, trip updates, service alerts, and related transit information.



### Transit Simulation



* **Eclipse SUMO**

  Open-source microscopic traffic and mobility simulation platform. Supports public-transit simulation, route planning, vehicle movement, traffic interactions, and transport-system experimentation.



* **MATSim**

  Open-source agent-based transportation simulation framework useful for evaluating large-scale transport networks and mobility policies.



* **A/B Street**

  Open-source transportation planning and traffic simulation tool with strong support for analyzing streets, intersections, walking, cycling, and public transport.



* **SimMobility**

  Open-source transportation simulation platform developed by MIT for large-scale mobility research.



* **BEAM**

  Open-source agent-based transportation simulation framework built around MATSim and designed for multimodal transportation analysis.



* **SUMO-GTFS Tools**

  Tools and integrations for importing public-transit schedules into SUMO and evaluating operational scenarios.



### Open-Source Transit Applications



* **Trufi App**

  Open-source public-transit application framework for journey planning and transit information.



* **Transitous**

  Open-source mobility-data and routing ecosystem designed around open transit data.



* **OneBusAway**

  Open-source rider-information platform and API.



* **Conveyal Analysis**

  Open-source transit accessibility and network-planning analysis platform associated with the Conveyal ecosystem.



* **OpenTripPlanner UI**

  Open-source web components and applications that can be deployed on top of OpenTripPlanner.



### Open-Source Routing / Mapping Foundations



* **OpenStreetMap**

  Open geographic database providing the street, pedestrian, cycling, and geographic foundation used by many open-source transit routing systems.



* **GraphHopper**

  Open-source routing engine supporting road-network routing and multimodal use cases.



* **OSRM**

  Open-source high-performance routing engine based on OpenStreetMap road data.



* **Valhalla**

  Open-source routing engine supporting automobile, bicycle, pedestrian, and multimodal routing.



* **OpenLayers**

  Open-source web mapping library frequently used for transit mapping applications.



* **Leaflet**

  Open-source JavaScript mapping library commonly used for public-transit maps and operational dashboards.



## Additional Strong Open-Source Options



### Trip Planning & Passenger Information



* **OpenTripPlanner**

* **OneBusAway**

* **MOTIS**

* **Navitia**

* **Transitous**

* **R5**

* **Trufi App**

* **Conveyal Analysis**



These projects are the strongest open-source alternatives for the **passenger information / journey-planning / transit-data** portion of commercial platforms.



### Transit Data & Standards



* **GTFS**

* **GTFS-Realtime**

* **TODS**

* **MobilityData GTFS Validator**

* **Transitland**

* **gtfs-kit**

* **Partridge**

* **osm2gtfs**



The open-data ecosystem around GTFS is arguably the most mature open-source part of public transit software.



### CAD/AVL & Real-Time Operations



* **AVI**

* **Transitime**

* **OneBusAway**

* **GTFS-Realtime tooling**



These projects can provide building blocks for vehicle tracking, real-time feeds, arrival prediction, and passenger information.



### Simulation & Planning Research



* **Eclipse SUMO**

* **MATSim**

* **A/B Street**

* **BEAM**

* **SimMobility**

* **R5**

* **Conveyal Analysis**



These are particularly useful for evaluating **route changes, travel times, accessibility, demand, traffic interactions, fleet movements, and transportation scenarios**.



### Mapping Infrastructure



* **OpenStreetMap**

* **OpenLayers**

* **Leaflet**

* **OSRM**

* **Valhalla**

* **GraphHopper**



These provide the geographic and routing foundation for many custom transit applications.



## Open-Source Public Transit Stack



A modern open-source alternative to a large commercial transit-management suite generally needs to be **composed from multiple projects** rather than purchased as a single open-source package.



```text

                         PUBLIC TRANSIT PLATFORM

                                  │

          ┌───────────────────────┼───────────────────────┐

          │                       │                       │

       PLANNING               OPERATIONS              PASSENGER

          │                       │                   INFORMATION

          │                       │                       │

   ┌──────▼──────┐        ┌───────▼───────┐       ┌──────▼──────┐

   │ Conveyal    │        │ AVI           │       │ OneBusAway  │

   │ R5          │        │ Transitime    │       │ OTP         │

   │ SUMO        │        │ GTFS-RT       │       │ Navitia     │

   └──────┬──────┘        └───────┬───────┘       └──────┬──────┘

          │                       │                       │

          └───────────────────────┼───────────────────────┘

                                  │

                         ┌────────▼────────┐

                         │   GTFS / TODS   │

                         │ Transit Data    │

                         └────────┬────────┘

                                  │

                         ┌────────▼────────┐

                         │ OpenStreetMap   │

                         │ Geographic Data │

                         └────────┬────────┘

                                  │

                    ┌─────────────▼─────────────┐

                    │     Transit APIs /       │

                    │      Applications        │

                    └──────────────────────────┘

```



### A More Complete Open-Source Architecture



```text

                         PUBLIC TRANSIT AGENCY

                                  │

                                  ▼

                     ┌─────────────────────────┐

                     │ Strategic Network Design │

                     │                         │

                     │ Conveyal / R5 / SUMO    │

                     └────────────┬────────────┘

                                  │

                                  ▼

                     ┌─────────────────────────┐

                     │ Schedule / GTFS          │

                     │                         │

                     │ GTFS / TODS / Custom    │

                     └────────────┬────────────┘

                                  │

                ┌─────────────────┼─────────────────┐

                │                 │                 │

                ▼                 ▼                 ▼

          Vehicle Data       Crew Data         Stop Data

                │                 │                 │

                └─────────────────┼─────────────────┘

                                  │

                                  ▼

                     ┌─────────────────────────┐

                     │     Operations Layer    │

                     │                         │

                     │ AVI / Transitime        │

                     │ GTFS-Realtime           │

                     └────────────┬────────────┘

                                  │

                                  ▼

                     ┌─────────────────────────┐

                     │ Journey Planning         │

                     │                         │

                     │ OpenTripPlanner / MOTIS │

                     │ Navitia / Transitous    │

                     └────────────┬────────────┘

                                  │

                ┌─────────────────┼─────────────────┐

                │                 │                 │

                ▼                 ▼                 ▼

           Web App            Mobile App       Open API

                │                 │                 │

                └─────────────────┼─────────────────┘

                                  │

                                  ▼

                           TRANSIT RIDER

```



## Commercial Platform Capability Map



| Capability                 | Commercial Leaders                    | Strong Open-Source Options             |

| -------------------------- | ------------------------------------- | -------------------------------------- |

| Network planning           | Optibus, HASTUS, Remix, Trapeze       | R5, Conveyal, SUMO                     |

| Route design               | Optibus, Remix, HASTUS                | Conveyal, R5, SUMO                     |

| Timetabling                | HASTUS, Trapeze, Optibus              | GTFS tooling, research optimizers      |

| Vehicle blocking           | HASTUS, Trapeze, Optibus              | Mostly custom/research implementations |

| Crew scheduling            | HASTUS, Trapeze, Optibus              | Limited mature OSS alternatives        |

| Crew rostering             | HASTUS, Trapeze                       | Limited mature OSS alternatives        |

| Labor-rule optimization    | HASTUS, Trapeze, Optibus              | Custom optimization required           |

| Fixed-route scheduling     | HASTUS, Trapeze, Optibus              | GTFS tooling + custom optimization     |

| Paratransit                | Ecolane, RouteMatch, Trapeze          | Spare is commercial; OSS is fragmented |

| Demand-responsive transit  | Via, Spare, RideCo, Ecolane           | Open-source components, custom systems |

| CAD/AVL                    | INIT, Trapeze, Clever Devices, Avail  | AVI, Transitime                        |

| Vehicle tracking           | Swiftly, INIT, Clever Devices         | AVI, Transitime                        |

| Dispatch                   | INIT, Trapeze, Clever Devices         | AVI + custom operational UI            |

| GTFS generation            | Commercial scheduling suites          | osm2gtfs, gtfs-kit, custom tools       |

| GTFS validation            | Commercial tools                      | MobilityData validators                |

| GTFS-Realtime              | Swiftly, INIT, Clever Devices         | GTFS-RT ecosystem                      |

| Passenger information      | Passio, INIT, Swiftly, Clever Devices | OneBusAway, OTP                        |

| Journey planning           | Moovit, Optibus, Transit              | OpenTripPlanner, MOTIS, Navitia        |

| Multimodal routing         | Via, Moovit                           | OTP, MOTIS, R5                         |

| Accessibility analysis     | Optibus, Remix, Conveyal              | Conveyal, R5                           |

| Transit simulation         | Commercial simulation suites          | SUMO, MATSim, BEAM                     |

| Traffic simulation         | Various commercial platforms          | SUMO, MATSim                           |

| Mapping                    | Commercial GIS                        | OpenStreetMap, Leaflet, OpenLayers     |

| Real-time prediction       | Swiftly, INIT, Trapeze                | Transitime, custom ML                  |

| Transit data aggregation   | Swiftly, Moovit                       | Transitland, GTFS ecosystem            |

| Passenger mobile apps      | Passio, Via, Moovit                   | Trufi, custom OTP clients              |

| Fleet management           | INIT, Trapeze, Clever Devices         | Custom + AVL components                |

| EV scheduling              | Optibus, HASTUS, INIT                 | SUMO + custom optimization             |

| Depot management           | Trapeze, INIT, Optibus                | Mostly custom                          |

| Fare integration           | INIT, KUBA, Conduent                  | Open standards + custom                |

| Transit analytics          | Swiftly, Optibus, Remix               | R5, SUMO, Python ecosystem             |

| Open data                  | Swiftly, Moovit                       | GTFS, GTFS-RT, Transitland             |

| Real-time passenger alerts | Swiftly, INIT                         | OneBusAway, OTP                        |

| MaaS                       | Via, Moovit, INIT                     | OTP, MOTIS, Navitia                    |

| API infrastructure         | Commercial platforms                  | OTP, Navitia, MOTIS                    |

| Self-hosting               | Limited                               | Strong                                 |

| Source-code access         | Limited                               | Strong                                 |



## SaaS vs Open Source



| Attribute                      | SaaS / Enterprise Platforms                        | Open-Source Ecosystem                                  |

| ------------------------------ | -------------------------------------------------- | ------------------------------------------------------ |

| Full transit-management suite  | INIT, Trapeze, HASTUS, Optibus                     | Usually requires multiple projects                     |

| Network planning               | Strong                                             | Strong for analysis, weaker for production scheduling  |

| Vehicle scheduling             | Very strong                                        | Limited                                                |

| Crew scheduling                | Very strong                                        | Limited                                                |

| Labor-rule handling            | Very strong                                        | Usually custom                                         |

| Paratransit                    | Very strong                                        | Fragmented                                             |

| CAD/AVL                        | Very strong                                        | AVI, Transitime                                        |

| Dispatch                       | Very strong                                        | Requires custom operational layer                      |

| Passenger information          | Strong                                             | Very strong                                            |

| Journey planning               | Strong                                             | Very strong                                            |

| GTFS support                   | Strong                                             | Extremely strong                                       |

| GTFS-Realtime                  | Strong                                             | Extremely strong                                       |

| Transit simulation             | Strong                                             | Extremely strong                                       |

| Accessibility analysis         | Strong                                             | Strong                                                 |

| Geographic data                | Often integrated                                   | OpenStreetMap                                          |

| Customization                  | Vendor APIs/configuration                          | Extremely high                                         |

| Self-hosting                   | Usually limited/available at additional complexity | Core strength                                          |

| Source availability            | Proprietary                                        | Open                                                   |

| Enterprise support             | Strong                                             | Community / specialist vendors                         |

| Implementation effort          | Lower for agency                                   | Higher                                                 |

| Infrastructure ownership       | Vendor-managed or hybrid                           | Agency-managed                                         |

| Vendor lock-in                 | Higher                                             | Lower                                                  |

| Data portability               | Varies                                             | Generally strong with open standards                   |

| Community ecosystem            | Vendor-specific                                    | Broad                                                  |

| Standards support              | Strong                                             | Excellent                                              |

| Best fit                       | Large operational agencies                         | Developers, researchers, agencies with technical teams |

| One-to-one HASTUS replacement  | Yes                                                | Not currently mature                                   |

| One-to-one Trapeze replacement | Yes                                                | Not currently mature                                   |

| One-to-one Optibus replacement | Yes                                                | Not currently mature                                   |

| One-to-one INIT replacement    | Yes                                                | Not currently mature                                   |

| Custom transit platform        | Less flexible                                      | Excellent                                              |



## Open-Source Projects by Transit Function



### 🗺️ Network Planning & Accessibility



* **Conveyal Analysis**

* **R5**

* **Eclipse SUMO**

* **MATSim**

* **A/B Street**

* **BEAM**



### 🚌 Journey Planning



* **OpenTripPlanner**

* **MOTIS**

* **Navitia**

* **Transitous**

* **R5**



### 📡 Real-Time Operations



* **AVI**

* **Transitime**

* **OneBusAway**

* **GTFS-Realtime ecosystem**



### 📊 Transit Data



* **GTFS**

* **GTFS-Realtime**

* **Transitland**

* **MobilityData GTFS Validator**

* **gtfs-kit**

* **Partridge**

* **osm2gtfs**

* **TODS**



### 🌎 Mapping



* **OpenStreetMap**

* **Leaflet**

* **OpenLayers**

* **OSRM**

* **Valhalla**

* **GraphHopper**



### 🚦 Simulation



* **Eclipse SUMO**

* **MATSim**

* **BEAM**

* **SimMobility**

* **A/B Street**



### 📱 Passenger Applications



* **OneBusAway**

* **Trufi App**

* **OpenTripPlanner clients**

* **Transitous ecosystem**



## Building an Open-Source HASTUS / Trapeze Alternative



A serious open-source transit-management platform would need significantly more than a journey planner.



A potential architecture could look like:



```text

                         ┌─────────────────────┐

                         │   Transit Authority │

                         └──────────┬──────────┘

                                    │

                ┌───────────────────┼───────────────────┐

                │                   │                   │

                ▼                   ▼                   ▼

         Network Planning      Scheduling          Demand Model

                │                   │                   │

         Conveyal / R5        Custom Optimizer       SUMO

                │                   │                   │

                └───────────────────┼───────────────────┘

                                    │

                                    ▼

                           ┌─────────────────┐

                           │ GTFS / TODS     │

                           └────────┬────────┘

                                    │

                   ┌────────────────┼────────────────┐

                   │                │                │

                   ▼                ▼                ▼

              Vehicle          Crew / Labor       Depot

              Scheduling        Scheduling       Management

                   │                │                │

                   └────────────────┼────────────────┘

                                    │

                                    ▼

                             Daily Operations

                                    │

                                    ▼

                           ┌─────────────────┐

                           │ AVI / Transitime│

                           │ CAD/AVL Layer   │

                           └────────┬────────┘

                                    │

                         ┌──────────┴──────────┐

                         │                     │

                         ▼                     ▼

                    Dispatch             GTFS-RT

                         │                     │

                         └──────────┬──────────┘

                                    │

                                    ▼

                           Passenger Information

                                    │

                  ┌─────────────────┼─────────────────┐

                  │                 │                 │

                  ▼                 ▼                 ▼

              OpenTripPlanner     OneBusAway      Mobile Apps

                  │                 │                 │

                  └─────────────────┼─────────────────┘

                                    │

                                    ▼

                                  Riders

```



The most difficult components to reproduce as open source are generally **vehicle blocking, crew scheduling, rostering, collective-bargaining-rule handling, depot optimization, dispatch workflows, and tightly integrated agency operations**.



The easiest components to build from open-source foundations are generally **GTFS data management, journey planning, passenger information, real-time vehicle feeds, mapping, accessibility analysis, simulation, and transit APIs**.



## Open Standards



Open standards are especially important in public transit because they allow agencies to connect otherwise independent systems.



### GTFS



**General Transit Feed Specification (GTFS)** describes scheduled public transportation services including:



* Stops

* Routes

* Trips

* Stop times

* Calendars

* Service exceptions

* Transfers

* Shapes

* Fare information

* Frequencies



### GTFS-Realtime



GTFS-Realtime extends the ecosystem with:



* Vehicle positions

* Trip updates

* Service alerts

* Arrival predictions

* Disruptions



### TODS



**Transit Operational Data Standard (TODS)** extends open transit scheduling concepts toward operational information used by planners, dispatchers, drivers, and related systems.



This is particularly interesting for open-source transit management because interoperability between **scheduling systems and CAD/AVL systems** is one of the major architectural challenges in public transportation.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` while following the existing format.

3. Include the project's official website or GitHub repository.

4. For open-source projects, preferably include the license.

5. Include a concise description of the project's public-transit capabilities.

6. Clearly distinguish between:



   * **Transit Planning**

   * **Scheduling**

   * **Crew Scheduling**

   * **Rostering**

   * **CAD/AVL**

   * **Dispatch**

   * **Paratransit**

   * **Demand-Responsive Transit**

   * **Fleet Management**

   * **Passenger Information**

   * **Journey Planning**

   * **Transit Data**

   * **Transit Simulation**

   * **MaaS**

7. Submit a PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



* This is a **community-curated** list — not exhaustive and not an endorsement.

* Public transit management is a very broad category. Some products listed here are focused on **planning**, some on **scheduling**, some on **CAD/AVL**, some on **passenger information**, and others on **demand-responsive transportation**.

* Commercial products frequently combine several of these categories into integrated suites.

* The open-source ecosystem is considerably more mature in **GTFS, journey planning, real-time passenger information, mapping, routing, simulation, and data tooling** than in complete enterprise-grade **crew scheduling, rostering, vehicle blocking, labor-rule optimization, and daily transit operations**.

* OpenTripPlanner should not be treated as a complete HASTUS/Trapeze replacement. It is primarily an open-source multimodal journey-planning and transit-information platform.

* Similarly, SUMO, MATSim, R5, Conveyal, and related projects provide important planning, simulation, or analysis capabilities but do not constitute complete transit-management suites.

* Transit agencies deploying software for live operations must consider safety, labor agreements, accessibility requirements, cybersecurity, service reliability, data protection, and local regulatory requirements.

* Product names, ownership, capabilities, pricing, and licensing can change over time. Always verify the current status before adopting a platform or project.



---



**Made for transit planners, public transportation agencies, scheduling teams, operations managers, dispatchers, fleet managers, transportation researchers, agency IT teams, mobility developers, and open-source transit engineers.**



**Let's make public transportation more open, interoperable, data-driven, efficient, and passenger-centric.**
