# ✈️ Hajj Flight Logistics Time Calculator (جدول مواعيد رحلات الحج)

A lightweight, responsive, single-page web application designed to streamline transit and bus scheduling logistics for Hajj pilgrims. It automatically calculates precise bus departure and drop-off times based on flight data from **Medina Airport (🕌)** and **Jeddah Airport (🌴)**.

## 🚀 Key Features
* **Automated Logic Tracking:** Handles date and day-of-the-week rollovers seamlessly when subtracting hours.
* **Airport-Specific Parameters:** * **Medina:** Bus Departure = Flight − 3 hours | Drop-off = Departure − 4 hours.
  * **Jeddah:** Bus Departure = Flight − 12 hours | Drop-off = Departure − 4 hours.
* **Excel Integration:** Embedded SheetJS (`xlsx.full.min.js`) functionality allowing logistics coordinators to export calculated schedules directly into standard `.xlsx` sheets.
* **Clean UI/UX:** Fully responsive Arabic interface styled with the modern Tajawal font and dark/light contrast elements.

## 🛠️ Tech Stack
* **Frontend:** HTML5, CSS3 (Flexbox/Grid layout)
* **Logic:** Vanilla JavaScript (Date/Time manipulation and mathematical offset rules)
* **Libraries:** SheetJS (CDN integrated for client-side file generation)

## 📁 How to Run
Simply download or clone the repository and open the `index.html` file in any modern web browser.
