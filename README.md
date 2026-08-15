# Rent & Shine — GitHub Pages Catalogue

Upload the contents of this `site` folder to the root of your GitHub Pages repository.

`index.html` reads `products.json` and displays the 20 seeded SKUs. The SQLite database is maintained separately in the parent package for local/admin use; GitHub Pages itself cannot write to SQLite.

For a real multi-user rental database, migrate `schema.sql` to Supabase/Postgres and replace the JSON fetch with the Supabase API.
