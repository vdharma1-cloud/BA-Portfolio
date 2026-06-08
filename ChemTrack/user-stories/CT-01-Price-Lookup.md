User Story CT-01 – Lookup price for single-match product

As a staff processing orders,
I want the system to automatically find and insert the unit price when I type a product name that exists only once in the master inventory,
so that I don’t have to manually search the inventory file and avoid typing errors.

Acceptance Criteria:

    Given I enter a product name in the Order Entry sheet that matches exactly one entry in Master Inventory, When I move to the next row, Then the Unit Price field is auto-populated with the correct price.

    Given the product name has extra spaces or mixed case (e.g., " ACETONE "), When I move to the next row, Then the lookup still matches and populates the price.
