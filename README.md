# Kwiaty Teresy – Platforma E-commerce (B2B/B2C)

**Kwiaty Teresy** to rodzinna hurtownia kwiatów sztucznych działająca od ponad 15 lat na Śląskiej Giełdzie Kwiatowej. Projekt ten to cyfrowa transformacja firmy, która łączy tradycję z nowoczesną technologią. Celem platformy jest umożliwienie zamówień hurtowych i detalicznych przez Internet, z pełnym wsparciem logistyki, AI-asystentów i integracją z systemem Subiekt w kolejnych etapach.

---

## 🔧 Stos technologiczny

- **Frontend**: React + Next.js (SSR, ISG, SEO-friendly)
- **Backend**: Node.js + Express.js (REST API)
- **Baza danych**: PostgreSQL
- **Admin Panel**: React (osobna instancja lub `/admin`)
- **AI Integracje**: Flowise + WhatsApp/Instagram Bots
- **Płatności**: Stripe (z Przelewy24, BLIK, karta, przelew)
- **Infrastruktura**: VPS + PM2 + Nginx + SSL (Let's Encrypt)
- **Bezpieczeństwo**: JWT auth, role, RODO, rate-limity

---

## 📦 Funkcjonalności

### ✅ Dla klientów detalicznych (B2C)
- Katalog produktów z filtrami (kolor, okazja, sezon)
- Koszyk, płatność online, śledzenie zamówień
- Historia zamówień i newsletter

### ✅ Dla klientów hurtowych (B2B)
- Rejestracja konta hurtowego (z akceptacją)
- Indywidualne cenniki, zamówienia paletowe
- Płatność fakturą / przelewem
- Panel partnera (historia, pobranie faktur, szybkie zamówienia)

### ✅ Panel administracyjny
- Zarządzanie produktami, zamówieniami, klientami
- Planowanie dostaw i obsługa zamówień z giełdy
- Import danych z Subiekta (w przyszłości)
- Statystyki sprzedaży, alerty o niskim stanie magazynowym

### ✅ AI-asystenci
- Bot wsparcia hurtowego (WhatsApp/Instagram)
- Bot onboardingu nowych partnerów
- Możliwość rozszerzenia na CRM, logistykę i raportowanie

---

## 🚀 Wdrożenie

1. **Frontend**: `Next.js` SSR na porcie 3000
2. **Backend**: `Express.js` na porcie 4000
3. **Reverse proxy**: Nginx na porcie 443 (HTTPS)
4. **Baza danych**: PostgreSQL (zewnętrzna lub lokalna)

---

## 🔐 Bezpieczeństwo i zgodność

- Logowanie z JWT
- Role: admin, klient detaliczny, hurtownik, magazynier
- RODO: checkboxy, polityka prywatności, usuwanie danych
- Rate limiting, CSRF, XSS protection
- Szyfrowanie TLS (Let's Encrypt)

---

## 📈 Rozszerzenia (planowane)

- Integracja z Subiekt REST API
- Kalendarz sezonowości i produkcji
- Aplikacja mobilna dla hurtowników
- System lojalnościowy i CRM
- Wielojęzyczność (PL/EN)
- Marketplaces: Allegro, Etsy, Meta Shops

---

## 🧠 Repozytorium

Ten projekt to fundament cyfrowego ekosystemu dla rodzinnej firmy opartej na zaufaniu, doświadczeniu i kwiatowym pięknie.

---

> **Made with 💐 by Kwiaty Teresy & rodzinna dusza technologii**
