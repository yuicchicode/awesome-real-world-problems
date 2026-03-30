# No inventory control

## Problem summary
One of the most serious problems in local businesses is not having reliable inventory control. A store may have a rough sense of what sells more and what sits still, but without a clear, updated, and organized view of what came in, what went out, what is still available, and what needs to be replenished, day-to-day operations become confusing and costly.

## Real-world report
One of the biggest problems in a local business is not having inventory control that I can actually trust. Most of the time, I have a general feeling about what sells well and what is sitting still, but I do not really have a clear and updated view of what came in, what left, what is still available, and what needs to be restocked.

In practice, this shows up in several painful ways. A customer asks for a product, and we think we have it, but when we actually go look for it, it is gone. In other situations, the product is physically still in the store, but nobody is sure how many units exist, whether it is already reserved, whether it was sold through another channel, or whether it got lost in the middle of the store’s own internal disorder.

It also happens that products are forgotten, expire, lose their ideal selling moment, or occupy space for too long while the items that actually matter run out exactly when there is demand. What looked like a small organizational issue at first starts affecting sales, customer trust, and cash flow directly.

## Why this is difficult
The problem is not only counting products. The difficult part is maintaining inventory visibility in a real operation where stock changes all the time.

Items move through sales, returns, reservations, internal handling, restocking, and sometimes multiple channels. In a small business, these changes often happen faster than the records. If the workflow depends on memory, paper, or scattered notes, the gap between what exists physically and what the team believes exists keeps growing.

## Why it matters
When inventory is not under control, the business loses more than visibility.

It loses sales because a product appears unavailable when it should be sellable. It buys badly because the owner cannot clearly see what should or should not be replenished. Money gets trapped in the wrong merchandise while the products that actually generate revenue are missing.

It also damages customer experience. If the store answers with uncertainty, sells something it does not actually have, or takes too long to confirm availability, it creates a feeling of disorganization. In local commerce, losing trust can mean losing the customer entirely.

## Project opportunity
This is a strong project problem because it is common, concrete, and directly connected to the daily reality of small businesses.

A useful solution here could help local stores manage incoming and outgoing stock, reduce dependence on memory, improve replenishment decisions, and create better operational visibility without requiring a heavy enterprise system. It is also a strong portfolio problem because it mixes CRUD workflows, state tracking, operational logic, reporting, alerts, and low-complexity UX for real-world users.

## Technical requirements
- Support product registration with category, SKU or internal code, supplier, cost, sale price, and stock unit
- Track stock entry, stock exit, manual adjustment, return, loss, expiration, and reservation events
- Keep a current stock balance and a historical movement log
- Distinguish between physical stock, reserved stock, and available stock
- Surface low-stock and out-of-stock alerts
- Allow filtering by product, category, supplier, and stock status
- Support simple restocking workflows and replenishment suggestions
- Make the interface usable for small teams with low digital maturity
- Support mobile-friendly or tablet-friendly use inside the store
- Preserve history for audit and reconciliation
- Handle incomplete or approximate starting inventory during initial adoption
- Allow optional multi-channel sales context even if the MVP starts with one channel

## Suggested MVP
- Product catalog
- Stock movement log
- Current inventory dashboard
- Low-stock alerts
- Basic stock adjustment flow
- Replenishment list

## Possible extensions
- Barcode support
- Multi-location inventory
- Sales channel synchronization
- Expiration tracking
- Purchase order flow
- Inventory counting mode
- Profit and turnover analytics