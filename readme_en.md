[中文版 (Chinese Version)](README.md)

# hourly-journal

Hourly journal, practicing Lyubishchev's time-tracking method, light up your 24 "time coins."

## Introduction

"Hourly Journal" is a lightweight web application designed to help users record and review their activities and status on an hourly basis. Through simple logging and tagging, users can gain a clearer understanding of their time allocation, practice Lyubishchev's time-tracking method, and enhance self-awareness and life efficiency. All data is stored locally in the user's browser, ensuring privacy.

"Hourly Journal" is a lightweight web application. You can try it live at [coin.xyzhuang.asia](http://coin.xyzhuang.asia).


## Features

* **Hourly Logging:** Record activities and mood/status on an hourly basis.
* **Tagging System:**
    * Preset tags like "Efficient," "Slacking," "Average," "Perfect."
    * Users can customize tag names and their exclusive colors.
    * Tag colors are visually displayed as the background of time slots.
* **Smart Collapse:** Time slots with no records automatically collapse, keeping the interface clean. Click to expand and log.
* **Easy Navigation:**
    * Easily switch to view records for "Previous Day" and "Next Day."
    * Real-time clock display at the top; click it to quickly log the "previous hour."
    * Current hour is highlighted.
* **Personalization:**
    * **Light/Dark Mode** toggle.
    * **Font Size Adjustment** with a slider, buttons, and reset option.
* **Data Export:**
    * Export **today's** records.
    * Export **all** historical records as a `.txt` file.
    * Preview before exporting and one-click copy to clipboard.
* **Local Storage:** All data is stored in the browser's `localStorage`, protecting user privacy.
* **Add to Home Screen:** The web page can be added to the mobile home screen for an app-like experience.
* **Donation Support:** If you find this little tool useful, you can support the developer through the methods in the settings.

## How to Use

1.  Open the `index.html` file directly in your browser (or the web link if you deploy it, e.g., [Live Demo](https://xiaoyuzhuang.github.io/hourly-journal/)). 2.  **Main Interface:**
    * Displays the 24-hour record slots for the current day by default.
    * Click the "Click to Record" button in a time slot (or an already expanded area) to enter notes and select a tag.
    * Use the "< Prev Day" and "Next Day >" buttons to browse records from different dates.
    * Click the time display area at the top to quickly backfill a record for the previous hour.
3.  **Settings Interface (Gear icon ⚙️ in the top right):**
    * Toggle Light/Dark mode.
    * Adjust the global font size.
    * Manage (add/delete) custom tags and their colors.
4.  **Data Export (Bottom of the main interface):**
    * Choose "Export Today's Records" or "Export All Records (TXT)."

## Disclaimer

1.  **Data Safety & Backup:** All data in this application is stored in your current browser's **local storage (`localStorage`)**. This means:
    * Data is not uploaded to any server, ensuring your privacy.
    * **Clearing browser cache, changing browsers, using incognito/private mode, or reinstalling the operating system may result in permanent loss of recorded data.**
    * It is strongly recommended to use the "Export All Records" feature regularly to back up your data to a safe location. The developer is not responsible for data loss due to user mishandling or browser behavior.
2.  **Open Source & Usage:** This project's code is open source. We welcome and encourage community members to modify, create derivative works, or otherwise continue to advance its functionality based on this project. If you use the code, design concepts, or significant functional modules from this project, please **clearly credit the original author (e.g., XiaoyuZhuang) and link to this project's GitHub repository (https://github.com/XiaoyuZhuang/hourly-journal)** in your derivative work or related documentation. We promote a spirit of openness and collaboration, but also ask that you respect and correctly attribute original contributions.
3.  **Purpose:** This tool aims to provide a simple aid for time logging and reflection, helping users better manage their time. It does not guarantee any specific efficiency improvements, and actual results may vary by individual.
4.  **Feedback & Suggestions:** You are welcome to submit issues encountered or suggestions for improvement via GitHub Issues on the project repository.

## How to Contribute

We warmly welcome you to contribute to `hourly-journal`! Whether it's reporting bugs, proposing new features, or directly contributing code, your support is invaluable to the project.

1.  **Fork this repository**
2.  **Create your feature branch** (`git checkout -b feature/AmazingFeature`)
3.  **Commit your changes** (`git commit -m 'Add some AmazingFeature'`)
4.  **Push to the branch** (`git push origin feature/AmazingFeature`)
5.  **Open a Pull Request**

Before submitting a Pull Request, please ensure your code adheres to the project's existing style and has been adequately tested.

If you use code or inspiration from this project in your own work, please remember to **credit the original author and project link** as outlined in the "Disclaimer" section. Thank you for your respect and support!

## Future Plans (TODO)

* [ ] Cross-device synchronization (may require backend support)
* [ ] Richer data statistics and visualization
* [ ] PWA support for a better offline experience

---

Hope you enjoy this tool!
