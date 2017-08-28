# Unified Web App Development Process

## Purpose 

Leverage contributors' learning experience to formulate a Unified Web App Development Process(UWADP) to improve understanding of software engineering in web app development.

## Menu

- [Purpose](#purpose)

- [Menu](#menu)

- [Architecture](#architecture)

    - [1 Backend development](#1-backend-development)
    
        - [1.1 Authentication](#11-authentication)
    
        - [1.2 Refactor](#12-refactor)
    
        - [1.3 API at scale](#13-api-at-scale)

            - [1.3.1 REST API](#131-rest-api)

            - [1.3.2 GraphQL](#132-graphql)

            - [1.3.3 Migrate from REST API to GraphQL](#133-migrate-from-rest-api-to-graphql)
    
    - [2 Frontend development](#2-frontend-development)
    
        - [2.1 How to scale](#21-how-to-scale)
    
        - [2.2 Refactor](#22-refactor)
    
    - [3 Operation and maintenance](#3-operation-and-maintenance)
    
        - [3.1 Database backup](#31-database-backup)
            
        - [3.2 Database migration](#32-database-migration)
    
        - [3.3 Development better feedback](#33-development-better-feedback)

- [Reference](#Reference)


## Architecture

This section contain all parts of web app development and operations. Every part contain its own chanllenges and corresponding solutions.

### 1 Backend development

#### 1.1 Authentication

[JWT][4]

#### 1.2 Refactor

TDD

#### 1.3 API at scale

##### 1.3.1 REST API

[Microsoft REST API Guideline][5]

##### 1.3.2 GraphQL

API paradigm: GraphQL

##### 1.3.3 Migrate from REST API to GraphQL


### 2 Frontend development

#### 2.1 How to scale

React

#### 2.2 Refactor

TDD

### 3 Operation and maintenance

#### 3.1 Database backup

[backup strategy][1]

#### 3.2 Database migration

[migration strategy][2]

#### 3.3 Development better feedback

[continuous deployment stratgy kubernetes][3]


## Reference

[1]: https://docs.google.com/document/d/1F1uhdQpT8-V6UXAfekXi44h98daV_Lkoc4X5ibqbqmE/edit?usp=sharing

[2]: https://docs.google.com/document/d/1s4GvR72e2LbrxMGgFPxEUPPZuzCNX6rY1h7wdqDp4wY/edit?usp=sharing

[3]: https://docs.google.com/document/d/1Cg7KCYP42_cwwtvnoRV30-DNLdsgv1Ll3j2Ie5FCBZg/edit?usp=sharing

[4]: https://github.com/xuyuji9000/jwt-demo

[5]: https://github.com/Microsoft/api-guidelines/blob/vNext/Guidelines.md
