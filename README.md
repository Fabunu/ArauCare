# ArauCare
ArauCare is a digital health management ecosystem specifically designed for patients with reduced mobility and chronic conditions in the La Araucanía region, Chile.

The platform serves as a vital bridge between primary healthcare centers (CESFAM) and the patient's home. By digitalizing appointment scheduling, medical exam delivery, and pharmacy stock tracking, ArauCare eliminates the need for physical displacement for administrative tasks. This is especially critical in regions with harsh weather conditions, ensuring that physical limitations or geographical distance are no longer barriers to receiving timely and dignified healthcare.

---

## Index

1. [Introduction](#1-introduction)
    * [1.1. The Problem](#11-the-problem)
    * [1.2. The Solution](#12-the-solution)
2. [Team](#2-team)
3. [Strategy](#3-strategy)
    * [3.1. Value Proposition Canvas](#31-value-proposition-canvas)
    * [3.2. UIX Persona](#32-uix-persona)
    * [3.3. Benchmarking](#33-benchmarking)
4. [Scope](#4-scope)
    * [4.1. Customer Journey Map](#41-customer-journey-map)
5. [Structure](#5-structure)
    * [5.1. Navigation Flow](#51-navigation-flow)
6. [Skeleton](#6-skeleton)
    * [6.1. Low-Fi Wireframes](#61-low-fi-wireframes)
7. [Surface](#7-surface)
    * [7.1. Interface Evolution](#71-interface-evolution)
    * [7.2. High Definition Interfaces](#72-high-definition-interfaces)
8. [Evaluation & Usability](#8-evaluation-&-usability)
    * [8.1. Feedback Implementation & Interface Refinement](#81-feedback-implementation-&-interface-refinement)
    * [8.2. Heuristic Evaluation & SUS](#82-heuristic-evaluation-&-sus)
    * [8.3. Accessibility Themes](#83-accessibility-themes)

---

## 1. Introduction
### 1.1. The Problem
In the Araucanía Region, access to Family Health Centers (CESFAM - Centros de Salud Familiar) faces a critical barrier: physical displacement. Patients with reduced mobility, the elderly, and those with chronic conditions often have to travel long distances under harsh weather conditions (cold and heavy rain) just to perform simple administrative tasks. Currently, securing a medical appointment or checking the status of an interconsultation requires physical presence, leading to long queues from the early morning, physical exhaustion, and high transportation costs for the most vulnerable population.
### 1.2. The Solution
ArauCare is a comprehensive digital solution designed to restore autonomy to the patient. Through a mobile-friendly web ecosystem, users can manage appointments, view laboratory results in PDF format, and track pharmacy stock in real-time without leaving their homes. The platform includes accessibility features such as caregiver profiles and automated notifications (WhatsApp/Calls), ensuring that technology acts as an inclusive bridge rather than a barrier. By digitalizing these processes, we reduce absenteeism, protect the patient's physical integrity, and optimize the operational capacity of healthcare centers.

## 2. Team
* Fidel Barriga (Designer)
* Fabiola Cheuquelaf (Project Manager)
* Marco Contreras (Analist)

## 3. Strategy
### 3.1 Value Proposition Canvas
This canvas illustrates the strategic alignment between ArauCare’s features and the specific needs of patients with reduced mobility. By identifying arduous physical displacement, exposure to harsh weather, and the uncertainty of appointment availability as primary pain points, the solution focuses on centralizing healthcare management through a digital-first approach. The value lies in transforming a physically exhausting process—often dependent on third parties and favorable weather—into a transparent, home-based ecosystem. This ensures that appointment scheduling, exam results, and pharmacy stock tracking are just a click away, significantly reducing operational friction for patients, their caregivers, and CESFAM staff in the Araucanía region.
<img width="1292" height="697" alt="Captura de pantalla de 2026-04-20 13-47-09" src="https://github.com/user-attachments/assets/8b83972e-7443-4017-9247-c4c7eee8e12f" />

### 3.2 UIX Persona
<img width="1920" height="1080" alt="UXPersona" src="https://github.com/user-attachments/assets/6618ce66-a530-4f85-840d-f61128ffc846" />

### 3.3 Benchmarking
In order to obtain a clear strategic and visual reference for ArauCare compared to existing platforms, an in-depth benchmark was carried out to identify main functionalities, design patterns, and current service gaps that could be integrated into our project development. This analysis is specifically framed within the UX Strategy and Scope planes.

For the benchmark presented below (and detailed in the attached PDF documents), three key tools were considered: miRedSalud (Direct Competitor), Mi ChileAtiende (Analogous Competitor), and Google Calendar (Design Reference). Aspects such as visual design, navigation patterns, manual accessibility, and empty states management were analyzed.

Furthermore, domain-specific dimensions critical for our target audience in La Araucanía were evaluated, including caregiver support profiles, interoperability with State databases (FONASA / ClaveÚnica), and preventive alert systems designed to avoid unnecessary trips to the CESFAM for patients with reduced mobility.
<img width="774" height="434" alt="Captura de pantalla de 2026-05-16 17-33-25" src="https://github.com/user-attachments/assets/8032adc6-ce85-4e6b-af00-0840945ea795" />

## 4. Scope
Based on the benchmark findings, the functionalities and content of the application are determined. The characteristics identified delimit which features will be part of the solution and which were omitted or left out.

### 4.1 Customer Journey Map
Following the definition of our user profiles (UX Personas) and the platform's value proposition, we structured the Customer Journey Map. This artifact is essential for visualizing the emotional response of rural patients and their caregivers as they navigate the primary healthcare system, ensuring that ArauCare's features align perfectly with their real-time needs during high-stress and physically demanding situations.
<img width="1304" height="809" alt="Captura de pantalla de 2026-05-23 15-17-48" src="https://github.com/user-attachments/assets/201d7a05-9ced-41c6-828e-b25ae16abf06" />

## 5. Structure
### 5.1 Navigation Flow
The main navigation flow begins with Login, a necessary step to validate the user with their unique password and grant them access to the Homepage. From here, the flow branches into five main health service modules: Appointments and Care (where users can view scheduled appointments or request new ones), My Digital Health (to review their medical history, including tests and referrals), Pharmacy and Prescriptions (where users can view prescriptions associated with them and the pharmacy's stock at the CESFAM), Assistance and Mobility (for requesting transportation), and finally, account management in My Profile (where users can view their information and manage caregivers). This design allows access to all necessary functions in a maximum of three clicks.

<img width="1443" height="1080" alt="Collaborate (1)" src="https://github.com/user-attachments/assets/81cc25e8-9c3f-48bb-bd6b-5bf5605711cd" />


## 6. Skeleton
### 6.1 Low-Fi Wireframes
<img width="440" height="956" alt="Inicio sesión" src="https://github.com/user-attachments/assets/b1b42abd-ed4e-41b2-bc04-6b377aa1b8dc" /> <img width="440" height="956" alt="Home" src="https://github.com/user-attachments/assets/27318728-c356-400c-a2f7-bc57860664c3" /> <img width="440" height="1379" alt="Datos (1)" src="https://github.com/user-attachments/assets/8a6bd3ed-43d7-4b75-946d-a2b7f319c527" /> <img width="440" height="956" alt="Horas y Atenciones" src="https://github.com/user-attachments/assets/34d914bf-3f19-4343-8136-8905055509dc" /> <img width="440" height="1407" alt="Agendar una Hora" src="https://github.com/user-attachments/assets/11d4a426-65fe-4abd-93f6-04ccb93974b0" /> <img width="440" height="956" alt="Movilidad" src="https://github.com/user-attachments/assets/90ce8d57-d932-4fce-a12c-9a6e9485d510" /> <img width="440" height="956" alt="Mis recetas" src="https://github.com/user-attachments/assets/6ac3c452-6c87-4511-b904-3112affe90eb" /> <img width="440" height="956" alt="Farmacia" src="https://github.com/user-attachments/assets/0435cada-a79d-496c-a57a-1b06b3509b68" /> <img width="440" height="956" alt="Movilidad Familiar" src="https://github.com/user-attachments/assets/aee2ab8a-e7fb-471e-be58-40785cfd69f2" /> <img width="440" height="956" alt="Derivaciones" src="https://github.com/user-attachments/assets/69c5b206-02f3-450b-a350-8bfed8f0188b" /> <img width="440" height="956" alt="Mis Examenes" src="https://github.com/user-attachments/assets/09ef54da-4c5c-4370-99b7-44bd838dabb9" />

https://www.figma.com/design/1ZNKzkO1rZazYOjFfHjtcg/Wireframes?node-id=0-1&t=WLB21soTqcvsCmCk-1

## 7. Surface
### 7.1 Interface Evolution
Regarding the modifications made, the main area affected was the "Caregiver" section. The changes were as follows:

The section was renamed from "Family Mobility." This name was found to be potentially confusing with the "Mobility" section, so a clearer and more representative name was chosen.

Initially, the plan was to display family members and caregivers using a simple list with only their names. However, this display was redesigned using user cards, incorporating relevant information for each user along with a representative image, to improve the visual experience and information comprehension.

Furthermore, modifications were also made to the top bar and footer:

The top bar previously contained an icon representing a tutorial for using the corresponding section. This element was discarded because the interface was deemed intuitive enough for users to operate without additional support.
In the footer, the field indicating the user's associated CESFAM location was removed, as it was determined that this information was unnecessary in this section of the interface.

### 7.2 High Definition Interfaces
<img width="440" height="956" alt="Inicio sesión" src="https://github.com/user-attachments/assets/a2d4e247-0e93-44ea-addf-566cb8f9dd45" /> <img width="440" height="1070" alt="Home" src="https://github.com/user-attachments/assets/5f33930b-5eff-4742-85ba-8d66c8e516d6" /> <img width="440" height="1419" alt="Mis Datos" src="https://github.com/user-attachments/assets/400bab7d-6d90-40b8-99ae-2a5586dbcb53" /> <img width="440" height="1154" alt="Cuidador" src="https://github.com/user-attachments/assets/d3d4f2f5-5c90-4546-8788-e11e4d07bbb1" /> <img width="440" height="956" alt="Farmacia" src="https://github.com/user-attachments/assets/8d5f66a7-684c-442d-b68b-544ddbe0251c" /> <img width="440" height="956" alt="Mis recetas" src="https://github.com/user-attachments/assets/35dbf6bb-8952-434f-8b35-314db6daca9e" /> <img width="440" height="956" alt="Derivaciones" src="https://github.com/user-attachments/assets/6122faee-6002-4699-96a1-566669cecbc8" /> <img width="440" height="1013" alt="Mis Examenes" src="https://github.com/user-attachments/assets/f7d91ef4-abd6-40e7-9d32-8042b8524fe4" /> <img width="440" height="956" alt="Horas y Atenciones" src="https://github.com/user-attachments/assets/32a570cf-6e3a-4efd-bffc-79c6acd065fc" /> <img width="440" height="1452" alt="Agendar una Hora" src="https://github.com/user-attachments/assets/11a36efa-b4ee-43d3-a29b-889337a857b3" /> <img width="440" height="956" alt="Movilidad" src="https://github.com/user-attachments/assets/4d638202-5183-40ea-8015-b2c6261dc187" />

## 8. Evaluation & Usability

### 8.1. Feedback Implementation & Interface Refinement
Based on feedback received during the initial presentation from teaching assistants, classmates, and the professor, the following changes were implemented to improve the high-definition design:
*   **Complete UI Adjustment:** A complete adjustment of the interfaces was performed to make them look more polished, clean, and professional.
*   **Actionable Elements:** The option to "Download PDF" for prescriptions and exams was changed from a simple text link to a prominent button, facilitating interaction.
<img width="310" height="550" alt="Recetas" src="https://github.com/user-attachments/assets/ac55f3f2-f33e-42bf-ad24-453e07bf18b4" />
<img width="310" height="550" alt="Examenes" src="https://github.com/user-attachments/assets/d1651375-405a-4ae3-a093-2ce6b25fe26f" />

*   **Brand Contrast:** The color of the top *Header* was adjusted to generate greater contrast with the ArauCare institutional logo color.
<img width="364" height="74" alt="Captura de pantalla de 2026-06-23 23-52-18" src="https://github.com/user-attachments/assets/0082fb61-622f-472b-a1d8-5b358b6bbcc5" />

*   **News Redesign:** A modification was applied to the news section on the homepage so the carousel looks better and is more readable.
<img width="310" height="550" alt="Home" src="https://github.com/user-attachments/assets/97c7eab6-3a50-419c-b2c5-a606f565c695" />

*   **Scheduling Flow:** The appointment scheduling process was optimized by adjusting the specialist selection and the choice of times and dates to make it more intuitive.
<img width="310" height="550" alt="Captura de pantalla de 2026-06-24 00-12-09" src="https://github.com/user-attachments/assets/03a26edc-6a6f-498a-9497-c70a68e1edbc" />

### 8.2. Heuristic Evaluation & SUS
the project was subjected to a cross-evaluation using Heuristic Inspection and the *System Usability Scale* (SUS) metric.
*   **SUS Results:** The system obtained a global score of **61.25 (Marginally Acceptable)**, which allowed us to identify key frictions and iterate quickly.
*   **Top 5 Critical Problems Resolved:**
    1.  **Lack of feedback when scheduling (Criticality 7.66):** A success confirmation pop-up was added when the user schedules an appointment or updates their data, preventing uncertainty.
  <img width="441" height="340" alt="Captura de pantalla de 2026-06-24 00-02-00" src="https://github.com/user-attachments/assets/9ebcdc22-eb96-42bb-830e-a215c0186893" />
  <img width="432" height="320" alt="Captura de pantalla de 2026-06-24 00-02-51" src="https://github.com/user-attachments/assets/175e15bc-0332-4c31-99d8-3f126b497a8e" />

    2.  **No logo on login (Criticality 7.00):** The ArauCare logo was added to the login screen so the user always knows which application they are in.
  <img width="310" height="550" alt="Captura de pantalla de 2026-06-24 00-09-28" src="https://github.com/user-attachments/assets/0c9ab032-9ebd-4f77-85a7-cb9f84692b7d" />

    3.  **Lack of RUN format (Criticality 6.33):** Help text and a structured format were incorporated into the RUN input to prevent typing errors.
  <img width="310" height="550" alt="Captura de pantalla de 2026-06-24 00-11-04" src="https://github.com/user-attachments/assets/41bb9fb4-cbb8-4eb0-b155-5f682c2cf70a" />

    4.  **Small notifications (Criticality 6.00):** The original notification pop-up was too small for the amount of medical information, so it was replaced by a complete and detailed view.
  <img width="310" height="550" alt="Captura de pantalla de 2026-06-24 00-12-09" src="https://github.com/user-attachments/assets/71b87283-cb9d-41e4-ac81-4bfb58136014" />

    5.  **Long forms (Criticality 6.00):** The scheduling form was divided into separate steps (e.g., "Who is the appointment for?" on the first screen) to prevent user fatigue.
  <img width="441" height="929" alt="Captura de pantalla de 2026-06-23 21-29-36" src="https://github.com/user-attachments/assets/a88b5d50-889e-46c0-9929-81870b9f11b0" />

### 8.3. Accessibility Themes
Applying the guidelines covered in the class workshops, and considering that our target audience includes the elderly and people with reduced mobility, ArauCare integrates the following principles:
*   **Scalability Controls:** All main views include fixed `A- / A+` buttons so the patient can increase or decrease the font size according to their visual capacity.
*   **Contrast and Visibility:** Contrast levels were increased (such as the improvement of the *Header* against the logo) and "Empty States" were used to visually guide the user.
*   **Fitts's Law:** The conversion of text links to wide buttons (like the "Download PDF" button or the bottom navigation bar) ensures a large touch target area, ideal for users with reduced fine motor skills.
*   
figma: https://www.figma.com/design/pW9yNVOjkjajGDWZj2HGPA/Wireframes-HD?node-id=0-1&t=CXbJRbCNbrUvAqMV-1











