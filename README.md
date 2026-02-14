# iot_smoke_detection_ML
Detect smoke with the help of IOT data and trigger a fire alarm.

## how to use ?
**Option 1: Colab**
just click on notebook-> open in colab button
then run all
**google colab link**:
https://colab.research.google.com/github/hadif1999/iot_smoke_detection_ML/blob/main/smoke_detection_iot.ipynb

**Option 2: Local**
1. Create a virtual environment (optional but recommended).
2. Install dependencies: `pip install -r requirements.txt`
3. Launch Jupyter: `jupyter lab`
4. Open `smoke_detection_iot.ipynb` and run all cells.

## about project
A smoke detector is a device that senses smoke, typically as an indicator of fire. Smoke detectors are usually housed in plastic enclosures, typically shaped like a disk about 150 millimetres (6 in) in diameter and 25 millimetres (1 in) thick, but shape and size vary.

### Types of Smoke Detectors

#### Photoelectric Smoke Detector
A photoelectric smoke detector contains a source of infrared, visible, or ultraviolet light, a lens, and a photoelectric receiver. In some types, the light emitted by the light source passes through the air being tested and reaches the photosensor. The received light intensity will be reduced due to scattering from particles of smoke, air-borne dust, or other substances; the circuitry detects the light intensity and generates an alarm if it is below a specified threshold, potentially due to smoke. Such detectors are also known as optical detectors.

#### Ionization Smoke Detector
An ionization smoke detector uses a radioisotope to ionize air. If any smoke particles enter the open chamber, some of the ions will attach to the particles and not be available to carry the current in that chamber. An electronic circuit detects that a current difference has developed between the open and sealed chambers, and sounds the alarm

About the dataset
Collection of training data is performed with the help of IOT devices since the goal is to develop a AI based smoke detector device.
Many different environments and fire sources have to be sampled to ensure a good dataset for training. A short list of different scenarios which are captured:

Normal indoor
Normal outdoor
Indoor wood fire, firefighter training area
Indoor gas fire, firefighter training area
Outdoor wood, coal, and gas grill
Outdoor high humidity
etc.

Dataset link: https://www.kaggle.com/datasets/deepcontractor/smoke-detection-dataset
