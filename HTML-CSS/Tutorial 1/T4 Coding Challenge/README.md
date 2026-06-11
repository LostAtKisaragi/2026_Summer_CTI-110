Debug: Coding Challenge 4

The file provided contains 10 coding errors that needs to be fixed for the page to pass validation.

I ran the file through validator.w3.org to check for errors and received 6 total.

		1. Start tag seen without seeing a doctype first.
		2. Element head is missing a required instance of child element title.
		3. Element doctype not allowed as child of element body in this context. (Suppressing further errors from this subtree.)
		4. The doctype element is a completely-unknown element that is not allowed anywhere in any HTML content.
		5. Stray start tag html.
		6. Fatal Error: Cannot recover after last error. Any further errors will be ignored.

As the scan failed, I'll need to fix what I can and log other errors I noticed.

============================

Error 1: Line 1 missing "!" in "<!doctype html>"

Error 2: Line 2 "<html language="english">" instead of "<html lang="en">

Error 3: Line 15 "relation="stylesheet"" instead of "rel="stylesheet""

Error 4: Line 3 and 16 "<heading>" instead of "<head>"

Error 5: Line 19 "<image source=" instead of "<img src="

Error 6: Line 37 "</ol>" instead of "</ul>"

Error 7: Line 15 file name incorrect

Error 8: Line 4 "<--" instead of "< !--"

Error 9 and 10: Line 33 adjusted order of tags