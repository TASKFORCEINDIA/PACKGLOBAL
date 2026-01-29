
# FOB vs CIF Calculator – Export Pricing Logic

This document explains how to build FOB and CIF prices for bag exports
using container fit, freight, and margin logic.

This is a decision framework, not a rate card.

---

## Key Definitions

### FOB (Free On Board)
Seller responsibility ends when cargo is loaded on vessel
at the port of export.

FOB includes:
- Factory price
- Inland transport
- Port handling
- Customs clearance
- Documentation

Buyer pays ocean freight and insurance.

---

### CIF (Cost, Insurance, Freight)
Seller delivers cargo to destination port including:
- FOB value
- Ocean freight
- Marine insurance

CIF simplifies buying for importers but requires freight control.

---

## Inputs Required
Before calculating FOB or CIF, confirm:
- Bags per container (from Bag Fit)
- Factory price per bag
- Export handling costs
- Current ocean freight
- Desired margin per bag

Without confirmed bag count, pricing is unreliable.

---

## Step 1: Build FOB Cost

FOB Cost =
(Factory price per bag × Bags per container)
+ Inland transport
+ Port & CHA charges
+ Documentation costs
+ Trader margin

FOB must be calculated per container, not per bag.

---

## Step 2: FOB Per Bag

FOB per bag =
Total FOB value ÷ Bags per container

This is the number buyers compare.

---

## Step 3: Add CIF Components

CIF Cost =
FOB value
+ Ocean freight (per container)
+ Marine insurance (0.2–0.3%)

Insurance is calculated on CIF value.

---

## Step 4: CIF Per Bag

CIF per bag =
Total CIF value ÷ Bags per container

This determines buyer landed cost visibility.

---

## Example Calculation (40 FT – Empty Bags)

Assumptions:
- Bags per container: 21,000
- Factory price: ₹6.50 per bag
- Inland + port costs: ₹40,000
- Trader margin: ₹0.75 per bag
- Ocean freight: $1,100
- Exchange rate: ₹83 / USD

FOB calculation:
Factory cost = 6.50 × 21,000 = ₹136,500  
Margin = 0.75 × 21,000 = ₹15,750  
Total INR FOB = ₹192,250  
FOB USD ≈ $2,315

CIF calculation:
Freight = $1,100  
Insurance ≈ $20  

Total CIF ≈ $3,435  

CIF per bag ≈ $0.163

---

## When to Use FOB
- First-time buyers
- Buyer has strong forwarder
- Volatile freight markets
- Risk avoidance

FOB limits seller exposure.

---

## When to Use CIF
- Buyer prefers simplicity
- Smaller importers
- Competitive differentiation
- You control freight rates

CIF increases responsibility but improves conversion.

---

## Common Pricing Mistakes
- Quoting CIF without locking freight
- Ignoring bag count variation
- Absorbing freight increases
- Mixing FOB and CIF logic

Always state pricing basis clearly.

---

## Practical Rule (PACK Global)
Price is built in this order:
Bag Fit → Container Plan → FOB → CIF

Never reverse this sequence.
