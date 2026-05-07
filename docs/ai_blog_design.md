# AI Blog Design Concept

## Prompt

Create a modern editorial homepage and CRUD interface for a personal blog in Ruby on Rails. The design should feel like an intelligent writing desk: warm paper background, strong serif headlines, compact post cards, readable article pages, and clean forms for creating and editing posts. The interface must work well on desktop and mobile and keep CRUD actions visible without looking like a default scaffold.

## Generated Direction

- Brand mood: editorial, calm, focused, handmade but professional.
- Palette: warm paper, ink black, muted teal, clay accent, soft danger red.
- Homepage: large hero section with an abstract editorial visual, primary action for creating a post, and responsive grid of post cards.
- Show page: centered article layout with date, title, formatted content, edit/back/delete actions.
- New/Edit pages: two-column writing interface with guidance on the left and a clear form on the right.
- Components: reusable buttons, post cards, flash messages, form fields, empty state, responsive layout.

## Rails Integration

The generated design is implemented in ERB templates for `posts#index`, `posts#show`, `posts#new`, and `posts#edit`, with shared styles in `app/assets/stylesheets/application.css`.
