# POSit Project Charter

## Summary
POSit is an all inclusive business management system, from sales to inventory management all in one location.

## Goals
1. Create a user-first interface for retail business management that is simple to navigate without detracting from fuctionality. 
2. The software will be free to download and community driven, within 2 years after launch.

## Business Case
Business management systems are large, expensive, and clunky. What started as a good working concept has progressively grown over the years with many addons that some clients may have requested but other have limited use for, and has become so complex for businesses and support to maintain that it has become slow. Companies utilizing the system have servers at each branch location with a main server. To get information from branch to branch it first has to pass through the main server with hours of delays.
POSit aims to centralize everything with all information coming from a central location accessible to each level of a company, speeding up comunication throughout the business and reducing errors that can occur when multiple servers try and share continuously changing information. 

## Team
1. Nicholas James

## Scope
- This is not a payment system. Payment capabilities could be added at some point in the future.
- Documentation
..* Building, editing quotations
..* Building invoices, loading quotations to invoices, crediting invoice, crediting specific lines on invoices
..* Customizing standard quotation, invoice, and credit templates. However, not a template builder. Users can modify the standard template to include company details and some banking information, etc.
- Privilages, limiting access to some company personnel.
- Inventory
..* Inventory tracking.
..* Inventory tansfers.
- Sales tracking.
- Multi-curreny fuctionality.

## Success Criteria
- Community adoption with 2 years after launch

## Key Deliverables
- Retail portal
..* Quotations
..* Invoices
..* Credits
- Branch management portal
..* Sales tracking
..* Inventory management
- Upper management portal
..* Branch management

## Budget
- Free

## Milestones
1. Project Charter complete by 10 Oct 2021
2. Spider Diagram complete by 17 Oct 2021
3. Design
..* Login
..* Dashboard
..* Quotation/Credit/Invoice/Sales-Order
..* Logo
4. Programming
..* Dashboard
..* Login/logout
..* Inventory CRUD
..* Quotation CRUD
..* Invoice CRUD
..* S/O CRUD
..* Sales reconciliation
..* Sales tracking

## Constraints & Assumptions
- Laravel 8, php framework
- Vue 2, javascript frontend
- MySQL database
- Tailwind CSS