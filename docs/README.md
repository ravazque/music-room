*This project has been created as part of the 42 curriculum by ravazque, acerezo- and maanguit.*

---

## Description

Music Room is a **collaborative mobile application** for sharing music in real time. Several users join the same event or playlist and interact with it simultaneously, with the backend acting as the single source of truth.

The subject defines three user stories, of which at least two must be implemented:

- **Music Track Vote** — live events where participants vote for tracks; the most voted song moves up the queue and plays first. Events can be public or private, and voting rights can be restricted by invitation, location or time window.
- **Music Control Delegation** — playback control (play, pause, skip) can be delegated to other users under per-device licenses.
- **Music Playlist Editor** — playlists edited collaboratively in real time by several users at once.

Cross-cutting requirements include full authentication (email/password with validation and recovery, plus OAuth login and account linking), user profiles with granular visibility, integration with a music provider SDK for playback, a documented REST API, and real-time synchronization across devices with proper conflict handling. Security matters: users only access their own data, every action is logged, and all secrets stay out of the repository.
