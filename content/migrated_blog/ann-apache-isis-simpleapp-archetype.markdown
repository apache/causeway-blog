---
layout: post
title: "[ANN] Apache Isis simpleapp-archetype 1.13.2.1 Released"
date: '2017-01-03T19:17:17+00:00'
permalink: ann-apache-isis-simpleapp-archetype
---
<div>This release is for the simpleapp archetype only. &nbsp;It:</div> 
  <div><br /></div> 
  <div> 
    <ul> 
      <li>improves docker support - allowing docker images to be created easily</li> 
      <li>reduces the amount of boilerplate (by backing out some of the mixins)</li> 
      <li>fixes an issue with the fixture scripts</li> 
    </ul> 
  </div> 
  <div><br /></div> 
  <div>For example, the webapp can be packaged as a Docker image using:</div> 
  <div><br /></div> 
  <div><font face="courier new, courier, monospace">&nbsp; &nbsp; mvn package -Dmavenmixin-docker \</font></div> 
  <div><font face="courier new, courier, monospace">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;-Ddocker-plugin.imageName=mycompany/myapp</font></div> 
  <div><br /></div> 
  <div>and can then be run using:</div> 
  <div><br /></div> 
  <div><font face="courier new, courier, monospace">&nbsp; &nbsp; docker run -d -p8080:8080 mycompany/myapp</font></div> 
  <div> </div> 
  <p> </p> 
  <p>See the README.adoc (generated by the archetype) for further details.</p> 
  <div>Full release notes are available on the Apache Isis website at [1].</div> 
  <div><br /></div> 
  <div>You can access this release directly from the Maven central repo [2], or&nbsp;</div> 
  <div>download the release and build it from source [3].</div> 
  <div><br /></div> 
  <div>Enjoy!</div> 
  <div><br /></div> 
  <div>--The Apache Isis team</div> 
  <div><br /></div> 
  <div>[1] http://isis.apache.org/release-notes.html#r1.13.2.1</div> 
  <div>[2] http://search.maven.org</div> 
  <div>[3] http://isis.apache.org/downloads.html</div>
