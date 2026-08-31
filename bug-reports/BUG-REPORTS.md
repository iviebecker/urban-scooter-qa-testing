# Bug Reports

This section documents the defects identified during testing of the Urban Scooter mobile application.

## PF-21 — 2-Hour Order Deadline Notification

**Related test cases:** TC-01, TC-02, TC-03, TC-08

**Description:**

The notification that should be received 2 hours before the order delivery deadline was not displayed.

**Expected result:**

The notification should be received when the delivery deadline is 2 hours away. The notification should contain the required information and allow the user to access the "My Orders" tab when tapped.

**Actual result:**

No notification was received.

**Test cases affected:**

- TC-01 — Notification was not received.
- TC-02 — Notification content could not be verified because no notification was displayed.
- TC-03 — The "My Orders" tab could not be accessed through the notification because no notification was displayed.
- TC-08 — The notification layout could not be verified because no notification was displayed.

**Evidence:**

See the screenshots in this folder related to PF-21.

---

## PF-22 — Internet Connection Failure Layout

**Related test case:** TC-09

**Description:**

The "No internet connection" notification layout did not match the Figma design.

**Expected result:**

The connection failure notification should match the Figma specification, including text, size, positioning, spacing, and other visual elements.

**Actual result:**

The notification layout differed from the Figma design.

**Test case affected:**

- TC-09 — Failed

**Evidence:**

See the screenshot in this folder related to PF-22.
