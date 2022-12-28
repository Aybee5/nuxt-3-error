**Page 100** is intentionally broken. How this is handled by Nuxt depends on if you're in development mode and if it was a fresh pageload or after router navigation.

To see the differences in behavior:

1. First run `npm run dev`, browse back and forth and try a full page reload on **Page 100**.
2. Now run `npm run generate && npm run preview` and repeat.
