# IDOR Notes

## What is IDOR?

Insecure Direct Object Reference

## Example

/user?id=1001

Change to:

/user?id=1002

If another user's data opens = IDOR

## Testing Areas

- Profile pages
- Orders
- Invoices
- User IDs
- Download links

## Prevention

- Server-side authorization checks
