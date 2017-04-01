# PCF-Ops-Workshop
PCF Ops Workshop
# Pivotal Cloud Foundry Workshop for Thales

## Proposed Workshop Design & Schedule
* Installation (2 days)
 * June 22-23, 2016
* DevOps Workshop (1 day)
 * August 10, 2016
* pre-work for AppDev Workshop (1 week)
 * _TBD_
* AppDev Workshop (1 day)
 * _TBD_


## Topics

__Installation__
* PCF on AWS (vanilla, no LDAP)
* PCF & PCF Partner Services
 * MySQL
 * Redis
 * Rabbit
 * Spring Cloud Services
 * Jenkins Enterprise
 * others? (see network.pivotal.io)

__DevOps Workshop__
* Platform Administration -- 1 hour (10-11am) -- Ravi
  * Users, Orgs, Spaces, Quotas \[[slides](Presentations/ThalesDevOps_OrgsSpaces.pptx)][[lab](Labs/Lab-OrgsSpaces.adoc)]
  * Service Broker [[slides](Presentations/ThalesDevOps_BuildpacksServices.pdf)][[lab](Labs/Lab-ServiceBroker.adoc)]
  * Buildpacks [[slides](Presentations/ThalesDevOps_BuildpacksServices.pdf)][[lab](Labs/Lab-Buildpack.adoc)]
  * Custom Buildpacks [[blog](http://engineering.pivotal.io/post/creating-a-custom-buildpack/)] [[blog](http://engineering.pivotal.io/post/making-a-useful-c++-buildpack/)]
* [Platform Upgrades & Stemcell Updates](Presentations/DevOps_Workshop-Patching_and_Upgrading.pdf) -- 30 minutes (11-11:30am) -- Vivian
* Working Lunch:  [Bosh](Presentations/Bosh_Fundamentals.pdf) (Labs 1-4) -- 2 hours (11:30am-1:30pm) -- Vivian
  * [Lab1 - Environment Setup & Test](Labs/Lab01-Start_and_Test_Env.adoc)
  * [Lab2 - Deploy Existing Bosh Release](Labs/Lab02-Deploy_Existing_BoshRelease.adoc)
  * [Lab3 - Create Bosh release from Scratch](Labs/Lab03-Create_BoshRelease_From_Scratch.adoc)
  * [Lab4 - Deploy Existing Postgres Service Broker](Labs/Lab04-Deploy_Existing_postgres_ServiceBroker.adoc)
* [Custom Tile Creation](Presentations/PivotalTileCreation.pdf) -- 15 minutes -- Ravi & Vivian
* Concourse Deep Dive & Sample Pipeline -- 1 hour (1:30-2:30pm) -- Patrick
* Concourse Tile -- 15-30 minutes (2:30-3pm) -- Alejandro
* UAA + SSO [[slides](Presentations/ThalesDevOps_UAA-SSO.pdf)][[lab](Labs/Lab-SSO.adoc)][[sample apps](https://github.com/pivotal-cf/identity-sample-apps)]-- 1 hour (3-4pm) -- Ravi
* Extra for overflow (4-5pm)


__Pre-work for AppDev Workshop__
* Docs
  * _TBD_
* Videos
  * _TBD_
* Labs
  * _TBD_


__AppDev Workshop__
* Arch + Ops Discussion
* Java/Spring on PCF
* Handling SessionState
* Blue/Green + A/B
* Hackathon => Bring your own App
