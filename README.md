# Beta Campus Hub

A separate migration of the Student Connect / Campus Hub website.

## Project files
- Root HTML pages: public pages and authenticated application views.
- `css/`: page stylesheets and the shared `campus-ux.css` layer.
- `img/`: original image assets.

## Backend
The frontend retains its existing Supabase integration. Manage backend credentials and policies in Supabase. Never commit service-role keys or other secrets.

## Migration status
Migrated HTML, CSS, and original image assets are included. Browser and authenticated-workflow QA is still required before treating the migration as production-ready.
