Link Events Business Central use cases
======================================

## How to use examples
Just import this repository to the Business Central starts from 7.42.Final build and deploy the project and execute processes.

## simpleLinkTest.bpmn
> Tests simple Link Events example
![](src/main/resources/com/myspace/linksproject/LinksProject.simpleLinkTest-svg.svg)

## WeirdLinkNameTest.bpmn
> Tests `±§!@#$%^&*()_+=-{}][:"|\';<>?/.,~` Link name
![](src/main/resources/com/myspace/linksproject/LinksProject.WeirdLinkNameTest-svg.svg)

## DifferentLinksTest.bpmn
> Tests that Links with different names do not overlaps at runtime
![](src/main/resources/com/myspace/linksproject/LinksProject.DifferentLinksTest-svg.svg)

## MultipleThrowLinkTest.bpmn
> Test several Throw Link can trigger Catch Link
![](src/main/resources/com/myspace/linksproject/LinksProject.MultipleTrowLinkTest-svg.svg)

## LoopLinkTest.bpmn
> Tests loops created by Link Events
![](src/main/resources/com/myspace/linksproject/LinksProject.LoopLinkTest-svg.svg)

## EmbeddedLinkTest.bpmn
> Tests that Throw Link with same name do not trigger Catch Link on another level than it's own
![](src/main/resources/com/myspace/linksproject/LinksProject.EmbeddedLinkTest-svg.svg)
