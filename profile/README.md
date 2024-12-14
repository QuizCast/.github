# QuizCast Organization

Welcome to the **QuizCast GitHub Organization**! This organization hosts the repositories for **QuizCast**, a dynamic and interactive platform that allows users to create, host, and participate in real-time quiz challenges.

---

## About QuizCast

**QuizCast** is a feature-rich platform designed to deliver a seamless quiz experience. Whether you want to host a quiz or participate in one, QuizCast makes it easy, intuitive, and engaging. The platform leverages **Supabase** for real-time updates, authentication, and data management, ensuring that every interaction is smooth and efficient.

---

## Key Features

- **User Authentication**: Powered by Supabase with secure JWT token-based authentication.
- **Real-Time Updates**: Leaderboards, quiz broadcasts, and live submissions powered by Supabase Realtime.
- **Create and Join Quizzes**: Hosts can create quizzes, and participants can join using a unique quiz key.
- **Profile Management**: Hosts can upload profile pictures, stored securely in Supabase S3 buckets.
- **Responsive Design**: Built with Flowbite and Tailwind CSS for a clean and modern UI.
- **Open Source**: Fully open-source under the MIT License.

---

## Repositories

### 1. [QuizCast Frontend](https://github.com/QuizCast/frontend.git)
The frontend of QuizCast is built using **Next.js** and styled with **Tailwind CSS** and **Flowbite**. It provides an intuitive user interface for hosts and participants, featuring real-time updates and seamless interaction with the backend.

- **Key Technologies**: Next.js, Tailwind CSS, Flowbite, Supabase JS SDK
- **Hosted On**: [Vercel](https://quizcast-teamvertex.vercel.app/

#### Features:
- Realtime leaderboard updates.
- Quiz hosting and participation.
- Supabase integration for authentication and real-time broadcasting.

### 2. [QuizCast Backend](https://github.com/QuizCast/backend.git)
The backend is built with **FastAPI**, serving as the core of QuizCast's operations. It manages authentication, quiz creation, user data, and leaderboard calculations while integrating with Supabase for database operations.

- **Key Technologies**: Python, FastAPI, Supabase
- **Deployment Options**: Local, Docker

#### Features:
- User authentication with Supabase JWT tokens.
- API endpoints for quiz and user management.
- Realtime updates via Supabase PostgreSQL changes.

---

## How It Works

1. **Create an Account**:
   - Users can sign up or log in using Supabase-powered authentication.
   
2. **Host a Quiz**:
   - Create a quiz, add questions, and share the unique quiz key with participants.
   
3. **Join a Quiz**:
   - Enter the quiz key to join an active quiz.

4. **Real-Time Fun**:
   - Participants answer questions in real time while the leaderboard updates dynamically.

---

## Contribution Guide ❤️

We are an open-source organization and welcome contributions from the community! Here's how you can contribute:

1. Fork the repository you'd like to contribute to.
2. Clone it to your local machine:
   ```bash
   git clone https://github.com/your-username/repository-name.git
   ```
3. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
4. Make your changes and commit:
   ```bash
   git commit -m "Add your descriptive message here"
   ```
5. Push your changes:
   ```bash
   git push origin feature/your-feature-name
   ```
6. Create a pull request to the main repository.

---

## License

All projects under the QuizCast organization are licensed under the **MIT License**. Feel free to use, modify, and distribute our code.

---

## Contact Us

Have questions or feedback? Feel free to open an issue in any of our repositories or contact us directly. We’re excited to hear from you and improve together!

---

**Join us on this journey to redefine real-time quizzes!** 🎊
