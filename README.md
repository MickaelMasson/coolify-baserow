# coolify-baserow
🚀 A production-ready, multi-service Docker Compose configuration for self-hosting Baserow on a Coolify server.


## Description Détaillée
Deploy a **Production-Ready Baserow Stack** on Coolify
This repository provides a robust and reliable Docker Compose configuration to easily deploy a **multi-service Baserow stack** on a server managed by Coolify.

This setup is designed to be self-contained and avoids common reverse-proxy routing issues. It uses an integrated Caddy service to intelligently route traffic between the Baserow frontend and backend API, all while being managed by Coolify.

### Features
**Production-Ready**: Includes all necessary services for a full Baserow instance (backend, web-frontend, celery workers, postgres, and redis).

**Self-Contained Routing**: Uses an internal Caddy proxy for reliable path-based routing (/api, /ws, etc.), eliminating complex configurations with the main Coolify proxy.

**Easy to Deploy**: Simply configure your environment variables and deploy as a Docker Compose application in Coolify.

**Shareable**: The configuration is generic and can be easily shared and adapted for any domain.
