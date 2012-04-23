Waiver-Efficiencies
===================

Waiver Efficiencies

There is an opportunity to gain efficiencies in applying waivers. There are
four situations where we manually run a query to identify students who should
have a waiver. Then we must identify the students who either need to be added
to the waiver, and identify students who are no longer eligible for the waiver.
The students are then manually added or removed from the waiver. This should be
done on a daily basis. The four situations are: • Student enrolled in both
TTU/Law receive credit for the fees in which they are dually charged by being
enrolled in both terms. (e.g., library fee, medical fee, student union, etc) •
Student enrolled in both TTU/HSC receive credit for the fees in which they are
dually charged by being enrolled in both terms. (e.g., library fee, medical
fee, student union, etc) • Bordering County/Bordering State o Subquery to parse
out Bordering County Students o Subquery to parse out Bordering State Students
• Competitive Scholarship o Information is obtained thru a financial aid query
The solution for each item, would involve: 1. performing a query to identify
students eligible for the waiver (queries will be provided for each) 2. These
results would be compared to the students who currently have the waiver (waiver
specifics will be provided). a. If the student is new, the student will be
added to the waiver, via the gateway xml interface. b. If the student is no
longer eligible for the waiver, an eprint report is generated for manual review
of the situation.

-------------------
Key Documents
-------------------
ERD and Mock up documents are available in folder:
S:\jbaquero\Jorge\My Documents\Projects\Project 21893 - Waiver Efficiencies\Schematics

