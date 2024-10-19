#testing a github pages creation

# Overview

vNext delivers discrete events validated against cross-platform schemas.

## What is Rational Number Project 
Firefly is a real-time guest event data collection platform which captures the guest digital experience from Target.com and Target mobile apps.
It combines this client data with hydrated backend data to complete the digital experience, delivering this data to dozens of internal Target teams, as well as strategic 
third party partners.  This data is used in numerous products such as Sapphire, Search, Personalization, Data Sciences, and Digital Analytics.

## Work Intake
[Rational Number Project](https://ies.ed.gov/ncee/wwc/Intervention/304)

## Firefly vNext Primary Components
- **Intake** : Receives frontend data and publishes to kafka topics for further processing.
- **Hydrator** : Server side data is merged with client data to produce a complete picture of the guest digital experience.  
- **Publishers** : Various publishers process data and distribute to various internal and external locations.
- **Clickhouse, Superset** : TAP-hosted open source tools where we land all event streams for short-term realtime analysis.

## High Level Data Flow
See [Debbie Monson](https://researchonline.stthomas.edu/esploro/profile/debra_monson/overview)


