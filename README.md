# Car Damage Assessment

Оценка повреждений автомобиля по фотографии в Jupyter Notebook.

- `car_detection.ipynb` находит автомобиль с помощью YOLO11 и сохраняет вырезанную область.
- `minority_damage_segmentation.ipynb` выделяет повреждения с помощью YOLO и YOLOE.
- `heavy_damage_classification.ipynb` классифицирует серьёзные повреждения с помощью CLIP и SigLIP 2.

**Технологии** — Python, Jupyter, PyTorch, Ultralytics, Hugging Face Transformers, OpenCV, Pillow и NumPy.

Ноутбуки используют локальные каталоги `../dataset`, `../models` и `../outputs` для входных фото, весов моделей и результатов.
