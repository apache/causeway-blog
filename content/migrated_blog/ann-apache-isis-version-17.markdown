---
layout: post
title: "[ANN] Apache Isis version 2.0.0-M2 Released"
date: '2019-01-23T09:13:15+00:00'
permalink: ann-apache-isis-version-17
---
<p>
The Apache Isis team is pleased to announce the release of Apache Isis 2.0.0-M2. </p> 
  <p>This milestone introduces one new feature, namely support for a table tree view in the Wicket viewer. It also includes all the features as of Apache Isis 1.17.0. </p> 
  <p>The long-term goal (for v2.0.0) is to allow the framework to be run on top of either SpringBoot or JEE MicroProfile, with either of those lower-level frameworks taking responsibility for configuration and injection. In this milestone, some significant initial work has been done in this area. Notably, the IsisConfiguration is now immutable once instantiated, and its creation with respect to the AppManifest has been figured out.</p> 
  <p>Lots of work has also been done both in updating or removing dependencies, with google guava being notable as one dependency that has been removed.</p> 
  <p>Full release notes are available on the Apache Isis website at [1]. </p> 
  <p>You can access this release directly from the Maven central repo [2].
Alternatively, download the release and build it from source [3].

</p> 
  <p>Enjoy!
</p> 
  <p>
--The Apache Isis team

</p> 
  <p>[1] http://isis.apache.org/release-notes/release-notes.html#_release-notes_2.0.0-M2</p> 
  <p>[2] http://search.maven.org</p> 
  <p>[3] http://isis.apache.org/versions/2.0.0-M2/downloads.html</p>
