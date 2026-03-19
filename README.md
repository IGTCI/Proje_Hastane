# 🏥 Hospital Automation System

A hospital management and automation application developed with C# Windows Forms and SQL Server database.

## 📋 Features

### 👤 Patient Module
- Patient login and registration system
- Patient information viewing and editing
- Appointment list tracking

### 🩺 Doctor Module
- Doctor login panel
- Doctor detail information viewing and editing
- Patient management panel

### 📝 Secretary Module
- Secretary login panel
- Patient and doctor record management
- Department (branch) management
- Announcement management

## 🛠️ Technologies Used

| Technology | Usage |
|---|---|
| **C# (.NET Framework)** | Application development language |
| **Windows Forms** | Desktop UI design |
| **SQL Server** | Database management |
| **ADO.NET (SqlClient)** | Database connectivity |
| **Visual Studio** | Development environment |

## 📁 Project Structure

```
Proje_Hastane/
├── Proje_Hastane.sln                # Visual Studio solution file
└── Proje_Hastane/
    ├── Program.cs                   # Main entry point
    ├── sqlbaglantisi.cs             # SQL Server connection class
    ├── FrmGirisler.cs               # Main login screen
    ├── FrmHastaGiris.cs             # Patient login form
    ├── FrmHastaKayit.cs             # Patient registration form
    ├── FrmHastaDetay.cs             # Patient detail form
    ├── FrmDoktorGiris.cs            # Doctor login form
    ├── FrmDoktorPaneli.cs           # Doctor management panel
    ├── FrmDoktorDetay.cs            # Doctor detail form
    ├── FrmDoktorBilgiDuzenle.cs     # Doctor info editing
    ├── FrmSekreterGiris.cs          # Secretary login form
    ├── FrmSekreterDetay.cs          # Secretary detail form
    ├── FrmBilgiDuzenle.cs           # Info editing form
    ├── FrmBrans.cs                  # Department management form
    ├── FrmRandevuListesi.cs         # Appointment list form
    └── FrmDuyurular.cs              # Announcements form
```

## 🚀 How to Run

### Requirements
- Visual Studio 2019 or later
- SQL Server (LocalDB or full version)
- .NET Framework

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/IGTCI/Proje_Hastane.git
   ```
2. Open `Proje_Hastane.sln` with Visual Studio
3. Create the required database in SQL Server (`HastaneProje`)
4. Update the connection string in `sqlbaglantisi.cs` to match your server
5. Build and run the project (`F5`)

## 👤 Author

**Göktuğ Talha Coşkunsoy**  
Computer Programming Student — Istanbul, Turkey

## 📄 License

This project is open source and was developed for educational purposes.
