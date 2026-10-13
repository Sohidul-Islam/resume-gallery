# Candidates Document System

This directory stores all candidate documents. Each candidate has an isolated, self-contained folder.

## Folder Structure
```text
candidates/
├── Farhana-Akter/
│   ├── index.html       (CV document)
│   └── assets/          (photo.jpg, style.css)
├── Tanvir-Ahmed/
│   ├── index.html       (Resume document)
│   └── assets/          (photo.png, style.css)
├── Nusrat-Jahan/
│   ├── index.html       (Biodata document)
│   └── assets/          (photo.jpg, style.css)
└── _template/
    ├── index.html       (Starter template)
    └── assets/          (style.css)
```

## How to Add a New Candidate (3 Simple Steps)

1. **Duplicate Folder**: Copy the `_template` folder and rename it to your candidate's name (e.g. `candidates/Rakib-Hasan/`).
2. **Add Candidate Photo**: Place the candidate's portrait in `candidates/Rakib-Hasan/assets/photo.jpg`.
3. **Edit Document**: Open `candidates/Rakib-Hasan/index.html` and update the candidate's name, document type, experience, and contact details.

To display them on the main Dashboard, simply add their entry in `candidates-data.js` in the root folder, or click **"Add Candidate"** on the dashboard.
