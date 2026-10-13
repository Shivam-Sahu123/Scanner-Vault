
# Scanner Vault

## 1. Project Overview
- **Project Title:** Scanner Vault
- **Team Members:** Shivam Sahu , Subham Pandit, Bhisham Sahu, Priyanshu Kumar
- **Technology Stack:** React, Node.js, Express.js, MongoDB, Cloudinary, Gemini API
- **Project Guide/Mentor:** Aarshi Mam
- **Project Objective:** To simplify document storage, organization, text extraction, and AI-assisted document understanding.

## 2. Problem Statement
Managing documents manually makes it difficult to organize files and quickly find important information. Scanner Vault provides a centralized application for document management, OCR-based text extraction, and AI-generated summaries.

## 3. Features
- User registration and login
- Document upload and preview
- Cloud-based document storage
- OCR text extraction
- AI-generated document summaries
- Search by filename and extracted text
- Folder organization
- Trash, restore, and permanent deletion

## 4. Technology Stack
- Frontend: React, Vite, CSS, React Router, Axios
- Backend: Node.js, Express.js
- Database: MongoDB Atlas and Mongoose
- Authentication: JWT and bcrypt
- Storage: Cloudinary
- OCR: Configured OCR service
- AI: Google Gemini API

## 5. Project Structure
- `backend/` — API and server code
- `frontend/` — React application
- `docs/` — Project report and presentation
- `screenshots/` — Application screenshots

## 6. Installation and Execution

### Prerequisites
Install Node.js and npm. Configure MongoDB, Cloudinary, and Gemini API credentials.

### Backend
```bash
cd backend
npm install
```
Create `backend/.env` with the environment variables required by the project. Start the backend using the script defined in `backend/package.json`.

### Frontend
Open another terminal:
```bash
cd frontend
npm install
npm run dev
```
Open the local URL shown in the terminal.

## 7. Screenshots / Output
Add screenshots of the dashboard, document upload, preview, OCR, AI summary, folders, and trash in `screenshots/`.

## 8. DSA Concepts Used
Document only the DSA concepts actually implemented in the source code.

## 9. Learning Outcomes
- Full-stack web development
- REST API development
- Authentication and protected routes
- Database integration
- Cloud file storage
- OCR and AI integration
- Git and GitHub version control

## 10. Future Scope
- AI chat across stored documents
- QR code and barcode scanning
- Automatic document classification
- Advanced semantic search
- Enhanced document encryption

## 11. References
- React: https://react.dev/
- Express: https://expressjs.com/
- MongoDB: https://www.mongodb.com/docs/
- Cloudinary: https://cloudinary.com/documentation
- Gemini API: https://ai.google.dev/gemini-api/docs
- GitHub: https://docs.github.com/

## 12. License
Academic project. No reuse license has been specified.
