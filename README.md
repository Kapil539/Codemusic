# 🎵 MoodMusic

A modern mood-based music application that suggests and plays tracks based on your vibe.
Built with **React**, **Vite**, **TailwindCSS**, **Supabase**, and the **Spotify Web API**.

---

## 🚀 Tech Stack

- [React](https://reactjs.org/)
- [Vite](https://vitejs.dev/)
- [TailwindCSS](https://tailwindcss.com/)
- [Supabase](https://supabase.com/) (Database and Auth)
- [Spotify Web API](https://developer.spotify.com/documentation/web-api/)
- [Radix UI](https://www.radix-ui.com/) (for accessible UI components)

---

## 📂 Project Structure

```
src/
├── assets/           # Static files (images, icons, etc.)
├── components/       # Reusable UI components
│   └── ui/           # Custom styled UI primitives
├── pages/            # Application pages
├── services/         # API services (Spotify, Supabase integration)
├── lib/              # Utility functions (like `cn` className helpers)
├── App.tsx           # Main app file
└── main.tsx          # Entry point
```

---

## 🔧 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/moodmusic.git
cd moodmusic
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure Environment Variables

Create a `.env` file in the root:

```bash
# Spotify API
VITE_SPOTIFY_CLIENT_ID=your_spotify_client_id
VITE_SPOTIFY_CLIENT_SECRET=your_spotify_client_secret

# Supabase
VITE_SUPABASE_URL=https://your-project.supabase.co
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

> ⚡ You can get the Supabase credentials from your Supabase project dashboard.

---

### 4. Run the Development Server

```bash
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) to see the app running.

---

## 🛠 Features

- 🔍 **Search Tracks** — Search songs based on your mood and keywords.
- 🧐 **Mood-Based Playlists** — Smart music curation.
- 🎷 **Spotify API Integration** — Stream music directly.
- 🛡️ **Authentication** — Supabase Auth integration (coming soon).
- ☁️ **Supabase Database** — Save user moods, playlists, history, etc.
- 🎨 **Beautiful UI** — Built with TailwindCSS and Radix UI.

---

## 📝 TODO

- [ ] User Authentication with Supabase
- [ ] Save favorite playlists to Supabase
- [ ] Mood prediction using AI
- [ ] Mobile responsiveness improvements
- [ ] Upload user profile images (Supabase Storage)

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 🤝 Contributing

Pull requests are welcome!
Please open an issue first to discuss changes or improvements.

---

## 💬 Contact

Feel free to connect:

- GitHub: (https://github.com/Kapil539)
- Email: kapilsanodiya539@gmail.com

---

