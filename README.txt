ANANTAAL — Vercel Preview-Only Package

This is a self-contained static design preview. It supports the visible UI and browser-based demo interactions only.
It does NOT deploy the production Node.js backend, SQLite database, admin login, live bookings/payments, Shiprocket or Meta WhatsApp APIs.
Do not take real bookings or money with this preview.

DEPLOY:
1. Extract the files from this ZIP.
2. Upload the files (not the ZIP itself) at the root of a new GitHub repository.
3. Vercel > Add New > Project > Import the repository.
4. Framework Preset: Other, Root Directory: ./, no build command.
5. Deploy.

For the complete working server, use Railway with a persistent disk/volume, or move the backend to a platform-compatible data architecture.

SOUND ON BY DEFAULT (within browser rules):
The first tap, click, or keyboard activation starts soft ambient sound. The visitor
can toggle it off using the wave icon in the navigation or the listening button.
Audible sound cannot be guaranteed to play on page load without a user gesture;
modern browsers restrict autoplay. A first gesture is required.

Deploy this as the V1 demo in a separate GitHub repository and Vercel project
from the Cinematic V2 demo; both packages are independent.
