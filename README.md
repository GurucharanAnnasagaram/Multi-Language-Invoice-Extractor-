Key Features:
✅ Invoice Image Upload & Display – Supports JPG, JPEG, PNG formats.
✅ AI-Powered OCR & Understanding – Uses Gemini-Pro Vision to extract & analyze invoice data.
✅ User Query Handling – Users can input custom queries about the invoice, and the AI will respond accordingly.
✅ Multi-Language Support – Works with invoices in multiple languages for global usability.

Technology Stack:
Gemini-Pro Vision (Google Generative AI) – Extracts and understands invoice details.
Streamlit – Provides an easy-to-use web interface for image uploads and queries.
PIL (Pillow) – Handles image processing for previewing uploaded invoices.
Dotenv – Loads API keys securely from .env files.
How It Works:
User uploads an invoice image (in any supported format).
User enters a query related to the invoice (e.g., "What is the total amount?").
Gemini-Pro Vision processes the image and extracts the relevant data.
AI responds with the extracted details based on the user query.
