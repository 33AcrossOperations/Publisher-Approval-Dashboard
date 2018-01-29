# Publisher-Approval-Dashboard
Project:  Create an externally facing Platform Publisher Approval Dashboard, with logins for each Platform partner where they can approve individual domains.  

The goal of this Dashboard is to replace all approval Google Docs.
The dash would work off a table like this:
The Rubicon Project              Filter = All, Pending, Approved, Rej.      {SAVE}.        Sort By Requests, Reach
Publisher	Domain	Relationship	Approval
Intermarkets	drudgereport.com	Direct	[x] Approved | [ ] Rejected
The Approval column would be a radio button where only one status could be selected at a given time.  The table would exist in a separate frame, allowing the header with the Platform name and SAVE button to remain on-page at all times.
For Client-Side integrations, the save button would write changes to the 0,1 status for the relevant Platform in Tynt Admin approval.  For Server-Side, we will create a future feature (adding or removing rows with login:GUID).
May need to include columns for Publisher ID and GUID, in the event multiple platforms want them.  May also just make them visible for Platforms that require them.
(will add more)
