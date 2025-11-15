# Make The Lan — Laravel + Inertia + React

Back-office + front pour une boutique “réseau” (switch, routeur) :
- catalogue, panier, **wishlist**
- paiement **Stripe Checkout**
- profils / rôles (**admin**, vendeur, user)
- logs d’utilisation & préférences
- UI moderne (Tailwind, Inertia + React)

---

## 🧭 Sommaire
- [Stack](#-stack)
- [Prérequis](#-prérequis)
- [Setup rapide (Windows + WAMP + phpMyAdmin)](#️-setup-rapide-windows--wamp--phpmyadmin)

---

## 🧱 Stack
- **Laravel** (API + routes + modèles)
- **Inertia.js + React** (SPA sans API REST explicite)
- **Vite** (build front)
- **Tailwind CSS**
- **Stripe Checkout**
- **MySQL/MariaDB** (via **WAMP + phpMyAdmin** sur Windows)
- Icônes : **lucide-react**

---

## ✅ Prérequis
- **PHP 8.2+** & **Composer**
- **Node 18/20+** & **npm**
- **MySQL/MariaDB**
  - Windows : **WampServer** + **phpMyAdmin**
- (Optionnel) **Stripe CLI** pour écouter les webhooks en local

---

## ⚡️ Setup rapide (Windows + WAMP + phpMyAdmin)

1) **Cloner & entrer dans le projet**
```bash
git clone <votre-repo>
cd <dossier-projet>
