# Product Principles

## Purpose

These principles guide product, UX, technical, and architectural decisions throughout the development of Medicine Tracker.

When choosing between multiple solutions, the team should prefer the option that better follows these principles.

---

## 1. Solve a Real User Problem

Every feature should solve a clearly identifiable user problem.

A feature should not be added simply because it is technically interesting or because a competitor has it.

Before adding a feature, we should be able to answer:

> What problem does this solve for the user?

---

## 2. Simplicity Over Feature Count

The product should prioritize a small number of useful features over a large number of complicated ones.

The user should be able to perform common tasks without unnecessary steps.

A smaller product that solves its core problem well is preferable to a feature-rich product that is difficult to use.

---

## 3. Information Must Be Available Quickly

The primary purpose of the application is to provide quick access to information about the home medicine cabinet.

The most important information should be accessible within a few seconds.

Search, navigation, and common actions should therefore receive high priority during UX design.

---

## 4. Reduce Stress, Do Not Add It

The application is likely to be used during situations involving illness, urgency, or uncertainty.

The interface should therefore be calm, predictable, and easy to understand.

Notifications should be useful and actionable rather than excessive.

---

## 5. User Data Is Valuable and Sensitive

Information about medications and the household medicine cabinet should be treated as private user data.

Security and privacy should be considered from the beginning of the project rather than added after the product has been built.

---

## 6. Offline-First for Core Functionality

Core medicine-cabinet functionality should not depend on a permanent internet connection.

A user should be able to access and manage their local medicine cabinet even when connectivity is unavailable.

Online services should enhance the product rather than make its basic functionality unusable.

---

## 7. Automation Should Reduce User Effort

Automation should be introduced when it genuinely saves the user time or reduces manual work.

Examples may include:

- OCR;
- automatic extraction of medicine information;
- expiration-date recognition;
- intelligent reminders.

Automation should remain understandable and allow the user to correct incorrect results.

---

## 8. AI Must Be Assistive, Not Authoritative

Potential AI features should assist the user rather than replace a doctor or other medical professional.

AI-generated information must not be presented as a diagnosis, prescription, or definitive medical decision.

Any future AI functionality must be evaluated separately for safety, reliability, privacy, and regulatory implications.

---

## 9. Design for Families, Without Making the Product Complicated

The application should support multiple people and family medicine cabinets.

However, family functionality should not make the basic experience unnecessarily complex for users who only need a personal medicine cabinet.

The simplest use case should remain simple.

---

## 10. Build for Change

The product should be designed so that future capabilities can be added without unnecessarily rewriting the entire application.

However, anticipated future requirements should not be allowed to overcomplicate the MVP.

We should design for reasonable extensibility, not hypothetical requirements.

---

## 11. Safety Over Convenience

When a convenient feature could create a meaningful risk of misunderstanding or unsafe medication use, safety takes priority.

The product should clearly distinguish between:

- information provided by the user;
- information obtained automatically;
- informational recommendations;
- professional medical advice.

---

## 12. Every Feature Must Earn Its Place

A feature should be included in the product only if its value justifies its complexity.

When evaluating a feature, consider:

- User value;
- Frequency of use;
- Implementation complexity;
- Maintenance cost;
- Privacy implications;
- Safety implications;
- Impact on the core user experience.

If a feature does not provide enough value, it should be postponed or removed.