Project Summary: Manual Testing of Magento Demo E-Commerce Website

Step 1: Project Overview

Project Name: Manual Testing of Magento E-Commerce Website
Objective: End-to-end testing of e-commerce workflows including:
Login & Registration
Product Search with filters
Add to Cart & Wishlist
Checkout & Order Placement
Contact Form
UI/UX responsiveness

Step 2: Test Plan
Application URL: https://magento.softwaretestingboard.com/
Testing Type: Manual (Functional, UI, Regression)
Environment: Browsers – Chrome, Firefox, Edge
Tools Used: Browser DevTools, Excel/Google Sheets, Screenshot tools
In Scope: Registration, Login, Search, Product filters, Cart, Checkout, Wishlist
Out of Scope: Payment gateway (real transactions), Admin Panel
Deliverables: Test cases, Bug report, Test summary report

Step 3: Test Scenarios (High-Level)
Registration: New user signup, validation errors
Login: Valid/Invalid login, blank fields
Search & Filters: Product search, category filters, invalid keyword
Wishlist: Add product to wishlist, remove from wishlist
Cart & Checkout: Add product, update quantity, remove item, complete checkout
Order History: Verify past orders visible in My Account
Contact Us: Submit form with valid/invalid data
UI/UX: Verify layout, alignment, responsiveness, broken links/images
Step 4: Test Cases (Sample)
TC ID	      Module	Description	Steps	Data	Expected Result	Status
TC_01	Registration	Verify successful registration	Sign up with valid details	Email: user1@test.com	User redirected to My Account	Pending
TC_02	Login	Invalid login	Enter wrong password	user1@test.com / wrong123	Error message displayed	Pending
TC_03	Search	Search valid product	Search “T-Shirt”	“T-Shirt”	Relevant product list shown	Pending
TC_04     Wishlist	Add product to wishlist	Select product → Add to wishlist	Jacket	Product saved in wishlist	Pending
TC_05	Cart	Update quantity	Add item → Change qty to 2	Qty=2	Cart updates correctly	Pending
TC_06	Checkout	Verify order placement	Add item → Proceed checkout	Valid address & details	Order confirmation page shown	Pending
TC_07	Contact Us	Submit blank form	Click Send without filling	Blank	Validation error shown	Pending
TC_08	UI/UX	Verify responsiveness	Open in mobile browser	—	Layout adjusts properly	Pending

Step 5: Bug Report (Sample Defects)

Bug ID	Module	Description	Severity	Status

BUG_01	Login	No error shown on invalid password	Major	Open
BUG_02            Wishlist	Product not saving in wishlist sometimes Critical	Open
BUG_03	Cart	Total not updating after quantity change	 Major	Open
BUG_04	UI	Footer overlapping on mobile screen	 Minor	Open

Step 6: Test Summary Report
Total Test Cases: 20
Passed: 15
Failed: 5

Defects Found: 4 (1 Critical, 2 Major, 1 Minor)
Observations:
Wishlist sometimes fails to save product.
Cart calculation issue.
UI problem on mobile view.
Login module lacks proper error handling.
Conclusion:
Core shopping flow works but wishlist, cart updates, and UI need fixes.
Retesting recommended after defect fixes.
