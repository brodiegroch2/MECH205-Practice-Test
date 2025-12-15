# MECH 205 Practice Tests

This repository contains a structured JSON-based question bank for MECH 205 self-examination, designed for AI-assisted oral and written testing.

## Repository Structure

```
questions.json   — All questions and solutions
images/          — Diagrams referenced by questions
```

## Question Format (Schema Overview)

- question_number
- test_number
- question_text
- question_type
- images (array of filenames)
- options (array)
  - letter
  - text
  - is_correct
  - images (array of filenames)
  - is_image_answer
- correct_answer
- answer_text

## Image Linking Rule

Images are referenced by filename only. Images live in `/images`. Use raw GitHub URLs when testing in ChatGPT. Images without `-A` are used in the question itself; images with `-A#` are answer option images.

## How to Use With ChatGPT

- Paste a question object from questions.json
- Resolve image filenames to raw GitHub URLs
- Instruct ChatGPT to act as an examiner

## Scope

This is for MECH 205 exam preparation. Content is exam-focused. Questions prioritise understanding over memorisation.
