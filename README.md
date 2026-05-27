# TrustCenter AI - Conformite et Gouvernance d Entreprise

SaaS de gestion de la conformite pour PME. Pilotez votre conformite RGPD, vos politiques internes, vos certifications et audits depuis un seul tableau de bord.

## Stack

- Next.js 14 (App Router)
- PostgreSQL + Prisma
- Stripe (abonnements)
- JWT + bcryptjs (auth)
- Tailwind CSS + Lucide + Zod

## Fonctionnalites

- Registre de traitement RGPD (Article 30)
- Gestion des politiques internes et procedures
- Suivi des certifications et audits (ISO, SOC2)
- Workflow de validation et approbation des documents
- Tableau de bord conformite avec score et alertes
- Gestion des droits d acces par role

## Demarrage

bash
npm install
npx prisma migrate dev
npm run dev


Variables requises : DATABASE_URL, STRIPE_SECRET_KEY, JWT_SECRET