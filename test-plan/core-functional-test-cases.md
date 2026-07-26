# Indian Creek Cycles — Core Functional Test Cases

## Test Environment

- Application: Indian Creek Cycles
- Website: https://www.indiancreekcycles.com
- Browser: Google Chrome
- Device: MacBook Air
- Test Type: Manual functional testing

---

## TC-001: Verify the homepage loads successfully

**Priority:** High  
**Test Type:** Positive  
**Preconditions:** User has an internet connection.

### Steps

1. Open a supported browser.
2. Navigate to the Indian Creek Cycles website.
3. Wait for the page to load.

### Expected Result

- The homepage loads without an error.
- The main navigation is visible.
- Text and images display correctly.
- No broken layout elements are visible.

### Actual Result

_To be completed during testing._

### Status

Not Run

---

## TC-002: Verify navigation links open the correct pages

**Priority:** High  
**Test Type:** Positive  
**Preconditions:** User is on the homepage.

### Steps

1. Click each link in the main navigation.
2. Observe the page that opens after each click.
3. Return to the homepage and repeat for the remaining links.

### Expected Result

- Each navigation link opens the correct page or section.
- The page does not display a 404 error.
- The selected page matches the navigation label.

### Actual Result

_To be completed during testing._

### Status

Not Run

---

## TC-003: Verify the company logo returns the user to the homepage

**Priority:** Medium  
**Test Type:** Positive  
**Preconditions:** User is on a page other than the homepage.

### Steps

1. Click the Indian Creek Cycles logo.
2. Observe the page displayed.

### Expected Result

The user is returned to the homepage.

### Actual Result

_To be completed during testing._

### Status

Not Run

---

## TC-004: Verify available bicycles are displayed

**Priority:** High  
**Test Type:** Positive  
**Preconditions:** User is on the bicycle listing or rental page.

### Steps

1. Navigate to the bicycle listing.
2. Review the bicycles displayed.
3. Check the information shown for each bicycle.

### Expected Result

- Available bicycles are displayed.
- Each listing contains the expected information.
- Bicycle images and descriptions match the selected bicycle.

### Actual Result

_To be completed during testing._

### Status

Not Run

---

## TC-005: Verify a user can view bicycle details

**Priority:** High  
**Test Type:** Positive  
**Preconditions:** At least one bicycle is displayed.

### Steps

1. Select a bicycle.
2. Open its details page.
3. Review the displayed information.

### Expected Result

- The correct bicycle details are displayed.
- The bicycle name, image, description, and rental information are visible.
- The information matches the bicycle selected by the user.

### Actual Result

_To be completed during testing._

### Status

Not Run

---

## TC-006: Verify required reservation fields cannot be left blank

**Priority:** High  
**Test Type:** Negative  
**Preconditions:** User is on the reservation form.

### Steps

1. Leave all required fields empty.
2. Click the button to submit or continue the reservation.

### Expected Result

- The reservation is not submitted.
- Validation messages appear beside or near required fields.
- The messages clearly explain what information is missing.

### Actual Result

_To be completed during testing._

### Status

Not Run

---

## TC-007: Verify a reservation can be created with valid information

**Priority:** Critical  
**Test Type:** Positive  
**Preconditions:** A bicycle is available for the selected date.

### Steps

1. Select a bicycle.
2. Enter valid customer information.
3. Select valid rental dates or times.
4. Submit the reservation.

### Expected Result

- The reservation is successfully created.
- A confirmation message or page appears.
- The confirmation displays the correct reservation information.

### Actual Result

_To be completed during testing._

### Status

Not Run

---

## TC-008: Verify an end date before the start date is rejected

**Priority:** High  
**Test Type:** Negative  
**Preconditions:** User is completing the reservation form.

### Steps

1. Select a rental start date.
2. Select an end date that occurs before the start date.
3. Attempt to submit the reservation.

### Expected Result

- The reservation is not submitted.
- The user receives a clear date-validation message.
- The invalid dates remain available for correction.

### Actual Result

_To be completed during testing._

### Status

Not Run

---

## TC-009: Verify past rental dates cannot be selected

**Priority:** High  
**Test Type:** Negative  
**Preconditions:** User is completing the reservation form.

### Steps

1. Open the rental date selector.
2. Attempt to select a date in the past.
3. Attempt to submit the reservation if the date can be selected.

### Expected Result

- Past dates are disabled or rejected.
- The reservation cannot be created using a past date.
- A clear validation message appears when necessary.

### Actual Result

_To be completed during testing._

### Status

Not Run

---

## TC-010: Verify unavailable bicycles cannot be double-booked

**Priority:** Critical  
**Test Type:** Negative  
**Preconditions:** A bicycle already has a reservation for the selected period.

### Steps

1. Select the reserved bicycle.
2. Enter the same rental period as the existing reservation.
3. Attempt to complete the reservation.

### Expected Result

- The system prevents the duplicate reservation.
- The user is informed that the bicycle is unavailable.
- The system allows the user to select another bicycle or rental period.

### Actual Result

_To be completed during testing._

### Status

Not Run

---

## TC-011: Verify customer email validation

**Priority:** Medium  
**Test Type:** Negative  
**Preconditions:** User is completing a form containing an email field.

### Steps

1. Enter an invalid email address such as `katie@`.
2. Complete the remaining required fields.
3. Submit the form.

### Expected Result

- The form is not submitted.
- A clear message requests a valid email address.
- The user can correct the invalid email.

### Actual Result

_To be completed during testing._

### Status

Not Run

---

## TC-012: Verify forms prevent duplicate submissions

**Priority:** High  
**Test Type:** Negative  
**Preconditions:** User has completed a valid form.

### Steps

1. Complete the form with valid information.
2. Double-click the submit button quickly.
3. Review the resulting records or confirmation.

### Expected Result

- Only one submission or reservation is created.
- The submit button is disabled or protected while processing.
- The user receives only one confirmation.

### Actual Result

_To be completed during testing._

### Status

Not Run

---

## TC-013: Verify the website displays correctly on a mobile screen

**Priority:** High  
**Test Type:** Responsive  
**Preconditions:** The website is open in a browser.

### Steps

1. Open the browser's developer tools.
2. Select a mobile screen size.
3. Review the homepage and major application pages.
4. Open the navigation menu.
5. Complete or review a form.

### Expected Result

- Content fits within the mobile screen.
- Text remains readable.
- Navigation remains usable.
- Buttons and form fields are not cut off.
- Horizontal scrolling is not required.

### Actual Result

_To be completed during testing._

### Status

Not Run

---

## TC-014: Verify the website displays correctly at 200% zoom

**Priority:** Medium  
**Test Type:** Accessibility  
**Preconditions:** The website is open in a desktop browser.

### Steps

1. Increase the browser zoom to 200%.
2. Review the homepage.
3. Navigate through the main pages.
4. Attempt to use forms and buttons.

### Expected Result

- Content remains readable and usable.
- Text does not overlap.
- Important controls remain visible.
- The user can navigate without losing functionality.

### Actual Result

_To be completed during testing._

### Status

Not Run

---

## TC-015: Verify keyboard navigation

**Priority:** Medium  
**Test Type:** Accessibility  
**Preconditions:** User is on the homepage.

### Steps

1. Press the Tab key repeatedly.
2. Navigate through links, buttons, and form fields.
3. Use Enter or Space to activate a selected control.

### Expected Result

- Interactive elements receive visible keyboard focus.
- Focus moves in a logical order.
- Links and buttons can be activated using the keyboard.
- The user does not become trapped on one element.

### Actual Result

_To be completed during testing._

### Status

Not Run

---

## TC-016: Verify invalid URLs display an appropriate error page

**Priority:** Low  
**Test Type:** Negative  
**Preconditions:** The website is available.

### Steps

1. Add a nonexistent page name to the website URL.
2. Press Enter.
3. Review the response.

### Expected Result

- An appropriate error page is displayed.
- The website does not expose technical or sensitive information.
- The user has a way to return to the homepage.

### Actual Result

_To be completed during testing._

### Status

Not Run

---

## TC-017: Verify all images load correctly

**Priority:** Medium  
**Test Type:** Visual  
**Preconditions:** User can access the application's main pages.

### Steps

1. Open each major page.
2. Review all displayed images.
3. Check for broken-image icons or incorrect images.

### Expected Result

- All expected images load.
- Images correspond to the correct content or bicycle.
- Images are not stretched, pixelated, or cut off unexpectedly.

### Actual Result

_To be completed during testing._

### Status

Not Run

---

## TC-018: Verify browser refresh does not create duplicate data

**Priority:** High  
**Test Type:** Negative  
**Preconditions:** A form or reservation has just been successfully submitted.

### Steps

1. Submit a valid reservation or form.
2. Wait for the confirmation page.
3. Refresh the browser.
4. Review the stored record or confirmation.

### Expected Result

- Refreshing the page does not create a duplicate reservation or record.
- The user sees the existing confirmation or an appropriate message.

### Actual Result

_To be completed during testing._

### Status

Not Run
