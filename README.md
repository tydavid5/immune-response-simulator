# Immune Response Simulator

An interactive simulator of the human immune response to infection and vaccination, built for learning, classrooms and conferences.

Open `index.html` in a browser. No build step, no server, no account needed.

## What it does

Body level:
- 8 scenarios, including Influenza, Staph wound, mRNA vaccine, second-exposure memory response, malaria, TB, measles and cholera
- 9 tappable immune players, including dendritic cells, NK cells, cytokines and complement
- A playable 14-day timeline, live response curves, day-by-day plain-language explanations, fever, pathogen and antibody stats, a lymph-node journey tracker, a cytokine readout, and a Healthy vs Immunocompromised toggle
- A quiz

Population level:
- An Outbreak and Herd Immunity lab with 6 population diseases and 9 places: Nigeria, Ghana, Kenya, South Africa, Egypt, India, Brazil, UK, USA, plus Global
- A real SIR epidemic curve, herd threshold (1 - 1/R0), effective R, peak and total infected, a plus 20 percent coverage comparison, and a graded table showing each place's gap to the line

Public level:
- Presenter mode, fullscreen, session codes students can join to land on the teacher's exact scenario, a live class poll, and a 3-question team quiz with a session leaderboard

## Important notes

This is a simplified educational model, not medical advice, and not for diagnosis or treatment decisions.

Region coverage figures are rounded teaching estimates, not live data. For live figures, see WHO and UNICEF WUENIC.

The SIR model was audited in v3: it integrates in quarter-day steps with clamped compartments, so S plus I plus R is conserved and totals never exceed 100 percent. At Nigeria's 60 percent measles coverage, the model gives a peak of about 23,231 per 100,000, with 41.7 percent total infected.

Poll and leaderboard state is in-session only and is not saved.
