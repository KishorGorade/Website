# cyberSKA — High-End Interactive WebGL Website

A premium, feature-rich cybersecurity services experience built for GitHub and Vercel. The site uses a real Three.js/WebGL canvas hero, interactive operating method, capability map, SOC maturity assessment, service architecture, engagement models, and lead-generation form. It is an original cyberSKA design, not a clone of Microsoft or CrowdStrike.

## Features
- Three.js WebGL SOC network scene with connected telemetry nodes and core operating model
- Interactive hero states: visibility, detection, investigation, response
- Six-stage operating method with content-linked UI
- Interactive capability map
- Five-question SOC maturity assessment
- Nine service areas and five engagement models
- Responsive navigation and mobile layouts
- Scroll progress, hover, focus, and form states
- Reduced-motion support
- SEO metadata, Open Graph metadata, favicon, and robots.txt
- No fabricated certifications, customers, partnerships, statistics, or compliance claims

## Contact
Email: cyberska0101@gmail.com
Phone: 7721862116, 9503710226
Location: Pune, Maharashtra

## Deploy
Extract the ZIP and upload the files to the root of a new GitHub repository. Import that repository into Vercel. Use no build command and leave output directory empty. The Three.js dependency is loaded from a CDN in the browser.

## Production form
The form validates locally and displays a demo response. Connect it to Resend, Formspree, SendGrid, Supabase, a CRM, or a Vercel API route before launch. Store all secrets server-side and add rate limiting and spam protection.

## Performance notes
The WebGL renderer caps device pixel ratio at 2, uses a small scene, and respects reduced motion. For a full production build, add device-capability detection, lazy loading, a CSS fallback, compressed assets, and real Lighthouse testing on representative mobile devices.
