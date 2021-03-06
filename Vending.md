# Vending machine
## Security
- Ensures money is real
- Secures internal inventory
- Validates credit/debit cards

## Maintenance
- Runs a refrigerant system

- Senses issues with the vending system

- Provides a method of restocking

## Money
- Return change

- Senses if the money compartment is full

- Senses if the change drawer is empty

## Interface
- Receives money

- Displays products & prices

- Provides product selector

- Scans credit/debit cards

- Notify when a product is not available

- Notify when insufficient currency has been provided
   

## Vending
### Maintains an inventory
- [ ] VI1 - The system shall provide shelving appropriate for canned beverages.
- [ ] VI2 - The system shall provide space for up to 12 categories of beverage.
- [ ] VI3 - The system shall uniquely identify drink categories.
- [ ] VI4 - The system shall maintain a count of beverages in each drink category.

### Vend products selected
- [ ] VV1 - Upon receiving a drink selection (ref. TODO), when the specified quantity of currency for the selected category has been inserted (ref. TODO), and while drinks are in inventory to vend (ref. VI4) the system shall dispense at most one of the selected category of drink.

- [ ] VV2 - Upon vending a drink (ref. VV1), the system shall reduce the inventory count (ref. VI4) for the drink category by one prior to accepting further user input.

