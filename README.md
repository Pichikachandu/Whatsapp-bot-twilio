# WhatsApp Automation Bot (Python)  

This is a modified version of the **WhatsApp Bot Using Python**, originally cloned and customized for automated message handling using **Twilio API**. This bot enables sending various types of responses, including text, images, videos, documents, and audio messages.  

## Features  

- **Automated Text Responses**  
- **Image and Video Messaging**  
- **Document and Audio Handling**  
- **File Retrieval from WhatsApp to Server**  

## Installation  

### Prerequisites  
- **Python 3.x** installed  
- A **Twilio account** with a WhatsApp sandbox setup  

### Setup Instructions  

1. **Clone the Repository**  

   ```sh
   git clone <your-modified-repo-link>
   cd <your-repo-name>
   ```  

2. **Create a Virtual Environment**  

   ```sh
   virtualenv env --python=python3
   source env/bin/activate  # Activate the virtual environment
   ```  

3. **Install Dependencies**  

   ```sh
   pip install -r requirements.txt
   ```  

4. **Run the Flask App**  

   ```sh
   python whatsapp.py
   ```  

## How It Works  

1. Connect your WhatsApp account with Twilio's sandbox.  
2. Set up a Twilio webhook to receive and process incoming messages.  
3. Configure the bot to send automated responses.  
4. Handle different types of media files and save them on the server.  

## Credits  

Developed and customized by **Pichika Chandu**. Originally cloned and modified for personal enhancements.  
