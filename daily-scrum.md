# Daily Scrum – Jour 26/09/2025
**Sprint Goal** : Alerte temps réel ≤10 s sur 1 ruche, image + score, event loggué.  
**Probabilité d’atteindre le SG** : 3/5

## Olivier
- **Hier** : Pipeline capture → horodatage stabilisé, stockage image OK.
- **Aujourd’hui** : Table SQLite `events` (id, ruche, ts, espèce, score, image_path) + écriture depuis pipeline.
- **Blocages** : Drift horloge caméra/machine → (owner Olivier, ETA 15h via NTP).

## Kahina
- **Hier** : Annotation complétée (500/500), ROI entrée de ruche, maquette timeline Streamlit.
- **Aujourd’hui** : Webhook Discord (image + score + horodatage) + filtres par ruche/date.
- **Blocages** : Besoin de 10 vidéos “faux positifs” (ombres/nuages) → (owner Romuald, ETA 14h).

## Romuald
- **Hier** : Export YOLOv8n ONNX + quantization ; latence 12,1 s → 8,7 s (machine terrain).
- **Aujourd’hui** : Ajouter hard negatives + réglage `conf/iou` ; petit sweep d’augmentations luminosité.
- **Blocages** : Mémoire GPU Jetson limitée → batch=1, FP16 (owner Romuald, ETA 16h).

---

### Actions ≤24 h
- Olivier : créer `events` + write depuis pipeline.
- Kahina : envoyer alerte Discord avec vignette + score ; activer filtres timeline.
- Romuald : livrer 10 vidéos “faux positifs” à Kahina ; optimiser mémoire Jetson.

### Impediments
- Vidéos terrain manquantes (créneau collecte) — à planifier demain 10–12h.

### Décision du jour
- L’audio est hors scope du Sprint S02 (report Sprint S03).
