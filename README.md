# Christmas Trivia

Live trivia web apps for Jonny's Christmas quizzes, one folder per year.

- [`/2026/`](https://jonnyblack-dev.github.io/christmastrivia/2026/): The Red Brick Hotel, Woolloongabba, Saturday 5 December 2026

Each page has five views (hash routing): `#register` and `#leaderboard` for phones, `#present` for the TV, and `#admin` and `#answers` for the quizmaster (PIN protected). Scores sync through a Firebase Realtime Database; with no database configured the page runs in a single-browser test mode.

Presenter keys: → / Space / click = next, ← = back, G = slide list, F = full screen, B = black screen.
