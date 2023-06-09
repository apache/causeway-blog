---
layout: post
title: "[ANN] Isis 1.4.0 released - yet more cool stuff!"
date: '2014-03-14T19:00:43+00:00'
permalink: ann_isis_1_4_0
---
<div style="color: #222222; font-family: arial; font-size: small;">The Isis team is pleased to announce the release of:</div> 
  <div style="color: #222222; font-family: arial; font-size: small;"><br /></div> 
  <div style="color: #222222; font-family: arial; font-size: small;">* Core 1.4.0</div> 
  <div style="color: #222222; font-family: arial; font-size: small;">* JDO Object Store 1.4.1</div> 
  <div style="color: #222222; font-family: arial; font-size: small;">* Wicket Viewer 1.4.1</div> 
  <div style="color: #222222; font-family: arial; font-size: small;">* Restful Objects Viewer 2.2.0</div> 
  <div style="color: #222222; font-family: arial; font-size: small;">* Shiro Security 1.4.0</div> 
  <div style="color: #222222; font-family: arial; font-size: small;">* File Security 1.4.0</div> 
  <div style="color: #222222; font-family: arial; font-size: small;">* Quickstart Archetype 1.4.1</div> 
  <div style="color: #222222; font-family: arial; font-size: small;">* Simple Archetype 1.4.1</div> 
  <div style="color: #222222; font-family: arial; font-size: small;"><br /></div> 
  <div style="color: #222222; font-family: arial; font-size: small;">There are many new features in this release!</div> 
  <div style="color: #222222; font-family: arial; font-size: small;"><br /></div> 
  <div style="color: #222222; font-family: arial; font-size: small;"><br /></div> 
  <div style="color: #222222; font-family: arial; font-size: small;"> 
    <div>For Isis core and also the JDO objectstore, these include:</div> 
    <div><br /></div> 
    <div>- extensions to .layout.json files for additional facets/UI hints</div> 
    <div>- @javax.validation.constraints.<wbr />Digits for length/scale of BigDecimal action parameters</div> 
    <div>- better reporting of metamodel validation errors (including a new page in Wicket viewer)</div> 
    <div>- improved support for bulk update</div> 
    <div>- @javax.enterprise.context.<wbr />RequestScoped for request-scoped services</div> 
    <div>- QueryResultsCache request-scoped domain service (for performance tuning)</div> 
    <div>- new MementoService to support view models</div> 
    <div>- new request-scoped @Bulk.InteractionontextService for standardized co-ordination between bulk action invocations</div> 
    <div>- Scratchpad request-scoped domain service (for adhoc coordination between actions, eg bulk action invocations)</div> 
    <div>- Command, CommandContext, BackgroundCommandService, for profiling and background task support</div> 
    <div>- improvements to JDO implementations of auditing and publishing services, to integrate closely with the new Command/backgroundCommand services</div> 
    <div>- improved support for running arbitrary Isis jobs via a scheduler</div> 
    <div>- UUID and URI value type support</div> 
    <div>- supporting methods (disableXxx, validateXxx) for contributed actions/associations now supported</div> 
    <div>- services autowired prior to @PostConstruct, and Isis session present for service initialization</div> 
    <div>- JRebel support (JRebel plugni itself is third-party, see Isis website for details)</div> 
    <div><br /></div> 
    <div><br /></div> 
    <div>New features in the Wicket viewer include:</div> 
    <div><br /></div> 
    <div>- show action dialogs in a modal dialog, rather than new page</div> 
    <div>- limit number of bookmarks, make less easier to accidentally trip, show/hide with keyboard shortcut</div> 
    <div>- improved IE9 support, bundle CSS files</div> 
    <div>- simplify URLs in Wicket viewer</div> 
    <div>- actions returning URL open new browser window</div> 
    <div>- UI sorting/ordering hints, pop-up to copy to clipboard</div> 
    <div>- breadcrumb drop-down to easily revisit previous page</div> 
    <div>- upper/lower case now switchable</div> 
    <div>- standalone tables now rendered according to runtime type, not compile-time type</div> 
    <div>- better tooltips over icon/titles</div> 
    <div>- widget for java.sql.Timestamp</div> 
    <div><br /></div> 
    <div><br /></div> 
    <div>Full release notes are available at [1,2,3,4,5,6,7,8,9,10,11] on the Isis website.</div> 
    <div><br /></div> 
    <div>You can access this release directly from the Maven central repo [12],&nbsp;</div> 
    <div>or download the release and build it from source [13].</div> 
    <div><br /></div> 
    <div>Enjoy!</div> 
    <div><br /></div> 
    <div>-The Isis team</div> 
    <div><br /></div> 
    <div>[1] <a href="http://isis.apache.org/core/release-notes/isis-1.4.0.html" target="_blank" style="color: #1155cc;">http://isis.apache.org/core/<wbr />release-notes/isis-1.4.0.html</a></div> 
    <div>[2] <a href="http://isis.apache.org/components/viewers/wicket/release-notes/isis-viewer-wicket-1.4.0.html" target="_blank" style="color: #1155cc;">http://isis.apache.org/<wbr />components/viewers/wicket/<wbr />release-notes/isis-viewer-<wbr />wicket-1.4.0.html</a></div> 
    <div>[3] <a href="http://isis.apache.org/components/viewers/wicket/release-notes/isis-viewer-wicket-1.4.1.html" target="_blank" style="color: #1155cc;">http://isis.apache.org/<wbr />components/viewers/wicket/<wbr />release-notes/isis-viewer-<wbr />wicket-1.4.1.html</a></div> 
    <div>[4] <a href="http://isis.apache.org/components/viewers/restfulobjects/release-notes/isis-viewer-restfulobjects-2.2.0.html" target="_blank" style="color: #1155cc;">http://isis.apache.org/<wbr />components/viewers/<wbr />restfulobjects/release-notes/<wbr />isis-viewer-restfulobjects-2.<wbr />2.0.html</a></div> 
    <div>[5] <a href="http://isis.apache.org/components/objectstores/jdo/release-notes/isis-objectstore-jdo-1.4.0.html" target="_blank" style="color: #1155cc;">http://isis.apache.org/<wbr />components/objectstores/jdo/<wbr />release-notes/isis-<wbr />objectstore-jdo-1.4.0.html</a></div> 
    <div>[6] <a href="http://isis.apache.org/components/security/shiro/release-notes/isis-security-shiro-1.4.0.html" target="_blank" style="color: #1155cc;">http://isis.apache.org/<wbr />components/security/shiro/<wbr />release-notes/isis-security-<wbr />shiro-1.4.0.html</a></div> 
    <div>[7] <a href="http://isis.apache.org/components/security/file/release-notes/isis-security-file-1.40.html" target="_blank" style="color: #1155cc;">http://isis.apache.org/<wbr />components/security/file/<wbr />release-notes/isis-security-<wbr />file-1.40.html</a></div> 
    <div>[8] <a href="http://isis.apache.org/getting-started/release-notes/quickstart_wrj-archetype-1.4.0.html" target="_blank" style="color: #1155cc;">http://isis.apache.org/<wbr />getting-started/release-notes/<wbr />quickstart_wrj-archetype-1.4.<wbr />0.html</a></div> 
    <div>[9] <a href="http://isis.apache.org/getting-started/release-notes/quickstart_wrj-archetype-1.4.1.html" target="_blank" style="color: #1155cc;">http://isis.apache.org/<wbr />getting-started/release-notes/<wbr />quickstart_wrj-archetype-1.4.<wbr />1.html</a></div> 
    <div>[10] <a href="http://isis.apache.org/getting-started/release-notes/simple_wrj-archetype-1.4.0.html" target="_blank" style="color: #1155cc;">http://isis.apache.org/<wbr />getting-started/release-notes/<wbr />simple_wrj-archetype-1.4.0.<wbr />html</a></div> 
    <div>[11] <a href="http://isis.apache.org/getting-started/release-notes/simple_wrj-archetype-1.4.1.html" target="_blank" style="color: #1155cc;">http://isis.apache.org/<wbr />getting-started/release-notes/<wbr />simple_wrj-archetype-1.4.1.<wbr />html</a></div> 
    <div>[12] <a href="http://search.maven.org/" target="_blank" style="color: #1155cc;">http://search.maven.org</a></div> 
    <div>[13] <a href="http://isis.apache.org/download.html" target="_blank" style="color: #1155cc;">http://isis.apache.org/<wbr />download.html</a></div> 
  </div>
