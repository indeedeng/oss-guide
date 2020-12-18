# Open Source Repository Standards

In order to ensure quality across open source repositories owned by Indeed, we have defined a set of standards that should be used when setting up these repos. These standards will be enforced for any project that lives as part of the [Indeedeng organization on Github](https://github.com/indeedeng). If you are hosting a project in another Indeed org (IndeedSecurity, IndeedAlpha, etc), we encourage you to adopt these same standards to ensure project consistency. We have based the standards on industry best practices.

This document assumes the repository is hosted on [Github.com](http://www.github.com/).

The easiest way to ensure that your repository conforms to these standards is to have the GitHub repository created using the [default template](https://github.com/indeedeng/default-template) we have configured for the IndeedEng organization.

## Readme Contents
Every project should have a Readme that contains, at a minimum, the following information:
* What the project does
* How to get started
* How to ask questions
* How To Contribute (This can be in a CONTRIBUTING.md)
* Project Maintainers
* Code of Conduct
* License

## OSSMETADATA file
Every project should contain an OSSMETADA file containing machine readable information that indicates the status of the project. cf. https://github.com/Netflix/osstracker/blob/master/OSSMETADATA

The OSSMETADATA file can be used to show an OSS Lifecycle shield in the README by adding the following code:

```![OSS Lifecycle](https://img.shields.io/osslifecycle/indeedeng/default-template.svg)```

## License Selection And Identification

We generally prefer the Apache 2 license (http://www.apache.org/licenses/LICENSE-2.0), but if the repository fits into a broader ecosystem with a prevailing license preference, we should default the prevailing license. No approval is needed to use Apache 2, MPL 1.1, EPL 1.0, BSD, or MIT licenses. If you wish to use a license not shown here for your project, please open a ticket.

The license should be identified both in a distinct LICENSE file, and in the last stanza of the Readme.md, titled “License” following this format: PROJECT_NAME is licensed under the LICENSE_NAME(linked to LICENSE). **Example Follows:** 

**License**

Imhotep is licensed under the [Apache 2 license](http://www.apache.org/licenses/LICENSE-2.0)

## Code Of Conduct

We have standardized on the [Contributor Covenant v 2.0](https://www.contributor-covenant.org/) as the code of conduct that governs how we interact with contributors to our open source projects.

Selecting a Code of Conduct for your project is important for a wide range of reasons. We strongly advise against trying to write your own code of conduct. If you want to use something besides the Contributor Covenant, we’d love to hear why. Please open a ticket assigned to OSS and let us know!

The Code of Conduct should include the opensource@indeed.com email address as a point of contact. The Code of Conduct should be identified in both a distinct https://www.contributor-covenant.org/ file, and as the second-to-last stanza of the [Readme.md](http://readme.md/), titled “Code Of Conduct” following this format: PROJECT_NAME is governed by the Contributor Covenant v 2.0  (linked to CODE_OF_CONDUCT.md). **Example Follows:**

**Code Of Conduct**

Imhotep is governed by the [Contributor Covenant v2.0](https://www.contributor-covenant.org/)

## Responsiveness

Project maintainers should acknowledge and respond to any pull requests, issues, and questions within 48 hours (weekends and holidays excluded). By responding promptly to inbound requests from the community, maintainers send a clear signal that the project is actively maintained.

## Inclusive Terminology
The project should be reviewed to ensure that it follows Indeed's [guidelines for the use of inclusive terminology](https://engineering.indeedblog.com/blog/2020/07/inclusion-in-code/), including replacing the master branch with primary, main, or trunk. 
