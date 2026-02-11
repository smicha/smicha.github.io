# Lost and Found Platform - Requirements

## Overview

A platform to help people reunite with their lost items by connecting finders and owners through automated matching and secure communication.

-----

## Business Requirements

### BR-1: Platform Purpose

Enable people to reunite with their lost items by connecting finders and owners through an automated matching system that facilitates secure communication and handover.

### BR-2: Target Users

- Item owners who have lost belongings
- Finders who want to return found items
- Geographic focus: Initially Seattle, expandable to other cities

### BR-3: Core Value Proposition

Reduce friction in the lost-and-found process through intelligent matching rather than manual browsing of listings.

### BR-4: Success Metrics

- Successful item reunifications
- Time-to-match efficiency
- User satisfaction with handover process

-----

## Functional Requirements

### FR-1: Item Reporting

- Users can report lost items with description, category, location, date/time, and photos
- Users can report found items with the same attributes
- System captures structured data for ML matching

### FR-2: ML-Powered Matching

- System analyzes lost and found reports using ML to identify potential matches
- Matching criteria: item category, physical description, location proximity, temporal proximity, visual similarity (photos)
- Generate confidence scores for each potential match

### FR-3: Search & Discovery

- Users can search existing lost/found reports
- Filter by category, location, date range, item characteristics
- Browse recent listings in their area

### FR-4: Match Notification & Confirmation

- System notifies both parties when a potential match is identified
- Users can review match details and confirm/reject the match
- Support for requesting additional verification (photos, specific details)

### FR-5: Secure Communication

- Platform facilitates anonymous communication between matched parties
- Users exchange verification details without exposing personal contact info initially
- Enable photo/message exchange within the platform

### FR-6: Handover Coordination

- Users can coordinate pickup/delivery through the platform
- Optional: Suggest safe public meetup locations
- Mark items as “returned” upon successful handover
- Collect feedback on the experience

-----

## Platform Information

**Active Instances:**

- lostandfounditems.org (Status: Active, Provider: Squarespace)
- seattlelostandfound.org (Status: Active, Provider: Squarespace)

-----

*Last Updated: February 2026*