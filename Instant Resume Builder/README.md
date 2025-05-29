# Instant Resume Builder (Demo)

A modern resume builder that allows users to create, preview, and export professional resumes.  
Includes cloud save and load features using Firebase.

Note: This is a showcase project. Source code is not publicly available.

## Live Demo

https://instant-resume-builder.vercel.app/

## Features

- Editable sections: Profile, Education, Skills, Experience, Projects
- Real-time preview matching final PDF export
- High-quality PDF output with consistent spacing and formatting
- Smart formatting for multilingual content (CJK support)
- Auto-formatting of contact information with conditional separators
- Resume cloud storage using Firebase (unique Resume ID)
- Fully responsive UI built with Tailwind CSS

## Tech Stack

- Frontend: React, Vite
- Styling: Tailwind CSS
- Cloud: Firebase Firestore
- Deployment: Vercel

## How It Works

1. Fill in resume content section by section
2. Preview the resume layout in real-time
3. Export a PDF with matching formatting
4. Save resume to the cloud and retrieve using Resume ID

## Recent Updates

May 2025

- Improved consistency between preview and PDF
- Enhanced bullet point spacing and alignment
- Added support for Chinese, Japanese, Korean fonts
- Smarter contact formatting
- Section titles bolded in export

## Local Development

```bash
cd insta-site
npm install
npm run dev
```

Visit http://localhost:5173

## Cloud Storage

- Resume content is stored as JSON documents in Firebase
- Each cloud save generates a new Resume ID

## License

MIT License  
Built using React, Vite, Tailwind CSS, and Firebase
