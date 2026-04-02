# Brevoneu 🧠

**Multimodal Healthcare AI for Early Health Risk Detection**

Brevoneu uses non-invasive digital biomarkers across three signal modalities to detect early health risks — no wearables, no lab tests.

## Modalities
- 🫁 **Respiratory** — breathing pattern analysis
- 🎙️ **Voice / Acoustic** — vocal biomarker features
- 🤝 **Neuromuscular Tremor** — micro-tremor signal analysis

## Stack
| Layer | Technology |
|-------|-----------|
| Backend API | Python + FastAPI |
| ML / Inference | TensorFlow Lite |
| Mobile App | Flutter (Android + iOS) |
| Web Dashboard | React.js |
| Infra | Docker + Nginx |

## Structure
```
brevoneu/
├── backend/       # FastAPI server + ML pipeline
├── mobile/        # Flutter app
├── web/           # React.js dashboard
├── data/          # Raw & processed biomarker data
├── notebooks/     # Research & EDA notebooks
├── docs/          # Architecture, API, research docs
└── infra/         # Docker, Nginx, CI configs
```
