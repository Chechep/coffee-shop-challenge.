# Coffee Shop Challenge

## Features

### Customer

- Getter/setter validation for name
- `.orders()` - Returns all orders by this customer
- `.coffees()` - Returns unique list of coffees ordered
- `.create_order(coffee, price)` - Creates a new order
- `Customer.most_aficionado(coffee)` - Class method that returns the customer who spent the most on a given coffee

### Coffee

- Immutable name after initialization
- `.orders()` - Returns all orders for this coffee
- `.customers()` - Returns unique list of customers who ordered it
- `.num_orders()` - Returns number of orders
- `.average_price()` - Returns average order price

### Order

- Validates input types and ranges
- Properties: `.customer`, `.coffee`, `.price`
- Tracks all instances in a class-level list

---

## Running Tests

You can run the tests using the Python `unittest` module:

```bash
python -m unittest discover tests
