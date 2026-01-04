# 🏗️ System Architecture

## Current MVP Stack

### Google Sites
- Landing page
- Project documentation
- Navigation hub

### Canva
- Interactive UI prototype
- 6 screens with clickable navigation
- Dark theme with neon accents

### Google Forms
- Scholar Strike (MCQ game)
- Pinocchio's Code (Bug finder)
- Debug Arena submissions

### Google Sheets
- Real-time leaderboard
- XP tracking
- Guild rankings

### Google Drive
- Shared guild resources
- Code templates
- Project documentation

## Future Architecture

### Frontend Layer
- Flutter for cross-platform mobile
- PWA for web access
- Responsive design system

### Backend Services
- Firebase Authentication
- Cloud Firestore (real-time DB)
- Cloud Functions (serverless logic)
- Cloud Storage (media files)

### AI/ML Layer
- Gemini API (AI mentor)
- Vertex AI (learning paths)
- TensorFlow (skill analysis)

### Infrastructure
- Google Kubernetes Engine (scaling)
- Cloud Run (containers)
- Cloud CDN (global delivery)
- BigQuery (analytics)

## Data Flow
```
User Action → Forms → Sheets → Real-time Update → Leaderboard Display
```

## Security
- All Google Cloud infrastructure
- OAuth authentication (future)
- Data encryption at rest
- Rate limiting on submissions