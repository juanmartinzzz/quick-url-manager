# Future Features

This document contains future feature specifications in user story format. Each feature follows this structure:

## Format Template
**Code**: Auto-incrementing code (F001, F002, etc.)
**Title**: The end result or goal of the feature - e.g. what Users can do after feature implementation.
**Body**: User story in "As a [user type], I want [goal] so that [benefit]" format
**Requirements**: Technical implementation requirements (bullet points)
**Acceptance Criteria**: Specific, testable completion conditions (checklist format)

---

## F001 - Link Group Visibility Limit

### Title
Users can set a maximum number of visible links per group.

### Body
As a User managing multiple groups with a lot of links, I want to be able to set a maximum number of visible links per group so that long lists don't overwhelm the interface. When the limit is exceeded, remaining links should be hidden and a "Show All Links" button should appear to reveal them at the bottom of the links grid.

### Requirements
- Add a number input field for each group with default value of 18
- Hide links beyond the specified limit
- Display a "Show All Links" button when links are hidden
- Implement toggle functionality to show/hide additional links
- Persist the visibility limit setting per group
- Ensure smooth user experience when toggling link visibility

### Acceptance Criteria
- [ ] Number input appears for each link group with default value 18
- [ ] Links beyond the limit are hidden from view
- [ ] "Show All Links" button appears when links exceed the limit
- [ ] Clicking "Show All Links" reveals all hidden links
- [ ] Clicking "Show All Links" changes to "Hide Extra Links" when expanded
- [ ] Setting persists across page refreshes
- [ ] UI remains responsive and accessible when toggling visibility
