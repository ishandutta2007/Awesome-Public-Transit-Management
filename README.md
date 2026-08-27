# ðŸšŒ Awesome Public Transit Management

<div align="center">

![Awesome Public Transit Management Banner](assets/banner.svg)

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Public-Transit-Management/stargazers"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Public-Transit-Management?style=flat-square&logo=github&color=gold" alt="Stars"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Public-Transit-Management/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Public-Transit-Management?style=flat-square&color=blue" alt="Forks"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Public-Transit-Management/issues"><img src="https://img.shields.io/github/issues/ishandutta2007/Awesome-Public-Transit-Management?style=flat-square&color=green" alt="Issues"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Public-Transit-Management/pulls"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square" alt="PRs Welcome"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Public-Transit-Management/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square" alt="License"/></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

**A curated index of top SaaS platforms, enterprise suites, CAD/AVL software, GTFS tooling, microtransit dispatch engines, and open-source transportation technologies.**

*Search Keywords: Public Transit Management, CAD/AVL, GTFS, GTFS-Realtime, Transit Scheduling, Crew Rostering, Paratransit, On-Demand Microtransit, Passenger Information Systems (PIS), Multimodal Journey Planning, Transit Simulation, Smart City Mobility.*

**Last updated: August 2026**

</div>

---

## ðŸ“‘ Table of Contents

* [ðŸŒ Market Overview & Ecosystem](#-market-overview--ecosystem)
* [ðŸ¢ SaaS & Hosted Platforms](#-saashosted-platforms)
  * [Major Transit Management SaaS Platforms](#major-transit-management-saas-platforms)
  * [Specialized SaaS Modules & Sub-Systems](#specialized-saas-modules--sub-systems)
* [ðŸ’» Open-Source GitHub Projects](#-open-source-github-projects)
  * [ðŸ—ºï¸ Mapping & Spatial Web Foundations](#ï¸-mapping--spatial-web-foundations)
  * [ðŸš¦ Traffic, Transit & Urban Simulation](#-traffic-transit--urban-simulation)
  * [ðŸ§­ Multimodal Journey & Route Planning](#-multimodal-journey--route-planning)
  * [ðŸ“Š GTFS Tooling, Parsers & Transit Data Infrastructure](#-gtfs-tooling-parsers--transit-data-infrastructure)
  * [ðŸ“¡ CAD/AVL, Real-Time Dispatch & Passenger Applications](#-cadavl-real-time-dispatch--passenger-applications)
* [ðŸ§© Open-Source Public Transit Stack](#-open-source-public-transit-stack)
* [ðŸ—ºï¸ Commercial Platform Capability Map](#ï¸-commercial-platform-capability-map)
* [âš–ï¸ SaaS vs Open Source](#ï¸-saas-vs-open-source)
* [ðŸ“ Open Standards (GTFS, GTFS-RT, TODS, NeTEx)](#-open-standards)
* [â­ Star History](#-star-history)
* [ðŸ¤ How to Contribute](#-how-to-contribute)
* [ðŸ“œ Disclaimer](#-disclaimer)

---

## ðŸŒ Market Overview & Ecosystem

Public transit management software coordinates **network planning, timetable synchronization, vehicle blocking, collective-bargaining crew scheduling, CAD/AVL telemetry, real-time dispatch, paratransit/NEMT, demand-responsive transit (DRT), passenger information, automated fare collection (AFC), transit simulation, and GTFS/GTFS-RT pipelines**.

* **Open-Source Strengths:** GTFS/GTFS-RT validation, multimodal journey planning (OTP, MOTIS), accessibility analytics (R5), microscopic traffic simulation (SUMO, MATSim), map rendering (Leaflet, MapLibre), and open transit data standards.
* **Commercial SaaS Strengths:** Tightly integrated mathematical optimization engines for driver duty run-cutting, complex union labor rules, depot charging management, mission-critical real-time operations, and turn-key CAD/AVL hardware integration.

> **ðŸ’¡ Architectural Note:** There is no single open-source repository that completely substitutes an end-to-end enterprise suite like HASTUS or Trapeze. Production-grade open transit stacks are assembled by orchestrating **OpenTripPlanner / MOTIS, OneBusAway, R5, SUMO, OpenStreetMap, and custom dispatch layers**.

---

## ðŸ¢ SaaS/Hosted Platforms

> ðŸ“Š **Estimated Market Size & Sector Fragmentation:**  
> The global **Public Transit & Intelligent Transportation Systems (ITS)** software market is valued at approximately **$35.8 Billion in 2025â€“2026** and is projected to expand to **$68.5+ Billion by 2032**, registering a compound annual growth rate (CAGR) of **~10.8%**. The sector is **moderately fragmented**: core enterprise domains (driver union scheduling, fixed-route master blocking, and rail operations) remain consolidated among established global transport conglomerates (Modaxo/Trapeze, GIRO HASTUS, INIT, and Conduent), while fast-growing cloud verticals (AI dynamic scheduling, on-demand microtransit pooling, and machine-learning GTFS-RT arrival prediction) are actively driven by agile venture-backed innovators (Optibus, Via, Spare, RideCo, and Swiftly).

### Major Transit Management SaaS Platforms

*Sorted by Company Size / Valuation / Revenue (Descending)*

| Platform / Vendor | Company Size / Valuation / Revenue | Focus Areas & Core Capabilities | Description | Pricing (Starting Tier) | Free Tier / Free Trial Limits |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Conduent Transportation** | **~$3.7B Revenue** (Parent Conduent Inc.) | Enterprise Fare Collection, Tolling & Fleet CAD/AVL | Global transit technology suite delivering automated fare collection (AFC), transit operations management, CAD/AVL integration, and mobility analytics. | $4,166 / month ($50,000 / year base enterprise tier) | No free forever plan; 30-day integration testbed limited to 5 test fare gates and 20 simulated vehicle transponders |
| **Via Transportation / Remix** | **~$3.5B Valuation** (~$200M+ ARR) | Microtransit, Network Planning, On-Demand Routing | Turnkey and SaaS mobility platform offering algorithmic vehicle pooling, dynamic routing, Remix transit planning, and rider booking apps. | $4,000 / month ($48,000 / year base on-demand SaaS tier) | No free forever plan; 30-day simulation environment limited to 1 virtual service zone and 10 vehicle simulations |
| **Optibus** | **~$1.3B Valuation** (Unicorn, ~$90M ARR) | Cloud-Native Scheduling, Rostering, EV & Operations | Cloud-native public transportation platform powered by AI optimization for route planning, timetabling, vehicle blocking, crew rostering, EV charging scheduling, and live operations. | $1,500 / month ($18,000 / year base planning tier) | No free forever plan; 14-day sandbox trial limited to 1 agency network model and up to 50 route variations |
| **Moovit** | **~$900M Valuation** (Intel Mobility Division) | Multimodal MaaS, Transit Data APIs, On-Demand Routing | Urban mobility platform and data service providing passenger navigation, transit APIs, trip planning SDKs, and flexible on-demand microtransit dispatch. | $1.99 / month (Moovit+ app) or $500 / month for Developer Transit Data API | Free forever plan includes ad-supported multimodal journey planning & arrival alerts; 7-day free trial for Moovit+ (ad-free & SafeRide) |
| **INIT** | **~$260M Revenue** (â‚¬240M+ / Frankfurt: IXX) | Integrated ITS, Planning, CAD/AVL, Ticketing | Integrated public transport technology provider covering planning, scheduling, intermodal transport control (MOBILE-ITCS), fleet management, passenger info, and account-based ticketing. | $3,333 / month ($40,000 / year base license) | No free forever plan; 30-day sandbox pilot trial limited to synthetic telemetry of 15 test vehicles |
| **Modaxo Transit** | **~$250M+ Revenue** (Constellation Software Group) | Global Transportation Software Portfolio Solutions | Global conglomerate operating dedicated transit technology business units covering scheduling, ticketing, CAD/AVL, and passenger data systems. | $2,500 / month ($30,000 / year base portfolio module tier) | No free forever plan; 30-day pilot deployment limited to 1 selected subsidiary tool and 15 simulated vehicles |
| **Trapeze Group** | **~$200M+ Revenue** (Modaxo Subsidiary) | Enterprise Scheduling, Workforce, CAD/AVL, Paratransit | Major enterprise transit software ecosystem spanning fixed-route scheduling, operations dispatch, operator bidding/workforce management, paratransit, and EAM. | $2,083 / month ($25,000 / year base single module) | No free forever plan; 30-day guided pilot evaluation limited to 20 vehicle records and 5 operator rosters |
| **Clever Devices** | **~$150M Revenue** | Intelligent Transportation Systems (ITS), CAD/AVL, RTPI | Provider of on-board vehicle computers, transit signal priority, automated voice announcements, automated vehicle monitoring, and control center CAD/AVL. | $2,083 / month ($25,000 / year base cloud analytics tier) | No free forever plan; 30-day telemetry evaluation sandbox limited to 10 vehicle tracking data streams |
| **GIRO HASTUS** | **~$120M Revenue** (CAD $160M+) | Advanced Timetabling, Vehicle/Crew Optimization, Rostering | Leading enterprise transit planning and operations suite known for mathematical optimization algorithms handling complex vehicle blocking, collective bargaining, and crew scheduling. | $2,500 / month ($30,000 / year base scheduling tier) | No free forever plan; 30-day proof-of-concept sandbox trial limited to 1 depot and up to 30 vehicle blocks |
| **GMV** | **~$110M+ Revenue** (ITS Division / â‚¬400M+ Group) | ITS, Fleet Management, CAD/AVL & Ticketing | Global intelligent transport systems provider offering cloud-based CAD/AVL (Syncromatics), real-time passenger info displays, and ticketing hardware. | $1,800 / month ($21,600 / year base cloud tracking tier) | No free forever plan; 30-day live tracking portal trial limited to 10 active GPS trackers / test vehicles |
| **Swiftly** | **~$300M Valuation** (~$35M ARR) | Real-Time Transit Data, CAD/AVL, Prediction Analytics | Cloud-based transit data engine providing high-accuracy vehicle arrival predictions, real-time dispatch tools, speed maps, and on-time performance analytics. | $1,000 / month ($12,000 / year base GPS tier) | No free forever plan; 30-day live pilot trial limited to 25 tracked vehicles and 5 active routes |
| **Spare** | **~$150M Valuation** (~$20M ARR) | On-Demand Transit, Paratransit, Microtransit Dispatch | Cloud-based microtransit and paratransit software providing automated on-demand dispatch, driver apps, pooling optimization, and rider booking interfaces. | $20 / vehicle / month ($1,200 / month minimum tier) | No free forever plan; 14-day sandbox dispatch trial limited to 5 test vehicles and 50 simulated bookings |
| **RideCo** | **~$80M Valuation** (~$15M ARR) | Demand-Responsive Transit & Microtransit Optimization | High-capacity microtransit and paratransit platform focusing on dynamic routing, shared-ride optimization, automated dispatch, and agency fleet coordination. | $3,500 / month ($42,000 / year base platform tier) | No free forever plan; 30-day agency pilot simulation limited to 1 designated zone and 10 active vehicles |
| **Transit** | **~$60M Valuation** (~$12M ARR) | Consumer Journey Planning & Real-Time Tracking | Passenger-facing mobile navigation app providing real-time vehicle positions, crowdsourced trip tracking (GO), multimodal routing, and agency mobility integrations. | $4.99 / month or $24.99 / year (Transit Royale); Agency sponsorship from $1,200 / year | Free forever plan includes real-time ETA for 2 closest routes per mode and navigation; 7-day free trial for Transit Royale (unlimited routes/maps) |
| **KUBA** | **~$50M Revenue** (Part of Modaxo) | Account-Based Ticketing, cEMV Payments & Back Office | Smart transit ticketing platform delivering open-loop contactless cEMV payments, mobile ticketing, validation hardware integrations, and cloud fare engines. | $1,000 / month base cloud fee plus 2.5% + $0.05 per fare transaction | No free forever plan; 14-day developer sandbox trial limited to 100 test ticketing transactions and 2 virtual validators |
| **Ecolane** | **~$45M Revenue** (Modaxo Subsidiary) | Paratransit Scheduling, NEMT, Dynamic Dispatch | Specialized demand-response scheduling engine designed for paratransit and non-emergency medical transportation with automated dispatch and driver manifest management. | $1,250 / month ($15,000 / year base tier) | No free forever plan; 30-day pilot trial limited to historical simulation of up to 100 daily paratransit trips |
| **Avail Technologies** | **~$35M Revenue** | Municipal CAD/AVL, ITS, Fixed-Route Operations | Transit operations and CAD/AVL software tailored to small and medium-sized public transit agencies for dispatch, tracking, and NTD compliance reporting. | $1,667 / month ($20,000 / year base municipal software tier) | No free forever plan; 30-day staging demo limited to 1 pre-configured agency network and 10 simulated buses |
| **Vontas** | **~$35M Revenue** (Modaxo Subsidiary) | Fixed-Route CAD/AVL, Dispatch, Planning & Yard Management | Transit management spin-off of Trapeze providing CAD/AVL (TransitMaster), passenger communications, yard management, and modular scheduling tools. | $2,083 / month ($25,000 / year base module tier) | No free forever plan; 30-day software evaluation sandbox limited to 15 vehicle connections and 2 dispatch seats |
| **RouteMatch** | **~$20M Revenue** (Trapeze / Modaxo) | Paratransit Dispatch, Demand-Response & Billing | Paratransit and flexible-route scheduling platform providing trip booking, automated vehicle scheduling, and coordinated human services transit. | $1,500 / month ($18,000 / year base rural/small-agency tier) | No free forever plan; 14-day paratransit dispatch simulation limited to 10 test vehicles and 50 reservations |
| **Passio Technologies** | **~$20M Revenue** | Real-Time Fleet Tracking, Passenger Info, Smart Signage | Transit technology suite delivering passenger apps (Passio GO!), automated passenger counting (APC), GPS fleet tracking, and on-board digital display integration. | $100 / vehicle / month ($1,200 / vehicle / year starting tier) | Free forever mobile app for riders; 30-day agency evaluation trial limited to 5 test vehicle tracking feeds |

---

### Specialized SaaS Modules & Sub-Systems

*Sorted by Parent Suite / Vendor Revenue & Valuation (Descending)*

| Product / Module | Parent Platform | Parent Valuation / Size | Functional Area | Description | Pricing (Starting Tier) | Free Tier / Free Trial Limits |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Remix Planning** | Via / Remix | ~$3.5B Valuation | Route Design & Demographics | Fast transit mapping and demographic accessibility analysis tool used by transit planners for service redesign. | $833 / month ($10,000 / year base tier) | No free forever plan; 14-day sandbox trial limited to 1 urban planning area |
| **Via Microtransit** | Via Transportation | ~$3.5B Valuation | Demand-Responsive Software | Algorithmic shared-ride routing platform powering municipal microtransit, night shuttles, and paratransit operations. | $4,000 / month ($48,000 / year base tier) | No free forever plan; 30-day simulation sandbox limited to 1 service zone and 10 vehicles |
| **Via TransitTech** | Via Transportation | ~$3.5B Valuation | Integrated Transit OS | Unified mobility suite uniting fixed-route planning, microtransit dispatch, paratransit operations, and rider apps. | $5,000 / month ($60,000 / year base tier) | No free forever plan; 30-day enterprise evaluation trial limited to 1 unified service zone |
| **Moovit Transit Data** | Moovit | ~$900M Valuation | Global Transit APIs & Feeds | Developer APIs providing global GTFS schedule queries, multimodal routing, and real-time transit disruption data. | $500 / month ($6,000 / year developer base tier) | Free forever plan for public mobile app; 14-day developer API trial limited to 1,000 test API requests |
| **INIT MOBILE-ITCS** | INIT | ~$260M Revenue | CAD/AVL & Dispatch | Real-time intermodal transport control system for dispatchers and operations control centers with live incident intervention. | $2,500 / month ($30,000 / year base tier) | No free forever plan; 30-day testbed limited to 10 virtual vehicle telemetry feeds |
| **INIT MOBILE-PLAN** | INIT | ~$260M Revenue | Network Planning | Planning and scheduling component for designing route networks, timetables, block creation, and vehicle duties. | $2,000 / month ($24,000 / year base tier) | No free forever plan; 30-day evaluation trial limited to 1 transit sub-network (max 20 lines) |
| **INIT MOBILE-PERDIS** | INIT | ~$260M Revenue | Crew Rostering & Dispatch | Personnel disposition and duty rostering system considering driver preferences, working hour regulations, and shift bidding. | $1,800 / month ($21,600 / year base tier) | No free forever plan; 30-day staging sandbox limited to 25 driver profiles and 1 roster cycle |
| **INIT MOBILEguide** | INIT | ~$260M Revenue | Passenger Information | Omnichannel real-time passenger information engine feeding web widgets, mobile apps, and smart displays. | $800 / month ($9,600 / year base tier) | No free forever plan; 14-day API sandbox limited to 5 stop location feeds |
| **INIT MOBILEstop** | INIT | ~$260M Revenue | Station Infotainment | Station and stop digital signage management for electronic paper and LED/LCD passenger arrival displays. | $600 / month ($7,200 / year base tier) | No free forever plan; 14-day digital display sandbox limited to 3 virtual digital sign outputs |
| **INIT MOBILEefficiency** | INIT | ~$260M Revenue | Eco-Driving & Fleet Analytics | Vehicle driving style analysis, energy consumption optimization, and electric bus battery state-of-charge monitoring. | $1,200 / month ($14,400 / year base tier) | No free forever plan; 30-day analytics trial limited to 10 vehicle CAN-bus streams |
| **INIT MOBILEvario** | INIT | ~$260M Revenue | Fare Management | Modular fare calculation and fare collection software managing multi-tariff structures and smart card ticketing. | $1,500 / month ($18,000 / year base tier) | No free forever plan; 14-day tariff simulation sandbox limited to 50 test transactions |
| **Trapeze PASS** | Trapeze Group | ~$200M+ Revenue | Paratransit Scheduling | Comprehensive demand-response and paratransit scheduling tool managing client eligibility, ride booking, and routing. | $2,000 / month ($24,000 / year base tier) | No free forever plan; 30-day pilot trial limited to 10 test vehicles and 100 client records |
| **Trapeze OPS** | Trapeze Group | ~$200M+ Revenue | Dispatch & Real-Time Ops | Real-time operations management tool handling day-of-service operator sign-ins, vehicle pull-outs, and detour logging. | $1,750 / month ($21,000 / year base tier) | No free forever plan; 30-day operational sandbox limited to 20 daily runs |
| **Trapeze Workforce** | Trapeze Group | ~$200M+ Revenue | Crew Bidding & Timekeeping | Operator workforce platform managing automated seniority bidding, daily dispatch rosters, timekeeping, and payroll export. | $1,500 / month ($18,000 / year base tier) | No free forever plan; 30-day workforce sandbox limited to 30 operator profiles |
| **Trapeze FX** | Trapeze Group | ~$200M+ Revenue | Fixed-Route Scheduling | Fixed-route scheduling software for creating master timetables, vehicle interlining, and driver run-cutting. | $1,800 / month ($21,600 / year base tier) | No free forever plan; 30-day scheduling demo limited to 10 route master files |
| **Trapeze EAM** | Trapeze Group | ~$200M+ Revenue | Fleet Asset Management | Enterprise transit asset management software for preventative vehicle maintenance, parts inventory, and work order tracking. | $1,600 / month ($19,200 / year base tier) | No free forever plan; 30-day maintenance sandbox limited to 25 vehicle asset records |
| **Trapeze PASS-Web** | Trapeze Group | ~$200M+ Revenue | Rider Web Portal | Web booking interface allowing paratransit riders and care facilities to book and manage trips online. | $750 / month ($9,000 / year base tier) | No free forever plan; 14-day web portal trial limited to 20 test passenger accounts |
| **Clever Devices CAD/AVL** | Clever Devices | ~$150M Revenue | Computer-Aided Dispatch & AVL | Centralized CAD/AVL software giving dispatchers real-time visibility over fleet locations, schedules, and headways. | $2,083 / month ($25,000 / year base tier) | No free forever plan; 30-day telemetry sandbox limited to 10 vehicle tracking streams |
| **Clever Devices TransitMaster**| Clever Devices | ~$150M Revenue | Comprehensive ITS Suite | Full-suite intelligent transportation system connecting on-board hardware, voice announcements, APC, and central dispatch. | $3,000 / month ($36,000 / year base tier) | No free forever plan; 30-day pilot testing portal limited to 15 virtual vehicle endpoints |
| **HASTUS-PLAN** | GIRO HASTUS | ~$120M Revenue | Network Design & Timetabling | Strategic network design and corridor timetable development with multi-scenario service evaluation. | $2,000 / month ($24,000 / year base tier) | No free forever plan; 30-day planning sandbox limited to 15 route alignments |
| **HASTUS-Vehicle** | GIRO HASTUS | ~$120M Revenue | Vehicle Blocking Optimization | High-performance vehicle block optimization minimizing deadhead mileage, vehicle requirements, and layover times. | $2,200 / month ($26,400 / year base tier) | No free forever plan; 30-day optimization trial limited to 25 peak vehicle schedules |
| **HASTUS-Crew** | GIRO HASTUS | ~$120M Revenue | Crew Run-Cutting & Rostering | Mathematical crew scheduling optimizer satisfying union rules, break regulations, overtime constraints, and shift preferences. | $2,500 / month ($30,000 / year base tier) | No free forever plan; 30-day optimization sandbox limited to 30 operator duties |
| **HASTUS-MiniBus** | GIRO HASTUS | ~$120M Revenue | Small Fleet & EV Scheduling | Specialized scheduling module for paratransit, on-demand shuttles, and electric bus battery replenishment management. | $1,500 / month ($18,000 / year base tier) | No free forever plan; 30-day trial limited to 10 electric/minibus vehicles |
| **HASTUS-OnDemand** | GIRO HASTUS | ~$120M Revenue | Microtransit Integration | Integrated planning module bridging scheduled fixed routes with on-demand and flexible transit feeder zones. | $1,400 / month ($16,800 / year base tier) | No free forever plan; 30-day simulation trial limited to 2 flexible service zones |
| **HASTUS-Operations** | GIRO HASTUS | ~$120M Revenue | Daily Dispatch & Service Control | Day-of-service dispatch management, vehicle assignments, operator substitution, and delay remediation. | $2,000 / month ($24,000 / year base tier) | No free forever plan; 30-day live dispatch testbed limited to 20 active service runs |
| **HASTUS-Customer** | GIRO HASTUS | ~$120M Revenue | Passenger Timetable Publishing | Automated generation of passenger timetables, web timetable APIs, and GTFS schedule exports. | $900 / month ($10,800 / year base tier) | No free forever plan; 14-day export sandbox limited to 5 published timetables |
| **Swiftly Transit Data** | Swiftly | ~$300M Valuation | GTFS-RT Pipeline & Data Cleaner | Normalization and validation engine turning raw GPS and CAD/AVL feeds into clean, standardized GTFS-RT data. | $800 / month ($9,600 / year base tier) | No free forever plan; 30-day data pipeline trial limited to 2 GTFS-RT feed outputs |
| **Swiftly Prediction Engine**| Swiftly | ~$300M Valuation | Machine Learning ETAs | Machine-learning arrival prediction engine generating accurate real-time predictions for passengers and displays. | $900 / month ($10,800 / year base tier) | No free forever plan; 30-day prediction validation trial limited to 15 bus routes |
| **Spare Platform** | Spare | ~$150M Valuation | Microtransit & Paratransit SaaS | Full-stack platform supporting rider app booking, automated pooling algorithms, driver turn-by-turn navigation, and billing. | $20 / vehicle / month ($1,200 / month min) | No free forever plan; 14-day sandbox trial limited to 5 simulated vehicles |
| **RideCo On-Demand** | RideCo | ~$80M Valuation | Dynamic Microtransit SaaS | Cloud routing platform optimizing shared-ride microtransit, paratransit commingling, and first/last mile services. | $3,500 / month ($42,000 / year base tier) | No free forever plan; 30-day simulation pilot limited to 1 microtransit zone and 10 vehicles |
| **Ecolane Scheduler** | Ecolane | ~$45M Revenue | Automated Paratransit Routing | Automated continuous optimization engine generating efficient shared-ride paratransit trip itineraries. | $1,000 / month ($12,000 / year base tier) | No free forever plan; 30-day scheduling trial limited to 50 simulated trip manifests |
| **Ecolane Dispatch** | Ecolane | ~$45M Revenue | Real-Time Demand Dispatch | Real-time paratransit dispatch console managing same-day cancellations, will-call trips, and driver messaging. | $800 / month ($9,600 / year base tier) | No free forever plan; 30-day dispatch sandbox limited to 10 active driver tablets |
| **Avail CAD/AVL** | Avail Technologies | ~$35M Revenue | Dispatch & GPS Tracking | Dispatch and automatic vehicle location system tailored for fixed-route transit agencies to monitor headway and schedules. | $1,667 / month ($20,000 / year base tier) | No free forever plan; 30-day demo sandbox limited to 10 simulated buses |
| **Vontas TransitMaster** | Vontas | ~$35M Revenue | Fleet CAD/AVL & Dispatch | Real-time vehicle management and dispatch platform providing headway management, incident tracking, and driver comms. | $2,083 / month ($25,000 / year base tier) | No free forever plan; 30-day evaluation sandbox limited to 15 vehicle connections |
| **Vontas Planning** | Vontas | ~$35M Revenue | Transit Timetabling & Run-Cut | Timetabling, route design, and run-cutting software built for mid-size transit operators. | $1,500 / month ($18,000 / year base tier) | No free forever plan; 30-day scheduling sandbox limited to 10 route files |
| **Passio GO!** | Passio Technologies | ~$20M Revenue | Passenger Mobile App | Passenger-facing mobile app providing live GPS bus tracking, estimated arrival times, and agency push alerts. | Free for riders; Agency setup from $1,200 / year | Free forever for riders; 30-day agency trial limited to 5 bus GPS feeds |
| **Passio Transit Technologies**| Passio Technologies | ~$20M Revenue | Agency Fleet Management | Cloud fleet tracking, automated passenger counts (APC), driver behavior tracking, and maintenance logs. | $100 / vehicle / month ($1,200 / vehicle / year) | No free forever plan; 30-day pilot portal limited to 5 test vehicles |

---

## ðŸ’» Open-Source GitHub Projects

*Each open-source repository is annotated with its live GitHub star badge (linking directly to its stargazers page) and sorted by total star count in descending order.*

### ðŸ—ºï¸ Mapping & Spatial Web Foundations

*Foundational client-side map rendering engines and geospatial web toolkits utilized across modern transit dashboards, AVL map displays, and journey planner interfaces.*

* **[Leaflet](https://github.com/Leaflet/Leaflet)** [![GitHub stars](https://img.shields.io/github/stars/Leaflet/Leaflet?style=social&color=white)](https://github.com/Leaflet/Leaflet/stargazers)  
  Leading lightweight, open-source JavaScript library for mobile-friendly interactive transit maps, stop markers, and real-time vehicle movement visualizations.
* **[OpenLayers](https://github.com/openlayers/openlayers)** [![GitHub stars](https://img.shields.io/github/stars/openlayers/openlayers?style=social&color=white)](https://github.com/openlayers/openlayers/stargazers)  
  High-performance, feature-packed spatial mapping engine supporting complex GIS projections, Vector Tiles, WMS/WFS, and high-density vehicle fleet layers.
* **[MapLibre GL JS](https://github.com/maplibre/maplibre-gl-js)** [![GitHub stars](https://img.shields.io/github/stars/maplibre/maplibre-gl-js?style=social&color=white)](https://github.com/maplibre/maplibre-gl-js/stargazers)  
  Open-source TypeScript WebGL map rendering engine rendering high-fps vector tiles, 3D transit lines, and dynamic smooth vehicle animations.

---

### ðŸš¦ Traffic, Transit & Urban Simulation

*Microscopic, mesoscopic, and agent-based transportation simulation platforms for analyzing transit priority, dedicated bus lanes, EV charging, and fleet scaling.*

* **[A/B Street](https://github.com/a-b-street/abstreet)** [![GitHub stars](https://img.shields.io/github/stars/a-b-street/abstreet?style=social&color=white)](https://github.com/a-b-street/abstreet/stargazers)  
  Interactive traffic and transit simulation game/tool using OpenStreetMap to prototype dedicated bus lanes, signal timing adjustments, and active mobility interventions.
* **[Eclipse SUMO](https://github.com/eclipse-sumo/sumo)** [![GitHub stars](https://img.shields.io/github/stars/eclipse-sumo/sumo?style=social&color=white)](https://github.com/eclipse-sumo/sumo/stargazers)  
  Highly scalable, microscopic multi-modal traffic simulation suite supporting scheduled transit vehicles, passenger boarding dynamics, and vehicle emissions modeling.
* **[MATSim](https://github.com/matsim-org/matsim-libs)** [![GitHub stars](https://img.shields.io/github/stars/matsim-org/matsim-libs?style=social&color=white)](https://github.com/matsim-org/matsim-libs/stargazers)  
  Extensible multi-agent transportation simulation framework modeling individual daily travel plans, public transit usage patterns, and congestion pricing policies.
* **[BEAM](https://github.com/LBNL-UCB-STI/beam)** [![GitHub stars](https://img.shields.io/github/stars/LBNL-UCB-STI/beam?style=social&color=white)](https://github.com/LBNL-UCB-STI/beam/stargazers)  
  Behavior, Energy, Autonomy, and Mobility agent-based simulation model built on MATSim to evaluate electric transit fleets, grid charging, and shared mobility fleets.

---

### ðŸ§­ Multimodal Journey & Route Planning

*High-throughput routing backends, transit routing algorithms (RAPTOR, CSA), and accessibility computation tools using GTFS and OpenStreetMap.*

* **[OSRM (Open Source Routing Machine)](https://github.com/Project-OSRM/osrm-backend)** [![GitHub stars](https://img.shields.io/github/stars/Project-OSRM/osrm-backend?style=social&color=white)](https://github.com/Project-OSRM/osrm-backend/stargazers)  
  Ultra-fast C++ routing engine based on Contraction Hierarchies, commonly used for transit deadhead path calculations and road-network distance matrix generation.
* **[GraphHopper](https://github.com/graphhopper/graphhopper)** [![GitHub stars](https://img.shields.io/github/stars/graphhopper/graphhopper?style=social&color=white)](https://github.com/graphhopper/graphhopper/stargazers)  
  Fast Java routing engine supporting customizable vehicle profiles, turn restrictions, isochrone generation, and integrated public transit routing algorithms.
* **[Valhalla](https://github.com/valhalla/valhalla)** [![GitHub stars](https://img.shields.io/github/stars/valhalla/valhalla?style=social&color=white)](https://github.com/valhalla/valhalla/stargazers)  
  Open-source multimodal routing engine with a tiled dynamic routing pipeline, supporting transit schedule routing, elevation, and complex multimodal transfers.
* **[OpenTripPlanner (OTP)](https://github.com/opentripplanner/OpenTripPlanner)** [![GitHub stars](https://img.shields.io/github/stars/opentripplanner/OpenTripPlanner?style=social&color=white)](https://github.com/opentripplanner/OpenTripPlanner/stargazers)  
  The flagship open-source public transit journey planner worldwide. Implements the Range-RAPTOR routing algorithm, GTFS-RT real-time updates, NeTEx, OSM walking/biking graphs, and GraphQL APIs.
* **[OpenRouteService](https://github.com/GIScience/openrouteservice)** [![GitHub stars](https://img.shields.io/github/stars/GIScience/openrouteservice?style=social&color=white)](https://github.com/GIScience/openrouteservice/stargazers)  
  Geographic routing platform built on OSM data for multimodal travel times, isochrones, matrix calculations, and accessibility evaluations.
* **[Transportr](https://github.com/grote/Transportr)** [![GitHub stars](https://img.shields.io/github/stars/grote/Transportr?style=social&color=white)](https://github.com/grote/Transportr/stargazers)  
  Privacy-friendly public transport assistant for Android connecting to global open transit networks and public transport authorities without proprietary tracking.
* **[MOTIS](https://github.com/motis-project/motis)** [![GitHub stars](https://img.shields.io/github/stars/motis-project/motis?style=social&color=white)](https://github.com/motis-project/motis/stargazers)  
  Multi-modal journey planning and timetable information system optimized for ultra-fast query execution, real-time delays, and multi-day train/bus connections.
* **[Navitia](https://github.com/hove-io/navitia)** [![GitHub stars](https://img.shields.io/github/stars/hove-io/navitia?style=social&color=white)](https://github.com/hove-io/navitia/stargazers)  
  Battle-tested web service API for journey planning, line departure boards, disruption management, and transit data query services.
* **[Conveyal R5](https://github.com/conveyal/r5)** [![GitHub stars](https://img.shields.io/github/stars/conveyal/r5?style=social&color=white)](https://github.com/conveyal/r5/stargazers)  
  Rapid Realistic Routing on Real-world and Reimagined networks. Specialized in computing fast accessibility matrices, cumulative opportunity measures, and travel-time distributions.
* **[Peartree](https://github.com/kuanb/peartree)** [![GitHub stars](https://img.shields.io/github/stars/kuanb/peartree?style=social&color=white)](https://github.com/kuanb/peartree/stargazers)  
  Python library that converts GTFS transit feeds into NetworkX directed multigraphs for network topology analysis and transit accessibility research.

---

### ðŸ“Š GTFS Tooling, Parsers & Transit Data Infrastructure

*Utilities, validation tools, data cleaners, format converters, and data store solutions for General Transit Feed Specification datasets.*

* **[Node-GTFS](https://github.com/BlinkTagInc/node-gtfs)** [![GitHub stars](https://img.shields.io/github/stars/BlinkTagInc/node-gtfs?style=social&color=white)](https://github.com/BlinkTagInc/node-gtfs/stargazers)  
  Node.js library that imports GTFS data into SQLite databases and provides comprehensive helper methods for querying routes, stops, schedules, and real-time feeds.
* **[MobilityData GTFS Validator](https://github.com/MobilityData/gtfs-validator)** [![GitHub stars](https://img.shields.io/github/stars/MobilityData/gtfs-validator?style=social&color=white)](https://github.com/MobilityData/gtfs-validator/stargazers)  
  The official canonical open-source tool for validating GTFS Static datasets, verifying semantic rules, timetable consistency, and spatial sanity.
* **[GTFS-to-HTML](https://github.com/BlinkTagInc/gtfs-to-html)** [![GitHub stars](https://img.shields.io/github/stars/BlinkTagInc/gtfs-to-html?style=social&color=white)](https://github.com/BlinkTagInc/gtfs-to-html/stargazers)  
  Automated tool that reads GTFS schedule feeds and compiles accessible, printable HTML timetables and route charts for agency websites.
* **[GTFS-to-GeoJSON](https://github.com/BlinkTagInc/gtfs-to-geojson)** [![GitHub stars](https://img.shields.io/github/stars/BlinkTagInc/gtfs-to-geojson?style=social&color=white)](https://github.com/BlinkTagInc/gtfs-to-geojson/stargazers)  
  Converts transit routes and stop locations from a GTFS feed into GeoJSON format for rapid GIS mapping and spatial analysis.
* **[GTFS-Kit](https://github.com/mrcagney/gtfs_kit)** [![GitHub stars](https://img.shields.io/github/stars/mrcagney/gtfs_kit?style=social&color=white)](https://github.com/mrcagney/gtfs_kit/stargazers)  
  Python library for reading, validating, transforming, computing service speeds, and extracting statistics from GTFS feeds using Pandas.
* **[GTFS-Realtime Validator](https://github.com/CUTR-at-USF/gtfs-realtime-validator)** [![GitHub stars](https://img.shields.io/github/stars/CUTR-at-USF/gtfs-realtime-validator?style=social&color=white)](https://github.com/CUTR-at-USF/gtfs-realtime-validator/stargazers)  
  Java-based validation application developed by USF/CUTR that compares GTFS-RT feeds against GTFS static schedules to flag real-time mismatch errors.
* **[Transitland Lib](https://github.com/interline-io/transitland-lib)** [![GitHub stars](https://img.shields.io/github/stars/interline-io/transitland-lib?style=social&color=white)](https://github.com/interline-io/transitland-lib/stargazers)  
  Go library providing core extraction, normalization, and validation primitives for reading and manipulating GTFS, GTFS-RT, and Transmodel datasets.

---

### ðŸ“¡ CAD/AVL, Real-Time Dispatch & Passenger Applications

*Open-source Automatic Vehicle Location (AVL), Computer-Aided Dispatch (CAD) backends, vehicle tracking prediction engines, and passenger mobile interfaces.*

* **[OneBusAway](https://github.com/OneBusAway/onebusaway)** [![GitHub stars](https://img.shields.io/github/stars/OneBusAway/onebusaway?style=social&color=white)](https://github.com/OneBusAway/onebusaway/stargazers)  
  Widely adopted open-source transit information platform providing real-time bus tracking, arrival predictions, SMS/Voice feeds, and multi-agency APIs.
* **[OneBusAway Application Modules](https://github.com/OneBusAway/onebusaway-application-modules)** [![GitHub stars](https://img.shields.io/github/stars/OneBusAway/onebusaway-application-modules?style=social&color=white)](https://github.com/OneBusAway/onebusaway-application-modules/stargazers)  
  Core server backend modules for OneBusAway handling GTFS schedule caching, vehicle location matching, and arrival estimation algorithms.
* **[The Transit Clock](https://github.com/CUTR-at-USF/transit-clock)** [![GitHub stars](https://img.shields.io/github/stars/CUTR-at-USF/transit-clock?style=social&color=white)](https://github.com/CUTR-at-USF/transit-clock/stargazers)  
  Open-source arrival prediction and AVL processing engine (formerly Transitime) generating high-accuracy GTFS-RT TripUpdate and VehiclePosition feeds.
* **[Trufi App](https://github.com/trufi-association/trufi-app)** [![GitHub stars](https://img.shields.io/github/stars/trufi-association/trufi-app?style=social&color=white)](https://github.com/trufi-association/trufi-app/stargazers)  
  Cross-platform Flutter mobile application designed for public transport in emerging markets with strong support for informal transit routes.

---

## ðŸ§© Open-Source Public Transit Stack

A production open-source architecture for a municipal transit authority is assembled from complementary specialized components:

```text
                          â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”
                          â”‚   PUBLIC TRANSIT AGENCY   â”‚
                          â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”¬â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜
                                        â”‚
           â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”¼â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”
           â”‚                            â”‚                            â”‚
           â–¼                            â–¼                            â–¼
  STRATEGIC PLANNING            OPERATIONS & CAD/AVL          PASSENGER INFORMATION
           â”‚                            â”‚                            â”‚
   Conveyal / R5 / SUMO         Transit Clock / AVI          OpenTripPlanner / MOTIS
  Accessibility & Routing     GTFS-Realtime Telemetry       OneBusAway / Trufi App
           â”‚                            â”‚                            â”‚
           â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”¼â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜
                                        â”‚
                               â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â–¼â”€â”€â”€â”€â”€â”€â”€â”€â”
                               â”‚   GTFS / TODS   â”‚
                               â”‚  Transit Data   â”‚
                               â””â”€â”€â”€â”€â”€â”€â”€â”€â”¬â”€â”€â”€â”€â”€â”€â”€â”€â”˜
                                        â”‚
                               â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â–¼â”€â”€â”€â”€â”€â”€â”€â”€â”
                               â”‚  OpenStreetMap  â”‚
                               â”‚ Geographic Data â”‚
                               â””â”€â”€â”€â”€â”€â”€â”€â”€â”¬â”€â”€â”€â”€â”€â”€â”€â”€â”˜
                                        â”‚
                         â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â–¼â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”
                         â”‚   Web & Mobile Client Apps   â”‚
                         â”‚ Leaflet / MapLibre / HTML5  â”‚
                         â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜
```

---

## ðŸ—ºï¸ Commercial Platform Capability Map

| Transit Capability | Commercial Market Leaders | Strong Open-Source Alternatives |
| :--- | :--- | :--- |
| **Network Planning & Redesign** | Optibus, Remix (Via), HASTUS-PLAN | Conveyal R5, SUMO, Peartree |
| **Timetable Generation** | GIRO HASTUS, Trapeze FX, Optibus | Custom solvers, Node-GTFS, GTFS-to-HTML |
| **Vehicle Blocking Optimization** | HASTUS-Vehicle, Optibus, Trapeze | Custom OR-Tools / ILP mathematical models |
| **Crew Scheduling & Union Rostering** | HASTUS-Crew, Optibus, Trapeze Workforce | Limited mature OSS (custom MIP / heuristics) |
| **CAD / Automatic Vehicle Location** | INIT MOBILE-ITCS, Clever Devices, Avail, GMV | The Transit Clock, OneBusAway |
| **Real-Time GTFS-RT Predictions** | Swiftly, INIT, Clever Devices | The Transit Clock, OneBusAway Core |
| **On-Demand Microtransit & Paratransit**| Via Transportation, Spare, RideCo, Ecolane | Custom OpenTripPlanner / VRP algorithms |
| **Multimodal Passenger Journey Planning**| Transit, Moovit, Optibus | OpenTripPlanner 2, MOTIS, Navitia |
| **Map Rendering & Fleet Visuals** | Proprietary GIS Platforms | Leaflet, MapLibre GL JS, OpenLayers |
| **Microscopic Urban Simulation** | PTV Vissim, Aimsun | Eclipse SUMO, MATSim, A/B Street, BEAM |
| **Account-Based Ticketing (ABT)** | KUBA, INIT MOBILEvario, Conduent | Open standards + custom payment gateways |

---

## âš–ï¸ SaaS vs Open Source

| Dimension | SaaS / Commercial Platforms | Open-Source Transit Stack |
| :--- | :--- | :--- |
| **Enterprise Crew/Duty Run-Cutting** | Industry standard; handles multi-tier union rules | Requires bespoke mathematical modeling (e.g. CBC/SCIP) |
| **Deployment Speed** | Rapid cloud onboarding (SaaS) | Moderate to High (multi-service integration) |
| **Data Ownership & Portability** | Vendor API dependent | 100% Agency owned via open GTFS/TODS standards |
| **Real-Time Passenger Info (RTPI)** | High accuracy turn-key ML pipelines | Mature & robust via OneBusAway, OTP & Transit Clock |
| **Customizability** | Constrained to vendor product roadmap | Complete flexibility for custom algorithms & UI |
| **Upfront License & Subscription** | Annual recurring contract fees | $0 Software license cost; infrastructure & maintenance |

---

## ðŸ“ Open Standards

Interoperability across transit planning and operational hardware depends on established open standards:

* ðŸš **GTFS (General Transit Feed Specification - Static):** The global data format for transit schedules, stops, routes, service calendars, shapes, and fares.
* ðŸ›°ï¸ **GTFS-Realtime (GTFS-RT):** Protocol buffer specification transmitting live vehicle positions, trip arrival updates, and service disruption alerts.
* ðŸ“Š **TODS (Transit Operational Data Standard):** Open data specification standardizing operational schedules and deadhead details between scheduling and CAD/AVL software.
* ðŸ‡ªðŸ‡º **NeTEx (Network Timetable Exchange):** European CEN standard for exchanging detailed public transport scheduled network information.
* ðŸš² **GBFS (General Bikeshare Feed Specification):** Open data standard for real-time shared micromobility availability (bikes, scooters, docks).

---

## â­ Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Public-Transit-Management&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Public-Transit-Management&type=date&legend=top-left)

---

## ðŸ¤ How to Contribute

Contributions are welcome! Please follow these guidelines:

1. Fork this repository.
2. Add your suggested platform or open-source tool ensuring correct categorization.
3. For SaaS products, include specific starting tier pricing and explicit free tier / free trial limits.
4. For Open-Source projects, link to the GitHub repository and include the official stargazer badge `[![GitHub stars](https://img.shields.io/github/stars/<owner>/<repo>?style=social&color=white)](https://github.com/<owner>/<repo>/stargazers)`.
5. Submit a concise Pull Request describing the addition.

â­ **Star this repository** if you find it helpful for public transit technology research!

---

## ðŸ“œ Disclaimer

* This repository is a **community-curated index** for informational and educational purposes.
* Product names, trademarks, logos, and company valuations belong to their respective owners.
* Pricing tiers, contract terms, and subscription limits are subject to change by vendors. Always consult vendors directly during municipal transit procurement and RFP procedures.

---

<div align="center">
  <b>Built for transit planners, schedulers, dispatchers, transit agency IT teams, and open-source mobility engineers worldwide.</b>
</div>
