As a staff processing orders,
I want any row with a missing or unresolved price to be highlighted in a different color on the Invoice sheet,
so that I notice the problem before printing and giving the invoice to a client.

Acceptance Criteria:

    Given a product was flagged as multi-variant and price is still blank, When I view the Invoice sheet, Then that row has a yellow (or other distinct) background.

    Given I then manually enter a price for that row, When I refresh the Invoice sheet, Then the highlight is removed.
