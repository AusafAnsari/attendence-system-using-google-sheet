
# 📝 Attendance System Using Google Sheets

A simple and effective desktop app built with **CustomTkinter** and **Google Sheets API** that allows users to mark attendance and automatically log it to a Google Sheet. Perfect for small teams, classrooms, or event check‑ins!

---

## ✨ Features

- ✔️ Mark attendance status: Present, Absent, or Late
- 🕓 Log timestamp and name directly into Google Sheets
- 📋 View current attendance records in-app before submitting
- 🧹 Clear form functionality for new entries
- Simple and intuitive user interface

---

## 🚀 Getting Started

### Prerequisites

- Python 3.x installed
- A Google Cloud project with **Google Sheets API** enabled
- `credentials.json` OAuth credentials downloaded

### Setup Instructions

1. **Clone the repository**

```bash
git clone https://github.com/AusafAnsari/attendence-system-using-google-sheet.git
cd attendence-system-using-google-sheet
```

2. **Install required packages**

```bash
pip install gspread oauth2client customtkinter
```

3. **Add your Google API credentials**

Place your `credentials.json` file in the project root.

4. **Update spreadsheet ID**

Open `attendance_system.py` and set:

```python
SPREADSHEET_ID = 'your_google_sheet_id_here'
```

5. **Run the application**

```bash
python attendance_system.py
```

---

## 🧠 How It Works

- User enters name and selects status (Present / Absent / Late)
- On submission, a new row is added to the specified Google Sheet, including timestamp
- App retrieves and displays the current attendance log in real time

---

## 📂 Project Structure

```
attendence-system-using-google-sheet/
├── attendance_system.py      # Main app logic and UI
├── credentials.json          # Google Sheets API credentials
├── requirements.txt          # Python dependencies
└── README.md
```

---

## 🔐 Security & Permissions

- Make sure your Google Sheet has appropriate sharing settings — e.g. accessible to your service account
- Secure your `credentials.json` and do **not** commit it to public repositories

---

## ✍️ Author

**Ausaf Ansari**

[GitHub Profile](https://github.com/AusafAnsari)

---

## 📝 License

This project is open-source under the **MIT License**.


![image](https://github.com/user-attachments/assets/30b14a1b-2450-4341-b163-96e351f4d92b)


ɪɴ ᴛʜɪꜱ ᴘʀᴏᴊᴇᴄᴛ ᴡᴇ ʜᴀᴠᴇ ᴍᴀᴋᴇ ᴀ ꜱᴛᴜᴅᴇɴᴛ ᴀᴛᴛᴇɴᴅᴀɴᴄᴇ ꜱʏꜱᴛᴇᴍ ᴜꜱɪɴɢ ɪɴᴘᴜᴛꜱ ᴡʜɪʜ ᴀʀᴇ ʙᴇɪɴɢ ᴅɪʀᴇᴄᴛʟʏ ꜱᴀᴠᴇᴅ ᴛᴏ ɢᴏᴏɢʟᴇ ᴅʀɪᴠᴇ ᴜꜱɪɴɢ ɢᴏᴏɢʟᴇ ᴄʟᴏᴜᴅ ᴄᴏɴꜱᴏʟᴇ ɪɴ ᴇxᴄᴇʟ ꜰɪʟᴇ


![image](https://github.com/user-attachments/assets/c6fcc0d1-4f9e-42f2-bf60-1e248d773595)
