```
gantt
title Projet SCRUM - Detection attaques frelons
dateFormat YYYY-MM-DD
axisFormat %d/%m

section Sprint 1 Infrastructure video
Installation camera et pipeline :done, cam1, 2025-09-25, 7d

section Sprint 2 IA classification
Constitution dataset et annotation :active, data1, 2025-10-02, 5d
Entrainement modele IA :model1, after data1, 5d
Preparation dashboard :dash1, 2025-10-04, 3d

section Sprint 3 Alertes et dashboard
Notifications mail SMS :notif1, 2025-10-09, 4d
Push mobile :notif2, after notif1, 3d
Dashboard web final :dash2, 2025-10-10, 4d

section Sprint 4 Finalisation MVP
Capture photo intrus :photo1, 2025-10-16, 5d
Filtrage meteo :filt1, after photo1, 5d
Documentation tests :doc1, 2025-10-17, 5d

```