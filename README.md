# J-Tech Omni Solutions — static multi-page upgrade

This is a direct HTML/Tailwind/JavaScript upgrade of the supplied original HTML. No Next.js, Node build or package installation is required.

## Deploy on GitHub + Vercel
1. Create a new branch in your GitHub repository.
2. Upload all `.html` files to the repository root. `index.html` is the homepage.
3. Upload your existing logo file as `jtech logo.png` to the same root folder (it was not included in the supplied HTML upload).
4. In Vercel project settings, use Framework Preset **Other**, leave Build Command blank, and set Output Directory to `.` if prompted. If the current project already serves static HTML correctly, keep its existing settings.
5. Preview the branch deployment, check all navigation links and responsive pages, then merge to the production branch.
6. In `index.html` and `contact.html`, replace `https://formspree.io/f/your_formspree_id` with your real Formspree endpoint; test delivery before removing the setup notice.

## Notes
- Original colours, logo path, Tailwind CDN, icons, animations, contact details and core copy are retained.
- Existing project summaries are not independently verified. Add client-approved screenshots and substantiated results.
- The original source has a claim of `40% Reporting Efficiency`; verify before keeping it public.
- The original source has specific delivery-time and ownership promises; review them before publication.
- Do not replace the entire existing repository without first checking whether it contains other assets/configuration.
- This implementation uses CDN resources; a future production hardening pass can compile Tailwind locally and pin dependencies.
