# Church Web Product

A reusable church website product for creating low-cost, customized websites for churches.

## Structure

- `showcase/english/` — English public demo
- `showcase/swahili/` — Swahili public demo
- `showcase/premium/` — Alternative premium/editorial demo
- `client-template/` — future reusable client template
- `docs/` — product documentation
- `client-template/js/config.js` — example church-specific configuration

## Important

The three showcase HTML files are the current working designs. Do not rewrite them all at once.

The next development step is to refactor ONE design into a configuration-driven template. Once that works, apply the same approach to the other designs.

## Client customization

Keep church-specific information in one configuration object where practical:
- church name
- tagline
- contact information
- service times
- colors
- logo
- social links
- image paths

## Deployment

The showcase can be published as a static site. GitHub Desktop can upload this entire directory tree while preserving folders.

## Commercial boundary

Include normal content/branding replacement in the basic package. Quote backend/CMS, authentication, databases, payment integration, advanced forms, automation and mobile apps separately.
