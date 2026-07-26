# BUG-002: Expired Pending Reservations Never Transition to a Final Status

## Status

Open

## Severity

Medium

## Priority

Medium

## Environment

- macOS
- Google Chrome
- Admin Dashboard

## Module

Reservation Management

## Description

Reservations remain in a **Pending** status after their reservation period has ended. There does not appear to be a process that transitions expired pending reservations to a final status.

## Steps to Reproduce

1. Log into the admin dashboard.
2. Navigate to the Recent Reservations table.
3. Locate a reservation with a **Pending** status.
4. Verify that the reservation end date has already passed.

## Expected Result

Expired pending reservations should not remain pending indefinitely.

After a configurable grace period, the reservation should automatically transition to an appropriate final status (such as **Cancelled**) if no further action has been taken.

## Actual Result

Reservations remain in a **Pending** status after the reservation end date has passed.

## Impact

- Reservation statuses become inaccurate over time.
- Staff may believe action is still required for expired reservations.
- Dashboard metrics may become misleading if pending reservations are included in summary counts.

## Suggested Fix

Implement a configurable expiration policy for pending reservations. After the defined grace period expires, automatically transition the reservation to an appropriate final status (for example, **Cancelled**) if payment or administrative action has not occurred.

## Notes

The length of the grace period should be configurable to support different business policies rather than hard-coded.

## Screenshot

`BUG-002-expired-pending-reservation.png`
