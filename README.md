Spring-StringTemplate-SiteMesh
==============================

This library provides a reusable integration mechanism between the [StringTemplate](http://www.stringtemplate.org/) java
template engine and the Spring MVC Framework. The pattern used is very similar to the way that the Freemarker template
engine is already integrated with Spring's MVC. In addition this project provides a StringTemplateDecoratorServlet that
can be used to allow StringTemplate's templates to act as [SiteMesh](http://www.opensymphony.com/sitemesh/) decorators.

An example of this integration with both Spring MVC and SiteMesh can be found in the `src/test/webapp/WEB-INF` directory
of this project and is actually used to verify runtime compatiblity with both Spring and SiteMesh.

Runtime dependencies:

- stringtemplate 3.2.1 (required)
- antlr 2.7.7 (stringtemplate dependency)
- springframework 3.x (required)
- commons-lang 2.7.7 (required)
- sitemesh 2.4.1 (optional)
