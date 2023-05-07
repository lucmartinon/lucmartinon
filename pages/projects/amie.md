---
layout: default
title: AMIE's intranet
parent: Projects
nav_order: 4
---
# AMIE's intranet

### AMIE: Accueil des Mineur.e.s Isolé.e.s Étranger.e.s
AMIE is a french NGO helping young unaccompanied migrants arriving in Lyon. They offer counseling once a week, and guidance in the various procedures that they have to face alone, especially since France is almost always refusing to consider them as minor.

AMIE exists since 2016 and has helped more than 2500 migrants since. The volunteers - mostly retired women - help young migrants in complex and different procedures (suing the state to have their minority recognized, getting into school, into the healthcare system, etc.). They need to a way to share the status of the different procedures. For long it was a gigantic Excel file that was updated once a week and shared by Dropbox.

### The intranet
After meeting a few times with some of the volunteers, I designed and setup an intranet that allows to follow and update the status of the different procedures for each of the young migrant they help, as well as a safe way to store documents. It sits on a Postgres database, and uses <a href="https://www.appsmith.com/" target="_blank">Appsmith</a>, an open-source low-code solution.

While the project is nothing spectacular from the tech point of view, I am proud of the solution found: it meets the needs while keeping the complexity as low as possible. The low-code solution has so far been super easy to adapt when changes are needed. And since the tech-stack is entirely open-source, there are only very low hosting costs for the association.
