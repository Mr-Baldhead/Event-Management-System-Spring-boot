# Event Management System

Ett eventhanteringssystem för scoutorganisationer, byggt med Spring-boot och Thymeleaf

---

## 🚀 Snabbstart

### Förutsättningar

- [Docker Desktop](https://www.docker.com/products/docker-desktop/) installerat
- Git

### 1. Klona projektet

```bash
git clone <repository-url>
cd Event-Management-System-Spring-boot
```
### 3. Starta systemet

```bash
mvn spring-boot:run
```

### 4. Öppna applikationen

|  URL |
|--------|
| http://localhost:8080

---

## 🔐 Inloggningsuppgifter

| Fält | Värde |
|------|-------|
| **Användare** | admin |
| **Lösenord** | admin123 |

---

## **Alla tillgängliga endpoints:**
```
- GET    /api/events                    - Lista alla events
- GET    /api/events/{id}               - Hämta ett event
- GET    /api/events/upcoming           - Kommande events
- POST   /api/events                    - Skapa nytt event
- PUT    /api/events/{id}               - Uppdatera event
- DELETE /api/events/{id}               - Ta bort event
```
```
- GET    /api/participants              - Lista alla deltagare
- GET    /api/participants/{id}         - Hämta en deltagare
- GET    /api/participants/patrol/{id}  - Deltagare i en kår
- POST   /api/participants              - Skapa deltagare
- PUT    /api/participants/{id}         - Uppdatera deltagare
- DELETE /api/participants/{id}         - Ta bort deltagare
```
```
- GET    /api/patrols                   - Lista alla scoutkårer
- GET    /api/patrols/{id}              - Hämta en scoutkår
- POST   /api/patrols                   - Skapa scoutkår
- PUT    /api/patrols/{id}              - Uppdatera scoutkår
- DELETE /api/patrols/{id}              - Ta bort scoutkår
```
```
- GET    /api/allergens                 - Lista alla allergener
- GET    /api/allergens/{id}            - Hämta en allergen
- GET    /api/allergens/critical        - Kritiska allergener
- POST   /api/allergens                 - Skapa allergen
- PUT    /api/allergens/{id}            - Uppdatera allergen
- DELETE /api/allergens/{id}            - Ta bort allergen
```
```
- GET    /api/registrations             - Lista alla registreringar
- GET    /api/registrations/{id}        - Hämta en registrering
- GET    /api/registrations/event/{id}  - Registreringar för event
- POST   /api/registrations             - Skapa registrering
- PUT    /api/registrations/{id}/confirm - Bekräfta registrering
- PUT    /api/registrations/{id}/cancel  - Avboka registrering
- DELETE /api/registrations/{id}        - Ta bort registrering
```
<img width="711" height="648" alt="517589556-827579b4-f3cf-4ee0-bc00-d08af1ce4dc1" src="https://github.com/user-attachments/assets/5203e7d5-b9bb-4c90-b2c8-cea7d9dabd89" />
<img width="817" height="868" alt="517589579-91b27417-11e0-480d-84e8-aa7bb6bd8a79" src="https://github.com/user-attachments/assets/2b759015-b97e-4a09-8027-cb6274975dbd" />
<img width="1017" height="933" alt="Skärmavbild 2026-03-08 kl  16 22 43" src="https://github.com/user-attachments/assets/aded9177-089d-40df-8540-039a7daaf900" />
