---

## Important Notes

*   **Database:** The `shawarma_pos.db` file is automatically created upon the first launch.
*   **Environment:** Ensure that the `.db` file is ignored by Git to protect business data (already configured in `.gitignore`).
*   **Auto-Reload:** If the app reloads during database writes, ensure the `.db` file is located outside the `src-tauri` watch path.

---

##  Contribution

Contributions are welcome! If you have ideas for new features or find any bugs, feel free to open an **Issue** or submit a **Pull Request**.

---

##  Key Features

*   ** Blazing Fast Performance:** Built with Rust and Tauri, ensuring minimal RAM usage and instant response times.
*   ** Offline-First:** Uses a local SQLite database, meaning the system works perfectly without an internet connection.
*   ** Customer Loyalty System:** Track customer points, apply discounts based on loyalty, and manage phone-linked profiles.
*   ** Smart Reporting:** Real-time tracking of total sales, expenses, order counts, and net profit.
*   ** Expense Management:** Easily record inventory purchases with Quantity × Price calculations.
*   ** Admin Dashboard:** Manage menu items, prices, and categories without needing technical skills.

---

## Tech Stack

*   **Frontend:** React.js, TypeScript, Tailwind CSS.
*   **Backend:** Rust (Tauri framework).
*   **Database:** SQLite (via Rusqlite).
*   **State Management:** React Hooks.

---

## Getting Started

### Prerequisites
1.  Install [Rust](https://www.rust-lang.org/tools/install).
2.  Install [Node.js](https://nodejs.org/).
3.  Install a package manager (npm, yarn, or pnpm).

### Installation Steps
1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git)
    cd YOUR_REPO_NAME
    ```

2.  **Install Dependencies:**
    ```bash
    pnpm install  # or npm install
    ```

3.  **Run in Development Mode:**
    ```bash
    pnpm tauri dev
    ```

4.  **Build Production Executable:**
    ```bash
    pnpm tauri build
    ```

---

## Project Structure
```text
├── src/                # Frontend code (React/TypeScript)
├── src-tauri/
│   ├── src/            # Backend logic (Rust)
│   ├── Cargo.toml      # Rust dependencies
│   └── tauri.conf.json # Tauri configuration
└── README.md           # Project documentation

## Developed By: Alan Mouawad
