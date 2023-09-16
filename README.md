# whatsapp-web-automation
This project is a Python script that automates sending messages on WhatsApp using the Selenium web automation library and managing data with Pandas and Openpyxl. It allows you to send messages to multiple WhatsApp contacts , listed in an Excel file. The script logs the sent messages and updates the spreadsheet with the status and timestamp of each message sent.

## Usage

- Clone this repository or download the script to your local machine.
- Update the `driver_path` variable in the script with the correct path to ChromeDriver.
- Create an Excel spreadsheet with the following columns:
  - `phone`: Phone numbers of the contacts you want to message.
  - `name-surname`: Name and surname of the contact.
  - `has_send`: Status of the message (leave it blank initially).
  - `sending_date`: Timestamp of when the message was sent (leave it blank initially).
- Update the `URL` variable in the script with the path to your Excel spreadsheet.
- Run the script by executing the following command in your terminal:
  ```bash
  python whatsapp_automation.py

## Customize
You can customize the message you want to send by modifying the send_message function in the script. Change the message content as needed.


