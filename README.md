 Shipment Management System
A simple and user-friendly web application to manage shipment records. Built with HTML, Bootstrap, and JavaScript, and powered by JsonPowerDB for data persistence.

🚀 Features
🔍 Fetch Shipment by ID
Enter a shipment number to view details or check if it exists.


💾 Add New Shipment
Save a new shipment record including description, source, destination, and shipping details.

✏️ Update Shipment
Modify an existing shipment’s details easily.

🔄 Reset Form
Clear the form and start fresh.

🛠️ Technologies Used
Frontend: HTML5, Bootstrap 3, jQuery

Database: JsonPowerDB (JPDB)

API Interaction: JPDB Commons JS SDK

🧰 Setup Instructions
Clone the Repository

bash
Copy
Edit
git clone https://github.com/your-username/shipment-management.git
cd shipment-management
Open the Application
Open index.html in your web browser.

Update JPDB Token (Optional)
Replace the connectionToken in the script with your own if needed.

⚙️ How It Works
On loading the page, the form resets and waits for input.

Enter a Shipment Number:

If found, the form loads existing data for update.

If not found, it enables form fields for adding new data.

Fill in the fields and click Save or Change as needed.

📁 Project Structure
bash
Copy
Edit
.
├── index.html         # Main HTML file with embedded JS and CSS
└── README.md          # Project documentation
✅ Validation Rules
All fields are mandatory.

Shipment No is treated as a primary key.

Alerts and focus handling ensure no field is left empty.

📌 Notes
This app uses JPDB’s free trial token. You can get your own from login2explore.com.

Make sure to allow cross-origin requests if hosting on a local server.

📷 UI Preview

Simple and functional shipment form UI

🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you'd like to change.

📄 License
This project is open source and available under the MIT License.

