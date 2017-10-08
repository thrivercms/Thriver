[![Build Status](https://travis-ci.org/thrivercms/Thriver.svg?branch=wcasa-dev)](https://travis-ci.org/enove/Thriver)

# Thriver
Thriver is a Content Management System for Nonprofit Organizations.  Thriver helps staff communicate and engage with the community, provide education and services to its membership, accept payments and donations, and automate the more painful aspects of nonprofit work.  Thriver also helps the Board of Directors train and recruit, remain compliant on annual requirements, and retain a high-level view of the organization's activities and its alignment with organizational strategy.

## Getting Started
To contribute, you'll need the [Meteor](https://www.meteor.com/install) platform.

    curl https://install.meteor.com/ | sh
    git clone https://github.com/enove/Thriver.git
    cd Thriver
    meteor npm install
    meteor

Then navigate your web browser to http://localhost:3000/

## How can I help?
Thriver needs a lot of help.  The architecture needs to be re-evaluated and modified per [best practices](https://guide.meteor.com).  Furthermore, the platform was initially developed for a single institution.  Some parts of the platform still need to be abstracted.

### An incomplete list of major work that needs help:
* Abstraction from any specific nonprofit
* Architectural redesign
* Designing a system for applying organizational brand (fonts, colors, whitespace, etc)
* Better authorization mechanisms, esp. RBAC
* Technical writing and project management (deployment guides for non-techies, etc)
* Better package/extension support
* Better administration interface
* Basically all board-related visions still need to be programmed
* Init scripts for new contributors and users (right now the platform doesn't work without importing a sample db)
* A testing framework, including unit and integration testing

We use the shared repository model of the [Github Flow](https://guides.github.com/introduction/flow/) but may switch to the fork-and-pull model in the near future.
