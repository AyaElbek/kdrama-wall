# kdrama-wall

🌸 K-Drama Wall
A personal K-Drama tracker with social features, built as a portfolio project combining my love for Korean dramas with hands-on web development practice.
Live app → your-username.github.io/kdrama-wall

What it does

📋 Track every K-Drama you've watched with mood tags, genre, rating and a personal note
🖼️ Upload poster images stored in the cloud
👥 Create an account and follow friends to see what they're watching
📰 Social feed showing recent adds from people you follow
🔍 Filter by mood, genre, rating, era, actor or search by title
🔗 Share your public wall via a personal link


Why I built this
I couldn't find a tracker that felt personal enough, most are databases, not spaces that reflect your taste. I wanted something that looked like a mood board, felt like a diary, and worked like a social app.
It also gave me a reason to learn full-stack fundamentals from scratch: authentication, database design, file storage, and deploying a real app.

Tech stack
LayerTechnologyFrontendHTML, CSS, Vanilla JavaScriptDatabaseSupabase (PostgreSQL)AuthSupabase Auth (email/password)Image storageSupabase StorageHostingGitHub Pages

Features in detail
Your wall
Each drama card shows the poster, mood tag, genre tag, star rating and your personal vibe note. Cards are filterable by mood, genre, rating, decade and actor.
Social layer
Users can follow each other and see a live feed of recent additions. Every wall has a public shareable link.
Data
On first login, the wall is pre-populated with a curated list of 47 dramas — my personal watchlist with notes and tags already filled in.

Running locally
No build step needed — just open index.html in a browser.
To connect your own Supabase project:

Create a project at supabase.com
Run supabase_setup.sql in the SQL Editor
Replace the SUPABASE_URL and SUPABASE_KEY values in index.html


About me
Built by Aidai Elbekova — Business Development professional with 10+ years in Fintech and E-Commerce, currently researching Digital Transformation at University of Kassel. This project is part of my journey into product development and building things from scratch.
LinkedIn · Notion Portfolio
