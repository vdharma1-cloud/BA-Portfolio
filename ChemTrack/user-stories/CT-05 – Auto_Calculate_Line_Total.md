As a staff processing orders,
I want the system to calculate Quantity × Unit Price for each line and sum everything into a Grand Total,
so that I don’t make math mistakes that cause incorrect invoices.

Acceptance Criteria:

    Given I have a line with Quantity=5 and Unit Price=₹100, When the Invoice sheet is generated, Then Line Total shows ₹500.

    Given three lines with totals ₹500, ₹300, ₹200, When I view the Grand Total, Then it shows ₹1000.
