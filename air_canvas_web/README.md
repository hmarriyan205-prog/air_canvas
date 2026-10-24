# Air Canvas (Web)
Static site: sirf `index.html`. Build/backend ki zaroorat nahi.

## Local test
VS Code me "Live Server" extension se index.html open karo (ya `npx serve`).
Camera sirf HTTPS ya localhost par chalta hai.

## Vercel deploy
Option A (GitHub): GitHub par new repo -> "Upload files" -> index.html upload -> vercel.com -> Add New > Project -> repo import -> Framework: Other -> Deploy.
Option B (CLI): `npm i -g vercel` -> folder me `vercel` -> `vercel --prod`.
