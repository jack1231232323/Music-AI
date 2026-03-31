# Music-AI
IT1030SEF

Musetify – Beats for Your Soul

Getting Started
Open the music AI l .html file in any modern web browser.

You will see the login screen.

Demo admin account: admin / admin123

Or click Create account to register a new user.

After logging in, you can start exploring music recommendations.

User Guide
Dashboard
Mood selector: choose from Happy, Sad, Focus, Energetic, Relax.

Activity selector: choose from Work/Coding, Workout/Gym, Chill/Relax.

Refresh my mix: generate a new set of 5 songs based on your current mood and activity.

Recent activity: shows your last three ratings (like/dislike) with the song title.

Playlist
Each song card shows title, artist, and genre.

Click the ▶️ icon to listen on YouTube.

Use the 👍 (like) or 👎 (dislike) buttons to rate the song. Your feedback instantly improves future recommendations.

Chat Assistant
Click the floating chat bubble at the bottom‑right corner.

Type a message describing your mood or activity – e.g., “I’m feeling happy and going to the gym” or “Need focus music for coding”.

The bot will detect your vibe, generate a playlist, and reply with a list of songs.

The new playlist will also appear in the dashboard.

Admin Guide
If you log in with an admin account (e.g., admin / admin123):

Click the Admin button on the top‑right.

In the admin panel you can:

Users – view all registered users, delete non‑protected accounts.

Songs – view all songs, delete any song, or add a new song manually.

Note: The admin account with id 1001 is protected and cannot be deleted.

Technical Notes
The app is entirely client‑side – no server or database is needed.

All user data (accounts, songs, feedback) is stored in localStorage.

The “AI” chat assistant uses keyword detection to infer mood and activity, then calls the same recommendation engine.

Recommendations combine:

Mood‑energy‑valence matching

Activity‑based scoring

User’s like/dislike history (+25 points for liked, –90 for disliked)

Random variation to avoid repetition

Troubleshooting
No songs appear?
The app comes with a default library of 11 songs. If you accidentally deleted them, you can re‑add songs via the admin panel.

Chat bot doesn’t understand me?
Try to include clear mood words like happy, sad, focus, energetic, relax, and activity words like work, gym, chill. If still unsure, it will prompt you.

Likes/dislikes not saving?
They are saved instantly. You can verify them in the recent activity section.
