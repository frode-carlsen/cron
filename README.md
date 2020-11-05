[![SonarCloud Bugs](https://sonarcloud.io/api/project_badges/measure?project=frode-carlsen_cron&metric=bugs)](https://sonarcloud.io/component_measures/metric/reliability_rating/list?id=frode-carlsen_cron)
[![SonarCloud Vulnerabilities](https://sonarcloud.io/api/project_badges/measure?project=frode-carlsen_cron&metric=vulnerabilities)](https://sonarcloud.io/component_measures/metric/security_rating/list?id=frode-carlsen_cron)
[![Known Vulnerabilities](https://snyk.io/test/github/frode-carlsen/cron/badge.svg?targetFile=pom.xml)](https://snyk.io/test/github/frode-carlsen/cron?targetFile=pom.xml)
![GitHub](https://img.shields.io/github/license/frode-carlsen/cron)

# cron

 Cron expression parser and evaluator.  
 
 Allows for specifying cron - expressions (in Unix or Quartz like format) and evaluating when it will next match.

# Modules
  * cron-jodatime:  Based on jodatime.  Supports java6
  * cron-java8: Based on java8/time. Requires java8+
  
# Usage

See javadoc


# Change history and credits
 
## version 1.6:
 * 2020-11-05: fix issue #7 for java8 Switching Month/Year with given Month fails on nextTimeAfter by @foto-andreas
 
## version 1.5:
 * 2019-08-02: performance improvement when next time is further into the future (java8) by @n3world
 
## version 1.4:
 * 2017-02-13: added support for java6 (supports android 4) by @adelnizamutdinov
 * 2016-09-11: rewritten to Java 8 DateTime by @zemiak

## version 1.3:
 * 2015-09-23: added timezone to tests by @alf

## version 1.2:
 * 2015-08-05: added protection for endless loop when looking up Feb 30th & optional seconds by @michaelknigge
 
 
