# TIERS Redesign

## Executive Summary

*This redesign will implement changes to the TIERS program, a program used by Texas Health and Human Services Commision case workers to test for state funded benefits, to assist with completion of cases for distributing benefits to Texas families in need. The redesign will include changes to better assist the case worker and personalize the interface.*

## Business Objectives

*TIERS must be able to distinguish between programs being tested for, and the type of case (application, redetermination,a case where previously missing information is received, and nursing facility cases) earlier, so the application can reconstruct the pages the worker will come across (the driver flow) as they are working through their data entry.*

## Background

*In recent times, the Health and Human Services Commission (HHSC) have experienced a significant set back in completing cases in a timely manner. One of the biggest reasons for this set back is an application that needlessly slows the worker down with an unorganized driver flow that is usually full of pages for data entry that many case workers will not need. The confusing interface makes it difficult to retain workers and to train new ones to navigate the application.*

## Scope

*Redesigning TIERS must change the way the driver flow is organized with minimal input from the user. The user must still have access to an overall navigation pane, as user error is to be expected, but the need to flip back and forth between pages and keep track of which pages are not required by the user must be reduced. The application must retain it's basic framework and the formulas for calculating budgets and resources, as well as prevent the user from moving forward until all required entries have been made.*

## Functional requirements

*At the very beginning of the driver flow, TIERS should ask the user what programs are being tested for and the type of case (initial application, redetermination, missing information). From there, TIERS will grab only the applicable pages containing the logistical units of work (LUWs) that must be updated by the user. This page should also take on all of the attributes of the existing programs page to populate data for the first of the two eligibility runs. The next page should include a list of other applicable LUWs for the case that may not be common, but are pertenent in some situations. From here TIERS will take the user through all of the existing non-financial pages, and begin the first run. After the first run, it should be apparent to TIERS that many of the existing Questions pages (that currently exist to filter out some unnecessary pages) do not apply to the case. This should reduce the Questions to one page, that will allow the user to finish customizing the driver flow and take them to the final run before certifying the case. It is imperative that aside from the initial programs page and the new questions pages, all of the existing pages remain available. However, each of the LUWs from these pages should adapt to the way the driver flow based on the original critera of programs being tested and the type of case. For cases that include Medicaid Cost Share programs only, many questions that only apply to SNAP and Children's Medicaid should disappear.*


## Personnel requirements

*IThis project will require a dedicated team of development specialists. A team of no less than 10 developers, as well as a dedicated and tenured worker from each facet of the HHSC to assist with implementation of policy, one full time HHSC IT specialist to advise on system specifications and assist with trouble shooting, and a knowledgeable program manager to coordinate inter-agency support and to make final decisions on design, legal matters and to protect the interests of the department.*

## Delivery schedule

*The team will be given through the end of the fiscal year to plan and design this project. When the new year begins, the results of the design phase will offer a basis for the time needed to implement and test the desgin and the budget may be re-evaluated if need be. The final phase of the project will include reassigning the team to begin development of a training program for wokers, and for the IT department (for troubleshooting and maintenance in the future).*

## Other requirements

*The style of the application must remain simple and the most minimal resources will be expended to this point in order to keep the focus on functionality of the application.*

## Assumptions

*The application must remain compatible with the most current version of the Windows OS as well as Windows 10 and Windows 7. It is also important that our Electronic DATA Verification Systems interface as well as our interfaces with the Social Security Administration remain intact.*

## Limitations

*Due to constraints in the budget, this project must be planned by fiscal year. While we would like to have the application fully implemented by November of 2022, constraints to man power and unforseen circumstances may delay the project.*

## Risks

*While we are fully capable of funding this project through fiscal year 2020, circumstances may arise that will force a cut to the manpower and hours dedicated to the project. We are optimistic that our goals can be acomplished by the proposed launch of fall 2022, it is possible that funding will not allow the completion of this project, in which case it will be shelved until a time that it may be resumed.*
