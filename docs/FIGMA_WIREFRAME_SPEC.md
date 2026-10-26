# EduCore LMS — Figma Wireframe Specification

Use this brief to create the required three low-fidelity wireframes in Figma. Keep the same navigation, spacing, typography, and button styles across screens. Use realistic sample content, but do not use real student personal data.

## Frame 1 — Authentication
**Suggested desktop frame:** 1440 × 900

- Centered EduCore wordmark and short value proposition.
- Sign in / Create account tabs or a clearly discoverable toggle.
- Email and password fields with labels, not placeholder-only labels.
- Primary Sign in button and secondary Create account action.
- Space for validation feedback and a password-recovery link.
- Responsive mobile variant with a single-column form.

**States to plan:** default, invalid email, missing required field, loading.

## Frame 2 — Student Dashboard
**Suggested desktop frame:** 1440 × 1000

- Persistent left navigation: Dashboard, My Courses, Course Catalog, Profile.
- Top bar with page title and learner profile menu.
- Three summary cards: Active Courses, Average Progress, Learning Hours.
- Continue Learning section with course cards, instructor, progress bar, and action.
- Clear empty state for a learner with no enrollments.
- Responsive mobile variant where navigation collapses to a menu.

**States to plan:** populated dashboard, no courses, loading/error.

## Frame 3 — Course Details / Learning View
**Suggested desktop frame:** 1440 × 1000

- Breadcrumb or back-to-catalog action.
- Course title, category, instructor, short description, and enrollment/continue action.
- Progress indicator.
- Lesson list with completion status, duration, and Start/Continue action.
- Course information and learning outcomes section.
- Responsive mobile variant with stacked content and full-width actions.

**States to plan:** not enrolled, enrolled/in progress, completed lesson.

## Consistency and accessibility checklist

- Use consistent spacing and component styles across all three frames.
- Use clear text contrast and visible keyboard focus styles.
- Label all form fields and provide useful validation messages.
- Do not communicate progress or status using color alone.
- Link the three frames with Figma prototype connections where practical.

## Delivery checklist

- [ ] Create all three frames in Figma.
- [ ] Add a mobile variant or responsive notes.
- [ ] Share the Figma file with view access enabled.
- [ ] Paste the public/viewable Figma URL into the README's **Figma file** section.
