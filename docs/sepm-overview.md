# [Project Definition Document]
Create a RESTful API service, exposed at port 8080 via HTTP, with URI "/predict", able to receive HTTP POST requests with JSON formatted payload, which contains a data object, e.g. "{"data": [list of needed elements type]})".
Service name: keras-rest-api-python

Focus:
- process and functionality
- extensibility
- simplicity

Questions:
- what is the vision?
- what is the end result?
- which style is preffered?

Project management triangle:
- time
- quality
- price

# [Work Breakdown Structure] (Project Scope, Big Picture) (What, Who, When, Time, Estimation, %Cmplt, Actual)
## [business]
Project setup, funding
Requirements
Project Documentation
Technical Documentation
## [development]
Design
Implement (Scrum)
Test
Deploy

# [Issues List] (Project Scope, All)
Order infrastructure
Order development team
...

# [Backlog] (Development Scope)
## [epic-1, keras-rest-api-python]
feat-1/infra-setup [done]
feat-2/add-rest-api [done]
feat-3/load-keras-model [done]
feat-4/add-predict-endpoint [done]
feat-5/add-minimum-tests [done]
feat-6/setup-containers [in_progress] 4
feat-7/update-documentation [next] 5
feat-8/load-any-model [done]
feat-9/gather-predictions-and-present-on-dashboard [next] 6
feat-10/add-security [next] 7
feat-11/add-prediction-logic [next] 8
feat-12/design-ds-and-flow-model [next] 4
...

OR:
feat/UC-1_infra-setup
feat/UC-2_add-rest-api
feat/UC-3_load-keras-model
feat/UC-4_add-predict-endpoint
feat/UC-5_add-minimum-tests
feat/UC-6_setup-containers
feat/UC-7_update-documentation
feat/UC-8_load-any-model
feat/UC-9_gather-predictions-and-present-on-dashboard
feat/UC-10_add-security
...

# [Issues Tracking] (Development Scope)
git

# [Roadmap] (Project Scope)
git

# [Software Requirements Specification] (Development Scope)
keras-rest-api-python_srs.pdf

# [Software User Documentation] (Development Scope)
user-manual.pdf
user-manual.txt
user-manual.md
keras-rest-api-python_v1.0.yaml