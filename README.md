# Scout24 IT Principles

### History
This are the guiding principles that we came up with during our [Project Tatsu](http://inside.autoscout24.com/project_tatsu/2015/01/04/autoscout24-changes-technology-aws-linux-jvm/). We learned that those principles are valuable and later used them to drive the cultural alignment between ImmobilienScout24 and AutoScout24. As a result we now have common *Scout24 IT Principles*.

The first team in project Tatsu was closely aligned on how we should approach "microservices in the cloud". When more and more teams joined Tatsu, previously obvious decisions, became harder to explain. And decisions by new members were in conflict with our implicit understanding, of how things should work. So we made our implicit understanding explicit and created our principles.

### Usage
The value of those principles comes from the common understanding they create and the guidance they provide around new ideas and solutions. We can avoid deadlocks and lengthy discussions.

To create a common understanding, we regularly talk about them. New colleagues get an introduction to the principles. We print them on big papers and pin them to the walls.

We also constantly evolve our principles. We value feedback and change proposals.

### Disclaimer for non Scout24 employees
These are the Scout24 IT Principles. Don't just copy them! Some of the principles might be considered common sense for a microservices architecture and are generic enough to be reused. Your culture is different and the journey is valuable. So please take the time, to come up with your own principles :-).

**Make your own. Keep evolving.**


### Principles as markdown
PowerPoint and PDF files can be found in the repository.

This is quick transfer into markdown:

| STRATEGIC GOALS<br>Goals of the business side                                                                               | ARCHITECTURALPRINCIPLES<br>High-Level Principle                                                                                                              | DESIGN AND DELIVERY PRINCIPLES<br>Tactical measures                                                                                                                                      |
|---------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| REDUCE TIME TO MARKET<br>Speed, Fast Feedback                                                                                 | ORGANIZED AROUND BUSINESS CAPABILITIES<br>Build teams around products not projects. Follow the domain and respect bounded contexts. Inverse Conway Maneuver. | YOU BUILT IT, YOU RUN IT<br>The team is responsible for shaping, building, running and maintaining its products. Fast feedback from live and customers helps us to continuously improve. |
| COST EFFICIENCY<br>Collect metrics to allow decisions cost vs. value.                                                         | CONTAINMENT AND BOUNDARIES<br>Align blast radius and vendor lock-in with the boundaries of the organization or business capabilities.                        | COLLABORATION CULTURE<br>Engineers from all backgrounds work together in collaborative teams as engineers and share responsibilities. No silos.                                          |
| SUPPORT DATA-DRIVEN DECISIONS<br>Listen to users and validate hypothesis.Provide as many relevant metrics & data as possible. | ELIMINATE ACCIDENTAL COMPLEXITY<br>Strive to keep it simple. Focus on essential complexity. You build one, you delete one.                                   | AUTONOMOUS TEAMS<br>Make fast local decisions. Be responsible. Know your boundaries. Share findings.                                                                                     |
| ONE SCOUT IT<br>Big things should be common.                                                                                  | LOOSELY COUPLED<br>By default avoid sharing and tight coupling, except for the big things in common. Don’t create the next monolith.                         | BE BOLD<br>Go into production early. Value monitoring over tests. Recover and learn. Optimize for MTTR not MTBF.                                                                         |
| OPTIMIZE FOR GROWTH<br>Don’t optimize for forced exit but for voluntary exit at our speed.                                    | MACRO AND MICRO ARCHITECTURE<br>Clear separation. Autonomous micro services within the rules and constraints of the macro architecture.                      | DATA-DRIVEN / METRIC-DRIVEN<br>Collect metrics from processes and applications. Analyze, alert and act on them.                                                                          |
|                                                                                                                           | SECURITY, COMPLIANCE AND DATA PRIVACY<br>Security must be included from the beginning and everybody’s concern. Keep data-privacy in mind.                    | INFRASTRACTURE AS CODE<br>Automate everything: Reproducible, traceable and tested.Immutable servers over snowflake servers.                                                              |
|                                                                                                                           | AWS FIRST<br>Favor AWS platform service over managed service, over self-hosted OSS, over self-rolled solutions.                                              |                                                                                                                                                                                      |
 
