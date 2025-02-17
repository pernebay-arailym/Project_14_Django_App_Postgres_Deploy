# Django Project Settings for Render Deployment

J’ai utilisé Django pour le backend, PostgreSQL pour la base de données et Gunicorn pour le serveur de production. Le projet est configuré avec des variables d’environnement pour sécuriser les données sensibles et il est prêt pour un déploiement cloud!

This project contains the essential settings for deploying a Django application on Render. Key features include:

- **Environment Management**: Uses `python-dotenv` to load configuration from environment variables securely.
- **Database Flexibility**: Configured to use SQLite locally and switch to any database specified by the `DATABASE_URL` environment variable in production.
- **Security**: Handles secret keys and debug settings securely via environment variables.
- **Standard Middleware and Apps**: Includes typical Django middleware and apps, ensuring a robust base for building web applications.

These settings provide a solid foundation for deploying a Django project on Render, balancing ease of local development with production readiness. For more details, refer to the [Django documentation](https://docs.djangoproject.com/en/4.2/) and [Render's deployment guide](https://render.com/docs/deploy-django).
