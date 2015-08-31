## Source Code Management

Before we start talking about what ITDC CMS code should look like, it is appropriate to look at how and where the source code is stored. All serious software projects, whether driven by an Open Source community or developed within a company for proprietary purposes will manage the source code is some sort of source or version management system. The ITDC projects uses a Distributed Version Control System (DVCS) called Git hosted at [GitHub.com](http://github.com).

### The ITDC CMS

The ITDC CMS is a PHP framework that is designed to serve as a foundation for not only web applications (like a CMS) but other types of software such as command line applications. The files that form the ITDC CMS are stored in a Distributed Version Control System (DVCS) called Git hosted at github.com

ITDC CMS code is proprietary.

Because Git treats the concepts of file revision numbers differently than Subversion, the repository revision number is not required in files (that is, the `@version` tag is not necessary).

## Compliance Tool

The standards in this manual have been adopted across the ITDC CMS project and any other applications maintained by the ITDC. These standards apply to source code, tests and (where applicable) documentation.

A custom ITDC sniff standard for PHP files is maintained by the ITDC project and available from the code repository. The Sniff is based on the standard outlined in this document. For more information about how code standards are enforced see the analysis appendix of the manual. For information on using the Sniff see the documentation stored in its repository.
