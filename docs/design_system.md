# CleanScene Design SYSTEM

## Product Overview

CleanScene is a modern sustainability platform that empowers volunteers, NGOs, and brands to create measurable environmental impact through cleanup drives, gamification, and community engagement.

The design system aims to provide a consistent, scalable, and engaging user experience across the platform.

---

# 1. Product Personality

If CleanScene were a person, it would be:

* Modern
* Optimistic
* Energetic
* Trustworthy
* Community-driven
* Environmentally conscious
* Innovative
* Youth-focused
* Friendly
* Motivational

### Brand Values

* Sustainability
* Community
* Transparency
* Innovation
* Collaboration
* Positive Impact
* Gamification
* Inclusivity

### Brand Voice

* Friendly
* Encouraging
* Inspirational
* Simple
* Action-oriented
* Authentic

---

# 2. Color Palette

## Primary Color

Purpose:
Brand Identity, Primary Buttons, Important Highlights

```css
#22C55E
```

Eco Green

Represents:

* Nature
* Growth
* Sustainability
* Success

---

## Secondary Color

Purpose:
Interactive Elements

```css
#06B6D4
```

Electric Cyan

Represents:

* Technology
* Innovation
* Freshness

---

## Accent Color

Purpose:
XP, Rewards, Badges, Leaderboards

```css
#FACC15
```

Solar Gold

Represents:

* Achievement
* Progress
* Recognition

---

## Background

```css
#0B1120
```

Deep Navy

Provides a premium dark interface while reducing eye strain.

---

## Surface / Card

```css
#111827
```

Used for:

* Cards
* Containers
* Dashboard Widgets

---

## Primary Text

```css
#F9FAFB
```

---

## Secondary Text

```css
#9CA3AF
```

---

## Success

```css
#10B981
```

---

## Error

```css
#EF4444
```

---

## Warning

```css
#F59E0B
```

---

# 3. Typography

## Font Family

Primary Font

Inter

Reason:

* Modern
* Highly readable
* Widely used in SaaS applications
* Professional appearance

---

## Font Scale

| Type    | Size | Weight    |
| ------- | ---- | --------- |
| Hero    | 56px | Bold      |
| H1      | 40px | Bold      |
| H2      | 32px | Semi-Bold |
| H3      | 24px | Semi-Bold |
| H4      | 20px | Medium    |
| Body    | 16px | Regular   |
| Small   | 14px | Regular   |
| Caption | 12px | Regular   |

---

# 4. Spacing System

The application follows the **4-point spacing system**.

Spacing Scale:

4px

8px

12px

16px

24px

32px

48px

64px

96px

### Benefits

* Consistent layouts
* Better readability
* Easier maintenance
* Professional appearance

---

# 5. Border Radius

| Component     | Radius |
| ------------- | ------ |
| Small Buttons | 8px    |
| Inputs        | 10px   |
| Cards         | 16px   |
| Large Cards   | 20px   |
| Pills         | 9999px |

Purpose:

Rounded corners create a modern and approachable interface while maintaining consistency.

---

# 6. Shadows

### Small

Used for buttons.

Soft elevation.

---

### Medium

Used for cards.

Creates subtle depth.

---

### Large

Used for modals and dialogs.

Higher visual hierarchy.

---

### Principle

Shadows should be soft and realistic.

Avoid harsh shadows.

---

# 7. Animation Rules

Animations should enhance the user experience without becoming distracting.

## Principles

* Fast
* Smooth
* Purposeful
* Natural

---

## Hover Effects

* Slight scale increase
* Soft shadow elevation

---

## Buttons

* Scale: 1.03
* Duration: 200ms

---

## Cards

* Gentle lift
* Shadow enhancement

---

## Page Transitions

* Fade In
* Slide Up

Duration:

300ms

---

## Loading States

* Skeleton loaders
* Smooth shimmer animation

---

## Avoid

* Excessive bouncing
* Flashing elements
* Unnecessary spinning
* Long animations

---

# 8. Component Inventory

## Navigation

* Navbar
* Sidebar
* Footer
* Mobile Navigation

---

## Buttons

* Primary Button
* Secondary Button
* Icon Button
* Outline Button
* Ghost Button

---

## Inputs

* Text Input
* Search Bar
* Password Input
* Select Dropdown
* Checkbox
* Radio Button

---

## Cards

* Event Card
* Mission Card
* NGO Card
* Brand Card
* Statistic Card
* Leaderboard Card

---

## Gamification

* XP Card
* Badge Card
* Achievement Card
* Level Progress
* Reward Card

---

## Dashboard

* Analytics Widget
* Charts
* Activity Feed
* Progress Tracker

---

## Miscellaneous

* Avatar
* Modal
* Dialog
* Toast
* Tooltip
* Loading Spinner
* Empty State
* Pagination

---

# 9. Design Principles

## Consistency

Every screen should follow the same design language.

---

## Simplicity

Interfaces should remain clean and uncluttered.

---

## Accessibility

* High color contrast
* Readable typography
* Keyboard accessibility
* Screen-reader friendly

---

## Scalability

Every component should be reusable throughout the application.

---

## Mobile First

Design begins with mobile devices before scaling to tablets and desktops.

---

## User Focus

Every interface should answer:

* What is my impact?
* What should I do next?
* How can I contribute more?

---

## Performance

Animations and components should remain lightweight and responsive.

---

## Emotional Design

The interface should make users feel:

* Proud
* Motivated
* Connected
* Rewarded

Users should leave the platform feeling that their contributions genuinely matter.

---

# 10. Design Tokens (Future Implementation)

## Primary

```
--primary
```

## Secondary

```
--secondary
```

## Accent

```
--accent
```

## Background

```
--background
```

## Surface

```
--surface
```

## Text

```
--text-primary
--text-secondary
```

Using design tokens allows the application's entire theme to be updated by changing values in one location instead of modifying hundreds of files individually.

---

# Future Vision

CleanScene should feel like the perfect combination of:

* Spotify's elegance
* Strava's motivation
* Duolingo's gamification
* Discord's community
* Apple's minimalism

The experience should inspire users to return regularly, participate in environmental initiatives, and proudly showcase their positive impact.
