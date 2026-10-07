# InterviewIQ — AI-Powered Interview Preparation Platform

InterviewIQ is an AI-powered interview preparation platform designed to help students and job seekers prepare for technical interviews through AI-generated questions, resume-based mock interviews, performance analytics, and personalized feedback.

## 🚀 Features

- 🤖 **AI-Generated Interview Questions**
  - Generate technical and role-specific interview questions using LLM APIs.

- 📄 **Resume-Based Interview Preparation**
  - Analyze a candidate's resume and generate relevant interview questions.

- 🎤 **Mock Interviews**
  - Practice technical interviews in a simulated interview environment.

- 📊 **Performance Analytics**
  - Track interview performance and identify areas for improvement.

- 💡 **Personalized AI Feedback**
  - Receive feedback and suggestions based on interview responses.

- 🔐 **Authentication**
  - Secure user authentication and session management.

- 👤 **User Profiles**
  - Manage user information and interview preparation data.

## 🛠️ Tech Stack

### Frontend
- Next.js
- React.js
- Tailwind CSS
- shadcn/ui

### Backend & Database
- Next.js API Routes
- Supabase
- PostgreSQL

### Authentication
- Clerk

### AI
- LLM APIs

### Development Tools
- Git & GitHub
- VS Code
- npm

## 🏗️ Project Architecture

```text
InterviewIQ
│
├── app/
│   ├── api/
│   ├── dashboard/
│   ├── interview/
│   ├── profile/
│   └── ...
│
├── components/
│   ├── ui/
│   └── ...
│
├── lib/
│   ├── auth/
│   ├── database/
│   └── ...
│
├── public/
│
├── supabase/
│   └── migrations/
│
├── tests/
│
├── package.json
├── next.config.js
├── tailwind.config.js
└── README.md
```

## ⚙️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/InterviewIQ.git
```

### 2. Navigate to the project

```bash
cd InterviewIQ
```

### 3. Install dependencies

```bash
npm install
```

### 4. Configure environment variables

Create a `.env.local` file in the project root:

```env
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

LLM_API_KEY=your_llm_api_key
```

> Never commit `.env.local` or any file containing API keys or other secrets to GitHub.

### 5. Run the development server

```bash
npm run dev
```

Open:

```text
http://localhost:3000
```

## 🧪 Running Tests

Run the test suite using:

```bash
npm test
```

For a single test run:

```bash
npx vitest run
```

## 📊 Key Functional Modules

### Authentication

InterviewIQ uses Clerk for authentication and user session management.

### Interview Generation

The platform uses LLM APIs to generate interview questions based on the selected role, skills, and candidate information.

### Resume-Based Preparation

Users can use their resume information to create personalized interview preparation sessions.

### Performance Tracking

Interview results and user activity are stored in the database and can be used to provide performance insights.

### Database

Supabase PostgreSQL is used to store application data such as:

- User profiles
- Teams
- Team memberships
- Work items
- Interview-related data
- Activity information

## 🔒 Security

The project follows basic security practices including:

- Environment variables for sensitive credentials
- Authentication and authorization
- Database access controls
- Input validation
- Protected application routes
- No API keys committed to the repository

## 🎯 Future Improvements

- Real-time AI voice interviews
- Speech-to-text interview analysis
- Advanced resume parsing
- Coding interview environment
- Company-specific interview preparation
- Advanced performance dashboards
- Interview history and progress tracking
- Personalized preparation roadmap

## 👨‍💻 Author

**Arun Kumar Singh**

Computer Science & Engineering  
National Institute of Technology, Delhi

## 📄 License

This project is developed for educational and portfolio purposes.
