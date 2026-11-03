# Vedant Dethe

Third-semester student working with **C, Python, and Java**. My project work includes a movie-review emotion classifier and a group study of model compression under a limited GPU-memory budget.

## Selected work

### [Model Pruning Under an 8 GiB GPU Budget](https://github.com/DoC-Titan/minitron-pruning-under-8gb)

**Third-semester group project · Team repository hosted by [DoC-Titan](https://github.com/DoC-Titan)**

I worked on this project as part of a college group. The project studies Minitron-inspired structured compression of Qwen models under a limited GPU-memory budget.

- **Compression:** physical depth and feed-forward-network trimming, with low-rank recovery.
- **Experimental design:** matched cross-entropy-only and knowledge-distillation recovery runs across two compression levels and three seeds.
- **Systems work:** streamed teacher logits, resumable hash-verified checkpoints, and resource guardrails.
- **Evidence:** the team repository includes a technical report, per-seed results, reproduction instructions, and CPU/GPU comparisons with precision differences disclosed.

These describe the team's project scope, rather than individual ownership of every component.

[Read the team's technical report →](https://github.com/DoC-Titan/minitron-pruning-under-8gb/blob/main/reports/TECHNICAL_REPORT.md)

### [Movie Emotion Classifier](https://github.com/vedant-dethe/movie-emotion-classifier)

Classifies movie reviews into happy, sad, angry, or neutral using a **TF-IDF + LinearSVC** pipeline.

- **Two interfaces:** a Tkinter desktop application and a Streamlit web interface.
- **Shared inference:** both interfaces call the same prediction backend.
- **Training:** class balancing through resampling, with the vectorizer and classifier saved as one pipeline.
- **Engineering notes:** architecture, model trade-offs, setup, and evaluation limitations are documented in the repository.

[Read the technical overview and run locally →](https://github.com/vedant-dethe/movie-emotion-classifier#readme)

## Technical background

| Area | Current experience |
| --- | --- |
| Languages | C, Python, Java |
| Python project tools | scikit-learn, pandas, Streamlit, Tkinter |
| Fundamentals | Data structures, algorithms, object-oriented programming |

## Current focus

Strengthening programming fundamentals and developing projects with clear documentation, reproducible setup, and meaningful evaluation.
