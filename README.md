
# Day-12-Automatrix

## Day 12: Convert a Classifier to TensorFlow Lite

This project trains a small neural network to classify light-level readings as Dark, Normal, or Bright. The trained model is converted to TensorFlow Lite format and tested against the original model in Python.

## Project Files

- `python.py` — trains the classifier, converts the model to TensorFlow Lite, and compares predictions.
- `light_classifier.tflite` — converted TensorFlow Lite model.
- `sketch.ino` — ESP32 simulation code, if included.
- `diagram.json` — Wokwi ESP32 configuration, if included.

## Wowki Simulation 
Run the simulation 
https://wokwi.com/projects/477956004563572737

## Light-Level Classes

- **Dark** — low light reading
- **Normal** — medium light reading
- **Bright** — high light reading

The reading ranges depend on the dataset and thresholds used in `python.py`.

## Expected Result

The original TensorFlow model and the converted TensorFlow Lite model should produce matching or very similar predictions.
