[<img src="https://sling.apache.org/res/logos/sling.png"/>](https://sling.apache.org)

 [![Build Status](https://ci-builds.apache.org/job/Sling/job/modules/job/sling-org-apache-sling-fragment-ws/job/master/badge/icon)](https://ci-builds.apache.org/job/Sling/job/modules/job/sling-org-apache-sling-fragment-ws/job/master/) [![Test Status](https://img.shields.io/jenkins/tests.svg?jobUrl=https://ci-builds.apache.org/job/Sling/job/modules/job/sling-org-apache-sling-fragment-ws/job/master/)](https://ci-builds.apache.org/job/Sling/job/modules/job/sling-org-apache-sling-fragment-ws/job/master/test/?width=800&height=600) [![Sonarcloud Status](https://sonarcloud.io/api/project_badges/measure?project=apache_sling-org-apache-sling-fragment-ws&metric=alert_status)](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-fragment-ws) [![Maven Central](https://maven-badges.herokuapp.com/maven-central/org.apache.sling/org.apache.sling.fragment.ws/badge.svg)](https://search.maven.org/#search%7Cga%7C1%7Cg%3A%22org.apache.sling%22%20a%3A%22org.apache.sling.fragment.ws%22) [![JavaDocs](https://www.javadoc.io/badge/org.apache.sling/org.apache.sling.fragment.ws.svg)](https://www.javadoc.io/doc/org.apache.sling/org.apache.sling.fragment.ws) [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0) [![fragment](https://sling.apache.org/badges/group-fragment.svg)](https://github.com/apache/sling-aggregator/blob/master/docs/groups/fragment.md)

# Apache Sling System Bundle Extension: WS APIs

This module is part of the [Apache Sling](https://sling.apache.org) project.

Adds the WS API packages to the system bundle exports.
The list of packages is derived from the packages available
in the Java 7 platform. The system bundle exporting these
packages gives no guarantee the platform provides them.
For proper setup it is suggested to either install an
extension fragment adapted to the platform or to install
regular API packages as bundles.
