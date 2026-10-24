AFTERLIGHT — THE DAY-ONE RECOVERY NETWORK
Flipkart APM '29 | Product case-study prototype | Version 2
========================================================

ONE-LINE PITCH
"When half the world disappears, the other half connects."
AFTERLIGHT helps communities locate essential resources, request assistance, coordinate verified local responders, and track handovers in the first 72 hours after the fictional 2018 Snap.

1. THE PROBLEM
In the day after Thanos's Snap, people may need medicine, food, water or shelter while providers lose staff and normal communication is disrupted. The key problem is not simply a shortage of goods: it is a coordination gap. A person in need cannot reliably identify a working provider, confirm stock, find someone to collect essentials, or know whether help is on the way.

2. WHY THIS IS DESIGNED FOR 2018
Food delivery and ride-hailing businesses existed in 2018, but their coverage was uneven, and a sudden crisis could disrupt their workers and operations. AFTERLIGHT DOES NOT REQUIRE Swiggy, Zomato, Rapido, Porter or any commercial delivery integration. Instead, the proposed real-world model builds on existing local residents, participating NGOs, NSS/NCC groups, pharmacies and community organizations. Availability, safety and participation must be verified; no organization is assumed to be operational.

3. RAHUL'S MEDICINE STORY — THE COMPLETE JOURNEY
A. Rahul submits an SOS request: "Medicine needed", North District, high urgency.
B. AFTERLIGHT suggests a sample pharmacy in the relevant area. A suggestion is NOT a stock guarantee.
C. In a real deployment, authorized pharmacy staff confirm availability and whether the medicine can legally and safely be dispensed. In this demo, the button SIMULATES that confirmation.
D. Rahul chooses one of THREE fulfillment modes:
   - SELF-PICKUP: Rahul goes to the confirmed pharmacy and collects the medicine if travel is safe and possible.
   - COMMUNITY VOLUNTEER DELIVERY: A verified local responder accepts the delivery task, collects appropriately dispensed medicine, and delivers it to Rahul. No commercial courier is required.
   - RELIEF HUB PICKUP: An approved neighborhood relief desk coordinates a local pickup point, where legally permitted and properly staffed. A hub is not a substitute for a licensed pharmacy.
E. The tracker records the chosen route. In the demo, volunteer or hub assignment is a simulated button action.
F. Rahul confirms receipt, closing the request. A resource match or volunteer assignment alone does NOT count as completion.

WHAT IF THERE IS NO VOLUNTEER?
The request remains pending. The product would offer self-pickup where feasible or seek assistance through an approved local relief desk. It must never claim delivery is guaranteed.

4. THE PROPOSED COMMUNITY RESCUE NETWORK
- Participating pharmacy staff: verify supply, dispensing requirements, and safe handover.
- Verified community volunteers: accept feasible pickup and delivery tasks.
- NGOs, NSS/NCC and local residents: support non-medical coordination where participating and available.
- Neighborhood relief desk coordinators: log requests, help match volunteers, and coordinate permitted pickup points.
- Requester: chooses fulfillment mode and confirms actual receipt.
In a real system, volunteer identity checks, safeguarding, consent, privacy, prescription rules and safe handling are mandatory. The demo does not perform these checks.

5. WHY RELIEF HUBS MATTER
Direct point-to-point delivery can fail if vehicles, roads or volunteers are unavailable. Participating neighborhood relief hubs could batch non-medical assistance, provide local coordination and help residents who cannot use a smartphone. Any medication handling must remain under authorized professional supervision. Hubs in this demo are fictional.

6. WHAT IF INTERNET SERVICE FAILS?
2018-compatible proposed fallbacks: SMS request IDs, telephone assistance, and in-person registration at approved relief desks. These are FUTURE PRODUCT IDEAS only. The supplied prototype does not send SMS, make calls, synchronize across devices or operate a real dispatch network. The website itself runs offline with sample data.

7. PROTOTYPE SCREENS
COMMAND CENTER: Crisis context, 72-hour timeline, open/completed requests, and Recovery Pulse.
RESOURCE RADAR: Filterable fictional listings with update labels; listing data is unverified.
REQUEST HELP: Submit a need, area, urgency and fulfillment mode (delivery, self-pickup or hub).
MATCH ENGINE: Suggest a category/area match and SIMULATE provider confirmation.
RECOVERY TRACKER: For delivery, assign a demo volunteer before receipt; for hub pickup, assign a demo hub before receipt; for self-pickup, confirm receipt after provider confirmation.
RELIEF HUBS: Explains proposed local desks and 2018-compatible fallback channels.
IMPACT SIMULATOR: Adjust resources, volunteers and connectivity to explore an illustrative readiness score. Not a validated forecast.

8. EXACT EVALUATOR WALKTHROUGH (4–5 MINUTES)
1) Open index.html; show Command Center and explain the Day +1 coordination gap.
2) Select Resource Radar -> Medicine; show Northside Community Pharmacy and its unverified demo label.
3) Open Request Help; enter Rahul, Medicine, North District, High urgency, choose "Community volunteer delivery", and submit.
4) In Match Engine, choose "Simulate provider confirmation". Explain that real-world verification would be required.
5) Open Recovery Tracker. Click "Assign demo volunteer"; explain that in a real deployment a screened community responder would accept the task.
6) Click "Confirm received" to close Rahul's request. Show Command Center's updated Recovery Pulse.
7) Optionally create a second request choosing "Self-pickup" or "Collect at neighborhood relief hub" to show alternative routes.
8) Open Relief Hubs to explain phone/SMS/in-person fallback proposals and why the product does not depend on delivery platforms.
9) Open Impact Simulator; reduce connectivity to show the limitations and tradeoffs of the proposed network.
10) Click "Reset demo" to restore sample requests for another walkthrough.

9. WHAT MAKES THE CONCEPT DISTINCTIVE
- End-to-end fulfillment, not just a list of nearby resources.
- Three realistic delivery routes rather than dependence on commercial platforms.
- Community relief desks and 2018-compatible fallback channels.
- Transparent request status and explicit receipt confirmation.
- Recovery Pulse (demo completion percentage) and scenario simulator for discussing tradeoffs.
This is a proposed product differentiation, not a claim of novelty or demonstrated effectiveness.

10. METRICS FOR A REAL PILOT
Time to first verified resource confirmation; time to responder acceptance; percentage of requests actually received; number of stale resource listings; percentage of urgent needs resolved; user task completion and satisfaction. Do not confuse demo completion counts with real-world impact.

11. IMPORTANT RISKS / SAFEGUARDS
Resource information may be stale. Volunteers may not be available or safe to dispatch. Medicine requires authorized dispensing and may require prescriptions or controlled storage. Request details can expose personal data. Networks and roads may fail. The product should prioritize verified information, consent, minimal data collection, and transparent pending states. It cannot replace emergency services.

12. WHAT THE PROTOTYPE REALLY DOES
Runs fully in a browser with HTML, CSS and JavaScript. Contains fictional resource records and seed requests. Uses a simple category/area matching heuristic; there is no live map, distance computation, inventory check, provider integration, authentication, SMS, dispatch, payments, or real delivery. All assignments, confirmation and receipt statuses are manually simulated. Request data is saved in browser localStorage and can be reset. Do not enter real sensitive information.

13. HOW TO RUN
Extract the ZIP, then double-click index.html in Chrome, Edge, Firefox or Safari. No server or internet is needed. If testing a new journey, click "Reset demo". Keep index.html, style.css and script.js in the same folder.

14. SUBMISSION REMINDER
The prototype ZIP is one deliverable. The case study PDF is a separate required deliverable, using the prescribed template and assignment constraints. Do not present this README as the required PDF.

FILES_
index.html — UI and screen content
style.css — visual design and responsive layout
script.js — sample data, requests, matching, simulated handovers and simulator
README.txt — product rationale, evaluation script and instructions
