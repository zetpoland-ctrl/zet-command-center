# ZET Command Center

Prywatny panel właściciela Zet Transport & Logistics.

## Netlify
Wymagane zmienne środowiskowe:
- VITE_SUPABASE_URL
- VITE_SUPABASE_PUBLISHABLE_KEY

Build command: `npm run build`
Publish directory: `dist`

Aplikacja korzysta z Supabase Auth oraz polityk RLS owner-only.
