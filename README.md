# Automated Sales Reporting via Google Sheets & Apps Script

This project automates salesman-wise sales reporting using Google Sheets and Google Apps Script.  
It filters sales data based on an approved salesman list and sends each salesman an email containing only their relevant records.

The automation is triggered using a button inside Google Sheets, removing the need for manual filtering, copying, or emailing.

---

## How It Works

- **Sheet1** contains all sales transactions  
- **Sheet2** contains the approved list of salesmen and their email IDs  
- The script:
  - Reads the salesman list from Sheet2  
  - Filters matching sales records from Sheet1  
  - Groups data per salesman  
  - Emails each salesman their respective data in tabular format  

---

## Sheet Structure

### Sheet1 – Sales Data
| Column | Header |
|------|--------|
| A | Sale Date |
| B | Region |
| C | State |
| D | City |
| E | Product |
| F | Quantity |
| G | Salesman |
| H | Age |
| I | Price per Unit |
| J | Sales Amount |

### Sheet2 – Salesman Directory
| Column | Header |
|------|--------|
| A | Serial |
| B | Salesman |
| C | E-Mail |

---

## Setup Instructions

1. Open Google Sheets  
2. Go to **Extensions → Apps Script**  
3. Paste the script into the editor  
4. Save the project  
5. Insert a button using **Insert → Drawing**  
6. Assign the script function to the button  
7. Run once to authorize permissions  

---

## Key Features

- Salesman-wise data filtering  
- Automatic email delivery  
- One-click execution via button  
- No data modification or deletion  
- Fully customizable  

---

## Technologies Used

- Google Sheets  
- Google Apps Script  
- Gmail Service  

---

## Use Cases

- Sales reporting automation  
- Internal performance tracking  
- Team-wise data sharing  
- Manual reporting elimination  

---

## Special Thanks

Special thanks to **Vikas Singh**  
GitHub: https://github.com/vikas98SSS  

For guidance, inspiration, and contributions toward automation workflows.

---

## License

This project is open for learning and personal use.  
Feel free to fork, improve, and adapt it for your own workflows.
