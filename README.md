# OME POI

[![Build Status](https://travis-ci.org/ome/ome-poi.png)](http://travis-ci.org/ome/ome-poi)
[![Maven Central](https://img.shields.io/maven-central/v/org.openmicroscopy/ome-poi.svg)](http://search.maven.org/#search%7Cgav%7C1%7Cg%3A%22org.openmicroscopy%22%20AND%20a%3A%22ome-poi%22)
[![Javadocs](http://javadoc.io/badge/org.openmicroscopy/ome-poi.svg)](http://javadoc.io/doc/org.openmicroscopy/ome-poi)

Java API to handle Microsoft OLE 2 Compound Document format (Word, Excel). Based on poi-2.5.1-final-20040804.jar, with bugfixes for OLE v2 and memory efficiency improvements. Used by Bio-Formats for OLE support (cxd, ipw, oib, zvi). Used by VisBio overlays logic for XLS export feature.


More information
----------------

For more information, see the [Apache POI web
site](http://jakarta.apache.org/poi/).


Pull request testing
--------------------

We welcome pull requests from anyone, but ask that you please verify the
following before submitting a pull request:

 * verify that the branch merges cleanly into ```master```
 * verify that the branch compiles using Maven
 * verify that the branch does not use syntax or API specific to Java 1.8+
 * make sure that your commits contain the correct authorship information and,
   if necessary, a signed-off-by line
 * make sure that the commit messages or pull request comment contains
   sufficient information for the reviewer(s) to understand what problem was
   fixed and how to test it