ui hosts the angular ui code
server hosts nodejs backend

Expense / Budget Tool Outline

Service functions
	Auto Tagging 
		Parse for vendor or item name
	Database Interaction
		Select purchases for 1 year
		Select purchases for 1 month
		Add Purchase
		Add Tag
	import from csv

Database Schema
	Purchases
		Id
		Date
		Item
		Amount
		Method
		Vendor
		Tag
		Comment

	Tags
		id
		name
		colour
		icon

Calculated Fields
	Monthly Total
	Yearly Total
	Percentages

	Category Monthly Total
	Category Yearly Total

Pages
	Spreadsheet Page
		Header Bar
			Title
			Page	
		Table
			Month
				Budget
				Monthly Total
				Yearly Total

				Purchase List
					Icon
					Date
					Item
					Amount
					Method
					Vendor
					Tags

	Add Page
		import from csv
		Add individual
			Date
			Item
			Amount
			Method
			Vendor
			Tag
			Comment

	Manage Tags
		Header Bar
			Title
			Page	
		Tags
			Name
			Add/Remove
			Auto Rules
				Name regex
				Vendor regex

	Budget Page
		Yearly Budget
		Yearly Spending +/-
			Monthly Budget

		Month List
			Monthly Budget
			Monthly Spent
			Monthly Purchase Breakdown

list of tasks

