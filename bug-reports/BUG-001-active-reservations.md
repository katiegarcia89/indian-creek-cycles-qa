# BUG-001: Dashboard displays past reservations as active

## Description

The admin dashboard displays 19 reservations as “active right now,” but the count includes reservations whose end dates have already passed.

## Expected Result

Only reservations currently occurring should be counted as active.

## Actual Result

Past paid, completed, or pending reservations are included in the active reservation count.

## Severity

Medium

## Suggested Fix

Calculate active reservations using the current date:

- Start date is today or earlier
- End date is today or later
- Reservation is not cancelled

Alternatively, rename the dashboard label to accurately describe the existing count.
