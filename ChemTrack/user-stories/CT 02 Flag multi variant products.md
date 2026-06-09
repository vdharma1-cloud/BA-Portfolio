As a staff processing orders,
I want the system to leave the price blank and show a visible flag when a product name matches multiple inventory variants (different size or form),
so that I don’t accidentally charge the wrong variant’s price.

Acceptance Criteria:

    Given I enter a product name that has 3 size variants in Master Inventory, When I move to the next row, Then the Unit Price field remains blank and a flag (e.g., “Check variant”) appears.

    Given a flagged row exists, When I manually enter the correct price, Then the flag disappears.
