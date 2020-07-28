# E-RPID Mapper Client

The major goals of the E-RPID project fall into three distinct bins:
* Developing a software-based mechanism for the mapping of existing data repositories to be compatible with E-RPID services and the underlying Digital Object Interface Protocol (DOIP). This will allow adoption efforts to proceed without refactoring of the underlying data repository schema.

* Testing the DOIP with the four use cases defined in the project description. The DOIP will allow a set of well defined operations to be carried directly out on digital objects.

* Producing introductory educational and training materials that can inform data repository administrators, client developers, and project managers the advantages of operating within a Digital Object Architecture (DOA) environment and how this DOA environment encourages and aligns the repository with the FAIR (Findable, Accessible, Interoperable, and Reusable) principles.

## Installation Guide

### Software Dependencies

1. Apache Maven V3.0 or higher
2. JDK V1.6 or higher
3. Cordra V2.0
4. Handle service

### Required Software

1. Cordra (Object Service):
   1. download the Cordra service from https://cordra.org/index.html
   2. follow the instructions to install and run the Cordra service
      1. create the proper schema for Cordra Objects in Cordra **Admin > Types** (please follow the `DTR Type format.json` under the `samples`)
      2. create the proper schema for Cordra Types
      3. create the proper types for your objects

2. Handle System (Persistent Identifier Service)
  1. download the Handle service from http://handle.net
  2. follow the instructions to install and run the Handle service

### Building the Source

Check out source codes:

```
git clone https://github.com/luoyu357/E-RPID.git
```
