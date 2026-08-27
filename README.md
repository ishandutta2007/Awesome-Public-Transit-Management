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



* **INIT**

  Integrated public-transport technology provider covering planning, scheduling, intermodal transport control, fleet management, passenger information, ticketing, and related operational systems. Its MOBILE suite includes planning systems such as MOBILE-PLAN and MOBILE-PERDIS and the MOBILE-ITCS intermodal transport control system.



* **Trapeze Group**

  Major transit software ecosystem covering scheduling, workforce management, operations, dispatch, maintenance, passenger information, paratransit, fixed-route planning, and transit asset management. Trapeze's products are used across bus, rail, paratransit, and demand-responsive operations.



* **GIRO HASTUS**

  Enterprise public-transit planning and operations suite covering network planning, timetabling, vehicle scheduling, crew scheduling, operations, on-demand transportation, customer information, and system integration. HASTUS is particularly strong in complex scheduling and optimization.



* **Ecolane**

  Transit scheduling and dispatch platform particularly focused on paratransit, demand-responsive transportation, non-emergency transportation, and flexible mobility services.



* **Passio Technologies**

  Transit technology platform providing passenger information, vehicle tracking, transit apps, digital signage, fleet monitoring, and related transit-management capabilities.



* **Optibus**

  Cloud-native public transportation operating platform covering network planning, scheduling, rostering, operations, real-time control and monitoring, passenger information, and driver workflows. Its optimization engine handles vehicle and crew scheduling and operational constraints.



* **Swiftly**

  Transit data and operations platform focused on real-time vehicle tracking, transit performance analytics, passenger information, service planning, prediction, and operational intelligence.



* **Via / Remix**

  Via's Remix platform provides map-based transit planning, network redesign, scenario analysis, service planning, and transportation network design. Remix became part of Via's broader transportation technology ecosystem.



* **RouteMatch**

  Transit-management software historically focused on demand-response/paratransit scheduling, dispatch, reservations, and transportation operations. RouteMatch became part of the Trapeze ecosystem.



* **Avail Technologies**

  Transit technology provider offering CAD/AVL, dispatch, passenger information, real-time operations, scheduling, and related public transportation software.



* **Clever Devices**

  Public transportation technology provider specializing in intelligent transportation systems, CAD/AVL, real-time passenger information, fleet management, transit signal priority, and operational technology.



* **Vontas**

  Transit software portfolio covering planning, scheduling, operations, CAD/AVL, passenger information, demand-response transportation, and transit analytics.



* **Modaxo Transit**

  Transportation technology group containing multiple public-transit software businesses across planning, scheduling, operations, fleet, passenger information, and mobility management.



* **Spare**

  Cloud-based demand-responsive transit and paratransit platform covering booking, scheduling, dispatch, optimization, driver tools, and rider communications.



* **RideCo**

  On-demand public transportation platform for dynamically routed transit, microtransit, demand-responsive transportation, booking, dispatch, and real-time fleet management.



* **Via Transportation**

  Digital transportation platform providing on-demand transit, microtransit, transit technology, network design, and software for public transportation agencies and operators.



* **Moovit**

  Transit mobility platform providing journey planning, transit data, passenger information, MaaS capabilities, and transit-agency data services.



* **Transit**

  Passenger-facing public transportation application providing real-time transit information, journey planning, vehicle tracking, and multimodal transportation information.



* **Swiftly Transit Operations**

  Operations-oriented platform providing transit agencies with real-time data, service monitoring, vehicle predictions, analytics, and tools for improving reliability.



* **KUBA**

  Public transport technology provider focused on fare collection, ticketing, account-based ticketing, passenger information, and integrated transit systems.



* **GMV**

  Transportation technology provider offering fleet management, CAD/AVL, passenger information, scheduling, traffic management, and intelligent transportation systems.



* **Conduent Transportation**

  Enterprise transportation technology portfolio covering fare collection, transit operations, intelligent transportation systems, tolling, and mobility technology.



* **INIT MOBILE-ITCS**

  INIT's real-time intermodal transport control system for dispatchers and control centers, providing network visibility, vehicle monitoring, disruption management, and operational control.



* **INIT MOBILE-PLAN**

  Planning and scheduling component of INIT's transit ecosystem for planning networks, schedules, vehicles, and operational resources.



* **INIT MOBILE-PERDIS**

  INIT's personnel-disposition and workforce-planning solution for transit operations.



* **Trapeze PASS**

  Fixed-route transit planning and scheduling ecosystem covering route planning, schedules, vehicle blocks, operator duties, and operational planning.



* **Trapeze OPS**

  Operations-focused software for transit agencies, including dispatch, service monitoring, schedules, trips, crew assignments, and real-time operational workflows.



* **Trapeze Workforce Management**

  Workforce platform covering operator sign-ups, bidding, dispatch, timekeeping, workforce management, and payroll integration.



* **Trapeze FX**

  Transit scheduling and operations software family associated with fixed-route transit planning and scheduling.



* **Trapeze EAM**

  Enterprise asset-management capabilities for transit fleets and maintenance operations.



* **Trapeze PASS-Web**

  Web-oriented transit scheduling and planning workflows within the Trapeze ecosystem.



* **HASTUS-PLAN**

  HASTUS planning module for designing transit networks and evaluating service changes.



* **HASTUS-Vehicle**

  Vehicle scheduling and blocking module for creating optimized vehicle schedules, blocks, trips, and timetables.



* **HASTUS-Crew**

  Crew scheduling module for constructing optimized operator duties while considering labor rules, qualifications, breaks, and operational constraints.



* **HASTUS-MiniBus**

  Specialized HASTUS capability for planning and scheduling smaller or flexible transit operations, including electric-bus operations.



* **HASTUS-OnDemand**

  Demand-responsive and on-demand transportation planning and scheduling capability.



* **HASTUS-Operations**

  Operational control capabilities for managing service changes, assignments, disruptions, and day-to-day transit operations.



* **HASTUS-Customer**

  Customer-information functionality for communicating schedules, service information, and transit changes.



* **Passio GO**

  Passenger-facing transit information and tracking solution providing real-time vehicle information and transit agency communication.



* **Passio Transit Technologies**

  Broader Passio ecosystem covering vehicle tracking, passenger information, mobile applications, digital signage, and transit technology.



* **Swiftly Transit Data**

  Transit data platform focused on collecting, normalizing, analyzing, and operationalizing transit vehicle and service data.



* **Swiftly Prediction Engine**

  Real-time prediction capabilities for vehicle arrival and service performance.



* **Remix Planning**

  Transit network planning and scenario-analysis platform enabling agencies to design routes, compare scenarios, evaluate accessibility, and communicate service changes.



* **Ecolane Scheduler**

  Demand-responsive and paratransit scheduling engine designed to optimize trips, vehicle assignments, and operational resources.



* **Ecolane Dispatch**

  Dispatch and operational-management capabilities for demand-responsive transportation.



* **Spare Platform**

  Digital infrastructure for demand-responsive transportation including rider booking, scheduling, dispatch, driver applications, and service management.



* **RideCo On-Demand Transit**

  Dynamic transit-management platform supporting booking, vehicle routing, dispatch, passenger communications, and demand-responsive operations.



* **Clever Devices CAD/AVL**

  Computer-aided dispatch and automatic vehicle-location technology for monitoring transit vehicles, managing service, and supporting real-time operations.



* **Clever Devices TransitMaster**

  Transit management and CAD/AVL ecosystem used for real-time fleet management, dispatch, passenger information, and operational control.



* **Avail CAD/AVL**

  Computer-aided dispatch and automatic vehicle-location capabilities for fixed-route transit operations.



* **Vontas TransitMaster**

  Transit operations platform associated with CAD/AVL, dispatch, passenger information, and transit fleet management.



* **Vontas Planning**

  Planning and scheduling tools for transit agencies.



* **Moovit Transit Data**

  Transit-data platform supplying schedules, real-time information, routing, and mobility data to agencies and mobility applications.



* **Via Microtransit**

  Software platform for public agencies operating demand-responsive and dynamically routed transit services.



* **Via TransitTech**

  Broader technology platform integrating transit planning, on-demand services, routing, fleet operations, and passenger-facing applications.



* **INIT MOBILEguide**

  Passenger information and transit communication capabilities within INIT's ecosystem.



* **INIT MOBILEstop**

  Passenger-information technology for stops and transit stations.



* **INIT MOBILEefficiency**

  Transit operational and efficiency capabilities focused on optimizing fleet and energy use.



* **INIT MOBILEvario**

  Flexible transit-management capabilities supporting changing service and operational requirements.



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
