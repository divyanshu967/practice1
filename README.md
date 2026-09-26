# practice1
tech stack about the project :React 18 (UI library) — react + react-dom
Vite 5 (build tool and dev server) — fast HMR, ES module bundling
TypeScript 5.5 — strict mode, path alias @/ → src/
Routing

React Router DOM 7 — client-side routing across all 17 pages
Styling

Tailwind CSS 3.4 — custom design system with espresso/ivory/cognac/ink color ramps, 8px spacing scale, custom shadows, keyframe animations
PostCSS + Autoprefixer — CSS processing pipeline
Google Fonts — Playfair Display (headings) + DM Sans (body)
Icons

Lucide React — all UI icons (search, cart, heart, etc.)
Backend / Data

Bolt Database (via @supabase/Bolt Database-js) — provisioned instance with URL and keys in .env. The Bolt Database client is set up in src/lib/supabase.ts. Currently the product catalog is defined as static TypeScript data in src/lib/data.ts (16 products across 4 categories), structured so it can be swapped to Bolt Database tables later without changing the UI.
State management

React Context API — three providers in src/context/:
CartContext — cart items, add/remove/update, slide-out drawer state, localStorage persistence
WishlistContext — saved products, localStorage persistence


localStorage — cart and wishlist survive pa

this project is about a leather brand bullburry which sells preminum leatehr products across all ranges
author-divyanshu
