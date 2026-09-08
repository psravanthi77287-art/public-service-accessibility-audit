# Accessibility Audit Report

## Website Audited

**Website:** CPGRAMS – Centralized Public Grievance Redress and Monitoring System

**URL:** https://pgportal.gov.in/

**Audit Method:**
- Google Chrome Lighthouse
- Keyboard-only navigation testing

---

# Lighthouse Results

| Category | Score |
|----------|-------|
| Performance | 72 |
| Accessibility | 75 |
| Best Practices | 88 |
| SEO | 73 |

---

# Accessibility Issues Found

## Issue 1: Buttons do not have an accessible name

**Evidence:** Google Lighthouse Accessibility Audit

**Priority:** High

**Problem:** Some buttons do not have an accessible name, making it difficult for screen-reader users to understand their purpose.

**Recommendation:** Add visible text or an appropriate `aria-label` to buttons.

Example:

```html
<button aria-label="Search">Search</button>