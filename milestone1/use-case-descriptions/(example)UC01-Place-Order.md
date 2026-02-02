# UC01 – Place Order 

## Primary Actor
Customer

## Secondary Actors (if any)
- Payment Gateway (optional)

## Goal
Customer places an order for selected items.

## Preconditions
- Customer is logged in.

## Main Flow
1. Customer selects items.
2. System validates availability.
3. System creates an order.

## Alternate / Exception Flows
A1. Item out of stock.
E1. Payment fails.

## Postconditions
- Order is created.
