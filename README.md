## Urban Routes QA Testing Project

## Project Overview
The Urban Routes QA Testing Project is designed to test new and updated features in the Urban Routes application. The focus areas include:

Carsharing Feature: An existing feature with significant code changes, requiring a full retest as if it were a new feature.

Aero Taxi Booking Feature: A top-secret project that is not yet visible in the app but has been made available for testing through a special access method provided by developers.

This project integrates concepts from both Sprint 2 and Sprint 3, emphasizing requirement decomposition, test case creation, execution, and reporting.

## Project Components

1. Requirements Analysis

We analyzed functional requirements and decomposed them into atomic blocks to ensure structured testing. The requirements considered are:

Carsharing Payments Feature: FR-CS32, FR-CS33, FR-CS35 (optional)
Aero Taxi Booking Feature: FR-AT4, FR-AT6

2. Test Planning

No additional test planning was required for this project since it follows the structure of the previous test plan. Instead, we ensured alignment with the given instructions and requirements.

3. Test Case Creation

Test cases were designed using equivalence partitioning and boundary value analysis, including:
Identifying equivalence classes and boundary values for FR-CS33.
Creating 10 equivalence classes for each of the two features (20 total).
Writing detailed test cases for Aero Taxi (FR-AT4, FR-AT6), including special steps to enable the hidden feature using Chrome DevTools.

4. Environment Setup

The test environment was set up by the Urban Routes DevOps team.
The application runs on a dedicated test server, with deployment and access instructions followed as provided.

5. Test Execution

All test cases from 3.2 were executed.
Bugs found were recorded in Jira, with links added to the test documentation.
DevTools were used to simulate Aero Taxi activation and verify responses.