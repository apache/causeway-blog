---
layout: post
title: "[ANN] Apache Isis version 1.7.0 Released"
date: '2014-10-21T06:24:37+00:00'
permalink: ann_apache_isis_version_12
---
<div style="color: #222222; font-family: arial; font-size: small;">The Isis team is pleased to announce the release of:</div>
  <div style="color: #222222; font-family: arial; font-size: small;">* Apache Isis Core version 1.7.0</div>
  <div style="color: #222222; font-family: arial; font-size: small;">* Wicket Viewer 1.7.0</div>
  <div style="color: #222222; font-family: arial; font-size: small;">* SimpleApp Archetype 1.7.0</div>
  <div style="color: #222222; font-family: arial; font-size: small;">* ToDoApp Archetype 1.7.0</div>
  <div style="color: #222222; font-family: arial; font-size: small;"><br /></div>
  <div style="color: #222222; font-family: arial; font-size: small;">New features in this release include:</div>
  <div style="color: #222222; font-family: arial; font-size: small;">- ISIS-809: @ViewModel annotation, no longer requiring explicit implementation of the IViewModel interface.</div>
  <div style="color: #222222; font-family: arial; font-size: small;">- ISIS-916: ability to override framework-provided services, such as MementoService or BookmarkService.</div>
  <div style="color: #222222; font-family: arial; font-size: small;">- ISIS-917: (beta): pluggable representations for the RO viewer</div>
  <div style="color: #222222; font-family: arial; font-size: small;"><br /></div>
  <div style="color: #222222; font-family: arial; font-size: small;">There are also some security fixes:</div>
  <div style="color: #222222; font-family: arial; font-size: small;">- ISIS-883: Bookmarkable action URLs can be submitted by a user without permissions to bring up action dialog (thereafter that user can invoke).</div>
  <div style="color: #222222; font-family: arial; font-size: small;">- ISIS-884: ErrorPage vulnerable to XSS attacks.</div>
  <div style="color: #222222; font-family: arial; font-size: small;">- ISIS-895: HomePage should honour authorization rules.</div>
  <div style="color: #222222; font-family: arial; font-size: small;"><br /></div>
  <div style="color: #222222; font-family: arial; font-size: small;">Full release notes are available at [1,2,3,4] on the Isis website. &nbsp;</div>
  <div style="color: #222222; font-family: arial; font-size: small;"><br /></div>
  <div style="color: #222222; font-family: arial; font-size: small;">Isis modules that in 1.6.0 were released as part of Isis core have now moved to Isis addons [5]. Meanwhile the profilestore component (previously in core, but unused in the Wicket viewer) has been retired. &nbsp;Migration should be straightforward, see [6].</div>
  <div style="color: #222222; font-family: arial; font-size: small;"><br /></div>
  <div style="color: #222222; font-family: arial; font-size: small;">Significant updates in Isis add-ons:</div>
  <div style="color: #222222; font-family: arial; font-size: small;">- isis-module-security module [7], for administering authentication and authorization</div>
  <div style="color: #222222; font-family: arial; font-size: small;">- all modules re-released against for 1.7.0.</div>
  <div style="color: #222222; font-family: arial; font-size: small;"><br /></div>
  <div style="color: #222222; font-family: arial; font-size: small;">You can access this release directly from the Maven central repo [8],&nbsp;</div>
  <div style="color: #222222; font-family: arial; font-size: small;">or download the release and build it from source [9].</div>
  <div style="color: #222222; font-family: arial; font-size: small;"><br /></div>
  <div style="color: #222222; font-family: arial; font-size: small;">Enjoy!</div>
  <div style="color: #222222; font-family: arial; font-size: small;"><br /></div>
  <div style="color: #222222; font-family: arial; font-size: small;">--The Isis team</div>
  <div style="color: #222222; font-family: arial; font-size: small;"><br /></div>
  <div style="color: #222222; font-family: arial; font-size: small;">[1] http://isis.apache.org/core/release-notes/isis-1.7.0.html</div>
  <div style="color: #222222; font-family: arial; font-size: small;">[2] http://isis.apache.org/components/viewers/wicket/release-notes/isis-viewer-wicket-1.7.0.html</div>
  <div style="color: #222222; font-family: arial; font-size: small;">[3] http://isis.apache.org/archetypes/release-notes/todoapp-archetype-1.7.0.html</div>
  <div style="color: #222222; font-family: arial; font-size: small;">[4] http://isis.apache.org/archetypes/release-notes/simpleapp-archetype-1.7.0.html</div>
  <div style="color: #222222; font-family: arial; font-size: small;">[5] http://isis.apache.org/core/release-notes/migrating-to-1.7.0.html</div>
  <div style="color: #222222; font-family: arial; font-size: small;">[6] https://github.com/isisaddons/isis-module-security</div>
  <div style="color: #222222; font-family: arial; font-size: small;">[7] http://www.isisaddons.org</div>
  <div style="color: #222222; font-family: arial; font-size: small;">[8] http://search.maven.org</div>
  <div style="color: #222222; font-family: arial; font-size: small;">[9] http://isis.apache.org/download.html</div>
