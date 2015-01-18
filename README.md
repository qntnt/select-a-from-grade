# select-a-from-grade
##This application is a web-store for CMPSC431W.


# Phase 1 - Conceptual Database Design
A fifteen page, double-spaced document including the requirement analysis and conceptual design.

## Requirement Analysis
Your team should present a concise (itemized) summary of the
application and its operations. There is some vagueness in the project description. You
should clarify them and define exactly how Himalaya°com should operate and what
functions your systems will provide to support those operations. Clearly describe all the
extensions (i.e., those not specified in the project description) for your design and
prototype. You may include in the document (or as an appendix) some figures (e.g.,
projected screen shots or web designs) to illustrate the functions and operations. 

## Conceptual Design
Your team should present an entity-relationship diagram describing
your design. Also, your project document should include a narrative description of the
diagram. Please do not assume the underlying database system and do not map your
design into relations – which is the task for Phase 2 of the project.


# Phase 2 - Logical Database Design and Normalization
Finalize the schema for the database. Produce a refined schema that reduces redundancy to at least the 3rd Normal Form.

## Project Report
You should submit a report that describes your ER design from the first
phase with corrections based on your own and our evaluation. In addition, you should
provide SQL statements to create (specify) all of the relations in your database. As
mentioned above, I expect your design to be based on 1) transforming ER components
(i.e., entity set, relationship set, constraints, etc) to relation schema; 2) specify new
integrity constraints such as functional dependency; and 3) refining the schema through
normalization. In the report, I also expect you to describe how the created tables are
related to your ER design and how they meet the requirements you specified in Phase 1.
In addition, I would like you to describe your design approach and the relations it
produced (i.e., document what you have done on schema refinement). For coherence of
the report, you may choose to leave this part in the Appendix (i.e., it’s up to you to decide
how to organize your report.)

## Formatting
Your document, not including appendices should be no more than twenty
five double-space pages in length. Please note that this document extends your previous
document and for that reason will include it (with the proper corrections). Your document
must have page numbers, section numbers and a table of contents. Your document should
include (in an appendix) a clearly formatted summary of individual and group progress
reports from the beginning of the semester until the due date.


# Phase 3 - System Prototype
During this phase of the project you will implement the database system you have
previously designed for Himalaya°com. You will create a database in MySQL based on
your design and populate it with testing data you generate. In addition, you will
implement several transactions for the internal and/or external user operations of
Himalaya°com

## Populating the Database
* 15 users
** >5 users have commented on another
*** Comments are associated with some auction items
* 20 items waiting to be auctioned.
** Item I1 - auction complete, but waiting on delivery
** Item I2 and I3 - one has received at least one bid and the other has not
* 5 direct sale items to be sold directly from the stock
* 20 categories that form a category tree, at least three levels deep
** Do not count the root as one of the categories or one of the three levels

## Transactions
* AddUser
* BrowsingItems
* SearchingItems
* BuyItem
* AuctionItem
* BidItem
* TerminateAuction
* TeleMarketingReport

## General Constraints
Because the interaction with a user can be quite time consuming, you may divide
database interactions into short transactions

## Project Report
You should submit a cumulative report that describes your ER design,
schema refinement and implementation. Discuss any important implementation issues
you considered and discuss any details of the design you feel are noteworthy. Include
listing of all your source code in a appendix. You will be asked to demonstrate your
project to the TA or myself.

## Formatting
Your document, not including appendices should be no more than thirty-five
pages. Please note that this document extends your previous documents and for that
reason will include it (with the proper corrections). Your document must have page
numbers, section numbers and a table of contents. Your document should include (in an
appendix) a clearly formatted summary of individual and group progress reports from the
beginning of the semester until the due date.