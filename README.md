Components- API-Umbrella

All traffic is routed via Umbrella - API Proxy, which allows access control. End users shall not access API-umbrella. API Proxy is based on the NREL/Api-umbrella. NREL documentation is [here](https://api-umbrella.readthedocs.io/en/latest/)

API Umbrella is an open source API management platform for exposing web service APIs. The basic goal of API Umbrella is to make life easier for both API creators and API consumers. 

You can find details in the [Documentation](https://gitlab.publiccode.solutions/odala-public/documentation/-/tree/main/AccessControl).

NOTE! this project is intended to be run from GitLab - hence the -gitlab-ci.yml. See the gitlab-ci file to understand what is needed; for example variables and secrets are picked up from GitLab CI/CD variables.

© 2023 Contrasec Oy

[License EUPL 1.2](https://eupl.eu/1.2/en/)

![](https://ec.europa.eu/inea/sites/default/files/ceflogos/en_horizontal_cef_logo_2.png)

The contents of this publication are the sole responsibility of the authors and do not necessarily reflect the opinion of the European Union.
This project has received funding from the European Union’s “The Connecting Europe Facility (CEF) in Telecom” programme under Grant Agreement number: INEA/CEF/ICT/A2019/2063604
