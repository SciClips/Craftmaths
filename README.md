# Craftmaths

Craftmaths is a GitHub-first, cloud-based system for creating accurate, engaging mathematics explainer videos for YouTube and TikTok.

## Project direction

We are rebuilding the repository cleanly around the mathematics project. The previous repository content is being replaced; the repository itself and its Git history are retained.

### Core goals

- Turn mathematics topics and common learner difficulties into clear, structured explanations.
- Generate lesson scripts, worked examples, diagrams, and animation scenes from code.
- Use open-source tools and GitHub Actions so the workflow can run in the cloud without paid provider subscriptions.
- Validate calculations, algebraic transformations, units, and numerical examples before a video is rendered.
- Support both short-form and longer explainer formats.
- Use a hybrid visual approach: clean mathematical diagrams, 2D motion graphics, and code-generated 3D scenes when they genuinely improve understanding.
- Make the content accessible to learners at different levels, while keeping mathematical reasoning rigorous.

## Accuracy-first workflow

1. **Topic selection** — identify the concept, learning objective, prerequisites, and likely misconceptions.
2. **Mathematical planning** — define notation, assumptions, formulas, examples, and expected results.
3. **Validation** — run symbolic and numerical checks before accepting the explanation.
4. **Script generation** — create narration and a scene-by-scene teaching plan.
5. **Animation** — render diagrams and motion graphics from reproducible code.
6. **Audio and assembly** — generate or assemble narration using locally runnable/open-source components, then combine it with the visuals.
7. **Quality checks** — verify render output, timing, legibility, and mathematical consistency.
8. **Publishing assets** — prepare platform-ready video files, titles, descriptions, and captions. Publishing credentials and platform integrations will be added only when required.

## Operating principles

- **No paid provider dependency:** prefer open-source software and free GitHub-hosted automation.
- **Reproducible builds:** the same inputs and configuration should produce repeatable outputs.
- **No unverified mathematics:** a video must not pass the validation stage when its worked examples or calculations fail.
- **Beginner-friendly explanations:** teach each idea in logical steps without sacrificing correctness.
- **Small, testable increments:** build and test the pipeline module by module.

## Planned build stages

1. Repository foundation, project configuration, and automated tests.
2. Mathematics topic format and lesson/script schema.
3. Symbolic and numerical validation engine.
4. 2D animation renderer and reusable mathematical scene components.
5. Narration, subtitles, and audio/video assembly.
6. GitHub Actions workflow for end-to-end generation.
7. Short-form and long-form export profiles.
8. Quality reporting and publishing-ready metadata.

## Initial status

The repository is being reset to this project direction. Implementation will proceed in small, verifiable stages, beginning with the project foundation and mathematical validation tests.
