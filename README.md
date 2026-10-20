# Internlytic Technologies — 3D Virtual Office

A browser-based, third-person interactive virtual office prototype built with Vite and Three.js. Includes a generated 3D company exterior, road, branded building sign, lobby, reception interaction, departments, CEO office, services, about panel, contact email draft, and appointment-request email draft.

## Run locally
1. Install Node.js 20 or newer.
2. Open this folder in a terminal.
3. Run `npm install`
4. Run `npm run dev`
5. Open the local URL printed by Vite.

## Deploy on Vercel
1. Upload this folder to a GitHub repository.
2. In Vercel choose **Add New → Project** and import that repository.
3. Framework preset: **Vite** (or Other).
4. Build command: `npm run build`
5. Output directory: `dist`
6. Click Deploy.

## Controls
- WASD / arrow keys: move
- Mouse: look around (click the scene to enable pointer lock)
- E: interact with nearby locations
- Mobile: touch directional pad

## Prototype limitations
- The environment and people are procedural stylized 3D placeholders, not GTA assets or photorealistic character models.
- The receptionist and CEO interactions are scripted.
- Appointment and contact forms open the visitor's email app; they do not yet save bookings or send automatic confirmations. Connect a booking backend/email service before using this for real appointments.
- No external maps, analytics, or API keys are required.

## Brand
Internlytic Technologies · CEO & Founder: Arslan Fayyaz · arslanfayyaz1997@gmail.com

## Original reference project
The supplied `3d-portfolio-master.zip` was reviewed as inspiration. This implementation is a separate, clean Vite/Three.js prototype rather than a modification of the original project's files. Check applicable licenses before reusing third-party assets in a public/commercial deployment.
