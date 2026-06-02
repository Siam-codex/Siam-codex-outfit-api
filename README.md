====================================================================
🎮 FREE FIRE OUTFIT IMAGE GENERATOR API 🚀
====================================================================

An advanced, high-performance Python-based API that fetches real-time Free Fire player data and generates stunning custom outfit showcase images on a clean, professional template. Perfect for integration with Telegram Bots, web applications, and community tools! ⚡

✨ FEATURES:
--------------------------------------------------------------------
- Real-Time Data Fetching: Automatically retrieves active player profiles, avatar IDs, and equipped clothing data.
- Dynamic Image Composition: Smart layering system that crops, resizes, and positions character vectors and accessory icons with pixel-perfect precision using the Pillow library.
- Fail-Safe Mechanisms: Built-in multi-layered fallback image slots to handle missing server assets gracefully.
- Seamless Serverless Deployment: Pre-configured and fully optimized for continuous delivery on Vercel via modern WSGI serving (gunicorn).
- Telegram Bot Ready: Designed to directly serve binary image payloads or accessible image URLs suitable for automated responses.

🛠️ TECH STACK & DEPENDENCIES:
--------------------------------------------------------------------
The backend relies on a minimalist, cloud-optimized environment configured via requirements.txt:
- Framework: Flask (Lightweight Micro-framework)
- Image Processing: Pillow (High-performance image manipulation layer)
- Networking: requests (HTTP session-managed external requests)
- Production Server: gunicorn (WSGI HTTP server for production stability)

🚀 SETUP & DEPLOYMENT GUIDE:
--------------------------------------------------------------------
📂 Repository File Structure:
Your production environment must contain the following core architectural assets:
├── app.py              # Main Flask server engine & image processing logic
├── outfit.png          # High-resolution master layout background canvas
├── requirements.txt    # Frozen environment dependencies for the server host
├── vercel.json         # Vercel serverless deployment & routing architecture
└── .gitignore          # Cache and environment isolation registry

🌍 Deploying via Vercel (Recommended Workflow):
1. Repository Synchronization: Push your project files securely into a private or public GitHub repository.
2. Import Project: Open your Vercel Dashboard, select "Add New Project", and import the target repository.
3. Trigger Build: Leave default configurations unchanged. Vercel automatically parses vercel.json to configure deployment pipelines. Click "Deploy" and await your production endpoint URL.

🛸 API ENDPOINT ARCHITECTURE:
--------------------------------------------------------------------
GET/POST /outfit-image
Generates and serves the finalized composite image stream.

Query Parameters:
- uid (Type: string, Required: Yes) -> Target Free Fire Player Unique Identifier
- key (Type: string, Required: Yes) -> Secured Authorization Access Token (KRSXH)

Endpoint Usage Example:
https://your-deployment-subdomain.vercel.app/outfit-image?uid=710034057&key=KRSXH

👑 CREDITS & MAINTAINERS:
--------------------------------------------------------------------
This architecture was designed and structured by:

- Developer: 👑SIAM CODEXD👑
- Built By: SIAM CODEX
- Telegram Handle: @SIAM_CODEX 💬
- Official Telegram Channel: https://t.me/SIAM_CoDeX_FILE 📢
- Official Telegram Group: https://t.me/ARIYAN_CODEX_LIKE_GROUP 👥

--------------------------------------------------------------------
🔒 LICENSE & DISCLAIMER:
This utility project is developed for educational and gaming community enhancement purposes. All product names, logos, and brands are property of their respective trademark owners.
====================================================================
