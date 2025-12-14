<img width="757" height="297" alt="Image" src="https://github.com/user-attachments/assets/04cfb39e-1bc3-4eb6-8ee0-7f16c06b3eaf" />
# N8N-Whatsapp-To-Pipedrive-Automation
An automation that converts business card images received on WhatsApp into structured leads in Pipedrive. It uses GPT to extract contact details, checks or creates organizations and people, creates a lead, and sends a thank-you message back on WhatsApp — fully automated.

WhatsApp Business Card → Pipedrive Lead Automation

An end-to-end automation workflow that transforms business card images received on WhatsApp into fully structured leads inside Pipedrive — completely eliminating manual data entry.

This workflow listens for incoming business card images on WhatsApp, automatically downloads the image, and leverages GPT’s vision and language capabilities to analyze the card and extract key contact details such as name, phone number, email address, job title, and organization name. A custom code step then parses and normalizes the extracted data for reliable downstream processing.

The automation seamlessly integrates with Pipedrive to search for an existing organization. If the organization already exists, a new person is created and linked to it. If it does not exist, the workflow creates the organization first and then creates the person within it. In both cases, a lead is automatically generated in Pipedrive to ensure proper sales tracking.

Finally, the workflow sends a confirmation and thank-you message back to the sender on WhatsApp, creating a smooth, professional, and fully automated lead-capture experience.

🚀 Key Features

📸 Accepts business card images directly via WhatsApp

🤖 GPT-powered OCR and data extraction

🧠 Intelligent field parsing and normalization using code logic

🔍 Automated organization lookup in Pipedrive

🏢 Conditional organization creation if not found

👤 Automatic person creation linked to the correct organization

🎯 Lead creation for sales pipeline tracking

💬 WhatsApp confirmation / thank-you response

🧩 Use Cases

Sales teams capturing leads from WhatsApp

Agencies onboarding contacts quickly

Founders and SMBs reducing CRM manual work

WhatsApp-first customer acquisition flows

🛠️ Tech Stack

WhatsApp Business API

GPT (Vision + Text)

Workflow Automation (e.g. n8n / Make / custom logic)

Pipedrive CRM

✅ Outcome

By automating the entire flow from WhatsApp message to CRM lead, this workflow saves time, reduces human error, and ensures every incoming contact is immediately captured, structured, and actionable in Pipedrive.
