As a staff processing orders,
I want the Invoice sheet to automatically populate with the same products, quantities, prices, and line totals from my Order Entry sheet,
so that I don’t have to retype or reformat anything for the final invoice.

Acceptance Criteria:

    Given I have completed Order Entry with 10 products, When I switch to the Invoice sheet, Then all product names, quantities, units, and prices appear correctly.

    Given a product has a manually entered price (from flagged variant), When the Invoice sheet loads, Then that same price appears.
