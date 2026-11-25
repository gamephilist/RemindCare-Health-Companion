# RemindCare — Senior Medication & Caregiver Companion PWA

**RemindCare** is an accessible, local-first Progressive Web App (PWA) built to help seniors manage daily medications and vitals while giving caregivers real-time oversight and emergency dispatch tools.

🌐 **Live App:** [remindccare.netlify.app](https://remindccare.netlify.app)

---

## 🔒 Strict Privacy-First Architecture

User privacy is strictly maintained by **not storing any user, personal, or medical data on external servers**:
* **100% Local Storage:** All patient profiles, medication schedules, vitals logs, and caregiver notes stay on the user's own device via browser `localStorage`.
* **Zero Backend or Cloud Database:** No accounts, remote servers, or hidden data collection.
* **Portable Backups & Exports:** Users can export/restore full **JSON** backups or download **CSV** health reports locally anytime.
* **Explicit User Actions Only:** Phone calls and WhatsApp alerts/refill orders only open when the user taps the action button.

---

## ✨ Key Features

### Senior View (Accessibility-First)
* **High-Contrast Ergonomic Interface:** Large text, clear time slots (**Morning**, **Afternoon**, **Evening**, **Night**), and big tap targets.
* **Voice Schedule Readouts & Chimes:** Uses the **Web Speech API** to read pending medicines aloud and the **Web Audio API** for reminder chimes.
* **One-Tap Dose Confirmation:** Mark doses as taken (with automatic stock deduction and undo support) and track daily adherence progress.
* **Quick Vitals Check-In:** Log **BP Systolic**, **BP Diastolic**, **Blood Sugar**, and **Pulse** with instant clinical range status (`Normal`, `Elevated`, `High Alert`).
* **Emergency SOS:** One-tap call to the primary caregiver or doctor, plus a pre-filled WhatsApp alert with the latest vitals summary.

### Caregiver Dashboard
* **7-Day Adherence Trend:** Visual bar chart tracking weekly adherence with editable historical days.
* **Prescription Manager:** Add, edit, duplicate, or remove medicines, dosages, times, meal instructions, pill color tags, and low-stock thresholds.
* **Pharmacy Inventory & Refills:** Adjust stock counts (`-1`, `+1`, `+30 Refill`), copy the order list, or send a refill order on WhatsApp.
* **Caregiver Notes & Logs:** Manage care instruction notes, edit the daily dose audit log, and edit or export the vitals history log.

---

## 🛠️ Tech Stack
* **Frontend:** HTML5, Tailwind CSS, Vanilla JavaScript
* **Browser APIs:** Web Speech API, Web Audio API, Web Storage API (`localStorage`), Dynamic Blob PWA Manifest

---

## 🚀 How to Run & Install
1. Open the live app at **[remindccare.netlify.app](https://remindccare.netlify.app)** (or open the HTML file directly in any modern browser).
2. **Install on Phone Home Screen:**
   * **Android (Chrome):** Tap **⋮** → **Add to Home screen** / **Install app**.
   * **iPhone (Safari):** Tap **Share** → **Add to Home Screen**.

---

## ⚠️ Medical Disclaimer
RemindCare is a hackathon/assistive reminder and logging tool—not a certified medical device or medical diagnosis service. Always consult a qualified healthcare professional for medical advice and emergencies.
